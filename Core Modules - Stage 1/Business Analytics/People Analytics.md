# 📘 People Analytics

| Field | Details |
|-------|---------|
| **Roadmap Section** | Business Analytics |
| **Platform** | Coursera |
| **Institution / Instructor** | Wharton School, University of Pennsylvania — Prof. Cade Massey, Prof. Martine Haas, Prof. Matthew Bidwell |
| **Course URL** | [coursera.org/learn/wharton-people-analytics](https://www.coursera.org/learn/wharton-people-analytics) |
| **Duration** | 3 modules (plus wrap-up) |

---

## 🧭 Course Overview

People analytics applies data-driven approaches — like those used in finance, marketing, and operations — to the management of people in organizations. The course covers four main areas: performance evaluation (distinguishing skill from luck, avoiding cognitive biases), staffing (hiring, internal mobility, attrition), collaboration (organizational network analysis, mapping and improving collaboration), and talent management (evaluating fundamental abilities, legal and ethical considerations). The core message is that intuition and experience are insufficient for managing people effectively — data, properly analyzed, leads to better decisions about hiring, promotion, evaluation, and retention.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Distinguish between signal (true performance) and noise (random variation) in performance data
- [x] Identify and avoid common biases in performance evaluation (outcome bias, hindsight bias, narrative bias)
- [x] Explain regression to the mean and its implications for evaluating extreme performance
- [x] Apply the wisdom of crowds principle (signal independence) to performance assessment
- [x] Evaluate hiring assessments by their predictive validity (work samples, cognitive tests, structured interviews, etc.)
- [x] Distinguish correlation from causation and identify omitted variable bias and reverse causality
- [x] Analyze internal mobility (promotions, job postings) and attrition using data
- [x] Map and evaluate collaboration networks using organizational network analysis (size, strength, range, density, centrality)
- [x] Understand legal and ethical constraints in people analytics (adverse impact, discrimination)

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Performance Evaluation | Distinguishing skill from luck, cognitive biases, regression to the mean | ✅ |
| 2 | Staffing and Assessing Causality | Hiring, internal mobility, attrition, correlation vs. causation | ✅ |
| 3 | Collaboration and Talent Management | Organizational network analysis, improving collaboration | ✅ |

---

---

# Module 1 — Performance Evaluation

## A. Core Idea of the Module

Performance measures are noisy — they reflect both true performance (skill or effort) and random variation (luck). The challenge is separating signal from noise. The module covers cognitive biases that lead us to overestimate skill and underestimate luck: outcome bias, hindsight bias, narrative bias, and the law of small numbers. It introduces key statistical concepts: regression to the mean (extreme outcomes tend to move toward the average), the wisdom of crowds (independent signals improve accuracy), and the importance of process measures over outcome measures in uncertain environments.

---

## B. Key Concepts & Definitions

- **People Analytics:** Using data and analytical tools to make better decisions about managing people in organizations.

- **Signal vs. Noise:** Performance = True Performance (skill/effort) + Random Error (luck/noise). The goal of evaluation is to isolate the signal.

- **Outcome Bias:** Evaluating decisions based on outcomes rather than the quality of the decision process. A good decision can have a bad outcome due to luck; a bad decision can have a good outcome.

- **Hindsight Bias:** The tendency to see past outcomes as predictable, even when they were not. "I knew it all along."

- **Narrative Bias:** The tendency to create causal stories that explain outcomes, often overlooking the role of chance and statistical regression.

- **Law of Small Numbers:** The mistaken belief that small samples represent the population as accurately as large samples. Small samples have more extreme variation.

- **Regression to the Mean:** Extreme outcomes (very high or very low) are partly due to luck. In subsequent periods, performance tends to regress toward the average.

- **Wisdom of Crowds:** The average of many independent forecasts is more accurate than individual forecasts. Requires signal independence (opinions are not correlated).

- **Signal Independence:** The value of multiple assessments depends on their independence. Correlated opinions (from shared discussions, backgrounds, or advisors) add little new information.

- **Process vs. Outcome Measures:** Process measures (e.g., shots on goal, number of sales bids) are often more reliable predictors than outcome measures (e.g., goals, sales closed), especially in uncertain environments.

- **Persistence:** If performance is due to skill, it should persist over time. Lack of persistence suggests luck played a significant role.

---

## C. Main Arguments & Insights

1. **Performance evaluation is hard because data is noisy.** The NFL draft example shows that even with millions of dollars at stake and extensive data, distinguishing skill from luck is difficult. Top picks perform better on average, but year-to-year consistency (persistence) is low — much of draft success is chance.

2. **Regression to the mean is everywhere, and people misunderstand it.** The Israeli Air Force example: instructors observed that praising pilots after a good landing was followed by worse performance, while yelling after a bad landing was followed by improvement. They concluded yelling works. But this is just regression to the mean — extreme performance, good or bad, tends to move toward average regardless of feedback.

3. **Small samples produce extreme results.** A small factory has more extreme quality control days than a large factory with the same process. A batter's average in the first week of the season is more extreme than over a full year. People misjudge this, leading to overreaction.

4. **The wisdom of crowds requires independent signals.** If everyone shares the same information and biases, adding more people adds little value. To improve accuracy, seek diverse, independent opinions and design processes that prevent correlation.

5. **Process measures are often better than outcome measures.** In hockey, goals (outcome) are noisy; shots on goal and puck possession (process) are more reliable and predictive. In sales, number of bids or customer contacts may be better than closed sales, especially in uncertain markets. Dell shifted from pure results-based evaluation to a mix after seeing negative behaviors driven solely by outcome targets.

6. **Ask critical questions before evaluating performance:**
   - Are observed differences persistent over time?
   - Is the sample size sufficient? Can it be increased?
   - Are we using multiple independent signals?
   - Are our measures fundamental and comprehensive?

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Signal vs. Noise Model | Performance = Skill + Luck | Any performance evaluation |
| Regression to the Mean | Extreme outcomes regress toward average | After extreme performance (good or bad) |
| Wisdom of Crowds | Average of independent forecasts is accurate | When collecting multiple opinions |
| Signal Independence | Independent opinions add value; correlated opinions do not | When designing evaluation processes |
| Persistence Test | Does performance stay consistent over time? | To distinguish skill from luck |
| Law of Small Numbers | Small samples have extreme variation | When interpreting small-sample data |
| Process vs. Outcome | Process measures are often more reliable | In uncertain or noisy environments |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks only.*

- **Performance Decomposition:** Performance = True Performance (Skill/Effort) + Random Error (Luck)

---

## F. Practical Implications

- When evaluating performance, always ask: "How much of this outcome was luck?" Extreme outcomes almost always contain significant luck.

- Do not overreact to extreme performance. A record-breaking sales quarter is likely followed by a lower quarter (regression to the mean) regardless of what you do.

- Use large samples. Do not make decisions based on small data sets. If you cannot increase sample size, be very cautious.

- When collecting multiple opinions, ensure they are independent. Do not let people discuss before giving their assessment. Seek diverse backgrounds and perspectives.

- In uncertain environments, weight process measures more heavily than outcome measures. Reward the behaviors that lead to success, not just the outcomes.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish signal (true performance) from noise (luck)
- [x] Identify and avoid outcome bias, hindsight bias, and narrative bias
- [x] Explain regression to the mean and its implications for performance evaluation
- [x] Apply the wisdom of crowds principle (signal independence)
- [x] Explain why small samples produce more extreme results
- [x] Distinguish process measures from outcome measures
- [x] Ask critical questions to improve evaluation accuracy

---

## H. My Reflections & Critical Thoughts

The NFL draft example is powerful. Even in a data-rich, high-stakes environment with sophisticated evaluation methods, year-to-year consistency is low. Teams that draft well one year are no more likely to draft well the next year. This suggests much of what we call "talent evaluation skill" is actually luck. The same is likely true in many organizational contexts — hiring managers who made great hires last year may not be skilled; they may have been lucky.

The Israeli Air Force example is the clearest illustration of regression to the mean I have seen. The instructor's conclusion (yelling works, praise harms) was completely backward. This is not just an academic point — it has real consequences. People design feedback systems based on this misinterpretation every day.

Process vs. outcome is a crucial distinction. In sales, rewarding only closed deals encourages discounting, sandbagging, and other negative behaviors. Rewarding the number of quality bids or customer contacts encourages the right behaviors. The challenge is measuring process well.

---

---

# Module 2 — Staffing and Assessing Causality

## A. Core Idea of the Module

Staffing is about getting the right people into the right jobs. This module covers hiring (which assessments predict performance best), internal mobility (promotions, job postings, transfers), and attrition (understanding and reducing turnover). The module also covers causality: correlation does not imply causation. Common problems include omitted variable bias (a third variable explains the relationship) and reverse causality (Y causes X, not X causes Y). Methods for establishing causality include controlling for variables, natural experiments, and randomized controlled trials.

---

## B. Key Concepts & Definitions

- **Staffing:** The process of getting people into and moving people through jobs in an organization. Includes hiring, internal mobility (promotions, lateral transfers, job postings), and attrition management.

- **Predictive Validity:** The degree to which an assessment method predicts future job performance.

- **Work Sample:** A hiring assessment where candidates perform actual job tasks. Most effective predictor of performance.

- **Cognitive Ability Test (General Intelligence):** Strong predictor of performance across many jobs. Second most effective after work samples.

- **Structured Interview:** All candidates asked the same questions, scored against a rubric. Good predictive validity.

- **Unstructured Interview:** No fixed questions or scoring. Poor predictor due to biases and overconfidence.

- **Reference Check:** Surprisingly ineffective — reflects the referrer's biases more than the candidate's true performance.

- **Personality Tests:** Weak predictors of performance. Useful only for specific traits in specific jobs.

- **Multivariate Regression:** A statistical method that estimates the relationship between multiple predictors (e.g., GPA, experience, test scores) and an outcome (e.g., performance).

- **Peter Principle:** Employees get promoted until they reach a level where they are incompetent. Success in a current job does not guarantee success in a higher-level job.

- **Causality vs. Correlation:** Correlation means two variables move together. Causation means one variable causes the other.

- **Omitted Variable Bias:** An observed relationship between X and Y may be due to a third variable O that influences both.

- **Reverse Causality:** Y causes X, rather than X causing Y.

- **Natural Experiment:** A real-world situation where something approximating random assignment occurs (e.g., draft lottery, cutoff scores).

- **Randomized Controlled Trial (RCT):** The gold standard for causality — randomly assign treatment and control groups.

- **Attrition (Turnover):** Employees leaving the organization. Costly due to hiring/training costs, loss of knowledge, and disruption.

- **Survival Analysis:** A statistical method that models the timing and likelihood of employee departures over time.

---

## C. Main Arguments & Insights

1. **Not all hiring assessments are equal.** Work samples and cognitive ability tests have high predictive validity. Unstructured interviews and reference checks have very low validity. Yet organizations over-rely on unstructured interviews because interviewers are overconfident in their judgment.

2. **Algorithms outperform human judgment in hiring.** Studies show that algorithmic screening reduces turnover; manager discretion increases turnover. Algorithms are not perfect (they explain 30-40% of performance variation), but they are better than intuition.

3. **The Peter Principle is real: success in a current job does not predict success at a higher level.** A study of salespeople found that the best individual salespeople did not become the best managers. Promotion criteria often reward current job performance, not future potential.

4. **Internal job postings lead to better outcomes than manager-driven promotions.** Research shows internal postings produce more unusual career paths, better job matches, and stronger negotiation positions for employees (leading to higher pay raises). The structured selection process reduces bias.

5. **Correlation is not causation — and this matters for people decisions.** Common mistakes:
   - Poor performance might lead to job posting, not the other way around (reverse causality)
   - Improvement after training might be regression to the mean, not training effectiveness
   - Lower performers may stay longer because better performers get promoted, not because tenure causes lower performance

6. **Attrition is costly and often misunderstood.** Pay has a surprisingly weak correlation with turnover. The quality of the relationship with supervisors and job satisfaction are stronger predictors. Turnover is higher early in a job (fit assessment) and decreases with age and career progression.

7. **Natural experiments and RCTs are the gold standard for causality.** Example: the draft lottery (random assignment to military service) allowed researchers to study causal effects of education and veteran status. In organizations, randomized controlled trials are possible (e.g., randomly assign some candidates to a new screening process) but require commitment.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Predictive Validity Ranking | Work samples > cognitive ability > structured interview > personality > unstructured interview > reference checks | Designing hiring processes |
| Multivariate Regression | Estimates effect of multiple predictors on outcome | Identifying which traits predict performance |
| Natural Experiment | Real-world random or quasi-random assignment | When RCT is not feasible |
| Randomized Controlled Trial (RCT) | Random assignment to treatment/control groups | Gold standard for causal inference |
| Survival Analysis | Models timing of employee departures | Predicting and understanding attrition |
| Peter Principle Framework | Current performance ≠ future potential | Promotion decisions |

---

## E. Formulas & Equations

> *No specific formulas in this module — conceptual frameworks only.*

- **Attrition Rate (simple):** (Number of departures) / (Average headcount)

---

## F. Practical Implications

- Redesign hiring processes around what works: work samples and cognitive ability tests. Reduce reliance on unstructured interviews.

- Use algorithmic screening where possible. Algorithms are not perfect, but they are more consistent and less biased than human judgment.

- For promotions, look beyond current job performance. Assess future potential using different criteria (e.g., leadership, collaboration, strategic thinking).

- Use internal job postings instead of manager-driven promotions. The structured process reduces bias and leads to better matches.

- Before concluding that X causes Y, ask: is there an omitted variable? Could reverse causality explain the relationship?

- When possible, run experiments. Randomly assign candidates to different screening processes and compare outcomes.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Rank hiring assessments by predictive validity
- [x] Explain why unstructured interviews are poor predictors
- [x] Explain why reference checks are ineffective
- [x] Apply multivariate regression conceptually to hiring decisions
- [x] Distinguish correlation from causation
- [x] Identify omitted variable bias and reverse causality
- [x] Explain natural experiments and RCTs as causal methods
- [x] Analyze attrition patterns and identify drivers of turnover

---

## H. My Reflections & Critical Thoughts

The finding that unstructured interviews are poor predictors is striking, given how ubiquitous they are. Interviewers are overconfident — they believe they can judge candidates after a 30-minute conversation. The research says they cannot. Structured interviews (same questions, same scoring rubric) are much better, but organizations resist because they feel "mechanical."

The algorithm vs. human judgment finding is important. Algorithms explain only 30-40% of performance variation — that is not great. But human judgment explains even less. The standard is not perfection; it is "better than the alternative."

Internal job postings as a superior mechanism is counterintuitive. Managers believe they know their teams best and should make promotion decisions. But research shows that posted jobs lead to better matches and more unusual career paths. The structured process reduces the bias of manager familiarity.

Causality is the hardest concept in this course. Most organizational data is observational, not experimental. Smart analysts learn to ask: "What else could explain this pattern?" before concluding causation.

---

---

# Module 3 — Collaboration

## A. Core Idea of the Module

Collaboration is essential in modern organizations, but it is often poorly understood. Organizational Network Analysis (ONA) maps who collaborates with whom, revealing patterns invisible in formal organizational charts. Key dimensions of collaboration networks include size (number of connections), strength (intensity of ties), range (diversity of connections), density (how interconnected one's contacts are), and centrality (position in the network).

---

## B. Key Concepts & Definitions

- **Collaboration:** Working with others to produce or create something. Focuses on information sharing, knowledge exchange, and joint problem-solving among employees.

- **Organizational Network Analysis (ONA):** A set of tools and techniques to map and analyze collaboration networks within organizations. Reveals who seeks information from whom.

- **Formal Organizational Chart:** The official reporting structure (who reports to whom). Often different from actual collaboration patterns.

- **Collaboration Network:** The actual pattern of information sharing and collaboration among employees. May cross formal reporting lines.

- **Network Size:** The number of people an individual collaborates with. Larger networks provide more information but may lead to overload.

- **Network Strength (Tie Strength):** The intensity of a collaborative relationship. Strong ties indicate trust, frequent interaction, and mutual support. Require more maintenance.

- **Network Range (Diversity):** The variety of groups or departments an individual is connected to. Greater range provides access to diverse information and perspectives.

- **Network Density:** How interconnected an individual's contacts are with each other. High density means your contacts know each other (trust, shared context). Low density means your contacts are disconnected (access to novel information).

- **Network Centrality:** An individual's position in the network. Central positions provide access to information and influence. Can also lead to overload.

- **Collaborative Overload:** When employees are overwhelmed by excessive collaboration demands (too many requests for help, information, or input). Reduces productivity.

---

## C. Main Arguments & Insights

1. **Formal org charts and actual collaboration networks are different.** Who reports to whom is not the same as who talks to whom. ONA reveals the real collaboration patterns.

2. **Network position has trade-offs.** Central individuals have access to information and influence but risk overload. Isolated individuals have focus and autonomy but miss valuable information. Neither is universally good or bad.

3. **Dense networks (everyone knows everyone) enable trust but may limit novel information.** Sparse networks (contacts do not know each other) provide access to diverse information but require more effort to verify.

4. **Collaborative overload is real and costly.** Some employees spend 80%+ of their time helping others. These individuals are valuable but risk burnout. Redistributing collaboration demands can improve overall productivity.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Organizational Network Analysis (ONA) | Maps collaboration patterns | To understand who collaborates with whom |
| Network Size | Number of connections | To identify overload or isolation |
| Network Strength (Tie Strength) | Intensity of relationships | To identify trusted partners |
| Network Range (Diversity) | Variety of groups connected | To identify access to diverse information |
| Network Density | Interconnectedness of contacts | To understand trust vs. novel information |
| Network Centrality | Position in network | To identify influencers and bottlenecks |
| Collaborative Overload | Excessive collaboration demands | To identify at-risk employees |

---

## E. Formulas & Equations

> *No formulas in this module — conceptual frameworks and network metrics.*

- **Network Size:** Count of direct connections
- **Network Density (ego network):** (Actual ties among contacts) / (Possible ties among contacts)

---

## F. Practical Implications

- Map collaboration networks before trying to improve them. You cannot fix what you cannot see.

- Look for overloaded employees (many inbound requests) and redistribute collaboration demands. Ask: "Who else could answer these questions?"

- Look for isolated employees (few inbound requests). Are they underutilized? Do they need better connections?

- Use network analysis to break down silos. Identify bridges between departments and encourage cross-group collaboration.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Define collaboration and its importance in organizations
- [x] Distinguish formal org charts from actual collaboration networks
- [x] Describe the five building blocks of collaboration networks (size, strength, range, density, centrality)
- [x] Identify trade-offs of central vs. isolated network positions
- [x] Define collaborative overload and its risks

---

## H. My Reflections & Critical Thoughts

Organizational Network Analysis (ONA) is one of the most powerful tools in people analytics. Formal org charts tell you who reports to whom. ONA tells you who actually works with whom — often very different. A manager may be central in the org chart but isolated in the collaboration network. An individual contributor may be the hub of information flow. ONA reveals these hidden patterns.

Collaborative overload is a real phenomenon. Some employees become the go-to experts for everyone. They are valued, but they risk burnout. The solution is not to reduce collaboration — it is to redistribute it. Identify who else can answer common questions. Build systems that spread the load.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | Managing Social and Human Capital (Wharton) | Performance evaluation, motivation, and incentives from HR course |
| Connects to | Business Analytics Specialization | Regression, causality, and data analysis methods |
| Connects to | Introduction to Marketing | Survey design, data collection, and customer analytics methods apply to employees |
| Connects to | Project Risk Management | Manager judgment biases (overconfidence, outcome bias) appear in both |

---

# 📊 Concept Map

```
PEOPLE ANALYTICS
│
├── MODULE 1: Performance Evaluation
│   ├── Signal vs. Noise: Performance = Skill + Luck
│   ├── Cognitive Biases
│   │   ├── Outcome Bias (judge decisions by outcomes, not process)
│   │   ├── Hindsight Bias ("I knew it all along")
│   │   └── Narrative Bias (causal stories ignore chance)
│   ├── Regression to the Mean: Extreme outcomes regress to average
│   ├── Law of Small Numbers: Small samples have extreme variation
│   ├── Wisdom of Crowds: Independent signals improve accuracy
│   └── Process vs. Outcome: Process measures often more reliable
│
├── MODULE 2: Staffing and Causality
│   ├── Hiring Assessments (predictive validity)
│   │   ├── High: Work samples, cognitive ability, structured interviews
│   │   └── Low: Unstructured interviews, reference checks, personality tests
│   ├── Internal Mobility
│   │   ├── Peter Principle: Current success ≠ future potential
│   │   └── Internal job postings > manager promotions
│   ├── Causality Challenges
│   │   ├── Omitted Variable Bias (third variable explains relationship)
│   │   └── Reverse Causality (Y causes X, not X causes Y)
│   └── Attrition (Turnover)
│       ├── Drivers: Supervisor relationship, job satisfaction (not pay)
│       └── Methods: Survival analysis, regression
│
└── MODULE 3: Collaboration
    ├── Organizational Network Analysis (ONA)
    │   ├── Network Size (number of connections)
    │   ├── Network Strength (tie intensity)
    │   ├── Network Range (diversity of groups)
    │   ├── Network Density (interconnectedness of contacts)
    │   └── Network Centrality (position in network)
    └── Collaborative Overload: Too many requests → burnout
```

---

# ✅ Course-Level Takeaways

This course provides a practical framework for using data to manage people more effectively. The key insights: performance evaluation requires distinguishing skill from luck — cognitive biases lead us to overestimate skill and underestimate chance. Hiring assessments are not equal: work samples and cognitive ability tests work; unstructured interviews and reference checks do not. Correlation is not causation — omitted variables and reverse causality are everywhere. Organizational Network Analysis reveals hidden collaboration patterns that formal org charts miss.

The course's strength is its evidence-based approach. Every claim is supported by research (NFL draft, mutual funds, Israeli Air Force, sales studies, investment bank data). The case studies are memorable and applicable. The weakness is that the course is conceptual — it does not teach the statistical methods (regression, survival analysis) in depth. But as an introduction to people analytics, this course provides the conceptual foundation and the critical questions to ask.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *Moneyball* | Michael Lewis — Analytics in baseball |
| 📄 Article | "The Loser's Curse: Decision Making and Market Efficiency in the NFL Draft" | Cade Massey, Richard Thaler (2013) |
| 📄 Article | "Outcome Bias in Decision Evaluation" | Baron & Hershey (1988) |
| 📄 Article | "Retaining Talent: Replacing Misconceptions With Evidence-Based Strategies" | Allen, Bryant, Vardaman (2010) |
| 📄 Article | "Collaborative Overload" | Rob Cross, HBR (2016) |
| 📄 Article | "Algorithm Aversion" | Dietvorst, Simmons, Massey (2014) |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#PeopleAnalytics` `#HR` `#PerformanceEvaluation` `#Staffing` `#OrganizationalNetworkAnalysis` `#Causality` `#Wharton`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
