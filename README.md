# big-things-decision

> **在花第一分钱之前，用数据而非直觉判断"该不该做"**

A project decision framework based on Bent Flyvbjerg's *How Big Things Get Done* (16,000+ projects empirical data). Helps you make data-driven decisions before starting any project.

---

## What Is This

**One sentence**: Helps you decide whether a project is worth doing — before you spend a dime.

This is a **decision framework**, not a knowledge base or project management tool. It shifts decision-making from "gut feeling" to "data-driven analysis."

---

## Quick Demo

```
You: I want to build an AI novel-writing app, budget ~500K CNY, team of 3 with 2 years dev experience

Me: [Verdict] Conditional Go — AI writing tools are crowded, but vertical niches still have room

    [Risks]
    1. Homogeneity: ChatGPT/Notion AI already cover general writing
    2. PMF: Will users pay specifically for "AI novel writing"?
    3. Copyright: AI-generated content ownership is unclear

    [Next Step] Spend 1 week validating: find 10 users willing to beta-test on novel platforms

    💡 Say "expand" for full analysis
    💡 Say "tools" for risk assessment calculator
```

---

## v5.0 Key Features

| Feature | Description |
|---------|-------------|
| **Progressive Disclosure** | One-liner → Full report → Interactive tools |
| **Model-Driven Analysis** | 5 mental models as analysis engine (not just knowledge) |
| **Reproducible Scoring** | Transparent risk formula, same input = same result |
| **Plan Comparison** | Support "Plan A vs Plan B" multi-option analysis |
| **User Profile Adaptation** | Auto-detect entrepreneur/enterprise/student/tech team |
| **Case Auto-Matching** | Automatically match relevant success/failure cases |
| **AnySearch Integration** | Real-time search for up-to-date market data |

---

## Core Design

### 4-Layer Progressive Workflow

```
Layer 1: Understand intent + Identify user profile
    ↓
Layer 2: Enough info? → Give verdict / Not enough? → Ask key questions
    ↓ Say "expand"
Layer 3: Search → Model analysis (5 models) → Case matching → Full report
    ↓ Say "tools"
Layer 4: Decision tools (Risk calculator / RCF lookup / Commitment fallacy checklist)
```

### 5 Mental Models = Analysis Engine

Each model answers a key question and is invoked during every full analysis:

| Model | Question | Role in Analysis |
|-------|----------|-----------------|
| Outside View Anchoring | How far is expectation from reality? | Calibrate with search data |
| Commitment Fallacy | Are there cognitive biases? | 5-item checklist |
| Fat Tail Risk | How bad is the worst case? | Assess window of destruction |
| Modular Decomposition | Can it be broken down? | Evaluate modular potential |
| Think Slow, Act Fast | Is the pace correct? | Check planning sufficiency |

### Risk Assessment Calculator (Reproducible)

```
Score = Base(40-65) + Budget(0-15) + Timeline(0-15) - Experience(0-15) - Tech(0-15) - Reference(0-10)
≥70 🔴 High / 40-69 🟡 Medium / <40 🟢 Low
```

---

## Supported Scenarios

| Scenario | Trigger |
|----------|---------|
| **Feasibility Assessment** | "I want to build/make/launch..." |
| **Risk Diagnosis** | "Over budget / Delayed / Problems..." |
| **Case Benchmarking** | "Why did X succeed/fail?" |
| **Plan Comparison** | "A or B? / Build vs Buy / Outsource vs In-house" |
| **Methodology Q&A** | "What is RCF? / How does outside view work?" |

---

## Search Capability

Integrated with [AnySearch](https://github.com/anysearch-ai/anysearch-skill) for real-time data:

| Scenario | Parallel Queries | Content |
|----------|-----------------|---------|
| Feasibility | 5 | Market size, failures, successes, tech maturity, modularity |
| Risk Diagnosis | 3 | Project risks, policy, exit cases |
| Case Benchmarking | 3 | Success factors, failure lessons, comparable companies |
| Plan Comparison | 10 | 5 per plan |

---

## File Structure

```
big-things-decision/
├── SKILL.md                    # Core skill definition (v5.0)
├── README.md                   # This file
├── README_CN.md                 # Chinese README
├── LICENSE                     # MIT License
├── .gitignore
└── references/                 # Research materials
    ├── 01-notebook-analysis.md  # Source notebook analysis
    ├── 02-book-research.md      # Deep book research
    ├── 03-cases-external-views.md # Case studies & external reviews
    └── extraction-framework.md  # Mental model extraction framework
```

---

## Based On

- **Book**: Bent Flyvbjerg, *How Big Things Get Done* (2023)
- **Data**: 16,000+ project empirical database
- **Search**: [AnySearch](https://github.com/anysearch-ai/anysearch-skill) v2.0
- **Academic sources**: Oxford Saïd Business School, Environmental Science & Policy journal
- **Endorsements**: Daniel Kahneman, Frank Gehry

---

## License

[MIT](LICENSE)
