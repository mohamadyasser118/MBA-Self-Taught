# 📘 Introduction to Corporate Finance

| Field                        | Details                                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------ |
| **Roadmap Section**          | Core Stage 1 — Finance                                                               |
| **Part of Specialization**   | Business Foundations Specialization — Wharton School (Course 4 of 6)                 |
| **Platform**                 | Coursera                                                                             |
| **Institution / Instructor** | Wharton School, University of Pennsylvania                                           |
| **Course URL**               | [coursera.org/learn/wharton-finance](https://www.coursera.org/learn/wharton-finance) |
| **Duration**                 | 4 modules                                                                            |

---

## 🧭 Course Overview

This course teaches the core principles of corporate finance — the discipline of making decisions with financial implications. The central idea is the time value of money: a dollar today is worth more than a dollar tomorrow because you can invest it and earn a return. The course covers how to move money across time (discounting and compounding), how to value streams of cash flows (annuities, perpetuities), how to account for inflation and taxes, and how to compare different interest rate quotes (APR vs. EAR). The second half of the course applies these tools to capital budgeting: forecasting free cash flows, calculating net present value (NPV), and using decision rules like internal rate of return (IRR) and payback period. The core message is that finance provides a consistent framework for evaluating any decision with costs and benefits that occur at different times.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Explain why money at different times cannot be added directly
- [x] Discount future cash flows to present value and compound present cash flows to future value
- [x] Calculate present and future values for annuities, perpetuities, and growing streams
- [x] Convert between APR and EAR and handle different compounding frequencies
- [x] Distinguish nominal from real returns and adjust for inflation
- [x] Compute after-tax discount rates and after-tax cash flows
- [x] Forecast unlevered free cash flows from revenue, cost, and investment assumptions
- [x] Calculate NPV, IRR, and payback period for a project
- [x] Use sensitivity analysis to test the robustness of a valuation
- [x] Explain the limitations of IRR compared to NPV

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Time Value of Money | Discounting, compounding, annuities, perpetuities, taxes | ✅ |
| 2 | Interest Rates and Cash Flow Analysis | Inflation, APR vs. EAR, DCF decision making | ✅ |
| 3 | Free Cash Flow | Forecasting free cash flows for capital budgeting | ✅ |
| 4 | Decision Criteria and Sensitivity Analysis | NPV, IRR, payback, sensitivity analysis | ✅ |

---

---

# Module 1 — Time Value of Money

## A. Core Idea of the Module

Money at different times cannot be added directly — it is like adding dollars to euros. A dollar today is worth more than a dollar tomorrow because you could invest today's dollar and earn a return. This module teaches the tools for moving money across time: discounting (moving future cash flows back to the present) and compounding (moving present cash flows forward to the future). It also covers useful shortcuts for valuing common patterns of cash flows (annuities, perpetuities) and how to adjust for taxes.

---

## B. Key Concepts & Definitions

- **Time Value of Money:** The principle that a dollar today is worth more than a dollar in the future because of the opportunity to invest and earn a return.

- **Opportunity Cost:** The return you give up by not having money available to invest today. This is the core reason money has time value.

- **Discount Factor:** The exchange rate for converting money across time. Formula: (1 + R)^t, where R is the discount rate and t is the number of periods.

- **Discounting:** Moving future cash flows back to the present. Multiply by (1 + R)^(-t).

- **Compounding:** Moving present cash flows forward to the future. Multiply by (1 + R)^t.

- **Present Value (PV):** The value of future cash flows in today's terms. The sum of all discounted cash flows.

- **Future Value (FV):** The value of present cash flows at a future date after compounding.

- **Annuity:** A finite series of equal cash flows spaced evenly over time. Examples: mortgage payments, bond coupons.

- **Perpetuity:** An infinite series of equal cash flows spaced evenly over time. Example: consol bonds (rare).

- **Growing Annuity:** A finite series of cash flows that grow at a constant rate each period.

- **Growing Perpetuity:** An infinite series of cash flows that grow at a constant rate each period.

- **Discount Rate (R):** The rate of return used to discount future cash flows. Reflects the risk of the cash flows.

- **After-Tax Discount Rate:** R × (1 - Tax Rate). Used when cash flows are after-tax and taxes affect the return you can earn.

---

## C. Main Arguments & Insights

1. **Never add cash flows from different times without discounting.** This is the most important rule in finance. Adding $100 today and $100 next year is like adding 100 dollars to 100 euros — meaningless. Convert everything to the same time unit first.

2. **The discount rate reflects risk.** Higher risk means higher discount rate means lower present value. The opportunity cost of capital is not a single number — it depends on what else you could do with the money. Riskier investments must offer higher expected returns to be attractive.

3. **Annuities and perpetuities are everywhere, and the shortcuts save enormous time.** Mortgage payments, lease payments, bond coupons, pension payments — all are annuities. The formulas for present value of annuities and perpetuities are not just math tricks; they reflect real financial contracts.

4. **Taxes reduce effective returns significantly.** A 35% tax rate turns a 5% pre-tax return into a 3.25% after-tax return. This matters for personal finance (what you actually keep) and for corporate finance (cash flows are after-tax).

5. **The growing perpetuity formula is the basis for stock valuation.** The value of a stock is the present value of all future dividends. If dividends grow at a constant rate forever, the price = dividend / (R - g). This is the Gordon Growth Model.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Timeline | A visual showing when cash flows occur | Always use this first to avoid timing mistakes |
| Discount Factor | (1 + R)^t | To move money across time |
| Present Value (PV) | Sum of discounted cash flows | To find what future cash flows are worth today |
| Future Value (FV) | Present cash flows after compounding | To find what today's money grows to in the future |
| Annuity Formula | PV = C × [1 - (1+R)^-n] / R | For equal payments over a fixed number of periods |
| Perpetuity Formula | PV = C / R | For equal payments forever |
| Growing Perpetuity Formula | PV = C / (R - g) | For payments that grow forever at rate g |
| After-Tax Discount Rate | R × (1 - Tax Rate) | When taxes affect investment returns |

---

## E. Formulas & Equations

- **Discount Factor (forward):** (1 + R)^t

- **Discount Factor (backward):** 1 / (1 + R)^t = (1 + R)^(-t)

- **Present Value (single cash flow):** PV = FV / (1 + R)^t

- **Future Value (single cash flow):** FV = PV × (1 + R)^t

- **Present Value of Annuity:** PV = C × [1 - (1 + R)^(-n)] / R

- **Future Value of Annuity:** FV = C × [(1 + R)^n - 1] / R

- **Present Value of Perpetuity:** PV = C / R

- **Present Value of Growing Annuity:** PV = C × [1 - ((1+g)/(1+R))^n] / (R - g)

- **Present Value of Growing Perpetuity:** PV = C / (R - g)  (where R > g)

- **After-Tax Discount Rate:** R_after_tax = R_pre_tax × (1 - Tax_Rate)

---

## F. Practical Implications

- Always draw a timeline before doing any time value of money calculation. Write each cash flow at its time period. This prevents the most common mistake: adding cash flows from different times.

- Use the annuity formula for mortgages. A $200,000 mortgage at 4% for 30 years (360 months) has monthly payments of about $955. The formula tells you this instantly.

- Use the perpetuity formula for endowments. A university endowment that wants to pay out $10 million per year forever at 5% needs $200 million today.

- Remember that the growing perpetuity formula only works when R > g. If growth rate equals or exceeds the discount rate, the formula breaks (value becomes infinite). This is a warning sign that your assumptions are unrealistic.

- Adjust for taxes. In corporate finance, cash flows are after-tax. Use the after-tax discount rate or adjust the cash flows directly. Be consistent.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Explain why money at different times cannot be added directly
- [x] Draw a timeline for any series of cash flows
- [x] Discount future cash flows to present value
- [x] Compound present cash flows to future value
- [x] Calculate present and future value of annuities
- [x] Calculate present value of perpetuities and growing perpetuities
- [x] Adjust discount rates for taxes
- [x] Explain the relationship between risk and discount rate

---

## H. My Reflections & Critical Thoughts

The idea that money has a "time unit" — that cash flows from different periods are like different currencies — is the single most important concept in finance. Everything else builds on this. The discount factor is just an exchange rate for time. This framing makes the math intuitive: you would not add dollars to euros, so do not add today's dollars to tomorrow's dollars.

The growing perpetuity formula is elegant but dangerous. It is the foundation of stock valuation, but it is extremely sensitive to assumptions. A small change in the growth rate (g) or discount rate (R) changes the valuation dramatically. This is not a flaw in the formula — it is a feature that forces you to think hard about your assumptions.

The tax adjustment is often overlooked in personal finance. People see a 5% savings account rate and think they are earning 5%. After 35% taxes, it is 3.25%. Over 30 years, that difference is huge. The course makes this clear, which is valuable for personal decision-making.

---

---

# Module 2 — Interest Rates and Cash Flow Analysis

## A. Core Idea of the Module

Interest rates are quoted in different ways, and not all quotes mean the same thing. APR (Annual Percentage Rate) ignores compounding; EAR (Effective Annual Rate) includes it. This module explains how to convert between different rate quotes and how to handle different compounding frequencies. It also covers inflation (the difference between nominal and real returns) and introduces the Net Present Value (NPV) decision rule for making financial decisions.

---

## B. Key Concepts & Definitions

- **APR (Annual Percentage Rate):** The simple interest rate quoted by lenders. It ignores compounding. APR = Periodic Rate × Number of Periods per Year.

- **EAR (Effective Annual Rate):** The actual interest rate earned or paid after accounting for compounding. This is what matters for decision-making.

- **Periodic Rate:** The interest rate for one compounding period. Periodic Rate = APR / (Number of Periods per Year).

- **Compounding Frequency:** How often interest is calculated and added to the account. Common frequencies: annual, semi-annual, quarterly, monthly, daily.

- **Nominal Return:** The stated return without adjusting for inflation.

- **Real Return:** The return after adjusting for inflation. Measures actual purchasing power.

- **Fisher Equation (exact):** (1 + R_nominal) = (1 + R_real) × (1 + Inflation Rate)

- **Fisher Equation (approximate):** R_real ≈ R_nominal - Inflation Rate

- **Net Present Value (NPV):** Present value of benefits minus present value of costs. The gold standard decision rule.

- **NPV Decision Rule:** Accept projects with positive NPV. Reject projects with negative NPV. Positive NPV means the project creates value.

- **Cost of Capital (Hurdle Rate):** The minimum acceptable return for an investment. The discount rate used in NPV calculations.

---

## C. Main Arguments & Insights

1. **APR is a quoting convention, not a real rate.** APR ignores compounding, which means two loans with the same APR can have different true costs if they compound at different frequencies. Always convert APR to EAR before making comparisons.

2. **More frequent compounding increases effective returns.** Daily compounding gives a higher EAR than monthly, which gives higher than quarterly, which gives higher than annual. For the same APR, more frequent compounding is better for savers and worse for borrowers.

3. **Inflation eats purchasing power, not nominal dollars.** A 5% nominal return with 3% inflation leaves you with a 2% real return. Your bank account says you have more money, but you can buy only 2% more stuff. Long-term investors must focus on real returns.

4. **Discounting nominal cash flows with nominal rates gives the same result as discounting real cash flows with real rates.** This is a powerful consistency check. As long as you match nominal with nominal and real with real, the present value is the same.

5. **NPV is the only decision rule that always works.** Positive NPV means the project creates value. Negative NPV means it destroys value. Simple, clear, and mathematically correct. Other rules (IRR, payback) can be misleading in some situations.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| APR to EAR Conversion | EAR = (1 + APR/n)^n - 1 | To compare loans or investments with different compounding frequencies |
| Periodic Rate Calculation | Periodic Rate = APR / n | To find the rate per compounding period |
| Fisher Equation | (1 + R_nominal) = (1 + R_real) × (1 + inflation) | To convert between nominal and real returns |
| NPV Rule | Accept if NPV > 0 | For any investment decision |
| Timeline with Discounting | Visual + discount factors | For any multi-period cash flow |

---

## E. Formulas & Equations

- **APR to EAR:** EAR = (1 + APR / n)^n - 1, where n = number of compounding periods per year

- **Periodic Rate:** r_periodic = APR / n

- **Future Value with Compounding:** FV = PV × (1 + APR / n)^(n × t)

- **Fisher Equation (exact):** (1 + R_nominal) = (1 + R_real) × (1 + Inflation)

- **Fisher Equation (approx):** R_real ≈ R_nominal - Inflation

- **NPV:** NPV = PV(Benefits) - PV(Costs) = Σ [CF_t / (1 + R)^t]

---

## F. Practical Implications

- When comparing loan offers, always convert to EAR. The loan with the lower APR might have a higher EAR if it compounds more frequently. Credit cards often have low APRs but daily compounding — the EAR is higher than you think.

- For long-term investing, focus on real returns. A 7% nominal return with 3% inflation gives only 4% real. Over 30 years, that is the difference between doubling your money three times versus twice.

- Use the approximate Fisher equation for quick estimates, but use the exact version for precise work, especially when inflation is high.

- The NPV rule is the only rule you really need. If a project has positive NPV, take it. If it has negative NPV, do not. Everything else (IRR, payback) is just additional information.

- Be careful with the discount rate. The cost of capital should reflect the risk of the project, not the risk of the company. A safe project in a risky company should use a low discount rate.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish APR from EAR and convert between them
- [x] Calculate periodic rates for any compounding frequency
- [x] Compute future values with semi-annual, monthly, and daily compounding
- [x] Explain the difference between nominal and real returns
- [x] Use the Fisher equation to convert between nominal and real rates
- [x] State the NPV decision rule
- [x] Explain why positive NPV projects create value

---

## H. My Reflections & Critical Thoughts

The APR vs. EAR distinction is one of those things that seems obvious once you learn it, but it is amazing how many people get it wrong. Credit card companies rely on this confusion. A 18% APR with daily compounding is actually about 19.7% EAR. That is not a small difference. The course's emphasis on converting everything to EAR before comparing is essential.

The Fisher equation is a good reminder that money is just a medium of exchange. What matters is what you can buy with it. A 10% return in a 10% inflation world is zero real return. This is why long-term bonds are risky — not because the nominal payments might stop, but because inflation can destroy their purchasing power.

The NPV rule seems almost too simple. But simplicity is the point. Discount all future cash flows to today, subtract the cost, and if the number is positive, do it. This works for buying a machine, launching a product, or buying a house. The hard part is not the math — it is forecasting the cash flows.

---

---

# Module 3 — Free Cash Flow

## A. Core Idea of the Module

NPV is the rule, but you need cash flows to apply it. This module teaches how to forecast free cash flows (FCF) for a project or company. Free cash flow is the cash generated after paying for operations, taxes, and investments — the cash available to be paid out to investors. The module covers how to build forecast drivers (market size, market share, costs, working capital), how to construct a quasi-income statement, and how to handle special issues like opportunity costs, sunk costs, and cannibalization.

---

## B. Key Concepts & Definitions

- **Free Cash Flow (FCF):** The cash generated by a project after all operating expenses, taxes, and investments. The cash available to be distributed to debt and equity holders.

- **Unlevered Free Cash Flow:** FCF before interest payments. Does not depend on how the project is financed. Used for project valuation (separate investment decision from financing decision).

- **Levered Free Cash Flow (Free Cash Flow to Equity):** FCF after interest payments. Depends on financing. Used for equity valuation.

- **NOPAT (Net Operating Profit After Taxes):** EBIT × (1 - Tax Rate). Operating profit after taxes but before interest.

- **EBITDA:** Earnings Before Interest, Taxes, Depreciation, and Amortization.

- **Capital Expenditures (CapEx):** Spending on long-term assets (property, plant, equipment). Subtracted from cash flow because it is a cash outflow.

- **Net Working Capital (NWC):** Current Assets - Current Liabilities. Changes in NWC are cash outflows (if NWC increases) or inflows (if NWC decreases).

- **Forecast Drivers:** The assumptions used to forecast cash flows: market size, market share, price, COGS percentage, SG&A growth, CapEx, working capital days.

- **Opportunity Cost:** The value of the best alternative use of a resource. Should be included in FCF analysis.

- **Sunk Cost:** A cost that has already been paid and cannot be recovered. Should NOT be included in FCF analysis.

- **Cannibalization:** When a new product takes sales away from an existing product. Should be included as a cost.

- **Spillover (Externalities):** When a project affects cash flows of other parts of the company. Should be included.

---

## C. Main Arguments & Insights

1. **Free cash flow is what matters, not accounting earnings.** Accounting earnings include non-cash expenses (depreciation) and exclude capital expenditures. Free cash flow fixes both: it adds back depreciation (non-cash) and subtracts CapEx (cash). This is the cash the project actually generates.

2. **Unlevered FCF separates investment decisions from financing decisions.** A good project should be accepted regardless of how it is financed. Unlevered FCF ignores interest payments, so NPV depends only on the project's operations. Financing decisions (debt vs. equity) affect levered FCF but not unlevered FCF.

3. **Changes in working capital are cash flows that managers often forget.** When inventory increases, cash is tied up (cash outflow). When accounts receivable increase, cash is not yet collected (cash outflow). When accounts payable increase, cash is not yet paid (cash inflow). These changes can be large and must be included.

4. **Depreciation is a tax shield, not a cash flow.** Depreciation is a non-cash expense, so it is added back to get from accounting income to cash flow. But depreciation reduces taxes (because it reduces taxable income). This tax saving is a real cash inflow. The formula NOPAT = EBIT × (1 - tax rate) captures this effect automatically.

5. **Good forecasting comes from many departments, not just finance.** Marketing forecasts market size and market share. Operations forecasts costs and capacity needs. Strategy forecasts competitive response. Finance pulls it all together and checks for consistency. A DCF model is only as good as its inputs.

6. **The goal of DCF is not perfect accuracy — it is a structured conversation.** No one can predict the future perfectly. The value of DCF is that it forces you to make your assumptions explicit, see how they affect value, and debate them productively.

---

## D. Frameworks, Models & Tools

| Framework / Tool            | What It Is                                                                       | When to Use It                                    |
| --------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------- |
| Unlevered FCF Formula       | FCF = (Revenue - Costs - Depreciation) × (1 - Tax) + Depreciation - CapEx - ΔNWC | To calculate free cash flow for project valuation |
| Forecast Drivers            | Market size, market share, price, cost percentages, growth rates                 | To build a forecast from assumptions              |
| Quasi-Income Statement      | Sales → COGS → Gross Profit → SG&A → R&D → EBITDA → Depreciation → EBIT → NOPAT  | Intermediate step before FCF                      |
| Working Capital Forecast    | Days of inventory, days receivable, days payable                                 | To forecast changes in NWC                        |
| Opportunity Cost Adjustment | Include the value of resources used even if no cash changes hands                | When the project uses existing assets             |
| Sunk Cost Exclusion         | Ignore past costs that cannot be recovered                                       | Always — sunk costs are irrelevant                |

![[Pasted image 20260531015332.png]]
---

## E. Formulas & Equations

- **Unlevered Free Cash Flow:**
  - FCF = (Revenue - Operating Costs - Depreciation) × (1 - Tax Rate) + Depreciation - CapEx - ΔNWC
  - Or: FCF = NOPAT + Depreciation - CapEx - ΔNWC

- **EBITDA:** Revenue - Operating Costs (excluding depreciation)

- **EBIT:** EBITDA - Depreciation

- **NOPAT:** EBIT × (1 - Tax Rate)

- **Change in NWC:** ΔNWC = NWC_t - NWC_{t-1} (positive ΔNWC is cash outflow)

- **NWC:** (Cash + Inventory + Accounts Receivable) - Accounts Payable

---

## F. Practical Implications

- Start every DCF with a blank spreadsheet and a timeline. Write year 0, year 1, year 2, etc. Put every cash flow in the right column. Do not skip steps.

- Include opportunity costs. If a project uses a building you already own, that building has value in its next best use. That value is a cost of the project, even though no cash changes hands.

- Exclude sunk costs. What you paid last year for market research is gone. It should not affect the decision about whether to launch the product today.

- Include cannibalization. If a new product will steal sales from an existing product, that lost profit is a cost of the new product. Ignoring it overstates value.

- Forecast working capital changes carefully. Growing companies often have large negative cash flows from working capital (inventory and receivables grow faster than payables). This is real cash outflow.

- Use unlevered FCF for project evaluation. Do not subtract interest. The discount rate should reflect the project's risk, not the company's financing choice. Financing decisions come later.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define free cash flow and explain why it matters for valuation
- [x] Distinguish unlevered from levered free cash flow
- [x] Calculate NOPAT from EBIT
- [x] Explain why depreciation is added back but also provides a tax shield
- [x] Forecast changes in net working capital
- [x] Include opportunity costs and exclude sunk costs
- [x] Include cannibalization and spillover effects
- [x] Build a quasi-income statement and derive FCF from it

---

## H. My Reflections & Critical Thoughts

The free cash flow concept is one of the most important in finance, but it is also widely misunderstood. Many managers think cash flow equals accounting earnings plus depreciation. That is close but misses capital expenditures and working capital changes. For a growing company, CapEx and working capital can be huge — sometimes larger than earnings. A company can show accounting profits for years while going bankrupt from negative cash flow.

The treatment of depreciation is subtle. It is a non-cash expense, so you add it back. But it also reduces taxes, which is a real cash saving. The NOPAT formula handles this automatically: EBIT × (1 - tax rate) gives you the after-tax operating profit, then you add back depreciation (since it was subtracted in EBIT but is not a cash flow). This is cleaner than the old "add back depreciation" shortcut.

The point about DCF being a structured conversation rather than a prediction is important. Too many people treat DCF models as if they produce "the answer." They do not. They produce an answer based on your assumptions. Changing the market share assumption from 10% to 15% changes the NPV dramatically. The value of the model is that it shows you which assumptions matter most.

---

---

# Module 4 — Decision Criteria and Sensitivity Analysis

## A. Core Idea of the Module

Once you have forecasted free cash flows, you need to decide whether to accept or reject the project. This module covers the main decision criteria: Net Present Value (NPV), Internal Rate of Return (IRR), and Payback Period. NPV is the gold standard — it always gives the right answer. IRR is widely used but can be misleading in some situations. Payback period is simple but ignores cash flows after the payback date. The module also covers sensitivity analysis: testing how NPV changes when assumptions change, identifying which assumptions matter most, and assessing the risk of the project.

---

## B. Key Concepts & Definitions

- **Net Present Value (NPV):** The sum of discounted free cash flows. NPV = Σ [FCF_t / (1 + R)^t]. Accept if NPV > 0.

- **Internal Rate of Return (IRR):** The discount rate that makes NPV = 0. Accept if IRR > cost of capital.

- **Hurdle Rate:** The minimum acceptable IRR (same as cost of capital for NPV).

- **Payback Period:** The time it takes for cumulative cash flows to equal the initial investment. Accept if payback < cutoff.

- **Discounted Payback Period:** Same as payback, but using discounted cash flows instead of nominal.

- **Break-Even Analysis:** Finding the parameter value that makes NPV = 0 (holding other parameters constant).

- **Comparative Statics:** Changing one parameter at a time to see how NPV changes.

- **Elasticity:** Percentage change in NPV divided by percentage change in a parameter. Measures sensitivity.

- **Scenario Analysis:** Changing multiple parameters at once to see NPV under different scenarios (best case, worst case, base case).

- **Monte Carlo Simulation:** Drawing random values for parameters from distributions and computing NPV many times to get a distribution of possible outcomes.

- **Capital Rationing:** When there is a limit on how much capital can be invested. In this case, ranking projects by NPV may not be enough — you need to consider profitability index.

---

## C. Main Arguments & Insights

1. **NPV is the only decision rule that always works.** It correctly accounts for the time value of money, includes all cash flows, and uses the correct discount rate for risk. Positive NPV means the project creates value. Negative NPV means it destroys value. Simple and correct.

2. **IRR is popular but has problems.** When cash flows change sign more than once, there can be multiple IRRs (making it unclear which one to use). For mutually exclusive projects, IRR can rank projects differently than NPV (leading to wrong decisions). IRR also assumes reinvestment at the IRR rate, which may be unrealistic.

3. **The payback period is dangerously simple.** It ignores cash flows after the payback date (so a project with huge cash flows in year 5 might be rejected) and ignores the time value of money (unless you use discounted payback). Its only virtue is that it is easy to understand.

4. **Sensitivity analysis tells you which assumptions matter most.** If NPV is very sensitive to market share, you should spend more time refining your market share forecast. If NPV is insensitive to the discount rate, your decision is robust to cost of capital errors.

5. **Break-even analysis shows your margin for error.** If your base case market share is 20% and break-even is 5%, you have a lot of room for error. If break-even is 18%, you need to be very confident in your forecast.

6. **Scenario and simulation analysis help with risk assessment.** A project with a high expected NPV but a 40% chance of negative NPV might be too risky. A project with a moderate expected NPV but a 5% chance of negative NPV might be safer. The distribution of outcomes matters, not just the average.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| NPV | Sum of discounted cash flows | Always — the gold standard |
| IRR | Discount rate where NPV = 0 | As a communication tool, but check for problems |
| Payback Period | Time to recover initial investment | As a rough screen, but do not rely on it |
| Discounted Payback | Same but with discounted cash flows | Better than nominal payback, still flawed |
| Break-Even Analysis | Find value that makes NPV = 0 | To see how much error you can tolerate |
| Comparative Statics | Change one parameter at a time | To identify key value drivers |
| Scenario Analysis | Best, base, worst case | To see range of possible outcomes |
| Sensitivity Table | NPV as function of two parameters | To visualize how NPV changes with assumptions |

---

## E. Formulas & Equations

- **NPV:** NPV = Σ [FCF_t / (1 + R)^t] (from t=0 to T)

- **IRR:** Solve 0 = Σ [FCF_t / (1 + IRR)^t] for IRR

- **Payback Period:** Smallest T such that Σ FCF_t (from t=0 to T) ≥ 0

- **Discounted Payback:** Same, but using discounted FCF

- **Elasticity:** (%ΔNPV) / (%ΔParameter) = (dNPV/dParameter) × (Parameter / NPV)

- **Profitability Index (for capital rationing):** NPV / Initial Investment

---

## F. Practical Implications

- Always start with NPV. If the project has positive NPV, accept it. If negative, reject it. This is the rule. Everything else is additional analysis, not a substitute.

- Use IRR as a communication tool but check for problems. If cash flows have more than one sign change (e.g., negative, then positive, then negative again), IRR can give multiple answers. Do not use IRR for mutually exclusive projects of different sizes.

- Be very careful with payback period. It is popular because it is simple, but it can lead to terrible decisions. A project with a 2-year payback and then nothing is worse than a project with a 3-year payback and then 10 more years of cash flows.

- Run sensitivity analysis on every key assumption. Change market share up and down by 50%. Change the discount rate by 2%. See how NPV moves. If NPV changes from positive to negative with reasonable changes, your project is risky.

- Find the break-even values. Ask: how low can market share go before NPV becomes zero? How high can costs go? This tells you how much uncertainty you can tolerate.

- Use scenario analysis for board presentations. Show base case, best case, and worst case. Be honest about the range of possible outcomes. This builds credibility.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Calculate NPV and apply the NPV decision rule
- [x] Calculate IRR and explain when it can be misleading
- [x] Calculate payback period and discounted payback period
- [x] Explain the limitations of IRR and payback
- [x] Perform break-even analysis for key assumptions
- [x] Use comparative statics to identify value drivers
- [x] Build a sensitivity table
- [x] Explain the difference between scenario analysis and simulation
- [x] State why NPV is the preferred decision criterion

---

## H. My Reflections & Critical Thoughts

The NPV rule is almost too simple. Discount everything to today, subtract the cost, and if the number is positive, do it. That is it. But the simplicity is the point. All of the complexity in finance — forecasting cash flows, estimating discount rates, dealing with taxes and inflation — is in service of this one rule. NPV is the unifying framework.

IRR is dangerous in the wrong hands. The multiple IRR problem is not just theoretical — it happens whenever cash flows change sign more than once. Mining projects (negative cash flows to build the mine, positive while operating, negative to close the mine) can have two IRRs. Which one do you compare to the cost of capital? Neither. Use NPV.

The payback period is popular because managers like the idea of "getting their money back quickly." But this is just a mental shortcut that often leads to bad decisions. The discounted payback period is better but still ignores cash flows after the payback date. The only justification for payback is as a very rough screen for extremely risky projects where you want your money back fast. For anything else, use NPV.

Sensitivity analysis is where the real work happens. The base case NPV is just a number. The sensitivity analysis tells you how much to trust it. If NPV is very sensitive to an assumption you are uncertain about, the project is risky. If NPV stays positive across a wide range of assumptions, the project is robust. This is the analysis that matters in real decision-making.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | None (this is foundational) | Finance is a core business function alongside marketing, operations, and accounting |
| Connects to | Introduction to Financial Accounting | Free cash flow starts from accounting numbers (revenue, costs, depreciation, working capital) |
| Connects to | Introduction to Marketing | Revenue forecasts depend on market size, market share, and pricing — all marketing inputs |
| Connects to | Introduction to Operations Management | Cost forecasts, working capital (inventory days), and capital expenditure forecasts come from operations |
| Connects to | Valuation (advanced course) | DCF analysis is the foundation of all valuation — this course teaches the basics |

---

# 📊 Concept Map

```
INTRODUCTION TO CORPORATE FINANCE
│
├── MODULE 1: Time Value of Money
│   ├── Core Insight: Money at different times = different currencies
│   ├── Tools
│   │   ├── Timeline: visual representation of cash flows
│   │   ├── Discounting: move cash back → PV = FV / (1+R)^t
│   │   └── Compounding: move cash forward → FV = PV × (1+R)^t
│   ├── Shortcuts
│   │   ├── Annuity: PV = C × [1 - (1+R)^-n] / R
│   │   ├── Perpetuity: PV = C / R
│   │   └── Growing Perpetuity: PV = C / (R - g)
│   └── Taxes: After-tax R = R_pre × (1 - Tax Rate)
│
├── MODULE 2: Interest Rates and DCF
│   ├── APR vs. EAR
│   │   ├── APR: simple interest, ignores compounding
│   │   └── EAR: effective rate, includes compounding
│   ├── Inflation
│   │   ├── Nominal return: stated return
│   │   └── Real return: return after inflation (purchasing power)
│   └── NPV Rule: Accept if PV(benefits) > PV(costs)
│
├── MODULE 3: Free Cash Flow
│   ├── Unlevered FCF (project valuation)
│   │   └── FCF = NOPAT + Depreciation - CapEx - ΔNWC
│   ├── Forecast Drivers
│   │   ├── Revenue: market size × market share × price
│   │   ├── Costs: COGS%, SG&A, R&D
│   │   ├── CapEx: upfront + ongoing
│   │   └── Working Capital: days of inventory, receivable, payable
│   └── Special Issues
│       ├── Include opportunity costs
│       ├── Exclude sunk costs
│       └── Include cannibalization
│
└── MODULE 4: Decision Criteria & Sensitivity
    ├── NPV: Accept if > 0 (gold standard)
    ├── IRR: Accept if > hurdle rate (can be misleading)
    ├── Payback: Accept if < cutoff (flawed but simple)
    ├── Sensitivity Analysis
    │   ├── Break-even: find value where NPV = 0
    │   ├── Comparative statics: change one parameter at a time
    │   └── Scenario analysis: best, base, worst case
    └── Risk Assessment: distribution of possible NPVs
```

---

# ✅ Course-Level Takeaways

This course provides a complete toolkit for financial decision-making. The core idea — time value of money — is simple but profound. Once you understand that money at different times cannot be added directly, you see the world differently. Mortgage payments, retirement savings, stock prices, project valuations — all are applications of the same principle.

The NPV rule is the unifying framework. Discount all future cash flows to today, subtract the cost, and if the number is positive, do it. This works for buying a machine, launching a product, acquiring a company, or deciding whether to go to graduate school. The hard part is not the math — it is forecasting the cash flows and choosing the right discount rate.

The course's strength is its focus on practical application. The free cash flow module shows exactly how to build a forecast from assumptions. The sensitivity analysis module shows how to test those assumptions. The weakness is that the course does not go deep into estimating the discount rate (cost of capital) — that is a separate advanced topic. But for an introduction, this is exactly the right scope.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *Valuation* | McKinsey & Company — The definitive text on DCF valuation |
| 📖 Book | *The Little Book of Valuation* | Aswath Damodaran — Accessible introduction to valuation |
| 📖 Book | *Principles of Corporate Finance* | Brealey, Myers, Allen — The classic textbook |
| 📖 Book | *The Intelligent Investor* | Benjamin Graham — Value investing principles (Ch. 1-2 on Mr. Market) |
| 📄 Article | "NPV vs. IRR: A Nuanced Perspective" | HBR — Practical guide to decision criteria |
| 🌐 Website | Aswath Damodaran's website | Free valuation data and spreadsheets from NYU professor |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#Finance` `#CorporateFinance` `#TimeValueOfMoney` `#NPV` `#IRR` `#DiscountedCashFlow` `#Valuation` `#Wharton` `#Coursera`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
