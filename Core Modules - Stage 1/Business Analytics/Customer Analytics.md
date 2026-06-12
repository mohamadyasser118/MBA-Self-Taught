# 📘 Customer Analytics

| Field | Details |
|-------|---------|
| **Roadmap Section** | Business Analytics |
| **Platform** | Coursera |
| **Institution / Instructor** | Wharton School, University of Pennsylvania — Prof. Peter Fader, Prof. Ron Berman, Prof. Eric Bradlow |
| **Course URL** | [coursera.org/learn/wharton-customer-analytics](https://www.coursera.org/learn/wharton-customer-analytics) |
| **Duration** | 5 modules |

---

## 🧭 Course Overview

Customer analytics is a relatively new field that leverages data and technology to understand and influence customer behavior. The course is structured around three types of analytics: descriptive (understanding past behavior), predictive (forecasting future behavior), and prescriptive (recommending actions to influence outcomes). The core message is that customer analytics moves beyond aggregate data to granular, individual-level behavioral data, enabling firms to predict customer lifetime value, optimize marketing actions, and make better strategic decisions.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Distinguish between descriptive, predictive, and prescriptive analytics
- [x] Collect customer data through surveys, passive methods, and field experiments
- [x] Design effective surveys (question types, flow, validity, reliability)
- [x] Calculate and interpret Net Promoter Score (NPS)
- [x] Apply regression analysis for one-period-ahead predictions
- [x] Use probability models (BTYD) for long-term customer behavior prediction
- [x] Understand recency, frequency, and monetary value (RFM) as key predictors
- [x] Apply optimization to pricing decisions (marginal revenue = marginal cost)
- [x] Understand market structure, competition, and online advertising attribution
- [x] Apply customer analytics to real-world business problems

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Introduction to Customer Analytics | Overview of descriptive, predictive, prescriptive analytics | ✅ |
| 2 | Descriptive Analytics | Data collection: surveys, NPS, passive data, causal experiments | ✅ |
| 3 | Predictive Analytics | Regression, probability models (BTYD), RFM, CBCV | ✅ |
| 4 | Prescriptive Analytics | Optimization, pricing, market structure, competition | ✅ |
| 5 | Applications / Case Studies | ROI, attribution, new data sources, industry examples | ✅ |

---

---

# Module 1 — Introduction to Customer Analytics

## A. Core Idea of the Module

Customer analytics leverages data and technology to understand and influence customer behavior. The course is built around three types of analytics: descriptive (what happened), predictive (what will happen), and prescriptive (what should we do). The goal is to make learners conversant with key concepts, data structures, technologies, and models — not to teach technical programming skills.

---

## B. Key Concepts & Definitions

- **Customer Analytics:** The collection, management, analysis, and strategic use of detailed, granular, individual-level customer behavior data.

- **Descriptive Analytics:** Systematically collecting and interpreting data to understand past customer behavior. Answers "what happened?"

- **Predictive Analytics:** Using customer data to forecast future behaviors — purchase likelihood, frequency, churn, customer lifetime value.

- **Prescriptive Analytics:** Recommending actions to influence customer behavior and optimize outcomes (pricing, targeting, ad allocation).

- **Business Analytics Specialization (Wharton):** Covers financial analytics, people analytics, customer analytics, and operations analytics.

---

## C. Main Arguments & Insights

1. **Customer analytics is behavioral, not attitudinal.** It relies on actual customer actions (purchases, clicks, visits), not surveys or stated intentions.

2. **Granular, individual-level data is essential.** Aggregate data masks important heterogeneity. Customer analytics focuses on understanding each customer's behavior.

3. **Descriptive, predictive, and prescriptive analytics work together.** Descriptive provides the foundation; predictive forecasts; prescriptive recommends actions.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Descriptive Analytics | Summarizes past behavior | Understanding what happened |
| Predictive Analytics | Forecasts future behavior | Planning for what will happen |
| Prescriptive Analytics | Recommends actions | Optimizing decisions |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual introduction only.*

---

## F. Practical Implications

- Start with descriptive analytics to understand past patterns before predicting or prescribing.
- Different business questions require different types of analytics. Match the method to the question.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define customer analytics and its three types
- [x] Distinguish descriptive, predictive, and prescriptive analytics
- [x] Explain why individual-level behavioral data is essential

---

## H. My Reflections & Critical Thoughts

The three-part framework (descriptive, predictive, prescriptive) is a useful way to organize analytics work. Many organizations jump to prediction without first understanding descriptive patterns — this leads to garbage-in, garbage-out.

---

---

# Module 2 — Descriptive Analytics

## A. Core Idea of the Module

Descriptive analytics involves systematically collecting and interpreting data to inform actionable business decisions. Methods include exploratory techniques (focus groups, online communities), surveys (with careful question design), passive data collection (point-of-sales, media, social, web, mobile), and causal data collection (field experiments, A/B testing). The choice of method depends on the managerial question being asked.

---

## B. Key Concepts & Definitions

- **Exploratory Questions:** Seek to understand why trends occur. Methods: focus groups, market research online communities (100-500 people, 6-12 months).

- **Descriptive Questions:** Quantify customer behavior (market share, segmentation). Methods: surveys, passive data.

- **Causal Questions:** Investigate impact of changes (e.g., website modification). Methods: field experiments, A/B testing.

- **Focus Groups:** Small groups discussing brand perceptions. Traditional exploratory tool.

- **Market Research Online Communities (MROCs):** Larger groups (100-500) engaged over longer periods (6-12 months). Build deeper relationships and richer insights.

- **Survey Question Types:**
  - Itemized category (balanced satisfaction scales)
  - Comparative (specifies reference for comparison)
  - Ranking (order attributes by importance)
  - Paired comparisons (force comparison between two products)
  - Likert scales (agreement levels on statements)
  - Continuous scales (real-time preferences)

- **Validity:** Does the survey predict meaningful outcomes (customer profits, firm performance)?

- **Reliability (Test-Retest):** Stability of survey responses over time.

- **Net Promoter Score (NPS):** "How likely are you to recommend this brand to a friend or colleague?" (0-10 scale).
  - Promoters (9-10), Passives (7-8), Detractors (0-6)
  - NPS = %Promoters - %Detractors

- **Passive Data Collection:** Unobtrusive data collection without direct customer input.
  - Point of sales data (ACNielsen, IRI, SPINS)
  - Media data (Kantar Media, Nielsen — radio/TV audience)
  - Social media analytics (Hootsuite, Sprout Social — brand mentions, sentiment)
  - Web data (compete.com, company websites)
  - Mobile data (apps, location-based services like Foursquare)

- **Causal Data Collection:** Establishes cause-and-effect. Requires correlation, temporal precedence (cause before effect), and no confounding third factors.

- **A/B Testing (Field Experiment):** Randomly assign different versions (e.g., landing page A vs. B) to customer groups. Tools: Optimizely, Leanplum.

---

## C. Main Arguments & Insights

1. **The choice of data collection method must align with the managerial question.** Exploratory questions need qualitative methods; descriptive questions need quantitative; causal questions need experiments.

2. **NPS is simple and popular, but may not outperform other satisfaction measures** (like American Customer Satisfaction Index) in predicting industry growth.

3. **Higher satisfaction correlates with profitability, but the relationship is often nonlinear.** Many companies experience a plateau where increasing satisfaction does not boost profitability.

4. **Passive data (point of sales, web, mobile) is comprehensive and timely**, but lacks psychographic details and information on what customers considered but did not buy.

5. **Correlation does not imply causation.** The stork-baby story (warm houses have both storks and babies) illustrates hidden third factors.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Exploratory Methods | Focus groups, online communities | Understanding why trends occur |
| Surveys | Itemized, comparative, ranking, Likert, continuous | Quantifying attitudes and preferences |
| Net Promoter Score (NPS) | %Promoters - %Detractors | Measuring customer loyalty |
| Passive Data | POS, media, social, web, mobile | Comprehensive behavioral data |
| Causal Experiments | A/B testing, field experiments | Establishing cause-and-effect |
| Survey Design Steps | Population definition, question drafting, flow, pre-testing | Creating valid, reliable surveys |

---

## E. Formulas & Equations

- **NPS:** %Promoters (9-10) - %Detractors (0-6)

---

## F. Practical Implications

- Use focus groups and online communities for exploratory questions (why is this happening?).
- Use surveys and passive data for descriptive questions (how many, how much?).
- Use A/B testing for causal questions (does changing X cause Y?).
- When designing surveys: use simple language, avoid ambiguity, sequence easy questions first, pilot test.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish exploratory, descriptive, and causal questions
- [x] Calculate and interpret Net Promoter Score (NPS)
- [x] Design effective surveys (question types, flow, validity, reliability)
- [x] Collect passive data (POS, media, social, web, mobile)
- [x] Design A/B tests to establish causality
- [x] Explain why correlation does not imply causation

---

## H. My Reflections & Critical Thoughts

The distinction between exploratory, descriptive, and causal questions is critical. Many organizations jump to causal conclusions from descriptive data. The NPS is popular but limited; the nonlinear relationship between satisfaction and profitability is often ignored.

---

---

# Module 3 — Predictive Analytics

## A. Core Idea of the Module

Predictive analytics uses customer data to forecast future behaviors: purchase likelihood, frequency, churn, and customer lifetime value. Methods include regression analysis (for short-term, one-period-ahead predictions) and probability models like "buy till you die" (BTYD) for long-term projections. Key predictors are recency, frequency, and monetary value (RFM). The module also covers Customer-Based Corporate Valuation (CBCV), which aggregates customer lifetime values to value entire companies.

---

## B. Key Concepts & Definitions

- **Predictive Analytics:** Using customer data to forecast future activities — purchase likelihood, frequency, churn, customer lifetime value.

- **Regression Analysis:** Quantifies relationship between dependent variable (sales/demand) and independent variables (price, advertising). Equation: Demand = Intercept + (Slope × Price) + Error.

- **R-squared:** Measures model fit — proportion of demand variation explained by independent variables. 0.87 means 87% explained.

- **Recency, Frequency, Monetary Value (RFM):** Key predictors of customer behavior.
  - Recency (how recently) often outweighs frequency in predicting future value.

- **Probability Models (Buy Till You Die — BTYD):** Capture underlying behavioral processes for long-term projections.
  - "Purchase coin" — probability of purchase each period
  - "Death coin" — probability customer becomes inactive

- **Customer Lifetime Value (CLV):** Present value of future customer cash flows.

- **Customer-Based Corporate Valuation (CBCV):** Aggregates customer lifetime values to value a company from the bottom up.

- **Zodiac:** Company founded by Peter Fader to apply BTYD models at scale. Acquired by Nike in 2018.

---

## C. Main Arguments & Insights

1. **Regression works well for short-term predictions (one or two periods ahead)** but struggles with longer horizons because it requires input data from the immediately preceding period.

2. **Probability models (BTYD) are better for long-term predictions** because they model the underlying behavioral process (purchase and death coins).

3. **Recency is a stronger predictor than frequency.** A customer who donated recently but less frequently is often more valuable than one who donated frequently but missed a recent period.

4. **Customer lifetime value distributions are not normal.** Most customers have low value; a small segment generates high value.

5. **CBCV shifts valuation from traditional top-down financial metrics to a customer-centric perspective.** Even with limited public data, CBCV can estimate customer metrics and company value.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Regression Analysis | Quantifies relationships between variables | One-period-ahead predictions |
| RFM (Recency, Frequency, Monetary) | Key predictors of customer behavior | Customer value assessment |
| Buy Till You Die (BTYD) | Probability model with purchase and death coins | Long-term customer behavior prediction |
| Customer Lifetime Value (CLV) | Present value of future customer cash flows | Customer valuation |
| Customer-Based Corporate Valuation (CBCV) | Bottom-up valuation from customer CLVs | Company valuation |

---

## E. Formulas & Equations

- **Regression Equation:** Demand = Intercept + (Slope × Price) + Error

- **R-squared:** (Explained variation) / (Total variation)

- **CLV (conceptual):** Σ (Future cash flows) / (1 + r)^t

---

## F. Practical Implications

- Use regression for short-term predictions (next period). Use BTYD for long-term projections (customer lifetime value, churn timing).

- Recency matters more than frequency. A recent purchase is a stronger signal than many past purchases.

- Customer lifetime value distributions are highly skewed. Focus on identifying and serving high-value customers.

- CBCV helps companies communicate hidden customer value to investors.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Apply regression analysis for one-period-ahead predictions
- [x] Interpret R-squared as a measure of model fit
- [x] Explain why recency often outweighs frequency in predicting future value
- [x] Apply probability models (BTYD) for long-term customer behavior prediction
- [x] Define Customer Lifetime Value (CLV)
- [x] Explain Customer-Based Corporate Valuation (CBCV)

---

## H. My Reflections & Critical Thoughts

The BTYD model is elegant — modeling customer behavior as two coins (purchase and death) captures the essential uncertainty. The validation showing close matches between predicted and actual behavior by recency/frequency segments is impressive.

The CBCV application to Farfetch's IPO filing demonstrates practical value. Even with limited public data, the model accurately matched aggregate metrics (active customers, orders, cohort revenue).

---

---

# Module 4 — Prescriptive Analytics

## A. Core Idea of the Module

Prescriptive analytics recommends actions to influence customer behavior and optimize outcomes. It builds on descriptive and predictive analytics. Key applications include pricing optimization (balancing quantity, revenue, and profit), understanding market structure (competition, consumer heterogeneity, bundling), and online advertising attribution (measuring causal impact of ads).

---

## B. Key Concepts & Definitions

- **Prescriptive Analytics:** Recommends actions to influence customer behavior and optimize business goals.

- **Prescription Problem:** Goal (e.g., maximize profit) + Action (e.g., change price) + Model (e.g., demand curve).

- **Marginal Revenue = Marginal Cost:** Profit-maximizing condition. Additional revenue from selling one more unit equals additional cost of producing it.

- **Willingness to Pay:** Maximum price a consumer is willing to pay for additional units.

- **Bundling:** Selling items together at a fixed price. Can capture more consumer surplus than uniform pricing.

- **Strategic Interaction:** Competitors react to pricing changes. Lowering prices may trigger a price war (game theory).

- **Attribution (Online Advertising):** Measuring effect of ads on consumer behavior. Common metric: Click-Through Rate (CTR) = clicks / impressions.

- **Causality in Advertising:** Correlation (more ads → higher CTR) may be due to targeting (ads shown to consumers already likely to click). Experiments needed to establish causation.

---

## C. Main Arguments & Insights

1. **Different goals lead to different optimal prices.** Maximizing quantity suggests price = 0. Maximizing revenue suggests a positive price. Maximizing profit (including costs) suggests a higher price than revenue-maximizing.

2. **The profit-maximizing condition is marginal revenue = marginal cost.** This principle finds the optimal price without exhaustive calculation.

3. **Bundling can increase profit.** For a single consumer buying multiple items, calculating willingness to pay for each unit and bundling can capture more consumer surplus.

4. **Competition matters.** In strategic markets, lowering prices may trigger price wars that erode profits for all.

5. **Correlation in advertising data does not equal causation.** Ads may be targeted to consumers already likely to click. Experiments show that one ad increases CTR, but additional ads do not.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Profit Maximization | MR = MC | Pricing decisions |
| Willingness to Pay | Maximum price per unit | Bundling decisions |
| Bundling | Selling items together at fixed price | Capturing consumer surplus |
| Strategic Interaction (Game Theory) | Competitor reactions | Pricing in competitive markets |
| A/B Testing | Random assignment to treatment/control | Establishing causal ad effects |

---

## E. Formulas & Equations

- **Revenue:** R = Price × Quantity

- **Profit:** π = Revenue - Cost

- **Marginal Revenue (MR):** Additional revenue from selling one more unit

- **Marginal Cost (MC):** Additional cost of producing one more unit

- **Profit Maximization Condition:** MR = MC

- **Click-Through Rate (CTR):** Clicks / Impressions

---

## F. Practical Implications

- For pricing, consider your goal: maximize quantity, revenue, or profit? Each leads to a different optimal price.

- The MR = MC principle works for any profit-maximizing firm, regardless of market structure.

- Bundling can increase profits for products with heterogeneous willingness to pay.

- In competitive markets, consider strategic reactions before changing prices.

- Do not assume correlation in ad data is causation. Run experiments to measure true ad impact.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish quantity-maximizing, revenue-maximizing, and profit-maximizing prices
- [x] Apply the MR = MC condition to find optimal price
- [x] Explain how bundling can increase profit
- [x] Explain strategic interaction in competitive markets
- [x] Distinguish correlation from causation in advertising data
- [x] Design A/B tests to measure ad effectiveness

---

## H. My Reflections & Critical Thoughts

The MR = MC principle is foundational to microeconomics and pricing. The course applies it clearly to customer analytics.

The advertising attribution problem is critical: last-click attribution is flawed, but even multi-touch attribution is correlational, not causal. Experiments (A/B testing, geo experiments) are needed for causal claims.

---

---

# Module 5 — Applications / Case Studies

## A. Core Idea of the Module

The ultimate goal of analytics is to inform and improve business decision-making. Applications include measuring ROI of advertising channels, understanding channel cannibalization, using new data sources (shopper path, eye-tracking, RFID), and learning from leading firms (Kohl's, Netflix, American Express, Amazon, Starbucks).

---

## B. Key Concepts & Definitions

- **Last-Click Attribution:** Credits the last ad seen before purchase. Flawed because it ignores the full customer journey.

- **Channel Cannibalization:** New channel (e.g., mobile app) may reduce usage of existing channels (TV, web) but can increase total engagement.

- **Gross Rating Points (GRPs):** Reach (fraction of households) × Frequency (amount of content watched).

- **Wandering (Shopper Behavior):** Shoppers who wander more and take less efficient paths tend to buy more items.

- **Eye-Tracking Data:** Reveals which shelf positions (eye level, left side) attract more attention → higher recall, consideration, purchase.

- **Unplanned Purchases:** About 60% of purchases are unplanned. In-store marketing significantly influences buying decisions.

- **Media Carts:** Emerging technology providing real-time product recommendations based on shopper location and cart contents.

---

## C. Main Arguments & Insights

1. **Last-click attribution is flawed.** The customer journey involves multiple touchpoints. Analytics must consider full path to purchase.

2. **Channel cannibalization is not always bad.** Launching a mobile platform may reduce TV viewing but increase total engagement.

3. **Facebook likes and mentions add predictive power beyond traditional online and TV ads.** Market efficiency observed: economic value of ads aligns with cost across channels.

4. **Shoppers who wander more buy more.** Encouraging some wandering may increase sales, even if it reduces efficiency.

5. **Eye-level and left-side shelf positions get more attention.** Visual fixations correlate with recall, consideration, and purchase.

6. **Technology and granular data enable better targeting.** Kohl's uses Wi-Fi geospatial data for location-based discounts. Netflix uses meta-tagging for content design. American Express uses social network data to predict churn.

7. **Amazon predicts purchases before they happen** to enable same-day delivery by pre-shipping items to local retailers.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Last-Click Attribution | Credits last ad before purchase | Common but flawed |
| Channel Cannibalization | New channel may reduce existing channels | Multi-channel strategy |
| GRPs (Reach × Frequency) | Measures advertising exposure | Media planning |
| Shopper Path / RFID | Tracks customer movement in stores | Store layout optimization |
| Eye-Tracking | Measures visual attention | Shelf placement, packaging |
| Geospatial Targeting | Location-based offers (e.g., Kohl's) | In-store mobile marketing |
| Predictive Pre-shipping | Amazon ships before purchase | Same-day delivery |

---

## E. Formulas & Equations

- **GRPs:** Reach (%) × Frequency

- **Click-Through Rate (CTR):** Clicks / Impressions

- **Unplanned Purchase Rate:** ~60% of purchases

---

## F. Practical Implications

- Move beyond last-click attribution. Consider full customer journey.

- For retail, use shopper path and eye-tracking data to optimize store layout and shelf placement. Eye-level and left-side positions are valuable.

- About 60% of purchases are unplanned. In-store marketing (displays, placement, recommendations) significantly influences sales.

- Use granular data (Wi-Fi, mobile, social) to target customers based on behavior, not just demographics.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Explain the flaw in last-click attribution
- [x] Explain channel cannibalization
- [x] Apply GRPs (reach × frequency) to media planning
- [x] Use shopper path and eye-tracking data for store optimization
- [x] Apply geospatial targeting (e.g., Kohl's)
- [x] Explain Amazon's predictive pre-shipping
- [x] Apply customer analytics to real-world business problems

---

## H. My Reflections & Critical Thoughts

The wandering-shopper finding is counterintuitive: less efficient paths lead to more purchases. Efficiency is not always the goal in retail.

The eye-tracking finding (eye level, left side) is actionable. Many stores place high-margin items at eye level for a reason.

Amazon's predictive pre-shipping is a remarkable example of prescriptive analytics: predicting purchases before they happen to enable same-day delivery. This is the future of customer analytics.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | Introduction to Marketing (Wharton) | Customer analytics applies marketing concepts |
| Builds on | Business Analytics Specialization | Descriptive, predictive, prescriptive framework shared |
| Connects to | Operations Analytics (Wharton) | Regression, optimization, simulation shared methods |
| Connects to | People Analytics (Wharton) | RFM, CLV, BTYD models apply to employees as well |

---

# 📊 Concept Map

```
CUSTOMER ANALYTICS
│
├── MODULE 1: Introduction
│   ├── Descriptive Analytics (what happened)
│   ├── Predictive Analytics (what will happen)
│   └── Prescriptive Analytics (what should we do)
│
├── MODULE 2: Descriptive Analytics
│   ├── Exploratory Methods (focus groups, online communities)
│   ├── Surveys (itemized, comparative, ranking, Likert, continuous)
│   │   ├── Validity (predicts meaningful outcomes)
│   │   └── Reliability (stability over time)
│   ├── Net Promoter Score (NPS) = %Promoters - %Detractors
│   ├── Passive Data (POS, media, social, web, mobile)
│   └── Causal Data (A/B testing, field experiments)
│
├── MODULE 3: Predictive Analytics
│   ├── Regression Analysis (one-period predictions)
│   │   └── R-squared (model fit)
│   ├── RFM (Recency, Frequency, Monetary Value)
│   ├── Probability Models (Buy Till You Die)
│   │   ├── Purchase coin (probability of purchase)
│   │   └── Death coin (probability of inactivity)
│   ├── Customer Lifetime Value (CLV)
│   └── Customer-Based Corporate Valuation (CBCV)
│
├── MODULE 4: Prescriptive Analytics
│   ├── Pricing Optimization
│   │   ├── Quantity-maximizing (P = 0)
│   │   ├── Revenue-maximizing (MR = 0)
│   │   └── Profit-maximizing (MR = MC)
│   ├── Market Structure
│   │   ├── Willingness to pay
│   │   ├── Bundling
│   │   └── Strategic interaction (game theory)
│   └── Online Advertising Attribution (correlation ≠ causation)
│
└── MODULE 5: Applications
    ├── ROI / Attribution (last-click flawed)
    ├── Channel Cannibalization
    ├── GRPs (Reach × Frequency)
    ├── Shopper Path / RFID / Eye-Tracking
    ├── Geospatial Targeting (Kohl's)
    ├── Predictive Pre-shipping (Amazon)
    └── Examples: Kohl's, Netflix, AmEx, Google, Starbucks
```

---

# ✅ Course-Level Takeaways

This course provides a complete framework for customer analytics: descriptive (understanding past behavior), predictive (forecasting future behavior), and prescriptive (recommending actions). Key methods include surveys, NPS, passive data, A/B testing, regression, probability models (BTYD), RFM, CLV, CBCV, and pricing optimization. The applications module shows how leading firms (Kohl's, Netflix, AmEx, Amazon, Starbucks) use these methods to drive business decisions.

The course's strength is its practical, non-technical approach. It focuses on concepts, frameworks, and applications — not programming. The BTYD model and CBCV are particularly valuable for understanding long-term customer value and company valuation. The weakness is that it does not teach implementation details (regression, BTYD estimation) — but as an introduction, this is appropriate.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *Customer Centricity* | Peter Fader |
| 📖 Book | *The Customer-Base Audit* | Peter Fader, Bruce Hardie, Michael Ross |
| 📄 Article | "The Loser's Curse" | Cade Massey, Richard Thaler (NFL draft) |
| 🌐 Software | Optimizely, Leanplum | A/B testing tools |
| 🌐 Software | Hootsuite, Sprout Social | Social media analytics |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#CustomerAnalytics` `#MarketingAnalytics` `#CLV` `#BTYD` `#RFM` `#NPS` `#CBCV` `#Wharton`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
