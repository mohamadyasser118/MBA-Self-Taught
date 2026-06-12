# 📘 Introduction to Operations Management

| Field                        | Details                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------ |
| **Roadmap Section**          | Core Stage 1 — Operations Management                                                       |
| **Part of Specialization**   | Business Foundations Specialization — Wharton School (Course 5 of 6)                       |
| **Platform**                 | Coursera                                                                                   |
| **Institution / Instructor** | Wharton School, University of Pennsylvania — Prof. Christian Terwiesch                     |
| **Course URL**               | [coursera.org/learn/wharton-operations](https://www.coursera.org/learn/wharton-operations) |
| **Duration**                 | 4 modules                                                                                  |

---

## 🧭 Course Overview

This course teaches the fundamental tools and frameworks for analyzing and improving how work gets done. Operations management is the study of work processes — from making cars to treating patients to serving coffee. The course covers four main areas: process analysis (finding bottlenecks and measuring capacity), lean operations (eliminating waste and managing flow), Little's Law (the relationship between inventory, flow rate, and flow time), and quality management (reducing variability and preventing defects). The core argument is that operational excellence comes from understanding your processes deeply, identifying constraints, and systematically removing waste — not from working harder or cutting corners.

---

## 🎯 Course-Level Learning Objectives

By the end of this course, I will be able to:

- [x] Draw a process flow diagram and identify the bottleneck
- [x] Calculate capacity, flow rate, utilization, and cycle time
- [x] Compute labor content, cost of direct labor, and labor utilization
- [x] Apply Little's Law to inventory, flow time, and flow rate problems
- [x] Calculate inventory turns and days of supply
- [x] Use the Seven Sources of Waste framework (TIM WOOD) to spot inefficiencies
- [x] Calculate Overall Equipment Effectiveness (OEE) and percentage value-add time
- [x] Distinguish common cause from assignable cause variation
- [x] Calculate process capability (Cp)
- [x] Apply root cause analysis tools (5 Whys, fishbone diagrams, Pareto charts)

---

## 🗺️ Course Structure at a Glance

| Module | Title | Core Theme | Status |
|--------|-------|-----------|--------|
| 1 | Introduction to Operations & Process Analysis | The efficiency frontier, system inhibitors, finding bottlenecks | ✅ |
| 2 | Optimizing Flow & Lean Operations | Labor productivity, line balancing, waste reduction, pull systems | ✅ |
| 3 | Little's Law | The relationship between inventory, flow rate, and flow time | ✅ |
| 4 | Quality | Variability, process capability, root cause analysis, PDCA | ✅ |

---

---

# Module 1 — Introduction to Operations and Process Analysis

## A. Core Idea of the Module

Operations management is about how work gets done. This module introduces the basic framework for analyzing any process: breaking it down into resources and flow units, measuring capacity, finding the bottleneck, and calculating flow rate and utilization. The key insight is that every process has a bottleneck — the slowest step — and improving anything other than the bottleneck is waste. The module also introduces the efficiency frontier (the trade-off between cost and quality) and three system inhibitors: waste, variability, and inflexibility.

---

## B. Key Concepts & Definitions

- **Efficiency Frontier:** The set of firms that cannot be beaten on both cost and quality at the same time. Any firm not on the frontier is inefficient — it could improve either cost or quality without hurting the other.

- **Pareto Dominated:** Being worse on every measure compared to another firm. If you are Pareto dominated, you are clearly inefficient.

- **Waste:** Using inputs and resources that do not add value for the customer. The goal of lean operations is to eliminate waste.

- **Variability:** Changes in either demand or supply over time. Variability is a major source of inefficiency.

- **Flexibility:** The ability of an operation to respond to variability. Two types:
  - **Volume Flexibility:** Adjusting capacity to match demand
  - **Mix Flexibility:** Using the same resources to serve different customer needs

- **Flow Unit:** The thing moving through the process — a car, a patient, a sandwich, a dollar bill.

- **Processing Time:** How long each resource takes to work on one flow unit.

- **Capacity:** The maximum number of flow units a resource can process per unit of time. Formula: Capacity = Number of Resources / Processing Time

- **Bottleneck:** The resource with the lowest capacity. It limits the entire process.

- **Process Capacity:** The maximum output of the whole process — equal to the bottleneck's capacity.

- **Demand Rate:** How many flow units customers want per unit time.

- **Flow Rate (Throughput):** The actual number of flow units moving through the process per unit time. Flow Rate = Minimum of Demand and Process Capacity.

- **Utilization:** How busy a resource is. Utilization = Flow Rate / Capacity.

- **Inventory:** The number of flow units waiting in the system (between resources).

- **Flow Time:** The total time a flow unit spends in the process, including waiting time.

- **Genchi Genbutsu:** A Toyota principle meaning "go and see for yourself." To understand a problem, you must observe the work site directly.

---

## C. Main Arguments & Insights

1. **Operations is about trade-offs between cost and quality.** No firm can be both the cheapest and the highest quality at the same time. The efficiency frontier shows the best possible combinations. Firms inside the frontier are inefficient — they can improve on at least one dimension without hurting the other. The goal is to get to the frontier, then choose your position based on your strategy.

2. **The bottleneck determines everything.** The slowest resource in a process sets the maximum possible output. Improving any non-bottleneck resource does not increase overall process capacity — it just creates more idle time. Before trying to improve anything, find the bottleneck first.

3. **Waste, variability, and inflexibility are the three enemies of good operations.** Waste is anything the customer would not pay for. Variability creates uncertainty and forces you to hold excess inventory or capacity. Inflexibility means you cannot respond to variability when it happens. Good operations attack all three.

4. **Process analysis requires seeing both the flow unit perspective and the resource perspective.** The flow unit perspective follows one item through the process and measures flow time. The resource perspective looks at each worker or machine and measures capacity and utilization. Both views are needed to fully understand a process.

5. **A process can be either demand-constrained or capacity-constrained.** If demand is higher than process capacity, the bottleneck limits output (capacity-constrained). If demand is lower than process capacity, the process can handle all demand, and the flow rate equals demand (demand-constrained). Knowing which case you are in changes where you focus improvement efforts.

---

## D. Frameworks, Models & Tools

| Framework / Tool        | What It Is                                                  | When to Use It                                                                       |
| ----------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Efficiency Frontier     | A curve showing the best possible cost-quality combinations | To see where your firm stands against competitors and find improvement opportunities |
| Process Flow Diagram    | A map with boxes for resources and triangles for inventory  | To visualize any process before analyzing it                                         |
| Bottleneck Analysis     | Find the resource with lowest capacity                      | Always do this first before trying to improve a process                              |
| Three System Inhibitors | Waste, Variability, Inflexibility                           | To diagnose why a process is performing poorly                                       |
| Capacity Formula        | Capacity = Number of Resources / Processing Time            | To calculate each resource's maximum output                                          |
| Utilization Formula     | Utilization = Flow Rate / Capacity                          | To measure how busy a resource is                                                    |
**Efficiency Frontier:**

![[Pasted image 20260531014233.png]]

**Process Flow Diagram:**

![[Pasted image 20260531014353.png]]

---

## E. Formulas & Equations

- **Resource Capacity:** Capacity_i = (Number of Resources_i) / (Processing Time_i)

- **Flow Rate:** Flow Rate = Minimum(Demand, Process Capacity)

- **Utilization:** Utilization_i = Flow Rate / Capacity_i

- **Cycle Time (from flow rate):** Cycle Time = 1 / Flow Rate (when process is capacity-constrained)

---

## F. Practical Implications

- Before trying to improve any process, map it out. Draw the boxes (resources) and triangles (inventory). You cannot improve what you cannot see.

- Find the bottleneck first. Walk the process and watch where work piles up. That is your bottleneck. Improving anything else is a waste of time and money.

- If you are capacity-constrained (demand higher than capacity), your only job is to increase bottleneck capacity. Nothing else matters until the bottleneck moves.

- If you are demand-constrained (capacity higher than demand), your job is to either reduce capacity (cut costs) or increase demand (better marketing, lower prices). Running resources at low utilization is expensive.

- Use genchi genbutsu — go and see for yourself. Do not rely on reports or secondhand descriptions. Watch the actual work being done.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Draw a process flow diagram for any simple operation
- [x] Calculate the capacity of each resource in a process
- [x] Identify the bottleneck resource
- [x] Calculate process capacity, flow rate, and utilization
- [x] Distinguish between demand-constrained and capacity-constrained processes
- [x] Explain the efficiency frontier and what it means to be Pareto dominated
- [x] Define waste, variability, and inflexibility as system inhibitors

---

## H. My Reflections & Critical Thoughts

The bottleneck concept seems almost too simple, but it is amazing how often managers ignore it. In every organization, there is a slowest step — and working harder anywhere else does not increase output. Yet people constantly try to speed up things that are not the bottleneck. The discipline of finding the bottleneck first and only then improving is harder than it sounds, because non-bottleneck resources are often the loudest complainers.

The efficiency frontier is a useful way to think about strategy. Low-cost and high-quality are not opposites in an absolute sense — you can have better quality than a competitor at the same cost, or lower cost at the same quality. That is just being more efficient. The real trade-off happens only at the frontier. Most companies are not at the frontier.

---

---

# Module 2 — Optimizing Flow and Lean Operations

## A. Core Idea of the Module

This module moves from measuring processes to improving them. It covers labor productivity (how to measure and improve it), line balancing (making sure work is evenly distributed), and lean operations (eliminating waste and managing flow). The key insights are: (1) the bottleneck worker determines the cycle time of the whole line, (2) idle time is not waste if it is caused by the bottleneck — the bottleneck should never be idle, and (3) lean operations means pulling work through the system based on demand, not pushing work based on capacity.

---

## B. Key Concepts & Definitions

- **Labor Content:** The total amount of labor time needed to produce one flow unit. Sum of all processing times for tasks done by people.

- **Cycle Time:** The time between finishing two consecutive units. In a capacity-constrained process, cycle time = processing time of the bottleneck.

- **Idle Time:** The time a resource is not working during one cycle. Non-bottleneck resources have idle time.

- **Labor Utilization:** The percentage of time resources are not idle. Measures how balanced the line is. Formula: (Labor Content) / (Cycle Time × Number of Workers)

- **Cost of Direct Labor:** Labor cost per unit. Formula: (Total Wages per Hour) / (Flow Rate per Hour)

- **Takt Time:** The target cycle time needed to meet customer demand. Formula: Available Time / Demand

- **Target Manpower:** The number of workers needed to meet takt time. Formula: Labor Content / Takt Time

- **Value Add Time:** Work that directly increases the product's value in the customer's eyes.

- **Incidental Activity:** Work that does not add value but is necessary to keep operations running (e.g., cleaning, setup).

- **Waste (Muda):** Use of resources that adds no customer value and is not necessary for operations.

- **Overall Equipment Effectiveness (OEE):** The ratio of value-adding time to total paid time.

- **Percentage Value-Add Time (%-VAT):** The proportion of a flow unit's total flow time spent on value-adding work.

- **Pull System:** Work is pulled through the process based on downstream demand, not pushed based on upstream capacity.

- **Kanban:** A pull system that uses cards to limit inventory. Work is only done when a card authorizes it.

- **Heijunka:** Mixed-model production — making different products in small batches to smooth demand.

- **Seven Sources of Waste (TIM WOOD):** Transport, Inventory, Motion, Waiting, Overprocessing, Overproduction, Defects.

---

## C. Main Arguments & Insights

1. **The bottleneck worker should never be idle.** In a balanced line, the bottleneck determines the cycle time. Every other worker will have some idle time — that is fine. But if the bottleneck is idle, the whole process loses output. Protect the bottleneck at all costs.

2. **Line balancing is about matching the takt time.** Takt time is set by customer demand, not by your process. If your cycle time is longer than takt time, you cannot meet demand. If it is shorter, you are producing faster than customers want (overproduction — a form of waste). The goal is to get cycle time as close to takt time as possible.

3. **Labor cost per unit is more important than labor utilization.** High utilization on non-bottleneck workers does not increase output — it just means they are busy doing things that do not matter. The real measure of labor productivity is cost per unit, not how busy people look.

4. **Waste takes seven forms, but they all have the same effect.** The TIM WOOD framework helps you spot waste systematically. Overproduction (making more than demand) is often called the worst waste because it creates all the others: excess inventory, waiting, motion, and transport.

5. **Push systems create inventory; pull systems expose problems.** In a push system, work moves forward regardless of whether downstream resources are ready. This hides problems because inventory buffers cover them up. In a pull system (like Kanban), work only moves when there is demand. This exposes problems immediately, forcing you to fix them. This is uncomfortable but leads to better processes over time.

6. **Small batch sizes reduce inventory but require flexibility.** The ideal batch size is one (heijunka) — making one unit at a time in a mixed sequence. This minimizes inventory and flow time. But it requires very flexible equipment and workers who can switch tasks quickly. The trade-off is between setup time and inventory cost.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Labor Content & Utilization | Sum of processing times and ratio to cycle time | To measure how balanced a process is |
| Takt Time | Target cycle time = Available Time / Demand | To set the pace your process needs to hit |
| Target Manpower | Labor Content / Takt Time | To figure out minimum staffing needed |
| Seven Sources of Waste (TIM WOOD) | Transport, Inventory, Motion, Waiting, Overprocessing, Overproduction, Defects | To spot waste systematically |
| OEE (Overall Equipment Effectiveness) | Value-adding time / Total paid time | To measure how productively a resource is used |
| Pull System / Kanban | Work authorized by downstream demand | To reduce inventory and expose problems |
| Heijunka (Mixed Model Production) | Making different products in small batches | To smooth demand and reduce inventory |

---

## E. Formulas & Equations

- **Cycle Time (from bottleneck):** CT = Processing Time of Bottleneck (when process is capacity-constrained)

- **Idle Time:** Idle Time_i = Cycle Time - Processing Time_i

- **Labor Content:** LC = Sum of all processing times (p₁ + p₂ + ... + pₙ)

- **Average Labor Utilization:** ALU = (Labor Content) / (Cycle Time × Number of Workers)

- **Cost of Direct Labor:** CDL = (Total Wages per Hour) / (Flow Rate per Hour)

- **Takt Time:** Takt = Available Time / Demand

- **Target Manpower:** Target = Labor Content / Takt Time

- **OEE:** OEE = Value-Adding Time / Total Paid Time

- **%-VAT:** %-VAT = (Value-Add Time) / (Total Flow Time)

---

## F. Practical Implications

- Do not try to make everyone 100% busy. In any process with variation, only the bottleneck can be 100% utilized without creating inventory. Trying to keep everyone busy usually means overproducing.

- Calculate takt time before designing your process. The customer sets the pace, not your machines or your workers. If your process cannot hit takt time, you need more capacity. If it exceeds takt time easily, you have excess capacity.

- Walk your process with TIM WOOD in mind. Look for transport (things moving too far), inventory (piles of work waiting), motion (people walking too much), waiting (people or machines idle), overprocessing (doing more than needed), overproduction (making things not yet demanded), and defects (rework).

- Start with a pull system in one small part of your process. You do not need to convert everything at once. A Kanban system for one work cell can show the benefits and build support for wider changes.

- Reduce batch sizes. The best way to cut inventory and flow time is to make smaller batches. Yes, this increases setups. But the cost of holding inventory is usually higher than people think.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Calculate cycle time, idle time, and labor content for a process
- [x] Compute cost of direct labor and average labor utilization
- [x] Use takt time to determine if a process can meet customer demand
- [x] Calculate target manpower needed for a given demand rate
- [x] Identify the seven sources of waste (TIM WOOD) in any process
- [x] Explain the difference between push and pull systems
- [x] Calculate OEE and %-VAT
- [x] Explain why the bottleneck should never be idle

---

## H. My Reflections & Critical Thoughts

The takt time concept is powerful because it puts the customer at the center of process design. Most managers design processes around their own capacity — "how fast can we make this?" — instead of around demand — "how fast do customers want this?" The difference seems small but changes everything. Designing to takt time means you build only what is needed, when it is needed.

The Subway sandwich example in the lecture is simple but effective. Three workers, different processing times. The math is clear: the middle worker (46 seconds) is the bottleneck, cycle time is 46 seconds, capacity is 78 sandwiches per hour. The other workers are idle 9 seconds per sandwich. Trying to speed up the first or third worker does nothing. This is obvious in the example but harder to see in real processes.

The waste framework (TIM WOOD) is memorable. The mnemonic helps. The hardest waste to see is overprocessing — doing more than the customer wants. Engineers love to add features and tolerances that customers do not care about. That is waste.

---

---

# Module 3 — Little's Law

## A. Core Idea of the Module

Little's Law is one of the most elegant and useful equations in all of management. It states that Inventory = Flow Rate × Flow Time. This simple relationship holds for any stable process, in any industry, at any scale. The module shows how to apply Little's Law to inventory management (calculating days of supply and inventory turns) and to workforce management (calculating employee turnover and average tenure). The key insight is that you can calculate any one of the three variables if you know the other two — which is incredibly useful when one is hard to measure directly.

---

## B. Key Concepts & Definitions

- **Little's Law:** The fundamental equation linking the three basic process measures. I = R × T (Inventory = Flow Rate × Flow Time)

- **Days of Supply:** How many days the process can continue at the current flow rate before running out of inventory. Formula: Days of Supply = Inventory / Flow Rate

- **Inventory Turns:** How many times per year a company sells and replaces its inventory. Formula: Inventory Turns = 1 / Flow Time (when flow time is in years). Also: Inventory Turns = COGS / Average Inventory

- **Inventory Costs:** The annual cost of holding inventory. Higher turns mean lower per-unit inventory costs.

- **Employee Turnover:** The rate at which employees leave the organization. Formula: Turnover = Departures per Year / Average Number of Employees

- **Average Tenure (at departure):** The average time employees stay before leaving. Average Tenure at Departure = 1 / Turnover

- **Average Tenure (at any point):** About half of the tenure at departure (assuming steady state).

---

## C. Main Arguments & Insights

1. **Little's Law works everywhere.** It does not depend on the type of process, the industry, or the flow unit. It works for patients in a hospital, dollars in inventory, cars on a highway, and employees in a company. This universality makes it one of the most powerful tools in operations.

2. **Inventory and flow time move together.** For a given flow rate, if you want to reduce inventory, you must reduce flow time. There is no other way. This is why lean operations focuses so much on reducing flow time — it directly reduces inventory.

3. **Days of supply is just Little's Law rearranged.** Days of supply tells you how long your current inventory would last if you stopped producing. It is a intuitive measure that managers understand easily. Dell famously ran on about 7 days of supply while competitors had 30+ days — a huge competitive advantage.

4. **High inventory turns are not always good.** Tiffany has low inventory turns (high-margin luxury goods) and that is fine. Kroger has high inventory turns (low-margin groceries) and that is necessary. The right level of turns depends on your business model. The problem is when turns are low for your business model — that means cash is tied up in inventory that is not moving.

5. **Little's Law applies to people too.** Employee turnover is just the flow rate of people leaving. Average tenure is the flow time. If you know your workforce size (inventory) and your hiring rate (flow rate), you can calculate average tenure. This is useful for workforce planning.

---

## D. Frameworks, Models & Tools

| Framework / Tool | What It Is | When to Use It |
|-----------------|-----------|----------------|
| Little's Law (I = R × T) | Inventory = Flow Rate × Flow Time | To calculate any one of the three measures when you know the other two |
| Days of Supply | Inventory / Flow Rate | To measure how long inventory will last at current demand |
| Inventory Turns | COGS / Average Inventory | To measure how efficiently inventory is being used |
| Employee Turnover Calculation | Departures per Year / Average Employees | To measure workforce stability |
| Average Tenure Calculation | 1 / Turnover | To estimate how long employees stay |

---

## E. Formulas & Equations

- **Little's Law:** Inventory = Flow Rate × Flow Time (I = R × T)

- **Days of Supply:** Days of Supply = Inventory / Flow Rate (per day)

- **Inventory Turns (annual):** Turns = COGS / Average Inventory

- **Inventory Turns (from flow time):** Turns = 1 / T (where T is flow time in years)

- **Per Unit Inventory Cost:** Annual Inventory Cost per Unit = (Cost of Capital + Storage Costs) / Turns

- **Employee Turnover:** Turnover = Departures per Year / Average Number of Employees

- **Average Tenure at Departure:** Tenure = 1 / Turnover (when turnover is annual rate)

- **Average Tenure (at any point):** About half of tenure at departure (steady state assumption)

---

## F. Practical Implications

- If you need to measure flow time but cannot track individual units, count inventory and measure flow rate. Then use Little's Law: T = I / R. This is much easier than tracking individual flow units through the process.

- Compare your inventory turns to competitors. If you have lower turns (higher days of supply) than competitors with a similar business model, you are tying up cash in inventory unnecessarily.

- Be careful with days of supply for seasonal businesses. Measuring at the wrong time of year gives misleading numbers. Use average inventory across a full cycle.

- Use Little's Law for workforce planning. If you know your average turnover rate and your desired workforce size, you can calculate how many new hires you need each year. This is more reliable than guessing.

- Remember that flow time includes waiting time, not just processing time. When customers complain about slow service, they are complaining about flow time. Little's Law tells you that to reduce waiting (inventory), you must either reduce flow time or reduce flow rate — but reducing flow rate means serving fewer customers.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] State Little's Law and explain what each variable means
- [x] Calculate any one of I, R, or T when given the other two
- [x] Compute days of supply from inventory and flow rate
- [x] Calculate inventory turns from financial statements
- [x] Explain why high turns are good for some businesses but not all
- [x] Apply Little's Law to employee turnover and average tenure
- [x] Use Little's Law to measure flow time indirectly

---

## H. My Reflections & Critical Thoughts

Little's Law is beautiful because it is so simple and so general. I = R × T. That is it. Three variables. And yet it applies to everything from a factory to a hospital to a highway. The math is trivial, but the implications are deep. If you want to reduce inventory, you have two choices: reduce flow rate (sell less) or reduce flow time (move faster). Most managers want to reduce inventory without reducing sales — so the only path is reducing flow time. This shifts the conversation from "how much inventory should we hold?" to "how can we move work faster?"

The Dell vs. Compaq example is striking. Dell had about 7 days of supply; Compaq had about 29 days. That difference meant Dell's inventory turned about 4 times faster. For a low-margin business like PCs, that is a huge cost advantage. No wonder Dell dominated for years.

The application to employee turnover is clever. Most HR metrics focus on turnover rate, but Little's Law shows that turnover rate and average tenure are the same thing (inversely). A turnover rate of 10% per year means average tenure is 10 years. This is not just math — it changes how you think about retention. If you want to increase average tenure from 5 years to 10 years, you need to cut turnover in half.

---

---

# Module 4 — Quality

## A. Core Idea of the Module

Quality problems come from variability. Every process has variation — in inputs, in environmental conditions, in human performance. When variation exceeds customer specifications, defects happen. This module teaches how to measure variability (process capability, Six Sigma), how to find the root causes of defects (5 Whys, fishbone diagrams, Pareto charts), and how to build processes that prevent defects from happening (poka yoke, jidoka, PDCA). The key insight is that quality cannot be inspected in — it must be built in.

---

## B. Key Concepts & Definitions

- **Common Cause Variation:** Random variation inherent in the process. No specific cause can be identified.

- **Assignable Cause Variation:** Variation that can be traced to a specific change or event. This is what root cause analysis tries to find.

- **Lower Specification Limit (LSL):** The smallest acceptable value for a product characteristic.

- **Upper Specification Limit (USL):** The largest acceptable value.

- **Process Capability (Cp):** A measure of how well a process fits within specification limits. Formula: Cp = (USL - LSL) / (6 × σ)

- **Six Sigma:** A quality level where Cp = 2, meaning the specification width is 12 standard deviations. Defect rate about 3.4 per million.

- **Swiss Cheese Model:** Accidents happen when holes in multiple layers of defense line up. A way to think about how multiple small failures combine into big problems.

- **Jidoka:** Automation with human oversight. When a problem is detected, the machine (or worker) stops, alerts someone, and waits for help.

- **Andon Cord:** A cord (physical or digital) that workers pull to stop the line when they see a problem. The symbol of jidoka in Toyota.

- **Ishikawa (Fishbone) Diagram:** A brainstorming tool that organizes potential causes into categories (Machines, Methods, Materials, Manpower, Measurement, Environment).

- **Five Whys:** A technique for finding root causes by asking "why?" repeatedly until you reach a systemic cause, not just a surface symptom.

- **Pareto Chart:** A bar chart that ranks causes by frequency, showing which few causes account for most problems (80/20 rule).

- **Why-How Ladder:** A way to frame problems by asking "why?" to go broader (more strategic) and "how?" to go narrower (more tactical).

- **Poka Yoke:** Mistake-proofing — designing the process so mistakes cannot happen.

- **Baka Yoke:** Foolproofing — designing the process so mistakes are obvious and cannot be ignored.

- **Five Levels of Prevention:** A hierarchy of error prevention, from laws and signs to physical barriers to dedicated infrastructure.

- **PDCA Cycle (Deming Cycle):** Plan → Do → Check → Act. A data-driven approach to continuous improvement.

---

## C. Main Arguments & Insights

1. **Variability is the enemy of quality.** If every output were exactly the same, quality would be perfect. The problem is that processes have variation. The goal of quality management is not to eliminate variation entirely (impossible) but to keep it within customer specifications.

2. **Process capability tells you if your process is good enough.** Cp compares the width of the specification limits to the width of the process variation (6 standard deviations). If Cp < 1, your process variation is wider than the specs — you will produce defects even when the process is centered. If Cp = 1, you are at the edge. Six Sigma (Cp = 2) gives a large safety margin.

3. **Quick feedback loops are essential for quality.** Toyota's andon cord stops the line immediately when a problem is detected. This forces the team to fix the problem right now, not later. High inventory levels hide problems — they act as buffers that delay feedback. Lean operations reduces inventory specifically to expose problems faster.

4. **Most problems have root causes that are not obvious.** The 5 Whys technique shows that the first answer is almost never the real cause. "Why did the machine stop?" "Because it overheated." "Why did it overheat?" "Because the cooling system failed." "Why did the cooling system fail?" "Because we have not been doing preventive maintenance." "Why not?" "Because we are understaffed." The root cause might be staffing levels, not the machine at all.

5. **The best way to prevent defects is to make them impossible.** Poka yoke (mistake-proofing) is stronger than inspection. Inspection finds defects after they happen. Prevention stops them from happening at all. Examples: USB plugs that only fit one way, microwave ovens that shut off when the door opens, car interlocks that prevent starting in gear. These are not accidents — they are deliberate design choices.

6. **Quality improvement is a cycle, not a one-time project.** The PDCA cycle (Plan, Do, Check, Act) reflects that processes are never perfect. You plan a change, do it on a small scale, check the results, and act to standardize what worked. Then you start over. Continuous improvement means never being done.

---

## D. Frameworks, Models & Tools

| Framework / Tool            | What It Is                                               | When to Use It                                            |
| --------------------------- | -------------------------------------------------------- | --------------------------------------------------------- |
| Process Capability (Cp)     | (USL - LSL) / (6σ)                                       | To measure if a process can meet specifications           |
| Swiss Cheese Model          | Layers of defense with holes that can line up            | To understand how multiple failures cause accidents       |
| Jidoka / Andon Cord         | Stop, alert, wait                                        | To build quality into the process, not inspect at the end |
| Ishikawa (Fishbone) Diagram | Brainstorming organized by cause categories              | To list possible causes of a problem                      |
| Five Whys                   | Ask "why?" repeatedly                                    | To find root causes, not symptoms                         |
| Pareto Chart                | Ranked bar chart of causes by frequency                  | To prioritize which causes to address first               |
| Why-How Ladder              | Alternate between "why?" (broader) and "how?" (narrower) | To frame a problem at the right level                     |
| Poka Yoke / Baka Yoke       | Mistake-proofing and foolproofing                        | To prevent defects from being possible                    |
| PDCA Cycle                  | Plan, Do, Check, Act                                     | To manage continuous improvement projects                 |

**Toyota Production System:**

![[Pasted image 20260531014624.png]]

---

## E. Formulas & Equations

- **Process Capability (Cp):** Cp = (USL - LSL) / (6 × σ)

  - Cp < 1: Process variation exceeds specs → defects expected
  - Cp = 1: Process exactly meets specs at the edge
  - Cp > 1: Process fits within specs
  - Cp = 2: Six Sigma quality (3.4 defects per million)

- **Defect Rate (for normal distribution, centered process):**
  - Cp = 0.67: about 4.5% defects
  - Cp = 1: about 0.27% defects
  - Cp = 1.33: about 64 defects per million
  - Cp = 1.67: about 0.6 defects per million
  - Cp = 2: about 3.4 defects per billion (Six Sigma)

---

## F. Practical Implications

- Before trying to improve quality, measure your current process capability. If Cp < 1, you need to reduce variation (narrow the distribution) or change the specifications. No amount of inspection will fix a process that cannot meet specs.

- Use control charts to distinguish common cause from assignable cause variation. Do not overreact to common cause (random) variation — that is tampering and makes things worse. Do not ignore assignable cause variation — that means something changed and needs to be fixed.

- Pull the andon cord. In Toyota, any worker can stop the line. This is not just allowed — it is expected. The cost of stopping the line for a few minutes is much lower than the cost of sending defects downstream. Build this mentality into your culture.

- Use the 5 Whys for every significant problem. The first answer is almost never the root cause. Keep going until you find something in the process or system, not just a person's mistake. If the last answer is "someone made an error," you have not gone far enough.

- Build poka yoke devices wherever possible. Human error is inevitable. Design processes that catch errors immediately or make them impossible. This is cheaper and more reliable than training people to be perfect.

- Run PDCA cycles quickly. The faster you go through the cycle, the faster you learn. Small experiments are better than big plans. Do not wait for perfect data — act on good enough data, then check the results.

---

## G. Learning Outcomes

By completing this module, I can now:

- [x] Distinguish common cause from assignable cause variation
- [x] Calculate process capability (Cp) and interpret the result
- [x] Explain the Swiss Cheese model of accidents
- [x] Describe jidoka and the andon cord
- [x] Use a fishbone diagram to brainstorm possible causes
- [x] Apply the 5 Whys technique to find root causes
- [x] Build a Pareto chart to prioritize improvement efforts
- [x] Explain the difference between poka yoke and baka yoke
- [x] Use the PDCA cycle to manage improvement projects

---

## H. My Reflections & Critical Thoughts

The capability formula Cp = (USL - LSL) / 6σ is a great example of a simple equation that changes how you think. If your process variation is too wide for your specifications, no amount of inspection will fix it. You must reduce variation or widen specs. Period. This shifts quality from "catching defects" to "building a better process."

The 5 Whys technique sounds gimmicky but works. I have used it in real problem-solving sessions, and it is amazing how often the team stops at the first or second why — blaming an operator or a machine — when the real cause is several levels deeper. The discipline of asking "why?" five times forces you past easy answers.

The andon cord is culturally hard to implement outside of Toyota. In most organizations, stopping the line would be seen as failure, not as quality protection. Workers would be punished for causing delays. This is a deep cultural difference. The tool is simple, but the culture that makes it work is not. The course acknowledges this indirectly but could say more about how to build that culture from scratch.

---

---

# 🔗 Cross-Course Connections

| Connection | This Course → Other Course | Why It Matters |
|-----------|---------------------------|----------------|
| Builds on | None (this is foundational) | Operations is a core business function alongside marketing, finance, and HR |
| Connects to | Introduction to Financial Accounting | Inventory turns (Little's Law) appear on financial statements. Operations decisions affect accounting numbers directly |
| Connects to | Introduction to Marketing | The efficiency frontier is about cost vs. quality — which is exactly the positioning choice brands make |
| Connects to | Managing Social and Human Capital | Job design, worker empowerment, and the Toyota Production System appear in both courses (NUMMI case) |
| Connects to | Supply Chain Management (advanced) | This course covers operations inside a single firm; supply chain adds suppliers and customers |

---

# 📊 Concept Map

```
INTRODUCTION TO OPERATIONS MANAGEMENT
│
├── MODULE 1: Process Analysis
│   ├── Process Flow Diagram
│   │   ├── Resources (boxes) → add value, have capacity
│   │   └── Inventory (triangles) → waiting units
│   ├── Capacity Calculations
│   │   ├── Capacity_i = Resources_i / Processing Time_i
│   │   └── Bottleneck = resource with lowest capacity
│   ├── Flow Rate = Min(Demand, Process Capacity)
│   ├── Utilization = Flow Rate / Capacity
│   └── Efficiency Frontier
│       └── Trade-off between cost and quality
│
├── MODULE 2: Flow Optimization & Lean
│   ├── Labor Productivity
│   │   ├── Labor Content = sum of processing times
│   │   ├── Cycle Time = processing time of bottleneck
│   │   └── Cost of Direct Labor = wages / flow rate
│   ├── Takt Time = Available Time / Demand
│   ├── Seven Wastes (TIM WOOD)
│   │   ├── Transport, Inventory, Motion, Waiting
│   │   └── Overprocessing, Overproduction, Defects
│   ├── Push vs. Pull Systems
│   │   ├── Push: work moves regardless of demand
│   │   └── Pull (Kanban): work authorized by demand
│   └── Heijunka = mixed-model, small batches
│
├── MODULE 3: Little's Law
│   └── I = R × T (Inventory = Flow Rate × Flow Time)
│       ├── Days of Supply = I / R
│       ├── Inventory Turns = COGS / Average Inventory
│       └── Employee Turnover = Departures / Average Employees
│
└── MODULE 4: Quality
    ├── Variation
    │   ├── Common Cause (random)
    │   └── Assignable Cause (specific event)
    ├── Process Capability: Cp = (USL - LSL) / 6σ
    ├── Root Cause Analysis
    │   ├── 5 Whys
    │   ├── Fishbone (Ishikawa) Diagram
    │   └── Pareto Chart (80/20 rule)
    ├── Jidoka (Andon Cord) = stop, alert, wait
    ├── Poka Yoke = mistake-proofing
    └── PDCA Cycle = Plan → Do → Check → Act
```

---

# ✅ Course-Level Takeaways

This course provides a practical toolkit for analyzing and improving any work process. The most important ideas are simple but powerful: find the bottleneck first, measure everything, eliminate waste, and use data to drive improvement. The bottleneck concept alone is worth the whole course — once you understand that the slowest step determines everything, you stop wasting time on the wrong things. Little's Law gives you a universal relationship that works everywhere, from factories to hospitals to call centers. And the quality tools (5 Whys, fishbone, Pareto, PDCA) give you a systematic way to solve problems that keeps coming back to root causes, not symptoms.

The course's strength is its focus on simple math that actually gets used. Capacity = resources / processing time. I = R × T. Cp = (USL - LSL) / 6σ. These are not complicated formulas, but they are incredibly useful. The weakness is that the examples are mostly manufacturing (cars, sandwiches, iron ore) — service operations are mentioned but get less attention. Still, the tools apply to services just as well. A hospital is a process. A call center is a process. A restaurant is a process. The math does not know the difference.

---

# 📎 Supplementary Resources

| Type | Title | Reference |
|------|-------|-----------|
| 📖 Book | *The Goal* | Eliyahu Goldratt — Novel that teaches the theory of constraints (bottlenecks) through a story |
| 📖 Book | *Lean Thinking* | James Womack & Daniel Jones — Classic introduction to lean principles |
| 📖 Book | *The Toyota Way* | Jeffrey Liker — The 14 principles of the Toyota Production System |
| 📖 Book | *Out of the Crisis* | W. Edwards Deming — The original text on statistical process control and quality |
| 📖 Book | *The Phoenix Project* | Gene Kim — Novel about applying lean/DevOps to IT operations |
| 📄 Article | "The Seven Wastes of Lean" | Lean Enterprise Institute — Detailed explanation of TIM WOOD |

---

# 🏷️ Tags

`#MBA` `#SelfTaught` `#Operations` `#ProcessAnalysis` `#Lean` `#SixSigma` `#LittleSLaw` `#QualityManagement` `#Bottleneck` `#Wharton` `#Coursera`

---

*Part of my Self-Taught MBA Journey · Following the roadmap.sh MBA Roadmap*
