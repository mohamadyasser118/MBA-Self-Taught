# Contributing to Self-Taught MBA

Thanks for helping! This guide explains how to contribute.

---

## What You Can Add

- **New course summaries** – Any course from the roadmap
- **Extra resources** – Books, articles, videos, tools
- **Corrections** – Fix errors or typos
- **Case studies** – Real-world examples

---

## How to Contribute

**1. Fork the repo**

Click the "Fork" button on GitHub.

**2. Clone your fork**

```bash
git clone https://github.com/your-username/self-taught-mba.git
```

**3. Create a branch**

```bash
git checkout -b add/course-name
```

**4. Make your changes**

Follow the format below.

**5. Commit and push**

```bash
git add .
git commit -m "add: summary for Course Name"
git push origin add/course-name
```

**6. Open a Pull Request**

Go to the original repo on GitHub and click "New Pull Request".

---

## Simple Rules

**Do:**
- Write in your own words
- Follow the course summary format
- Keep it clear and simple

**Don't:**
- Copy-paste from course materials
- Submit AI content without checking it
- Change the structure without asking

---

## Course Summary Format

Here is the basic structure. Copy this for each new summary.

```markdown
# 📘 Course Title

| Field | Details |
|-------|---------|
| **Roadmap Section** | Part X — Topic |
| **Platform** | Coursera |
| **Institution / Instructor** | University — Instructor |
| **Duration** | X modules |

## 🧭 Course Overview

[2-3 paragraphs explaining what the course covers]

## 🎯 Learning Objectives

- [x] Objective 1
- [x] Objective 2

## 🗺️ Course Structure

| Module | Title | Core Theme |
|--------|-------|------------|
| 1 | Title | Theme |

---

## Module 1 — Title

### A. Core Idea

[What this module is about]

### B. Key Concepts

- **Term:** Definition

### C. Main Insights

1. **Insight:** Explanation

### D. Frameworks

| Framework | What It Is | When to Use |
|-----------|-----------|-------------|
| Name | Description | Situation |

### E. Formulas

- Formula (or "> *No formulas*")

### F. Practical Tips

- Tip 1

### G. Learning Outcomes

- [x] Outcome

### H. Reflections

[Your analysis of what matters]

---

## 🔗 Cross-Course Connections

| Connection | Why It Matters |
|-----------|----------------|
| Course A | Explanation |

## 📊 Concept Map

[Simple diagram of course structure]

## ✅ Course Takeaways

[2-3 paragraphs summarizing the whole course]

## 📎 Resources

| Type | Title | Link |
|------|-------|------|
| Book | Title | Author |

## 🏷️ Tags

`#tag1` `#tag2`
```

> A template file `TEMPLATE_summary.md` is in the repo root. Copy it to start.

---

## Folder Structure

Put summaries in the right folder:

```
01-foundation/
├── business-foundations/
├── economics/
└── finance-and-accounting/

02-core-stage-1/
├── project-management/
├── human-resource-management/
├── leading-people-and-teams/
└── business-analytics/

03-core-stage-2/
├── strategic-leadership/
├── supply-chain-management/
├── organizational-analysis/
├── marketing/
├── risk-management/
├── business-ethics/
└── entrepreneurship/

04-specializations/
├── consulting-and-data-analytics/
├── digital-transformation/
├── ai-for-business/
└── healthcare/
```

**Naming:** Use lower-case with hyphens (`introduction-to-marketing`)

---

## Style Tips

- Write simply. Explain technical terms.
- Use `**bold**` for key terms first time
- Use `✅` for completed items
- Keep sentences short

---

## Review

PRs are reviewed within 1-2 weeks. You may be asked to make changes.

---

## Questions?

Open an issue with the label "question".

---

Thanks for contributing!
