# 📘 Operations Analytics

| Field | Details |
|-------|---------|
| **Roadmap Section** | Core Stage 1 — Operations |
| **Platform** | Coursera |
| **Institution / Instructor** | Wharton School, University of Pennsylvania |
| **Course URL** | [coursera.org/learn/wharton-operations-analytics](https://www.coursera.org/learn/wharton-operations-analytics) |
| **Duration** | 4 modules |

---

## 🧭 Course Overview

This course teaches how to use analytics to solve operational problems under uncertainty. The core problems covered include: the newsvendor problem (how much to order before knowing demand), resource allocation (how to use limited resources optimally), network optimization (how to minimize shipping costs), and capacity planning. The course covers descriptive analytics (characterizing data and forecasting), predictive analytics (forecasting future demand), and prescriptive analytics (optimization and simulation to choose the best actions). Tools include Excel, moving averages, linear regression, Solver for optimization, and Monte Carlo simulation. The core message is that good decisions require not just forecasting the future but also modeling uncertainty and balancing risk and reward.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Define the newsvendor problem and apply it to inventory decisions
- [x] Forecast demand using moving averages and linear regression (trend + seasonality)
- [x] Calculate forecast errors using MAD, MSE, and MAPE
- [x] Fit demand distributions using the Actual-to-Forecast (A/F) ratio method
- [x] Build and solve optimization models (resource allocation, network flow) using Excel Solver
- [x] Use simulation to estimate reward (expected value) and risk (standard deviation)
- [x] Build and analyze decision trees under uncertainty
- [x] Combine simulation with optimization to find optimal order quantities
- [x] Incorporate risk constraints into optimization models

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Forecasting and the Newsvendor Problem | Descriptive analytics, demand forecasting, uncertainty modeling | ✅ |
| 2 | Prescriptive Analytics: Optimization | Resource allocation, network optimization, Excel Solver | ✅ |
| 3 | Decision-Making Under Uncertainty | Simulation, reward and risk estimation | ✅ |
| 4 | Decision Trees and Integration | Decision trees, simulation + optimization, newsvendor solution | ✅ |

---

---

# Module 1 — Forecasting and the Newsvendor Problem

## A. Core Idea of the Module

The newsvendor problem is a foundational operations problem: how much inventory to order before knowing actual demand. You must balance the cost of ordering too much (excess inventory) against the cost of ordering too little (lost sales). The module covers descriptive analytics (mean, standard deviation), forecasting methods (moving averages, trend, seasonality), forecast error measurement (MAD, MSE, MAPE), and how to fit demand distributions for new products using the Actual-to-Forecast (A/F) ratio method.

---

## B. Key Concepts & Definitions

- **Newsvendor Problem:** A decision problem where you must order inventory before demand is known, balancing the cost of overage (excess inventory) against the cost of underage (lost sales). Applications: retail inventory, magazine distribution, flu vaccines, mobile data plans, health insurance.

- **Descriptive Analytics:** Methods that characterize data — mean (expected value), standard deviation (spread), histograms, percentiles.

- **Predictive Analytics:** Methods that forecast future events — time series models, regression, causal models.

- **Prescriptive Analytics:** Methods that recommend actions — optimization, simulation, decision trees.

- **Forecast (F):** A prediction of future demand. Denoted with subscripts: F_{t,t+1} means forecast made at time t for period t+1.

- **Moving Average (MA(n)):** Forecasts the next period's demand by averaging the most recent n data points. Simple, stable, but lags trends.

- **Linear Regression for Trend:** Fits a trend line D_t = a + b×t to capture upward or downward trends. Uses Ordinary Least Squares (minimizes squared errors).

- **Seasonality:** Patterns that repeat at regular intervals (e.g., higher sales in December). Handled using multiplicative seasonal factors.

- **Seasonal Factors:** Numbers that quantify how each season compares to the baseline average. Factors sum to the number of seasons.

- **De-Seasonalization:** Dividing data by seasonal factors to remove seasonality, allowing trend or moving average forecasts on clean data. Then re-seasonalize by multiplying forecast by seasonal factors.

- **Forecast Errors:** Difference between forecast and actual demand: e_t = F_t - A_t (or A_t - F_t depending on convention).

- **Mean Absolute Deviation (MAD):** Average absolute error. Measures forecast accuracy in same units as data.

- **Mean Squared Error (MSE):** Average squared error. Penalizes large errors more heavily.

- **Mean Absolute Percentage Error (MAPE):** Average percentage error. Scale-independent, useful for comparing across different products.

- **Bias:** Systematic tendency to over-forecast (positive bias) or under-forecast (negative bias).

- **Actual-to-Forecast (A/F) Ratio:** Ratio of actual demand to forecast (A/F = Demand / Forecast). Used to fit demand distributions for new products.

- **Fitting a Normal Distribution for New Products:**
  - Mean of demand = Forecast × (Average of A/F ratios from similar products)
  - Standard deviation of demand = Forecast × (Standard deviation of A/F ratios from similar products)

---

## C. Main Arguments & Insights

1. **Point forecasts are almost always wrong.** Forecasts should include uncertainty measures — ranges, standard deviations, or probability distributions. A forecast without uncertainty is incomplete.

2. **Moving averages lag trends.** If demand is increasing, a moving average will consistently under-forecast. The longer the moving average window, the more lag. Use linear regression for trends.

3. **Seasonality must be removed before applying other forecasting methods.** If you apply moving averages to seasonal data without de-seasonalizing, the forecast will be biased. The four-step method: (1) compute sample mean, (2) compute seasonal averages, (3) derive seasonal factors, (4) de-seasonalize, forecast, then re-seasonalize.

4. **Forecast accuracy depends on data selection and model choice.** There is no single best forecasting method. Evaluate multiple methods using MAD, MSE, and MAPE. Choose the one with lowest error on historical data.

5. **The A/F ratio method allows forecasting for new products with no history.** Use forecast errors from similar products to estimate demand uncertainty. Multiply the forecast by the average A/F ratio (usually close to 1) for expected demand, and by the standard deviation of A/F ratios for demand variability.

6. **Longer horizon forecasts are less accurate.** As you forecast further into the future, uncertainty increases. Known information (e.g., promotions, competitor actions) should not be excluded from forecasts.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Newsvendor Problem | Order before knowing demand, balance overage vs. underage | Inventory decisions, capacity planning |
| Moving Average (MA(n)) | Average of last n periods | Stationary demand (no trend or seasonality) |
| Linear Regression | Fit trend line D_t = a + b×t | Demand with trend |
| Seasonal Factors | Multiplicative factors for each season | Demand with seasonality |
| De-seasonalization | Divide by seasonal factors, forecast, multiply back | Before applying MA or trend to seasonal data |
| MAD (Mean Absolute Deviation) | Average absolute error | Forecast accuracy (same units) |
| MSE (Mean Squared Error) | Average squared error | Penalizes large errors |
| MAPE (Mean Absolute Percentage Error) | Average percentage error | Scale-independent comparison |
| A/F Ratio Method | Demand distribution = Forecast × (A/F distribution) | New products with no history |

---

## E. Formulas & Equations

- **Moving Average (n periods):** F_{t+1} = (A_t + A_{t-1} + ... + A_{t-n+1}) / n

- **Linear Regression Trend Line:** D_t = a + b×t (a = intercept, b = slope)

- **Seasonal Factor (multiplicative):** SF_i = (Average of season i) / (Overall average)

- **De-seasonalized value:** D'_t = D_t / SF_{season(t)}

- **Re-seasonalized forecast:** F_t = F'_t × SF_{season(t)}

- **Forecast Error:** e_t = A_t - F_t (or F_t - A_t)

- **MAD:** (Σ |e_t|) / n

- **MSE:** (Σ e_t²) / n

- **MAPE:** (Σ |e_t / A_t| × 100%) / n

- **A/F Ratio:** AF = Actual / Forecast

- **Fitted Demand Mean:** μ = Forecast × (Average AF)

- **Fitted Demand Std Dev:** σ = Forecast × (StdDev of AF)

---

## F. Practical Implications

- Always include uncertainty with your forecast. A point forecast without a range is misleading.

- For stationary demand (no trend, no seasonality), moving averages work well. For demand with trend, use linear regression. For demand with seasonality, de-seasonalize first.

- Evaluate multiple forecasting methods on historical data using MAD, MSE, or MAPE. Choose the one with lowest error.

- When launching a new product, use A/F ratios from similar products to estimate demand uncertainty. This is better than guessing.

- Longer forecasts are less accurate. Update forecasts as new data arrives.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define the newsvendor problem
- [x] Calculate moving average forecasts
- [x] Fit a linear trend line using regression
- [x] Calculate seasonal factors and de-seasonalize data
- [x] Compute MAD, MSE, and MAPE
- [x] Detect bias in forecasts
- [x] Fit a demand distribution for new products using A/F ratios

---

## H. My Reflections & Critical Thoughts

The newsvendor problem is everywhere. Every time a retailer decides how many units to order before the holiday season, they are solving a newsvendor problem. The tension between overage (too much inventory) and underage (lost sales) is fundamental. The course introduces forecasting as the input to this decision, which is correct — better forecasts lead to better inventory decisions.

The A/F ratio method for new products is clever. Without historical data for the product itself, use forecast errors from similar products. If similar products had A/F ratios with mean 1.0 and standard deviation 0.2, then for a new product with forecast 10,000 units, demand is approximately normal with mean 10,000 and standard deviation 2,000. This is not perfect, but it is better than assuming no uncertainty.

The three error metrics (MAD, MSE, MAPE) serve different purposes. MAD is easiest to interpret (same units as data). MSE penalizes large errors heavily (useful if large errors are especially bad). MAPE is scale-independent (useful for comparing across products with different volumes). Use all three.

---

---

# Module 2 — Prescriptive Analytics: Optimization

## A. Core Idea of the Module

Optimization is used to make the best decisions in settings with low uncertainty (data known with certainty). An optimization model has three components: decision variables (what you control), an objective function (what you want to maximize or minimize), and constraints (limitations on resources). The module covers building optimization models in Excel, using Solver to find optimal solutions, and applying optimization to resource allocation (product mix) and network optimization (transportation / shipping) problems.

---

## B. Key Concepts & Definitions

- **Decision Variables:** The choices a company must make. Example: how many units of each product to produce.

- **Objective Function:** The goal to maximize (profit, revenue) or minimize (cost, time). Expressed as a formula in terms of decision variables.

- **Constraints:** Limitations that restrict feasible decisions. Example: resource availability, minimum demand, maximum capacity.

- **Feasible Solution:** A set of decision variable values that satisfies all constraints.

- **Optimal Solution:** The feasible solution that gives the best objective function value (maximum profit or minimum cost).

- **Linear Optimization Model:** Objective function and constraints are linear in the decision variables. Easier to solve.

- **Integer Constraint:** Decision variables must be whole numbers (integers). Common when decisions are indivisible (e.g., number of scooters, number of housing units).

- **SUMPRODUCT Function in Excel:** Multiplies corresponding arrays and sums the products. Useful for objective functions and constraints.

- **Absolute Cell Referencing (Anchoring):** Using $ signs in Excel formulas (e.g., $A$1) to keep references fixed when copying formulas.

- **Excel Solver:** An optimization tool in Excel that finds optimal solutions by changing decision variables subject to constraints.

- **Solver Messages:**
  - "Solver found a solution" → success
  - "Solver could not find a feasible solution" → constraints are impossible (infeasible)
  - "The objective cell values do not converge" → unbounded problem (missing constraints)

- **GRG Nonlinear:** A solving method in Solver for nonlinear problems (default choice when unsure).

- **Resource Allocation Problem:** Allocating limited resources (labor, materials, machine time) to different products to maximize profit.

- **Network Optimization (Transportation Problem):** Minimizing shipping cost from multiple supply points (warehouses) to multiple demand points (distribution centers) subject to supply and demand constraints.

---

## C. Main Arguments & Insights

1. **Optimization models have three components: decision variables, objective, constraints.** Always start by identifying these three before building the spreadsheet.

2. **SUMPRODUCT is your best friend in Excel optimization.** It makes objective functions and constraints easy to write and scale to large problems.

3. **Integer constraints make optimization much harder.** Solver can handle them, but problems with integer constraints take longer to solve. Use only when necessary (indivisible decisions like number of units).

4. **The GRG Nonlinear method works for most problems.** Choose this unless you know your problem is linear.

5. **Network optimization is a special case of resource allocation.** Instead of allocating resources to products, you allocate shipments from sources to destinations. The structure is the same: decision variables (shipment quantities), objective (minimize cost), constraints (supply and demand).

6. **Real-world optimization often combines with descriptive and predictive analytics.** Uncertainty makes optimization more complex. Weeks 3 and 4 cover simulation and decision trees for uncertain settings.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Optimization Model | Decision variables + objective + constraints | Any resource allocation or network problem |
| Excel Solver | Finds optimal solutions | After building model in spreadsheet |
| SUMPRODUCT | Multiplies and sums arrays | Objective function and constraints |
| Absolute Referencing ($) | Fixes cell references | When copying formulas |
| GRG Nonlinear | Solver method | Default choice for most problems |
| Resource Allocation | Maximize profit subject to resource limits | Product mix problems |
| Network Optimization | Minimize shipping cost subject to supply/demand | Transportation problems |

---

## E. Formulas & Equations

- **Objective Function (Max Profit):** Max Σ (Profit_per_unit_i × Q_i)

- **Resource Constraint:** Σ (Resource_usage_i × Q_i) ≤ Resource_available

- **Demand Constraint:** Σ (Shipments_from_j_to_k) ≥ Demand_k

- **Supply Constraint:** Σ (Shipments_from_j_to_k) ≤ Supply_j

- **SUMPRODUCT in Excel:** =SUMPRODUCT(array1, array2)

---

## F. Practical Implications

- Before using Solver, set up your spreadsheet clearly. Use color coding: decision variables (blue), objective (green), constraints (yellow). This prevents errors.

- Use absolute referencing ($) when copying formulas for multiple constraints. This is essential for scaling.

- If Solver says "infeasible," one of your constraints is impossible to satisfy. Check for conflicting constraints (e.g., minimum demand > maximum supply).

- If Solver says "unbounded," you are missing a constraint. The objective can go to infinity. Add limits.

- For large problems (hundreds or thousands of decision variables), commercial optimization tools are faster than Excel Solver.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Identify decision variables, objective, and constraints in a problem
- [x] Build an optimization model in Excel
- [x] Use SUMPRODUCT for objective functions and constraints
- [x] Apply absolute referencing when copying formulas
- [x] Run Solver to find optimal solutions
- [x] Interpret Solver messages (success, infeasible, unbounded)
- [x] Solve resource allocation (product mix) problems
- [x] Solve network optimization (transportation) problems

---

## H. My Reflections & Critical Thoughts

The SUMPRODUCT function is a hidden gem in Excel. It turns a messy formula into a clean, scalable one. Instead of writing "=B2*C2 + B3*C3 + ...", you write "=SUMPRODUCT(B2:B10, C2:C10)". This is essential when your model has dozens or hundreds of decision variables.

The resource allocation problem (Zooter scooters) is a classic linear programming problem. Two products, three constraints, maximize profit. The solution is intuitive: make as many of the high-profit product as possible until a constraint binds, then make the other product with remaining resources. Solver finds this automatically.

The network optimization problem (Keystone Dry Goods) is a transportation problem. The decision variables are shipment quantities from each warehouse to each distribution center. The constraints ensure supply does not exceed warehouse capacity and demand is met. This type of problem appears in logistics, supply chain, and public health (e.g., distributing vaccines).

---

---

# Module 3 — Decision-Making Under Uncertainty

## A. Core Idea of the Module

In low uncertainty settings, optimization with known data works well. But in high uncertainty settings, outcomes are described by probability distributions. Decisions must be evaluated based on reward (expected value) and risk (standard deviation, probability of loss). Simulation is used to estimate reward and risk when analytical formulas are not available (e.g., nonlinear pricing, complex decision rules). The module covers using Excel to simulate uncertain outcomes, interpreting simulation output (mean, standard deviation, histograms), and understanding how sample size affects precision.

---

## B. Key Concepts & Definitions

- **Low Uncertainty:** Decisions lead to certain outcomes. Known financial impacts. Optimization works well.

- **High Uncertainty:** Decisions lead to outcomes described by probability distributions. Profit or cost is uncertain. Need to consider both reward and risk.

- **Reward:** The expected (average) outcome. Usually measured as expected profit or expected cost.

- **Risk:** The variability of outcomes. Measured as standard deviation, probability of loss, or probability of exceeding a threshold.

- **Risk-Averse Decision Maker:** Prefers lower risk, even if it means lower expected reward.

- **Risk-Seeking Decision Maker:** Prefers higher reward, even if it means higher risk.

- **Risk-Neutral Decision Maker:** Cares only about expected value (reward). Ignores risk.

- **Simulation (Monte Carlo Simulation):** A method that generates random samples from probability distributions, computes outcomes for each sample, and uses sample statistics to estimate reward and risk.

- **Random Seed:** A starting number for random number generation. Different seeds produce different random samples. For long simulations, seed has minimal impact.

- **Histogram:** A graph that shows the distribution of simulated outcomes (shape, spread, percentiles).

- **Sample Size (Simulation Runs):** The number of random samples generated. Larger sample size = more precise estimates. 1,000 runs is common.

- **Law of Large Numbers:** As sample size increases, sample mean approaches true expected value.

---

## C. Main Arguments & Insights

1. **In high uncertainty settings, you need both reward and risk measures.** Expected value alone is not enough. A project with high expected profit but high chance of large loss may be rejected by risk-averse decision makers.

2. **Simulation is needed when analytical formulas fail.** If the profit function is nonlinear (e.g., pricing tiers, minimum of demand and order quantity), plugging the expected demand into the formula does NOT give the expected profit. You must simulate.

3. **Larger sample sizes give more precise estimates.** With 10 simulation runs, the mean changes significantly with different random seeds. With 1,000 runs, the mean stabilizes. Use enough runs to get stable results.

4. **Histograms reveal more than mean and standard deviation.** The shape of the distribution matters. Bimodal distributions, long tails, and skewed distributions are not captured by mean and standard deviation alone.

5. **Simulation is a bridge between descriptive and prescriptive analytics.** Use descriptive analytics (mean, std dev) to characterize uncertainty. Use simulation to estimate outcomes. Then use prescriptive analytics (optimization, decision trees) to choose actions.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Reward | Expected (average) outcome | Primary measure of performance |
| Risk | Variability of outcomes (std dev, P(loss)) | Secondary measure, important for risk-averse decision makers |
| Monte Carlo Simulation | Random sampling from distributions | When analytical formulas fail (nonlinear, complex) |
| Random Seed | Starting number for random generation | To replicate simulation results |
| Histogram | Distribution of simulated outcomes | To visualize full distribution |
| Sample Size | Number of simulation runs | Larger = more precise (1,000 typical) |
| Excel Analysis ToolPak | Add-in for random number generation | To run simulations in Excel |

---

## E. Formulas & Equations

- **Expected Value (Reward):** E[Profit] ≈ (1/n) × Σ Profit_i (over n simulation runs)

- **Standard Deviation (Risk):** σ ≈ √[ (1/(n-1)) × Σ (Profit_i - Mean)² ]

- **Normal Distribution Random Number (Excel):** =NORM.INV(RAND(), mean, stdev)

- **Uniform Distribution Random Number (Excel):** = min + (max-min) × RAND()

---

## F. Practical Implications

- When evaluating a decision under uncertainty, always report both expected value (reward) and standard deviation (risk). Risk-averse stakeholders will care about downside.

- Use at least 1,000 simulation runs for stable estimates. With fewer runs, results can change significantly with different random seeds.

- Use histograms to show the full distribution. A single bad outcome (e.g., 5% chance of large loss) may be acceptable or not depending on risk tolerance.

- For nonlinear problems (like tiered pricing or minimum of demand and order quantity), simulation is not optional — analytical formulas will give wrong answers.

- If you need to replicate results, set a fixed random seed. Otherwise, use different seeds to test robustness.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish low uncertainty from high uncertainty settings
- [x] Define reward (expected value) and risk (standard deviation)
- [x] Explain why simulation is needed for nonlinear problems
- [x] Generate random samples in Excel using normal and uniform distributions
- [x] Run a simulation with 10, 100, and 1,000 runs
- [x] Compute sample mean and standard deviation from simulation output
- [x] Create histograms to visualize simulation output
- [x] Explain why larger sample sizes give more precise estimates

---

## H. My Reflections & Critical Thoughts

The key insight of this module is that plugging expected demand into a nonlinear profit function gives the wrong expected profit. This is a common mistake. For a simple linear function, E[f(x)] = f(E[x]). But for a nonlinear function (like pricing tiers where the rate changes at 20 GB), E[f(x)] ≠ f(E[x]). You must simulate.

The wireless data plan example is perfect. The plan charges a fixed fee up to 20 GB, then a higher rate above 20 GB. If you plug the expected usage (say 18 GB) into the formula, you get the fixed fee. But the true expected payment is higher because some months exceed 20 GB. Simulation captures this.

The law of large numbers is important. With 10 simulation runs, the results are noisy. With 1,000 runs, they stabilize. Always use enough runs.

---

---

# Module 4 — Decision Trees and Integration

## A. Core Idea of the Module

Decision trees are a visual tool for decision-making under uncertainty. They consist of decision nodes (choices), event nodes (uncertain outcomes with probabilities), and outcome nodes (final payoffs). Decision trees can be analyzed using different strategies: maximin (risk-averse, maximize minimum outcome), maximax (risk-seeking, maximize maximum outcome), or expected value (risk-neutral, maximize expected value). The module also covers combining simulation with decision trees (when uncertainty is complex) and combining optimization with simulation (to find optimal order quantities). The newsvendor problem is solved using simulation + optimization.

---

## B. Key Concepts & Definitions

- **Decision Tree:** A visual diagram for decision-making under uncertainty. Components:
  - **Decision Node (square):** A choice to be made by the decision maker.
  - **Event Node (circle):** A point of uncertainty with probabilistic outcomes.
  - **Outcome Node (triangle):** Final payoff (profit, cost).

- **Maximin Strategy:** Choose the option that maximizes the minimum possible outcome. Risk-averse — focus on worst-case scenario.

- **Maximax Strategy:** Choose the option that maximizes the maximum possible outcome. Risk-seeking — focus on best-case scenario.

- **Expected Value Strategy:** Choose the option with the highest expected profit (probability-weighted average). Risk-neutral — ignores risk, focuses on average.

- **Decision Tree with Simulation:** When event nodes have complex probability distributions (not just a few discrete scenarios), use simulation to estimate expected payoffs for each branch, then plug those expected values into the decision tree.

- **Simulation + Optimization (Newsvendor):** Use simulation to estimate expected profit for different order quantities. Then use Excel Solver to find the order quantity that maximizes expected profit. Optionally, add a risk constraint (e.g., standard deviation ≤ some limit).

- **Risk Constraint:** A constraint in optimization that limits risk (e.g., standard deviation of profit ≤ $5,000). Adding a risk constraint typically reduces optimal order quantity and expected profit but lowers risk.

---

## C. Main Arguments & Insights

1. **Decision trees provide a visual framework for sequential decisions.** They are especially useful when decisions are made over time, with uncertainty resolving between decisions.

2. **The optimal strategy depends on risk preference.** Maximin (risk-averse), maximax (risk-seeking), and expected value (risk-neutral) can give different answers. There is no single "correct" strategy — it depends on the decision maker's risk tolerance.

3. **Simulation can be used within decision trees.** When event nodes have complex distributions (e.g., uniform demand with a range), simulation estimates expected payoffs. These expected values then feed into the decision tree.

4. **Optimization + simulation solves the newsvendor problem.** For a given order quantity, simulation estimates expected profit. Solver then finds the order quantity that maximizes expected profit. This works even when profit is nonlinear (which it always is for newsvendor problems).

5. **Risk constraints change the optimal order quantity.** A risk-averse newsvendor will order less than the risk-neutral optimal quantity. Less inventory means lower risk (less chance of excess inventory) but also lower expected profit. The trade-off is explicit in the optimization model.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Decision Tree | Visual diagram with decision and event nodes | Sequential decisions under uncertainty |
| Maximin | Maximize minimum outcome | Risk-averse decision maker |
| Maximax | Maximize maximum outcome | Risk-seeking decision maker |
| Expected Value | Maximize expected profit | Risk-neutral decision maker |
| Decision Tree + Simulation | Simulation estimates expected values for complex branches | When event nodes have complex distributions |
| Simulation + Optimization | Solver finds optimal decision variable | Newsvendor problem, capacity planning |
| Risk Constraint | Limits standard deviation of profit | Risk-averse decision makers |

---

## E. Formulas & Equations

- **Expected Value (decision tree):** EV = Σ (Probability_i × Payoff_i)

- **Maximin:** Choose action a* that maximizes min(Payoff over all outcomes)

- **Maximax:** Choose action a* that maximizes max(Payoff over all outcomes)

- **Profit (Newsvendor, no salvage):** If Q ≤ Demand: Profit = (Price - Cost) × Q; If Q > Demand: Profit = (Price - Cost) × Demand - Cost × (Q - Demand)

- **Risk Constraint:** σ(Profit) ≤ L (where L is maximum acceptable standard deviation)

---

## F. Practical Implications

- Use decision trees when decisions are sequential and uncertainty resolves between decisions. For one-stage decisions (order once, then demand realized), a decision tree is equivalent to an expected value calculation.

- For risk-averse decision makers, maximin is appropriate if the worst-case outcome must be protected. For most business decisions, expected value is appropriate (risk-neutral), especially if the decision is repeated many times.

- When event nodes have complex distributions (e.g., uniform demand with a range), use simulation to estimate expected values, then plug into the decision tree.

- The newsvendor problem is the canonical example of simulation + optimization. Use Solver to find the optimal order quantity that maximizes expected profit. Add a risk constraint to see the trade-off.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Build a decision tree with decision nodes, event nodes, and outcome nodes
- [x] Calculate expected value for each branch
- [x] Apply maximin, maximax, and expected value strategies
- [x] Combine simulation with decision trees for complex uncertainties
- [x] Combine simulation with optimization to solve the newsvendor problem
- [x] Add risk constraints to optimization models
- [x] Explain why adding a risk constraint reduces optimal order quantity

---

## H. My Reflections & Critical Thoughts

The decision tree is a classic tool. It forces you to be explicit about: (1) what decisions you can make, (2) what uncertainties exist, (3) probabilities of each outcome, and (4) payoffs. The visual nature helps stakeholders understand the trade-offs.

The three strategies (maximin, maximax, expected value) reflect different risk preferences. Expected value is the standard in finance (diversified investors are risk-neutral to idiosyncratic risk). Maximin is appropriate for decisions that cannot be repeated (e.g., one-shot decisions with catastrophic downside). Maximax is for gamblers.

The integration of simulation with decision trees and optimization is the heart of operations analytics. Descriptive analytics (forecasting) gives you demand distributions. Simulation estimates outcomes for different decisions. Optimization (Solver) finds the best decision. This three-step process — forecast, simulate, optimize — is the analytics workflow.

The risk constraint in the newsvendor problem is elegant. The risk-neutral newsvendor orders a certain quantity. A risk-averse newsvendor orders less (lower risk, lower expected profit). The optimization model makes this trade-off explicit. You can vary the risk limit and see how the optimal order quantity changes.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | Introduction to Operations Management | Newsvendor problem connects to inventory management, Little's Law, process analysis |
| Connects to | Introduction to Corporate Finance | Optimization (resource allocation) connects to capital budgeting |
| Connects to | Microeconomics | Decision trees connect to game theory and expected utility |
| Connects to | Introduction to Marketing | Forecasting demand is a marketing function |

---

# 📊 Concept Map

```
OPERATIONS ANALYTICS
│
├── MODULE 1: Forecasting & Newsvendor
│   ├── Newsvendor Problem: order before knowing demand
│   │   └── Balance overage (excess) vs. underage (lost sales)
│   ├── Forecasting Methods
│   │   ├── Moving Average (stationary demand)
│   │   ├── Linear Regression (trend)
│   │   └── De-seasonalization + Seasonal Factors
│   ├── Forecast Errors
│   │   ├── MAD (mean absolute deviation)
│   │   ├── MSE (mean squared error)
│   │   └── MAPE (mean absolute percentage error)
│   └── A/F Ratio Method: fit demand distribution for new products
│
├── MODULE 2: Optimization (Low Uncertainty)
│   ├── Optimization Model Components
│   │   ├── Decision Variables (what you control)
│   │   ├── Objective Function (max/min)
│   │   └── Constraints (limitations)
│   ├── Excel Tools
│   │   ├── SUMPRODUCT for objective & constraints
│   │   ├── Absolute Referencing ($)
│   │   └── Solver (GRG Nonlinear)
│   └── Applications
│       ├── Resource Allocation (product mix)
│       └── Network Optimization (transportation)
│
├── MODULE 3: Simulation (High Uncertainty)
│   ├── Reward: expected value (average outcome)
│   ├── Risk: standard deviation, P(loss)
│   ├── Monte Carlo Simulation
│   │   ├── Generate random samples from distributions
│   │   ├── Compute outcomes for each sample
│   │   └── Estimate reward and risk from sample statistics
│   └── Visualization: histograms of simulated outcomes
│
└── MODULE 4: Decision Trees & Integration
    ├── Decision Tree Components
    │   ├── Decision Node (square) → choices
    │   ├── Event Node (circle) → uncertainties with probabilities
    │   └── Outcome Node (triangle) → payoffs
    ├── Decision Strategies
    │   ├── Maximin (risk-averse, maximize minimum)
    │   ├── Maximax (risk-seeking, maximize maximum)
    │   └── Expected Value (risk-neutral, maximize average)
    ├── Integration
    │   ├── Decision Trees + Simulation (complex event nodes)
    │   └── Simulation + Optimization (find optimal Q)
    └── Newsvendor Solution: optimize order quantity with simulation, optionally add risk constraint
```

---

# ✅ Course-Level Takeaways

This course provides a complete toolkit for operational decision-making under uncertainty. The three-step process — descriptive (forecasting), predictive (simulation), prescriptive (optimization) — is the core workflow. The newsvendor problem ties it all together: forecast demand (descriptive), simulate profit for different order quantities (predictive), optimize order quantity (prescriptive), and optionally add risk constraints.

The course's strength is the integration of multiple analytics methods into a coherent framework. Excel is used throughout, making the methods accessible. The progression from simple moving averages to linear regression to seasonal adjustment is clear. The optimization module covers both resource allocation and network problems. The simulation module covers reward and risk. The decision tree module covers risk preferences. And the newsvendor solution at the end ties everything together.

The weakness is that the course assumes familiarity with Excel and basic statistics. But for learners with those prerequisites, this course provides a practical, hands-on introduction to operations analytics.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *Operations Management* | Cachon & Terwiesch — Textbook by Wharton professors |
| 📖 Book | *Matching Supply with Demand* | Cachon & Terwiesch — Focus on operations analytics |
| 📖 Book | *Data, Models, and Decisions* | Bertsimas & Freund — Analytics textbook |
| 🌐 Software | Excel (Analysis ToolPak, Solver) | Built-in tools for simulation and optimization |
| 📄 Article | "The Newsvendor Problem" | Various academic sources — classic operations problem |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#OperationsAnalytics` `#NewsvendorProblem` `#Forecasting` `#Optimization` `#Simulation` `#DecisionTrees` `#ExcelSolver` `#Wharton`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
