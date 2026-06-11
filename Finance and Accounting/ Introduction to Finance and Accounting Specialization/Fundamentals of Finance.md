# 📘 Fundamentals of Finance

| Field | Details |
|-------|---------|
| **Roadmap Section** | Finance |
| **Platform** | Coursera |
| **Institution / Instructor** | University of Pennsylvania — Wharton School |
| **Course URL** | [coursera.org/learn/finance-fundamentals](https://www.coursera.org/learn/finance-fundamentals) |
| **Duration** | 4 modules |

---

## 🧭 Course Overview

This course teaches the core principles of finance for making investment decisions (capital budgeting). The central idea is the Net Present Value (NPV) rule: invest in projects with positive NPV because they increase the value of the firm. The course covers time value of money concepts (present value, future value, annuities, perpetuities, compounding), valuation of fixed income securities (bonds), valuation of equity (stocks), and the Internal Rate of Return (IRR) compared to NPV. The key message is that NPV is the correct decision rule for maximizing value, while IRR can be misleading in some cases. The Separation Theorem shows that investment decisions can be made independently of consumption preferences because of borrowing and lending at market rates.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Calculate present value and future value of single cash flows
- [x] Value annuities, perpetuities, and growing streams
- [x] Convert between APRs and EARs for different compounding frequencies
- [x] Calculate bond prices and yields to maturity
- [x] Explain the relationship between coupon rate, YTM, and bond price
- [x] Value stocks using the dividend discount model (constant growth, multi-stage)
- [x] Calculate dividend growth from ROE and plowback ratio (g = b × ROE)
- [x] Apply the NPV rule to investment decisions
- [x] Calculate IRR and explain when it agrees or disagrees with NPV
- [x] State the Separation Theorem and why it matters

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Introduction and Net Present Value | Time value of money, NPV rule, Separation Theorem | ✅ |
| 2 | Fixed Income Valuation | Bond pricing, yield to maturity, yield curve | ✅ |
| 3 | Equity Valuation | Dividend discount model, growth from ROE | ✅ |
| 4 | NPV vs. Internal Rate of Return | Comparison, when IRR fails, correct use | ✅ |

---

---

# Module 1 — Introduction and Net Present Value

## A. Core Idea of the Module

The goal of capital budgeting is to make investment decisions that increase economic value. The Net Present Value (NPV) rule is the correct decision criterion: accept projects with positive NPV, reject projects with negative NPV. This module covers the time value of money (present value, future value, annuities, perpetuities), different compounding frequencies, and the Separation Theorem, which states that investment decisions can be separated from consumption preferences because investors can borrow or lend at market interest rates.

---

## B. Key Concepts & Definitions

- **Capital Budgeting:** The process of deciding which investment projects to undertake.

- **Future Value (FV):** The amount of money an investment will grow to over time at a given interest rate.

- **Present Value (PV):** The current worth of a future cash flow discounted back at an interest rate.

- **Discount Rate (r):** The interest rate used to discount future cash flows. Assumed to be ≥ 0 (with rare exceptions like negative rates during crises).

- **Net Present Value (NPV):** The sum of the initial investment (usually negative) plus the present value of all future payoffs. NPV = C₀ + C₁/(1+r) + C₂/(1+r)² + ...

- **NPV Rule:** Accept projects with NPV > 0. Reject projects with NPV < 0. Positive NPV projects increase the value of the corporation.

- **Separation Theorem:** Investment decisions can be separated from consumption preferences because investors can borrow or lend at market interest rates. Corporate officers do not need to know investors' time preferences — just follow the NPV rule.

- **Simple Interest:** Interest calculated only on the original principal. Linear growth.

- **Compound Interest:** Interest earned on both the principal and accumulated interest. Exponential growth.

- **Annuity:** A series of equal payments made over a fixed period of time.

- **Perpetuity (Console):** An annuity that lasts forever. Present value = C / r.

- **Growing Perpetuity:** A series of cash flows that grow at a fixed rate forever. PV = C / (r - g), valid only if r > g.

- **Delayed Perpetuity:** A perpetuity that starts after a delay. First find PV at the start date, then discount back to today.

- **Effective Annual Interest Rate (EAR):** The annual interest rate that, when compounded once per year, yields the same return as the stated rate compounded multiple times per year.

- **Continuous Compounding:** Compounding as frequency approaches infinity. FV = PV × e^(r × t).

---

## C. Main Arguments & Insights

1. **The NPV rule always works.** Accept positive NPV projects because they add value. Reject negative NPV projects because they destroy value. This holds regardless of individual preferences for present vs. future consumption.

2. **The Separation Theorem is fundamental.** Without it, corporate financial officers would need to know every investor's consumption preferences to make investment decisions. Because investors can borrow and lend at market rates, they can adjust the timing of their consumption independently of the firm's investment decisions. This allows stock markets to function.

3. **Compound interest is much more powerful than simple interest over long periods.** A small difference in interest rate or time horizon leads to huge differences in future value due to exponential growth.

4. **Annuities and perpetuities are everywhere.** Mortgages, bonds, pensions, and stock dividends are all annuities or perpetuities. The formulas derived from geometric series are essential shortcuts.

5. **APR is not the true interest rate.** APR ignores compounding. EAR accounts for compounding and is the correct rate for comparisons. Credit card APRs with monthly compounding have higher EARs than stated.

6. **A higher discount rate lowers present value.** Conversely, a higher growth rate (for growing perpetuities) increases present value. The condition r > g is necessary for the growing perpetuity formula to work.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| NPV Rule | Accept if NPV > 0 | Any investment decision |
| Present Value Formula | PV = FV / (1+r)^t | Single cash flow |
| Future Value Formula | FV = PV × (1+r)^t | Single cash flow |
| Annuity PV | C × [1 - (1+r)^-n] / r | Equal payments over fixed period |
| Perpetuity PV | C / r | Equal payments forever |
| Growing Perpetuity PV | C / (r - g) | Payments growing forever at rate g |
| Delayed Perpetuity | (C/r) / (1+r)^(t-1) | Perpetuity starting after delay |
| EAR | (1 + APR/n)^n - 1 | Compare rates with different compounding |
| Continuous Compounding | PV × e^(r×t) | Theoretical maximum compounding |

---

## E. Formulas & Equations

- **Present Value (single cash flow):** PV = FV / (1 + r)^t

- **Future Value (single cash flow):** FV = PV × (1 + r)^t

- **Net Present Value:** NPV = C₀ + C₁/(1+r) + C₂/(1+r)² + ... + Cₜ/(1+r)ᵗ

- **Annuity Present Value:** PV = C × [1 - (1+r)^(-n)] / r

- **Perpetuity Present Value:** PV = C / r

- **Growing Perpetuity Present Value:** PV = C / (r - g) (requires r > g)

- **Delayed Perpetuity Present Value:** PV = (C / r) / (1 + r)^(t-1) (where t = first payment year)

- **Effective Annual Rate (EAR):** EAR = (1 + APR/n)^n - 1

- **Continuous Compounding Future Value:** FV = PV × e^(r × t)

---

## F. Practical Implications

- Always use NPV to evaluate projects. Do not rely on intuition about payback periods or accounting returns.

- When comparing loan offers or investment returns, convert everything to EAR. The loan with the lower APR might have a higher EAR if it compounds more frequently.

- Use the perpetuity formula for endowments. To pay out $1 million per year forever at 5%, you need $20 million today.

- The growing perpetuity formula (dividend discount model) is very sensitive to assumptions about g and r. Small changes produce large valuation differences.

- The Separation Theorem implies that you should make investment decisions based on value creation, not on your personal need for cash now vs. later. You can always borrow against future payoffs or save current cash.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Calculate present value and future value of single cash flows
- [x] Calculate NPV for a series of cash flows
- [x] Apply the NPV rule to accept/reject decisions
- [x] State the Separation Theorem and explain why it matters
- [x] Value annuities, perpetuities, and growing perpetuities
- [x] Calculate the effective annual interest rate (EAR) from APR
- [x] Compute future value with monthly, daily, and continuous compounding

---

## H. My Reflections & Critical Thoughts

The Separation Theorem is a subtle but important idea. Most people think investment decisions are personal — "I need cash now, so I should not invest." But with borrowing and lending at market rates, you can always adjust consumption timing. A positive NPV project increases your wealth, and you can borrow against that wealth to consume now if you want. This is why corporate finance focuses on value creation, not on individual preferences.

The growing perpetuity formula is elegant but dangerous in practice. It assumes constant growth forever, which is unrealistic for most companies. The formula is very sensitive — a 1% change in g or r changes valuation dramatically. Professional analysts use multi-stage models (high growth phase, then terminal growth) to address this.

Compound interest is truly powerful. The difference between 5% and 7% over 30 years is huge. This is why starting to save early matters so much — time is the most powerful factor in compounding.

---

---

# Module 2 — Fixed Income Valuation

## A. Core Idea of the Module

Bonds are contracts where a borrower agrees to pay interest (coupons) and principal on specified dates. This module covers how to value bonds: zero-coupon bonds (single payment at maturity) and coupon bonds (periodic payments plus face value). The yield to maturity (YTM) is the discount rate that makes the bond's price equal to the present value of its cash flows. The module explains the relationship between coupon rate, YTM, and bond price: price = par when YTM = coupon rate; discount when YTM > coupon rate; premium when YTM < coupon rate. The yield curve shows yields for different maturities and is used to discount cash flows at appropriate rates.

---

## B. Key Concepts & Definitions

- **Bond:** A financial contract specifying payments of interest (coupon payments) and principal over time.

- **Face Value (Par Value):** The principal amount repaid at maturity (typically $1,000).

- **Coupon Payment (C):** The periodic interest payment. Annual coupon = Coupon Rate × Face Value.

- **Coupon Rate:** The annual interest rate stated on the bond. C = (Coupon Rate) × (Face Value).

- **Zero-Coupon Bond (Strip, Discount Bond):** A bond with no coupon payments. Pays only face value at maturity. Sold at a discount.

- **Yield to Maturity (YTM):** The discount rate that makes the present value of a bond's cash flows equal to its price. The internal rate of return (IRR) of the bond if held to maturity.

- **Holding Period Return (HPR):** The actual return earned on a bond, annualized. For zero-coupon bonds held to maturity, HPR = YTM. For bonds sold before maturity, HPR depends on market yields at sale.

- **Reinvestment Risk:** The risk that coupon payments cannot be reinvested at the same YTM. For coupon bonds, the actual holding period return equals YTM only if coupons are reinvested at YTM.

- **Par Bond:** A bond selling at face value (price = par). Occurs when YTM = Coupon Rate.

- **Discount Bond:** A bond selling below face value (price < par). Occurs when YTM > Coupon Rate.

- **Premium Bond:** A bond selling above face value (price > par). Occurs when YTM < Coupon Rate.

- **Semi-Annual Bond:** A bond that pays coupons twice per year. Common in US corporate and government bond markets. Each payment = (Coupon Rate × Face Value) / 2.

- **Yield Curve:** The relationship between bond yields (YTM) and maturities. Typically upward-sloping (higher yields for longer maturities), but can be flat or inverted.

- **Inverted Yield Curve:** Short-term yields higher than long-term yields. Often a predictor of recessions.

---

## C. Main Arguments & Insights

1. **Bond price is the present value of all future cash flows.** For zero-coupon bonds: Price = Face Value / (1 + YTM)^t. For coupon bonds: Price = PV of coupons (annuity) + PV of face value.

2. **YTM is not fixed — it changes with market conditions.** When market yields rise, bond prices fall. When yields fall, bond prices rise. This is why bonds are risky if sold before maturity.

3. **The relationship between coupon rate, YTM, and price is precise.** If YTM = coupon rate → price = par. If YTM > coupon rate → price < par (discount). If YTM < coupon rate → price > par (premium). This is a mathematical identity.

4. **Holding a bond to maturity eliminates price risk.** If you hold to maturity, you receive face value regardless of what happens to yields in between. The only risk is default risk (issuer fails to pay). This is why government bonds held to maturity are considered "risk-free" in nominal terms.

5. **Reinvestment risk is real for coupon bonds.** Even if held to maturity, the actual return may differ from YTM because coupon payments received early must be reinvested. If reinvestment rates are lower than YTM, the realized return will be lower.

6. **Semi-annual bonds are isomorphic to annual bonds with half the coupon and double the maturity.** Stated annual YTM with semi-annual coupons corresponds to half that rate per six-month period. The EAR = (1 + stated YTM/2)² - 1.

7. **The yield curve should be used for discounting, not a single flat rate.** Cash flows at different maturities should be discounted at the yield corresponding to their maturity. Using a single discount rate assumes a flat yield curve, which is rarely true.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Zero-Coupon Bond Pricing | P = F / (1+YTM)^t | Simple bonds with no coupons |
| Coupon Bond Pricing | PV of annuity (coupons) + PV of face value | Standard bonds with periodic coupons |
| YTM Calculation | Solve for r: P = Σ C/(1+r)^t + F/(1+r)^T | Find bond's implied return if held to maturity |
| Price-YTM Relationship | YTM = coupon → par; YTM > coupon → discount; YTM < coupon → premium | Quick bond valuation without calculation |
| Semi-Annual Bond Pricing | Use half the YTM, double the periods | US corporate and government bonds |
| Holding Period Return | (P₁ + Coupons - P₀) / P₀, annualized | Actual return from holding bond over a period |
| Yield Curve | Graph of YTM vs. maturity | Discounting cash flows at appropriate rates |

---

## E. Formulas & Equations

- **Zero-Coupon Bond Price:** P = F / (1 + YTM)^t

- **Coupon Bond Price:** P = C × [1 - (1+YTM)^-T] / YTM + F / (1+YTM)^T

- **Coupon Payment (annual):** C = Coupon Rate × Face Value

- **Coupon Payment (semi-annual):** C = (Coupon Rate × Face Value) / 2

- **Semi-Annual Bond Price:** P = C_semi × [1 - (1+YTM/2)^-(2T)] / (YTM/2) + F / (1+YTM/2)^(2T)

- **EAR from Semi-Annual YTM:** EAR = (1 + YTM/2)² - 1

- **Holding Period Return (annualized):** HPR = (Ending Price + Coupons - Beginning Price) / Beginning Price

---

## F. Practical Implications

- When interest rates rise, bond prices fall. If you own bonds and might need to sell before maturity, rising rates are bad. If you can hold to maturity, price changes do not matter.

- YTM is a promise, not a guarantee. For coupon bonds, the actual return depends on reinvestment rates. This is often overlooked.

- The yield curve contains information about market expectations. An inverted yield curve (short rates > long rates) has predicted many recessions.

- When valuing a project with cash flows at different times, use the yield curve. Do not use a single discount rate unless the yield curve is flat.

- Zero-coupon bonds (strips) are simpler to analyze than coupon bonds because there is no reinvestment risk.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define zero-coupon bonds and coupon bonds
- [x] Calculate the price of a zero-coupon bond given YTM
- [x] Calculate the price of a coupon bond given YTM
- [x] Explain the relationship between coupon rate, YTM, and bond price (par, discount, premium)
- [x] Calculate yield to maturity for a bond
- [x] Distinguish yield to maturity from holding period return
- [x] Explain reinvestment risk for coupon bonds
- [x] Value semi-annual bonds
- [x] Read and interpret the yield curve

---

## H. My Reflections & Critical Thoughts

The relationship between YTM and bond price is often misunderstood. When people hear "interest rates went up, so bond prices went down," they think it is unfair or irrational. But it is just math. A bond's cash flows are fixed. If market rates rise, those fixed cash flows are worth less in present value terms. The price must fall to offer the new higher yield.

Zero-coupon bonds are the purest form of fixed income. No reinvestment risk, no coupon payments to worry about. The price moves directly with changes in YTM. This is why strips are used for immunization and liability matching.

The yield curve is one of the most watched indicators in finance. An inverted yield curve has predicted every US recession since the 1970s (with some false positives). The economic logic: long-term investors demand higher yields for longer maturities (liquidity preference, term premium). When short rates exceed long rates, it signals expectations of falling rates, which often accompanies economic slowdown.

---

---

# Module 3 — Equity Valuation

## A. Core Idea of the Module

Equity represents a residual claim on a corporation's assets after bondholders are paid. The value of a stock is the present value of all future dividends. This module covers the dividend discount model (DDM): price = D₁/(1+r) + D₂/(1+r)² + ... to infinity. For constant growth, price = D₁/(r - g). Dividend growth comes from retained earnings: g = b × ROE, where b is the plowback ratio (fraction of earnings retained) and ROE is return on equity. Growth creates value only if ROE > r. If ROE < r, the company should pay out earnings as dividends rather than reinvest.

---

## B. Key Concepts & Definitions

- **Equity:** The residual claim on a corporation's assets after bondholders are paid. Represents partial ownership.

- **Dividends:** Cash payments to shareholders from the corporation's earnings.

- **Capital Gain:** The increase in stock price over time.

- **Holding Period Return (Equity):** (P₁ + Dividend - P₀) / P₀ = Dividend Yield + Capital Gain Yield.

- **Dividend Discount Model (DDM):** Stock price = present value of all future dividends. P₀ = Σ Dₜ / (1+r)ᵗ for t=1 to ∞.

- **Constant Growth Model (Gordon Growth Model):** Dividends grow at constant rate g forever. P₀ = D₁ / (r - g), requires r > g.

- **Plowback Ratio (b):** The fraction of earnings retained and reinvested in the firm. b = 1 - Payout Ratio.

- **Payout Ratio:** Fraction of earnings paid as dividends.

- **Return on Equity (ROE):** Earnings / Book Value of Equity. Measures profitability.

- **Dividend Growth Rate (g):** g = b × ROE, assuming constant ROE and plowback ratio.

- **Cash Cow:** A firm with no growth (b = 0, g = 0). Price = Earnings / r.

- **Present Value of Growth Opportunities (PVGO):** The additional value from growth beyond a cash cow. P₀ = Earnings₁ / r + PVGO.

- **Multi-Stage DDM:** Model with different growth phases (e.g., high growth for first 5 years, then terminal constant growth).

---

## C. Main Arguments & Insights

1. **The value of a stock is the present value of its future dividends.** This is a logical identity derived from the definition of return. Even if a company pays no dividends now, it is expected to pay dividends eventually. The price today reflects those future dividends.

2. **Constant growth assumption leads to a simple formula (Gordon Growth Model).** P₀ = D₁/(r - g). This is the most widely used valuation model, but it is very sensitive to inputs.

3. **Dividend growth comes from reinvesting earnings.** g = b × ROE. If a company retains earnings and invests them at a return equal to ROE, earnings and dividends grow at that rate.

4. **Growth creates value only if ROE > r.** If ROE > r, reinvesting earnings adds value (positive NPV). If ROE < r, reinvesting destroys value — the company should pay out earnings as dividends (cash cow). If ROE = r, reinvestment neither adds nor destroys value.

5. **The cash cow formula (Earnings/r) is the baseline.** Any additional value above that comes from growth opportunities (PVGO). PVGO = P₀ - Earnings₁/r.

6. **Multi-stage models are more realistic.** Most companies have an initial high-growth phase (where ROE > r) followed by a mature phase (where ROE = r or growth slows). The valuation is the present value of dividends in the high-growth phase plus the present value of the terminal value.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Dividend Discount Model (DDM) | P₀ = Σ Dₜ/(1+r)ᵗ | Fundamental equity valuation |
| Gordon Growth Model | P₀ = D₁/(r - g) | Constant growth, mature companies |
| Growth Formula | g = b × ROE | To estimate dividend growth from fundamentals |
| Cash Cow Valuation | P₀ = Earnings₁ / r | No-growth companies |
| PVGO | P₀ - Earnings₁/r | Value from growth opportunities |
| Multi-Stage DDM | Two or more growth phases | Companies with high initial growth |
| Holding Period Return | (P₁ + D₁ - P₀)/P₀ | Historical return calculation |

---

## E. Formulas & Equations

- **Dividend Discount Model (infinite horizon):** P₀ = Σ Dₜ / (1+r)ᵗ (t=1 to ∞)

- **Gordon Growth Model:** P₀ = D₁ / (r - g) (requires r > g)

- **Dividend Growth Rate:** g = b × ROE

- **Plowback Ratio:** b = 1 - (Dividends / Earnings) = 1 - Payout Ratio

- **Earnings (using growth):** E₁ = E₀ × (1 + g)

- **Cash Cow Price:** P₀ = E₁ / r

- **PVGO (Present Value of Growth Opportunities):** PVGO = P₀ - E₁ / r

- **Multi-Stage DDM:** P₀ = Σ Dₜ/(1+r)ᵗ (t=1 to n) + P_n/(1+r)ⁿ, where P_n = D_{n+1} / (r - g₂)

---

## F. Practical Implications

- The Gordon Growth Model is very sensitive. A 1% change in g or r changes valuation dramatically. Be careful with inputs.

- Companies with high ROE (> r) should reinvest earnings. Companies with low ROE (< r) should pay out dividends. This is a key insight for capital allocation.

- The cash cow valuation (Earnings/r) is a useful baseline. If a stock trades far above that, the market expects high growth. If far below, the market expects trouble.

- For companies that do not pay dividends, use a multi-stage model: estimate dividends starting at some future date (when the company matures), then discount back.

- PVGO is a useful metric. A high PVGO means the market expects significant growth. A low or negative PVGO means the market sees limited opportunities.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] State the Dividend Discount Model
- [x] Apply the Gordon Growth Model to value constant-growth stocks
- [x] Calculate dividend growth from plowback ratio and ROE (g = b × ROE)
- [x] Explain when growth creates value (ROE > r) vs. destroys value (ROE < r)
- [x] Value a cash cow (no growth) using P = E/r
- [x] Calculate PVGO (Present Value of Growth Opportunities)
- [x] Value a stock with a multi-stage dividend model

