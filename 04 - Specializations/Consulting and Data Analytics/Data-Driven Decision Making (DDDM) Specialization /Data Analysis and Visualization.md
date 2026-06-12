# 📘 Data Analysis and Visualization

| Field | Details |
|-------|---------|
| **Roadmap Section** | Consulting and Data Analytics |
| **Platform** | Coursera |
| **Institution / Instructor** | University at Buffalo — State University of New York |
| **Course URL** | [coursera.org/learn/data-analyze-visualize](https://www.coursera.org/learn/data-analyze-visualize) |
| **Duration** | 3 modules |

---

## 🧭 Course Overview

This is the second course in a three-part series on data-driven decision-making. It builds on the first course (aligning organizational goals, identifying data collection opportunities, value-stream mapping) and focuses on data analysis and visualization tools and best practices. The course covers: data analysis software tools (Excel, R, Minitab, MATLAB, Python), statistical process control (SPC) for studying variation over time (common vs. special causes, control charts, control limits, specification limits), data visualization principles (chart types, design best practices, common pitfalls), data storytelling and dashboards, visualization platforms (Tableau, Excel, Power BI), insight evaluation (Six Thinking Hats method), and post-implementation testing and re-evaluation. The core message is that data alone is insufficient — analysis must be aligned with objectives, variation must be understood and controlled, and insights must be communicated clearly through effective visualization.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I can:

- [x] Identify data analysis software tools (Excel, R, Minitab, MATLAB, Python) and their use cases
- [x] Develop analytics project plans (objectives, scope, analysis type, data readiness, timelines)
- [x] Apply data cleaning, outlier management, and bias avoidance techniques
- [x] Understand Statistical Process Control (SPC) and its objectives
- [x] Distinguish common cause from special cause variation
- [x] Calculate and interpret control limits (mean, standard deviation)
- [x] Create and interpret control charts
- [x] Apply data visualization best practices (chart types, color, scaling, labeling)
- [x] Create data stories and dashboards (inverted pyramid layout)
- [x] Distinguish visualization platforms (Tableau, Excel, Power BI)
- [x] Apply Six Thinking Hats method to insight evaluation
- [x] Conduct post-implementation testing and re-evaluation

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Data Analysis Software Tools | Excel, R, Minitab, MATLAB, Python; analytics project plans; best practices | ✅ |
| 2 | Statistical Process Control (SPC) | Variation sources, control charts, common vs. special causes | ✅ |
| 3 | Data Visualization and Translation | Guiding principles, data story, Tableau/Excel/Power BI, insight evaluation | ✅ |

---

---

# Module 1 — Data Analysis Software Tools

## A. Core Idea of the Module

Organizations often struggle to establish a data culture and treat data as a business asset. Stakeholder involvement (finance, IT, data science, end users) is crucial for evaluating data platforms. Analytics project plans must include clear objectives, scope, analysis type, data readiness, and realistic timelines. Data analysis tools include Excel (basic, limited capacity), Minitab (statistical, quality improvement), MATLAB (engineering, science), R (open-source, finance/banking/e-commerce), and Python (open-source, deep learning, machine learning). Best practices include understanding data (source, structure, type), cleaning data (formats, missing values, consistency), managing outliers (scatter plots, imputation or exclusion), avoiding confirmation bias, and documenting analysis steps.

---

## B. Key Concepts & Definitions

- **Data Culture:** Treating data as a business asset. Many large organizations struggle to establish this.

- **Stakeholder Involvement:** Finance, IT, data science, and end users must be involved in evaluating data platforms.

- **Analytics Project Plan Components:**
  - Clear objectives and scope
  - Type of analysis (descriptive, diagnostic, predictive, prescriptive)
  - Availability and readiness of data
  - Realistic timelines

- **Data Analysis Software Tools:**

| Tool | Best For | Strengths | Weaknesses |
|------|----------|-----------|-------------|
| Excel | Basic analysis | Easy to use, extensive resources | Limited capacity for large datasets |
| Minitab | Statistical analysis, quality improvement | User-friendly, dropdown interfaces | Less integrative |
| MATLAB | Engineering, science | Mathematical focus, strong visualization | Proprietary, less integrative |
| R | Finance, banking, e-commerce | Open-source, extensive packages | Steep learning curve |
| Python | Data science, deep learning, machine learning | Open-source, NumPy/pandas libraries | Less polished visualizations |

- **Data Understanding:** Know source, structure, type (qualitative/quantitative). Use data dictionaries or metadata repositories.

- **Data Cleaning:** Check formats, missing values, consistency. Essential for reliable insights.

- **Outlier Management:** Detect using scatter plots. Decide to impute or exclude.

- **Confirmation Bias:** Approaching analysis with preconceived desired outcomes. Avoid by keeping an open mind.

- **Documentation:** Document analysis steps and add comments. Supports business continuity and onboarding.

---

## C. Main Arguments & Insights

1. **Tool selection depends on industry, budget, scalability, and existing software.** Switching platforms is difficult, so consider long-term.

2. **No single tool does everything.** Organizations often use a combination of tools.

3. **Data cleaning is not glamorous but essential.** Garbage in, garbage out.

4. **Confirmation bias is a common threat.** Actively seek disconfirming evidence.

5. **Documentation is not optional.** Future analysts (including yourself) will need to understand your steps.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Analytics Project Plan | Objectives, scope, analysis type, data, timelines | Project initiation |
| Excel | Basic charts, pivot tables, sparklines | Small datasets |
| Minitab | Statistical analysis, quality improvement | SPC, descriptive statistics |
| MATLAB | Mathematical analysis, visualization | Engineering, science |
| R | Statistical programming | Finance, banking, e-commerce |
| Python | Data science, machine learning | Deep learning, large datasets |
| Data Cleaning | Formats, missing values, consistency | Before analysis |
| Outlier Detection | Scatter plots | Data preparation |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks and tool comparisons only.*

---

## F. Practical Implications

- Involve all stakeholders (finance, IT, data science, end users) before selecting a platform.

- For small datasets, Excel is sufficient. For large datasets or machine learning, use Python or R.

- Spend time cleaning data before analysis. Do not skip this step.

- Document your analysis steps. Add comments to code.

- Actively guard against confirmation bias. Seek evidence that contradicts your hypothesis.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Identify strengths and weaknesses of Excel, R, Minitab, MATLAB, and Python
- [x] Develop analytics project plans (objectives, scope, analysis type, data, timelines)
- [x] Apply data cleaning and outlier management techniques
- [x] Avoid confirmation bias
- [x] Document analysis steps for business continuity

---

## H. My Reflections & Critical Thoughts

The tool comparison is useful. Excel is ubiquitous but limited. Python and R are powerful but have steeper learning curves. Minitab is excellent for quality improvement but less common outside manufacturing.

Confirmation bias is a real threat in analytics. People tend to find what they expect to find. Active strategies (seeking disconfirming evidence, blind analysis) are essential.

---

---

# Module 2 — Statistical Process Control (SPC)

## A. Core Idea of the Module

Statistical Process Control (SPC) applies statistical methods to identify and control causes of variation in processes. Variation is present in all processes. Common cause variation is inherent, natural, and stable. Special cause variation is unusual, identifiable, and addressable. The objectives of SPC are: (1) identify and eliminate sources of variation ("get the bugs out"), (2) monitor and control the process to maintain low variation ("keep the bugs out"). Control charts plot data over time with control limits at ±3 standard deviations from the mean. Data points outside control limits indicate special cause variation (unstable process). Points within indicate common cause variation (stable process). Eliminate special causes first.

---

## B. Key Concepts & Definitions

- **Statistical Process Control (SPC):** Applies statistical methods to identify and control causes of variation in processes.

- **Objectives of SPC:**
  1. Identify and eliminate sources of variation ("get the bugs out")
  2. Monitor and control the process to maintain low variation ("keep the bugs out")

- **Variation:** Differences in process attributes or characteristics. Present in all processes.

- **Common Cause Variation:** Inherent, natural variation within a process. Stable. Cannot be eliminated without changing the process.

- **Special Cause Variation:** Unusual, identifiable sources of variation. Addressable. Indicates unstable process.

- **Mean (Average):** Indicates the center of the data distribution.

- **Standard Deviation:** Measures the spread or variation around the mean. Larger = more variation.

- **Control Limits:** Set at ±3 standard deviations from the mean. Distinguish common cause from special cause variation.

- **Control Chart:** Run chart with control limits added. Plots data over time.

- **Specification Limits:** Customer requirements or engineering tolerances. Different from control limits.

- **Process Performance Monitoring Methods:**
  - Standard operating procedures (SOPs)
  - Automated controls
  - Mistake-proofing (poka-yoke)
  - SPC (quick implementation, low capital investment)

---

## C. Main Arguments & Insights

1. **Eliminate special causes first.** Special cause variation is easier to address than common cause variation. Get the process stable before reducing inherent variation.

2. **Control limits are not specification limits.** Control limits are based on process performance (3σ). Specification limits are based on customer requirements.

3. **Points outside control limits indicate special causes.** Investigate immediately.

4. **Points within control limits indicate common causes.** Process is stable. Improvement requires process redesign.

5. **Visualizing performance through control charts increases awareness.** Public displays and management reports help maintain focus.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| SPC (Statistical Process Control) | Statistical methods for variation control | Process improvement |
| Common vs. Special Cause | Inherent vs. identifiable variation | Diagnosing process stability |
| Control Chart | Time-ordered data with control limits | Monitoring process variation |
| Run Chart | Time-ordered data (no limits) | Initial visualization |
| Mean (μ) | Center of distribution | Calculating control limits |
| Standard Deviation (σ) | Spread of distribution | Calculating control limits |
| Control Limits | μ ± 3σ | Distinguishing common vs. special causes |

---

## E. Formulas & Equations

- **Control Limits (Upper and Lower):** UCL/LCL = Mean ± 3 × Standard Deviation

- **Standard Deviation (Sample):** σ = √[Σ(xi - μ)² / (n - 1)]

---

## F. Practical Implications

- Before acting on a process, determine if variation is common cause or special cause. Special causes require immediate investigation.

- Do not adjust a stable process (common cause only) based on individual data points. You will increase variation.

- Control charts are effective when complete elimination of variation is not possible. Quick implementation, low capital investment.

- Public display of control charts increases awareness and accountability.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish common cause from special cause variation
- [x] Calculate control limits (mean ± 3σ)
- [x] Create and interpret control charts
- [x] Apply SPC objectives (identify and eliminate sources, monitor and control)

---

## H. My Reflections & Critical Thoughts

The distinction between common cause and special cause variation is the most important concept in SPC. Many managers react to every variation as if it were a special cause — adjusting a stable process makes it worse. Control charts provide the discipline to know when to act and when to leave the process alone.

Eliminate special causes first. A process with special cause variation is unstable. Improvement efforts on an unstable process are wasted.

---

---

# Module 3 — Data Visualization and Translation

## A. Core Idea of the Module

Effective data visualization translates analytical insights into simple, accessible messages. Best practices include: appropriate axis scales, benchmarks (means, medians, trend lines), thoughtful color choices (blue/orange for color vision deficiency, single-color gradients), clear labeling, avoiding 3D charts, using dual-axis charts sparingly. Recommended chart types: bar/column (category comparison), stacked charts (parts of whole), line graphs (time-series), scatter plots (trends/outliers), waterfall (financial changes). Data storytelling creates a narrative guiding the audience through analysis purpose, methods, and findings. Dashboards should use inverted pyramid layout (most important at top left), one page, whitespace. Visualization platforms: Excel (basic), Power BI (Microsoft ecosystem, cost-effective), Tableau (advanced visualizations, expensive). Insight evaluation uses Six Thinking Hats method (White: facts, Yellow: optimism, Black: judgment, Red: intuition, Green: creativity, Blue: process). Post-implementation monitoring is essential — unintended consequences are common.

---

## B. Key Concepts & Definitions

- **Data Visualization Guiding Principles:**
  - Use appropriate and consistent axis scales
  - Include benchmarks (means, medians, trend lines)
  - Choose colors thoughtfully (blue/orange for color vision deficiency, single-color gradients)
  - Perform grayscale checks
  - Label charts clearly and concisely
  - Avoid overcrowding
  - Avoid 3D charts (difficult to interpret)
  - Use dual-axis charts sparingly

- **Recommended Chart Types:**
  - **Bar/Column:** Comparing volumes across categories
  - **Stacked (bar, column, area):** Parts of a whole or percentage contributions
  - **Line graphs:** Time-series data and trends
  - **Scatter plots:** Identifying trends and outliers early
  - **Waterfall charts:** Financial changes (profit and loss)

- **Data Story:** Narrative guiding audience through analysis purpose, methods, and key findings. Tailor to audience (novices, experts, executives).

- **Dashboard Design:**
  - Sketch on paper first
  - Inverted pyramid layout: most important visuals at top left
  - One page (use filters or multiple linked dashboards if needed)
  - Use whitespace to improve readability

- **Visualization Platforms Comparison:**

| Platform | Best For | Strengths | Weaknesses |
|----------|----------|-----------|-------------|
| Excel | Basic visualization | Wide range of basic charts, pivot tables, sparklines | Limited with geographic data, very large datasets |
| Power BI | Microsoft ecosystems | Handles large datasets, natural language query, Python/R scripts, cost-effective initially | Less advanced visualizations than Tableau |
| Tableau | Advanced, well-designed visualizations | Processes large datasets, connects to almost any data source, extensive educational resources | Costly to scale |

- **Six Thinking Hats (Insight Evaluation):**
  - **White Hat:** Facts, data, information
  - **Yellow Hat:** Optimism, benefits, value
  - **Black Hat:** Judgment, limitations, feasibility
  - **Red Hat:** Intuition, emotions, gut feelings
  - **Green Hat:** Creativity, alternatives, new ideas
  - **Blue Hat:** Process management, organization

- **Post-Implementation Monitoring:** Unintended consequences are common (e.g., casino campaign increased Wednesday visits but did not increase overall revenue). Create dashboards with KPIs, scheduled reviews, automated notifications for threshold breaches.

---

## C. Main Arguments & Insights

1. **Data visualization translates analysis into action.** Without effective visualization, insights are not communicated.

2. **Simplicity is key.** Overcrowded charts, 3D effects, and dual axes obscure insights.

3. **The inverted pyramid layout works for dashboards.** Most important information at top left (where Western audiences look first).

4. **Tool selection depends on budget, ecosystem, and scalability.** Excel for basic; Power BI for Microsoft shops; Tableau for advanced visualizations.

5. **Unintended consequences are common.** Monitor after implementation. The casino example: increasing Wednesday visits did not increase overall revenue.

6. **The Six Thinking Hats method ensures multiple perspectives.** Do not rely on intuition alone.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Bar/Column Chart | Category comparison | Comparing volumes |
| Line Graph | Time-series data | Trends over time |
| Scatter Plot | Identifying trends and outliers | Early analysis |
| Waterfall Chart | Financial changes | Profit and loss |
| Inverted Pyramid Dashboard | Most important at top left | Dashboard design |
| Six Thinking Hats | White, Yellow, Black, Red, Green, Blue | Insight evaluation |
| Post-Implementation Monitoring | KPI dashboards, scheduled reviews, alerts | After implementation |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks and design principles only.*

---

## F. Practical Implications

- Before creating a visualization, ask: who is the audience? What is the key message?

- Use bar charts for categories, line charts for time-series, scatter plots for relationships.

- Avoid 3D charts. They distort perception.

- Use blue/orange color schemes for accessibility (color vision deficiency).

- Sketch dashboards on paper first. Use inverted pyramid layout.

- After implementing changes, monitor KPIs closely. Unintended consequences are common.

- Use Six Thinking Hats to evaluate insights before acting.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Apply data visualization best practices (chart types, color, scaling, labeling)
- [x] Create data stories and dashboards (inverted pyramid layout)
- [x] Distinguish Tableau, Power BI, and Excel visualization capabilities
- [x] Apply Six Thinking Hats method to insight evaluation
- [x] Conduct post-implementation testing and re-evaluation

---

## H. My Reflections & Critical Thoughts

The inverted pyramid dashboard layout (most important at top left) respects how Western audiences read. This is a simple but powerful design principle.

The Six Thinking Hats method is a useful framework for group decision-making. By explicitly assigning roles (optimist, critic, creative, etc.), groups avoid the common problem of everyone reacting emotionally.

Post-implementation monitoring is often neglected. The casino example (increased Wednesday visits but no overall revenue increase) illustrates why. Good analytics includes follow-up.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | Data-Driven Process Improvement (UC Irvine) | Process mapping, data collection, alignment |
| Connects to | Operations Analytics (Wharton) | SPC, control charts, variation |
| Connects to | Healthcare Analytics | Healthcare applications of SPC |

---

# 📊 Concept Map

```
DATA ANALYSIS AND VISUALIZATION
│
├── MODULE 1: Data Analysis Software Tools
│   ├── Analytics Project Plan: objectives, scope, analysis type, data, timelines
│   ├── Tools: Excel (basic), Minitab (statistical), MATLAB (engineering), R (finance), Python (ML)
│   ├── Best Practices: understand data, clean data, manage outliers, avoid confirmation bias, document
│   └── Data Cleaning: formats, missing values, consistency
│
├── MODULE 2: Statistical Process Control (SPC)
│   ├── Objectives: get bugs out (identify), keep bugs out (monitor)
│   ├── Variation: common cause (inherent, stable) vs. special cause (unusual, addressable)
│   ├── Control Chart: time-ordered data with control limits (μ ± 3σ)
│   ├── Run Chart: time-ordered data without limits
│   └── Interpretation: points outside limits = special cause (unstable); points inside = common cause (stable)
│
└── MODULE 3: Data Visualization and Translation
    ├── Guiding Principles: appropriate scales, benchmarks, thoughtful color, clear labels, avoid 3D, avoid dual-axis
    ├── Chart Types: bar/column (categories), line (time-series), scatter (trends/outliers), waterfall (financial)
    ├── Data Story: narrative tailored to audience (novice, expert, executive)
    ├── Dashboard: inverted pyramid (most important top left), one page, whitespace
    ├── Platforms: Excel (basic), Power BI (Microsoft), Tableau (advanced)
    ├── Insight Evaluation: Six Thinking Hats (White facts, Yellow optimism, Black judgment, Red intuition, Green creativity, Blue process)
    └── Post-Implementation: monitor KPIs, scheduled reviews, automated alerts, re-evaluate
```

---

# ✅ Course-Level Takeaways

This course provides a practical framework for data analysis, statistical process control, and data visualization. The key insights: tool selection depends on industry, budget, and scalability. Data cleaning and outlier management are essential — garbage in, garbage out. Confirmation bias is a common threat; document your analysis and seek disconfirming evidence.

Statistical Process Control (SPC) distinguishes common cause variation (inherent, stable) from special cause variation (unusual, addressable). Control charts plot data over time with control limits at μ ± 3σ. Points outside limits indicate special causes (unstable process); points inside indicate common causes (stable process). Eliminate special causes first.

Data visualization must translate insights into simple, accessible messages. Use appropriate chart types (bar for categories, line for time-series, scatter for relationships). Avoid 3D charts and dual axes. Dashboards should use inverted pyramid layout (most important at top left). Six Thinking Hats method evaluates insights from multiple perspectives. Post-implementation monitoring is essential — unintended consequences are common.

The course's strength is its practical, applied approach. The weakness is that it covers multiple topics (software tools, SPC, visualization) at introductory depth. But as an introduction to data analysis and visualization, this course covers the essentials clearly.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📄 Article | "Companies are Failing in Their Efforts to Become Data Driven" | HBR (2019) |
| 📄 Article | "Why Data Analytics Can Help Drive Sales for Your Business" | Entrepreneur |
| 📄 Article | "Big Data: What's your Plan?" | McKinsey |
| 📄 Article | "How to Choose the Right Data Analytics Tools" | TechRepublic |
| 📄 Article | "Business Analytics is Ridden with Confirmation Bias" | Towards Data Science |
| 📄 Article | "The Age of Analytics and the Importance of Data Quality" | Forbes |
| 📄 Article | "An Introduction to Statistical Process Control (SPC)" | Engineering.com |
| 📄 Article | "Common Cause Vs Special Cause: Types of Variation" | Simplilearn |
| 📄 Article | "Four Essential Ways Control Charts Guide Healthcare Improvement" | Health Catalyst |
| 📄 Article | "How to Tell a Story with Data" | HBR (2013) |
| 📹 Video | "The Beauty of Data Visualization" | David McCandless (TED) |
| 🌐 Website | Information Is Beautiful | informationisbeautiful.net |
| 🌐 Website | Tableau Public Gallery | public.tableau.com |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#DataAnalysis` `#DataVisualization` `#StatisticalProcessControl` `#SPC` `#ControlCharts` `#Tableau` `#PowerBI` `#Python` `#R` `#SixThinkingHats` `#UniversityAtBuffalo`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
