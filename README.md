# Adaptive Self-Assessment for Calculus II (MATH 150B)

An open-source behavioral specification, adaptive assessment architecture, and audit framework for evaluating LLM tutoring compliance, anti-sycophancy guardrails, and student confidence calibration in undergraduate mathematics.

Developed and deployed across **3 sections over 16 weeks** in **MATH 150B (Calculus II)** at **California State University, Fullerton (CSUF)**—a large public Hispanic-Serving Institution (HSI) and Primarily Undergraduate Institution (PUI).

## Why This Project Exists

Standard LLM tutoring benchmarks rely heavily on single-turn prompts or synthetic student personas. In real high-access classrooms, frontier models frequently fail by:
1. **Sycophantic answer leakage:** Giving away essential mathematical steps prematurely when students express low confidence or hesitation.
2. **Miscalibrated scaffolding:** Conflating breaking a problem into smaller non-leading questions with supplying answer-bearing hints.
3. **Unverifiable grading:** Failing to distinguish an algebraic slip from an essential conceptual misconception, or rejecting algebraically equivalent solutions.

This project addresses those failure modes through a deterministic, auditable prompt specification designed to run inside standard university LLM workspaces (such as CSUF ChatGPT Edu and Gemini) without custom model fine-tuning.

## System Architecture

The assessment engine decouples global pedagogical governance from weekly mathematical scope using a two-file protocol:

* **Master Governance Protocol (`protocols/`):** Enforces one-question-at-a-time pacing, preserves unedited first-attempt evidence, separates presentation granularity (`granular`, `standard`, `compressed`) from substantive hints, and exposes student-invocable audit commands (`RECHECK P##`, `FLAG P##`, `EXPLAIN SCORE P##`, `SHOW LEDGER`).
* **Modular Weekly Assessment Cards (`Fall 2026 Math 150B/`):** Define weekly learning objectives, prerequisite readiness checks, adaptive problem-generation templates, and mandatory coverage audits while blocking out-of-scope tools (such as CAS or integration tables).
* **Deterministic Audit Schema:** Every session produces a structured diagnostic report (`M150B-RPT`) capturing:
  * **Evidence Scores:** `3` (Independent), `2` (Minor prompting), `1` (Substantive support), `0` (Not demonstrated).
  * **Anomaly & Fault Flags:** `T` (unsolicited tutor disclosure), `V` (defective or out-of-scope generated problem), and `I` (incomplete attempt).
  * **Confidence Calibration:** Pre- and post-session self-reported confidence (`0–3`) paired against observed rubric performance.

## Repository Contents

* `Fall 2026 Math 150B/` — Master protocol specification and weekly Calculus II assessment cards.
* `exemplars/` — Redacted, instructor-verified sample diagnostic reports demonstrating standard and anomaly-flagged runs.

## Empirical Study & Data Release Roadmap

* **Fall 2026 (In Progress):** Multi-section classroom deployment (~120+ undergraduates across 16 weeks) logging longitudinal trajectories across ChatGPT Edu and Gemini.
* **January 2027 (Planned):** Release of local de-identification/parsing scripts, automated protocol-compliance auditors, and an anonymized `JSONL` benchmark dataset following semester completion and CSUF IRB secondary-data verification.

## Author

**Shoo Seto**
Associate Professor of Mathematics, California State University, Fullerton  
ORCID: [0009-0005-6276-7949](https://orcid.org/0009-0005-6276-7949)