---

## H. My Reflections & Critical Thoughts

The insight that growth only creates value if ROE > r is profound. Many managers think all growth is good. But reinvesting earnings at low returns destroys value — shareholders would be better off receiving the cash as dividends and investing elsewhere. This is why mature companies with low ROE should pay out high dividends, not chase growth.

The Gordon Growth Model is elegant but often misused. The assumption of constant growth forever is unrealistic for most companies. Professional analysts use multi-stage models: high growth for 5-10 years, then terminal constant growth. Even then, the terminal value (using Gordon) often dominates the valuation, so the growth assumption still matters a lot.

PVGO is a useful way to think about stock prices. For a mature utility, PVGO is near zero — the stock price is close to Earnings/r. For a high-growth tech stock, most of the price is PVGO. This explains why tech stocks are more volatile — small changes in growth expectations cause large changes in PVGO.

---

---

# Module 4 — NPV vs. Internal Rate of Return

## A. Core Idea of the Module

The Internal Rate of Return (IRR) is the discount rate that makes NPV = 0. It is popular because it condenses a project's cash flows into a single number. For conventional investing projects (initial negative cash flow, then positive cash flows), IRR and NPV give the same accept/reject decision: accept if IRR > r. But for unconventional cash flows (financing projects, multiple sign changes), IRR can give misleading answers. The module covers when IRR fails (multiple IRRs, no IRR, financing projects) and recommends using NPV as the primary decision rule.

