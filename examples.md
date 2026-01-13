# Examples — General Reasoning Core

This document demonstrates that **General Reasoning Core** is a
domain-agnostic reasoning engine, not a domain-specific system.

The same planning core is applied to different real-world domains
by changing only the **causal rules** and **state variables**.

---

## 🏗️ Example 1: Construction Planning

### Problem
Plan a construction project under:
- Uncertain outcomes
- Cost and time constraints
- Risk and quality trade-offs
- Human factors (stress, fatigue, recovery)

### State Variables
- design_quality
- plan_quality
- prototype_quality
- build_quality
- risk_level
- time_spent
- cost_spent
- stress_level
- comfort_level

### Actions
- draw_design
- causal_plan
- build_prototype
- simulate_tests
- execute_build
- take_break
- quality_audit

### Reasoning Process
- No rewards are used
- Actions cause **stochastic state transitions**
- Planning is **hierarchical**
- Plans are evaluated via **Monte-Carlo robustness testing**

### Outcome
The engine discovers that:
- Over-optimizing quality creates fragile plans
- Strategic recovery actions increase success probability
- Fewer audits with lower stress outperform excessive control

This mirrors how experienced human project managers reason.

---

## 🔬 Example 2: Scientific Research Workflow

### Problem
Plan a research project with uncertainty in results, peer review,
and experimental outcomes.

### Actions
- literature_review
- form_hypothesis
- design_experiment
- run_experiment
- analyze_results
- write_paper
- peer_review
- take_break

### Discovered Strategy
The engine autonomously finds that:
- A break after experimentation improves robustness
- Excessive peer review has diminishing returns
- Balanced plans outperform theoretically perfect ones

---

## 🌍 Key Insight

Only the **domain rules change**.

The **reasoning engine itself remains unchanged**.

This is the defining property of a general intelligence core.

---

## 🧠 What This Proves

- Intelligence ≠ reward maximization
- Robust planning > optimal planning
- General reasoning can be explicit, interpretable, and controllable

This system reasons like an expert — not like a classifier.
