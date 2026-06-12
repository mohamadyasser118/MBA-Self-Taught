# 📘 Data-Driven Process Improvement

| Field | Details |
|-------|---------|
| **Roadmap Section** | Consulting and Data Analytics |
| **Platform** | Coursera |
| **Institution / Instructor** | 	University at Buffalo — State University of New York |
| **Course URL** | [coursera.org/learn/data-driven-process-improvement](https://www.coursera.org/learn/data-driven-process-improvement) |
| **Duration** | 3 modules |

---

## 🧭 Course Overview

This course focuses on implementing data-driven process improvement to enhance organizational performance. It covers three main areas: aligning operations with performance goals (strategy deployment, catchball process, gap analysis, action planning), data collection (IoT data types, sensors, data processing levels, data validation), and process mapping (current state mapping, identifying data gaps, prioritizing gaps, future state mapping). The core message is that data collection must be aligned with business strategy — collecting data without a clear purpose wastes resources and produces no actionable insights.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I can:

- [x] Align data collection with organizational goals (avoid alignment failure)
- [x] Apply strategy deployment and catchball process to cascade objectives
- [x] Conduct gap analysis (current state vs. desired future state)
- [x] Create action plans with responsibilities, timelines, and tracking
- [x] Understand IoT data types (quantitative vs. qualitative, discrete vs. continuous, nominal vs. ordinal)
- [x] Identify IoT sensor types and their applications
- [x] Understand data processing levels (edge, fog, cloud)
- [x] Validate data quality (hardware, software, network, data checks)
- [x] Create current state process maps
- [x] Identify data gaps using process maps
- [x] Prioritize gaps using probability-impact matrix
- [x] Create future state process maps

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Operations and Performance Goals | Alignment, strategy deployment, gap analysis, action planning | ✅ |
| 2 | Data Collection | IoT data types, sensors, data processing, validation | ✅ |
| 3 | Process Mapping | Current state mapping, data gaps, prioritization, future state | ✅ |

---

---

# Module 1 — Operations and Performance Goals

## A. Core Idea of the Module

Organizations must align data collection with strategic goals. Misalignment wastes resources and produces data that cannot inform decisions. Strategy deployment (Hoshin Kanri) cascades corporate objectives down to daily work. The catchball process involves iteratively refining ideas by passing them up and down the organization. Organizations should focus on 3-5 key objectives to avoid resource conflicts. Gap analysis compares current performance to desired future state. Action plans break down goals into specific tasks with responsibilities, deadlines, and tracking.

---

## B. Key Concepts & Definitions

- **Data vs. Information:** Data = raw facts and measurements. Information = knowledge derived from analyzing data aligned with objectives.

- **Alignment Failure:** Measuring the wrong metrics disconnects performance assessment from actual objectives. Organizations waste resources building systems that do not support strategic goals.

- **Strategy Deployment (Hoshin Kanri):** Tool that aligns corporate objectives with daily work across all employees. Cascades objectives downward.

- **Catchball Process:** Cascading ideas down the organization and receiving feedback upward. Iterative review and adjustment. Rules: be open to others' ideas, propose alternatives when disagreeing, keep an open mind.

- **Key Performance Indicators (KPIs):** Should be tied to strategic objectives. Standardized across departments for consistent tracking. Limit to 3-5 critical objectives.

- **Gap Analysis:** Method to assess difference between current performance and desired future state. Questions: Where are we now? Where do we want to be? How do we close the gap?

- **Action Plan:** Breaks down goal achievement into specific tasks with assigned responsibilities and deadlines. Components: Action Steps, Responsibility (primary + support), Timing (due dates, completion dates), Comments.

- **Hoshin Kanri Benefits:** Flat management structure, creating shared vision, aligning everyone toward same objectives.

---

## C. Main Arguments & Insights

1. **Alignment failure is common and costly.** Senior management sets strategy in isolation, leading to misalignment between high-level objectives and day-to-day operations.

2. **Strategy deployment (catchball) solves the alignment problem.** By cascading ideas down and gathering feedback up, the entire organization aligns.

3. **Focus on 3-5 key objectives.** Organizations that try to do everything accomplish nothing. Limited resources require focus.

4. **Gap analysis reveals missing metrics.** List current KPIs alongside strategic objectives. Where objectives lack corresponding measurements, develop new metrics.

5. **Action plans enable execution.** Without specific tasks, responsibilities, and deadlines, strategies remain aspirations.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Strategy Deployment (Hoshin Kanri) | Align corporate objectives with daily work | Strategic planning |
| Catchball Process | Iterative feedback up and down organization | Strategy deployment |
| Gap Analysis | Current state vs. desired future state | Identifying missing metrics |
| Action Plan | Specific tasks, responsibilities, deadlines | Execution |
| Probability-Impact Matrix | Prioritize gaps by success probability and impact | Prioritization |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks only.*

---

## F. Practical Implications

- Start with strategic objectives. Design data collection to support them, not the reverse.

- Use catchball to get buy-in. Do not dictate strategy from the top without feedback.

- Limit strategic objectives to 3-5. More than that, nothing is a priority.

- Conduct gap analysis regularly. Are you measuring what matters?

- Action plans are not optional. If it is not in the plan, it will not get done.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define alignment failure and its consequences
- [x] Apply strategy deployment and catchball process
- [x] Conduct gap analysis
- [x] Create action plans (tasks, responsibilities, deadlines)

---

## H. My Reflections & Critical Thoughts

The catchball process is underused in Western organizations. Many companies cascade strategy downward without feedback loops. Catchball forces two-way communication, which builds buy-in and catches problems early.

The 3-5 objective limit is important. Many organizations have dozens of strategic objectives — which means nothing is a priority. Focus is a competitive advantage.

---

---

# Module 2 — Data Collection

## A. Core Idea of the Module

Data is broadly classified into quantitative (numerical, measurable) and qualitative (categorical, non-measurable). IoT sensors extract data from physical conditions (position, occupancy, velocity, pressure, temperature, etc.). Data processing occurs at three levels: edge (real-time response), fog (transactional responses), and cloud (centralized informational insights). Analytics maturity progresses from descriptive (what happened) to diagnostic (why) to predictive (what will happen) to prescriptive (what to do). Data validation is critical — spend ~80% of time validating data quality (hardware, software, network, data checks).

---

## B. Key Concepts & Definitions

- **Quantitative Data:** Numerical, measurable.
  - Discrete: countable (number of employees)
  - Continuous: measurable with decimals (height)

- **Qualitative Data:** Categorical, non-measurable.
  - Nominal: no order (marital status)
  - Ordinal: ordered categories (satisfaction levels)

- **IoT Sensor Types:** Position, occupancy, velocity, force, pressure, flow, acoustic, humidity, light, radiation, temperature, chemical, biosensors.

- **Data Processing Levels:**
  - **Edge:** Near the device for real-time response
  - **Fog:** Intermediate processing for transactional responses
  - **Cloud:** Centralized processing for informational insights

- **Analytics Maturity Levels (increasing complexity and value):**
  - Descriptive: what happened
  - Diagnostic: why it happened
  - Predictive: what will happen
  - Prescriptive: what actions to take

- **Data Validation Checks:**
  - Hardware: calibration, maintenance, focused validation tests
  - Software: CRM, financial software, integration, hosting, user experience
  - Network: data transmission protocols, connections (USB, Ethernet, Bluetooth, WiFi, cellular)
  - Data: anomalies, inconsistencies, corrupt data (80% of time)

- **Data Collection Strategy Framework:**
  - Context: key questions data must answer
  - Content: what data is needed
  - Collection: right type, amount, frequency (volume, variety, velocity, veracity, volatility)

- **Data Reporting Types:**
  - Static: historical insights
  - Live: real-time data
  - Dynamic: combined static and live, interactive, predictive (machine learning)

---

## C. Main Arguments & Insights

1. **Data is useless without context.** Simply having data does not guarantee useful information. Thoughtful analysis aligned with objectives is required.

2. **Messy data is the norm, not the exception.** Spend ~80% of time validating data quality. Do not skip this step.

3. **Edge processing enables real-time response.** For time-sensitive applications (autonomous vehicles, industrial control), cloud latency is unacceptable.

4. **Analytics maturity increases business value.** Descriptive is baseline; prescriptive is highest value but most complex.

5. **Data privacy must be designed in from the start.** Do not add privacy as an afterthought.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Quantitative vs. Qualitative | Numerical vs. categorical data | Data classification |
| Data Types (Discrete/Continuous, Nominal/Ordinal) | Measurement scales | Statistical analysis selection |
| Edge-Fog-Cloud Processing | Three levels of data processing | IoT architecture design |
| Analytics Maturity Model | Descriptive → Diagnostic → Predictive → Prescriptive | Capability assessment |
| Data Validation (Hardware, Software, Network, Data) | Four quality checks | Before analysis |
| Data Collection Strategy (Context, Content, Collection) | Three-part framework | Designing data collection |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks only.*

---

## F. Practical Implications

- Classify your data before analysis. Quantitative vs. qualitative determines appropriate statistical methods.

- For time-sensitive applications, use edge or fog processing. Do not send everything to the cloud.

- Spend 80% of your time validating data. Garbage in, garbage out.

- Start with descriptive analytics. Do not jump to prescriptive without mastering earlier levels.

- Design data privacy from the start. Retrospective privacy fixes are expensive and often fail.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish quantitative from qualitative data
- [x] Distinguish discrete from continuous, nominal from ordinal
- [x] Identify IoT sensor types and applications
- [x] Distinguish edge, fog, and cloud processing
- [x] Apply analytics maturity model (descriptive → diagnostic → predictive → prescriptive)
- [x] Validate data quality (hardware, software, network, data)

---

## H. My Reflections & Critical Thoughts

The 80% rule for data validation is realistic. Many analysts want to jump to analysis immediately, but messy data produces misleading results. Clean data is not glamorous, but it is essential.

The edge-fog-cloud distinction is important for IoT. Sending all data to the cloud creates latency and bandwidth costs. Edge processing (real-time) and fog processing (transactional) are often more appropriate.

---

---

# Module 3 — Process Mapping

## A. Core Idea of the Module

Process maps document every step in a process, combining material processing steps with information flow and related data. They serve as communication tools to clarify processes, build consensus, and identify data gaps. Steps include: assemble team, Gemba walk (observe actual work), document steps on sticky notes, arrange left to right, identify decision points, inspections, loops. After mapping current state, identify data gaps (what data is collected vs. what data is needed). Prioritize gaps using probability-impact matrix (probability of success vs. impact on organization). Create future state map by updating with prioritized gaps. Continuously update as gaps are resolved.

---

## B. Key Concepts & Definitions

- **Process Map:** Visual representation of all critical steps in a process, combining material processing steps with information flow and related data.

- **Gemba Walk:** Observe actual work where it happens. Gather data, understand workflow and challenges.

- **Common Process Structures:**
  - **Sequential:** Steps depend on output of previous steps
  - **Parallel:** Steps run simultaneously (splits and joins)
  - **Decision Points:** Assign transactions to different paths based on criteria
  - **Inspections:** Check for pass/fail outcomes (may send items back for repair)
  - **Loops:** Rework cycles that consume additional resources and time

- **Value Stream Map (VSM):** Visualizes flow of materials and information. Identifies waste and improvement opportunities.

- **Current State Map:** "As is" process. Do not jump to solutions. List issues for later analysis.

- **Data Gaps:** Where strategic objectives lack corresponding measurements. Compare existing data collection points with data requirements.

- **Probability-Impact Matrix (Prioritization):**
  - Axes: Probability of success (low to high) vs. Impact on organization (low to high)
  - Upper right (high probability, high impact): address immediately
  - Lower right (high probability, low impact): delegate
  - Upper left (low probability, high impact): plan and strategize
  - Lower left (low probability, low impact): avoid

- **Future State Map:** Current state map updated with prioritized gaps. Visual roadmap of improvement progress. Continuously update.

---

## C. Main Arguments & Insights

1. **Process maps reveal data gaps.** By visualizing the process, you can see where data is collected, what is collected, and how. Compare to strategic objectives to find gaps.

2. **Focus on current state first.** Do not jump to solutions. Understand the "as is" process before designing "to be."

3. **The probability-impact matrix forces prioritization.** Limited resources require focus. Not all gaps are equal.

4. **Future state maps are living documents.** Continuously update as gaps are resolved. They are not one-time deliverables.

5. **Gemba walks are essential.** You cannot map a process from a conference room. Observe actual work where it happens.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Process Map | Visual representation of steps | Understanding workflows |
| Gemba Walk | Observing actual work | Data collection, understanding challenges |
| Value Stream Map | Flow of materials and information | Identifying waste |
| Probability-Impact Matrix | Prioritize gaps (probability vs. impact) | Resource allocation |
| Current State Map | "As is" process | Baseline understanding |
| Future State Map | "To be" process with prioritized gaps | Improvement roadmap |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks only.*

---

## F. Practical Implications

- Assemble a cross-functional team for process mapping. Include those who perform and manage the process.

- Do a Gemba walk before mapping. Observing actual work reveals issues that interviews miss.

- Use sticky notes on a wall. Digital tools are fine, but physical mapping enables collaboration.

- Focus on current state first. Do not jump to solutions. List issues for later analysis.

- Validate the map with multiple sessions. Ensure all stakeholders agree.

- Use the probability-impact matrix to prioritize. Do not try to fix everything at once.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Create current state process maps
- [x] Conduct Gemba walks
- [x] Identify sequential, parallel, decision, inspection, and loop structures
- [x] Identify data gaps using process maps
- [x] Prioritize gaps using probability-impact matrix
- [x] Create future state process maps

---

## H. My Reflections & Critical Thoughts

The Gemba walk is a Lean principle that is often skipped. Managers sit in conference rooms and theorize about processes they have never observed. The Gemba walk forces you to see the actual work.

The probability-impact matrix is a simple but powerful prioritization tool. The upper right quadrant (high probability, high impact) gets immediate attention. The lower left (low probability, low impact) gets ignored. This is how to focus limited resources.

Future state maps as living documents is an important point. Many organizations create a future state map, then put it on a shelf. Continuous updating keeps improvement efforts aligned.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | Introduction to Operations Management | Process analysis, value stream mapping, Lean |
| Connects to | Operations Analytics (Wharton) | Data-driven decision-making, KPIs |
| Connects to | Healthcare Operations (Northeastern) | Healthcare applications (Adventist HealthCare case) |

---

# 📊 Concept Map

```
DATA-DRIVEN PROCESS IMPROVEMENT
│
├── MODULE 1: Operations and Performance Goals
│   ├── Alignment Failure: measuring wrong metrics, wasted resources
│   ├── Strategy Deployment (Hoshin Kanri): cascade objectives, align daily work
│   ├── Catchball Process: iterative feedback up and down
│   ├── Gap Analysis: current state vs. desired future state
│   └── Action Plan: tasks, responsibilities, deadlines, tracking
│
├── MODULE 2: Data Collection
│   ├── Data Types
│   │   ├── Quantitative: discrete (countable), continuous (measurable)
│   │   └── Qualitative: nominal (no order), ordinal (ordered)
│   ├── IoT Sensors: position, occupancy, velocity, pressure, temperature, etc.
│   ├── Processing Levels: edge (real-time), fog (transactional), cloud (informational)
│   ├── Analytics Maturity: descriptive → diagnostic → predictive → prescriptive
│   └── Data Validation: hardware, software, network, data (80% of time)
│
└── MODULE 3: Process Mapping
    ├── Process Map: visual representation of steps
    ├── Gemba Walk: observe actual work
    ├── Structures: sequential, parallel, decision points, inspections, loops
    ├── Current State Map: "as is" process
    ├── Data Gaps: compare existing collection to strategic objectives
    ├── Prioritization (Probability-Impact Matrix): probability vs. impact
    │   ├── High/High: address immediately
    │   ├── High/Low: delegate
    │   ├── Low/High: plan and strategize
    │   └── Low/Low: avoid
    └── Future State Map: current map updated with prioritized gaps
```

---

# ✅ Course-Level Takeaways

This course provides a practical framework for data-driven process improvement. The key insights: data collection must be aligned with strategic objectives — measuring the wrong metrics wastes resources. Strategy deployment (Hoshin Kanri) cascades objectives downward; the catchball process enables upward feedback. Focus on 3-5 key objectives. Conduct gap analysis to identify missing metrics. Create action plans with tasks, responsibilities, and deadlines.

Data is classified as quantitative (discrete/continuous) and qualitative (nominal/ordinal). IoT sensors collect data from physical conditions. Processing occurs at edge (real-time), fog (transactional), and cloud (informational) levels. Analytics maturity progresses from descriptive to diagnostic to predictive to prescriptive. Spend ~80% of time validating data quality (hardware, software, network, data).

Process mapping reveals data gaps. Conduct Gemba walks to observe actual work. Map current state ("as is") before designing future state. Identify sequential, parallel, decision, inspection, and loop structures. Prioritize gaps using probability-impact matrix (probability of success vs. impact). Create future state maps as living documents, continuously updated.

The course's strength is its practical, step-by-step approach. The weakness is that it focuses on healthcare applications (though principles apply broadly). As an introduction to data-driven process improvement, this course covers the essentials clearly.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📄 Article | "The True Measures of Success" | HBR (2012) |
| 📄 Article | "Why Your Data Strategy Needs to Align with Your Business Strategy" | Dataversity |
| 📄 Article | "Strategic Deployment: How To Think Like Toyota" | IndustryWeek |
| 📄 Article | "An Introduction to the Lean Concept of Catchball" | Kainexus |
| 📄 Article | "Hoshin Kanri" | Lean Production |
| 📄 Article | "Gap Analysis: Guide and Template" | Execute Strategy |
| 📄 Article | "12 Things about IoT Analytics every Technology CEO Needs to Know" | Towards Data Science |
| 📄 Article | "What is Value Stream Mapping?" | ASQ |
| 📹 Video | "How Facebook Tracks Your Data" | NYT (YouTube) |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#ProcessImprovement` `#DataDriven` `#IoT` `#ProcessMapping` `#ValueStreamMapping` `#HoshinKanri` `#GapAnalysis` `#UCIrvine`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