---

## B. Key Concepts & Definitions

- **Internal Rate of Return (IRR):** The discount rate that makes the NPV of a project equal to zero. Solve 0 = C₀ + C₁/(1+IRR) + C₂/(1+IRR)² + ... + Cₜ/(1+IRR)ᵗ.

- **IRR Rule:** Accept a project if IRR > discount rate (r). Reject if IRR < r.

- **Conventional (Investing) Project:** Initial cash flow is negative (investment), followed by positive cash flows. Only one sign change (from - to +).

- **Financing Project:** Initial cash flow is positive (borrowing), followed by negative cash flows (repayments). IRR rule must be reversed: accept if IRR < r.

- **Multiple IRRs:** When cash flows change sign more than once, the IRR equation can have multiple solutions. The IRR rule is not applicable.

- **No IRR:** Some projects have no discount rate that makes NPV = 0. NPV may be positive for all discount rates. IRR does not exist.

- **NPV Profile:** A graph of NPV vs. discount rate. For conventional projects, NPV decreases as r increases. Crosses zero at IRR.

---

## C. Main Arguments & Insights

1. **IRR is popular because it is a single number.** Executives like comparing a project's IRR to the cost of capital. But this simplicity comes at a cost: IRR can be misleading.

2. **For conventional investing projects, IRR and NPV agree.** If IRR > r, NPV > 0. If IRR < r, NPV < 0. Accept/reject decisions are the same.

3. **For financing projects, the IRR rule must be reversed.** A financing project (borrowing) has an initial positive cash flow (you receive money) followed by negative cash flows (you repay). A lower IRR is better because it means lower borrowing cost. IRR > r would mean reject, not accept.

4. **Projects with multiple sign changes can have multiple IRRs.** For example, a project with cash flows: -100, +200, -100. This has two IRRs. Which one do you compare to r? Neither — use NPV.

5. **Some projects have no IRR at all.** If the NPV profile never crosses zero, there is no discount rate that makes NPV = 0. The IRR rule simply does not apply.

6. **NPV is always correct.** NPV works for conventional projects, financing projects, projects with multiple sign changes, and projects with no IRR. It should be the primary decision rule.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| IRR Calculation | Solve 0 = Σ Cₜ/(1+IRR)ᵗ | To find the discount rate where NPV = 0 |
| IRR Rule (conventional) | Accept if IRR > r | Standard investing projects (initial negative CF) |
| IRR Rule (financing) | Accept if IRR < r (reverse rule) | Borrowing projects (initial positive CF) |
| NPV Profile | Graph of NPV vs. r | To visualize IRR and see multiple solutions |
| NPV Rule | Accept if NPV > 0 | Always correct for any project |

---

## E. Formulas & Equations

- **IRR Definition:** 0 = C₀ + C₁/(1+IRR) + C₂/(1+IRR)² + ... + Cₜ/(1+IRR)ᵗ

- **NPV Profile (conventional):** NPV(r) = C₀ + Σ Cₜ/(1+r)ᵗ, decreasing function of r

- **Multiple IRRs Occur When:** Cash flows change sign more than once

---

## F. Practical Implications

- Use NPV as your primary decision rule. It always works and directly measures value creation.

- IRR is useful for communication and for comparing projects with similar scale and timing. But be aware of its limitations.

- Do not use IRR for projects with multiple sign changes (e.g., mining projects with closure costs). Use NPV.

- Do not use IRR for financing projects unless you reverse the rule. Better yet, use NPV.

- If you must use IRR, check that the project is conventional (initial negative cash flow, then all positives). If not, be very careful.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define IRR as the discount rate where NPV = 0
- [x] Apply the IRR rule to conventional investing projects (accept if IRR > r)
- [x] Explain why financing projects require reversing the IRR rule
- [x] Identify when multiple IRRs occur (multiple sign changes)
- [x] Explain why some projects have no IRR
- [x] State that NPV is always correct and should be the primary rule

---

## H. My Reflections & Critical Thoughts

The popularity of IRR among executives is both understandable and dangerous. Understandable because a single percentage is easy to compare to the cost of capital. Dangerous because IRR can be misleading in many real-world situations. Mining projects with cleanup costs at the end (negative cash flows after years of positives) can have multiple IRRs. Which one is right? Neither — use NPV.

The financing project example is important. Imagine a project where you borrow $100 today and repay $110 in one year. IRR = 10%. If the bank's borrowing rate is 5%, is this good? No — you could borrow from the bank at 5% instead. The IRR rule (accept if IRR > r) would say accept (10% > 5%), which is wrong. You need to reverse the rule. This confusion is why NPV is better.

The course's recommendation is clear: use NPV. IRR can be a useful supplement for conventional projects, but never override NPV. This is the standard finance wisdom, and it is correct.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | None (this is foundational) | Finance fundamentals are core to all business decisions |
| Connects to | Introduction to Corporate Finance (Wharton) | This course covers similar ground (NPV, IRR, bonds, stocks) but more condensed |
| Connects to | Microeconomics | Time value of money and discount rates are used in micro for intertemporal choice |
| Connects to | Financial Accounting | Bond valuation uses accounting numbers (interest rates, cash flows) |
| Connects to | Investment Management (advanced) | Equity valuation is foundation for stock selection |

---

# 📊 Concept Map

```
FUNDAMENTALS OF FINANCE
│
├── MODULE 1: Net Present Value
│   ├── Time Value of Money
│   │   ├── PV = FV/(1+r)^t
│   │   ├── FV = PV×(1+r)^t
│   │   └── Compound vs. simple interest
│   ├── Annuities & Perpetuities
│   │   ├── Annuity: C × [1-(1+r)^-n]/r
│   │   ├── Perpetuity: C/r
│   │   └── Growing Perpetuity: C/(r-g)
│   ├── APR vs. EAR
│   │   └── EAR = (1+APR/n)^n - 1
│   ├── NPV Rule: Accept if NPV > 0
│   └── Separation Theorem: Investment ≠ consumption preferences
│
├── MODULE 2: Fixed Income Valuation
│   ├── Zero-Coupon Bonds: P = F/(1+YTM)^t
│   ├── Coupon Bonds: P = C×annuity factor + F/(1+YTM)^T
│   ├── Price-YTM Relationship
│   │   ├── YTM = coupon → par
│   │   ├── YTM > coupon → discount
│   │   └── YTM < coupon → premium
│   ├── Reinvestment Risk: Realized return ≠ YTM if reinvestment rates differ
│   ├── Semi-Annual Bonds: half coupon, half YTM, double periods
│   └── Yield Curve: YTM vs. maturity
│
├── MODULE 3: Equity Valuation
│   ├── Dividend Discount Model: P₀ = Σ Dₜ/(1+r)ᵗ
│   ├── Gordon Growth Model: P₀ = D₁/(r-g)
│   ├── Growth from Fundamentals
│   │   ├── g = b × ROE
│   │   ├── b = plowback ratio = 1 - payout ratio
│   │   └── ROE = Earnings / Book Equity
│   ├── Cash Cow: P₀ = E₁/r (no growth)
│   ├── PVGO = P₀ - E₁/r
│   └── Multi-Stage DDM: high growth + terminal growth
│
└── MODULE 4: NPV vs. IRR
    ├── IRR: discount rate where NPV = 0
    ├── IRR Rule (conventional): Accept if IRR > r
    ├── IRR Rule (financing): Accept if IRR < r (reverse)
    ├── Problems with IRR
    │   ├── Multiple IRRs (multiple sign changes)
    │   └── No IRR (NPV profile never crosses zero)
    └── NPV is always correct
```

---

# ✅ Course-Level Takeaways

This course provides the fundamental tools for making investment decisions. The NPV rule is the gold standard: accept projects with positive NPV because they add value. The time value of money (present value, future value, annuities, perpetuities) is the foundation. Bond valuation shows how interest rates and prices move inversely. Stock valuation shows that price equals the present value of future dividends, with growth coming from reinvesting earnings at returns above the cost of capital. The IRR is popular but can be misleading; NPV is always correct.

The course's strength is its focus on the core principles without too much complexity. The Separation Theorem is a key insight that separates investment decisions from consumption preferences. The growth formula (g = b × ROE) connects dividend growth to fundamental profitability. The warning about IRR (multiple IRRs, financing projects, no IRR) is essential for practitioners who might otherwise rely on it blindly.

The weakness is that the course is very condensed. Bonds and stocks deserve more depth. But as an introduction to finance fundamentals, this course covers the essential concepts clearly and correctly.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *Valuation* | McKinsey & Company — Comprehensive DCF guide |
| 📖 Book | *The Little Book of Valuation* | Aswath Damodaran — Accessible valuation |
| 📖 Book | *Principles of Corporate Finance* | Brealey, Myers, Allen — Classic textbook |
| 📖 Book | *The Intelligent Investor* | Benjamin Graham — Value investing (Ch. 1-2) |
| 🌐 Website | Aswath Damodaran's website | Free valuation data and spreadsheets |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#Finance` `#CorporateFinance` `#NPV` `#IRR` `#BondValuation` `#StockValuation` `#DividendDiscountModel` `#TimeValueOfMoney`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
