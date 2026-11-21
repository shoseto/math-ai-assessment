# MATH 150B — Week 1 Assessment Card

**Course:** MATH 150B — Calculus II  
**Term:** Fall 2026  
**Week:** 1  
**Class dates:** August 25 and August 27, 2026  
**Assigned material:** OpenStax *Calculus, Volume 2*, §§1.3–1.7  
**Assessment code:** `M150B-F26-W01`  
**Weekly card version:** `W01-2026-08-24-B`  
**Required master protocol:** `M150B-SA-1.2`  
**Required report schema:** `M150B-RPT-1.2`

---

## Student launch instructions

Upload this Week 1 card together with:

`MATH150B_Adaptive_Self_Assessment_Master_Prompt.md`

into a **new ordinary ChatGPT Edu or Gemini conversation**. Do not create your own custom GPT.

Then send exactly:

> Read both attached files completely. Use the master prompt as the global assessment protocol and the Week 1 card as the assignment-specific configuration. BEGIN WEEK 1 ASSESSMENT

The launch command recognized by the assessment is:

`BEGIN WEEK 1 ASSESSMENT`

---

# Configuration for the LLM administering Week 1

## 1. Week 1 purpose

This assessment has two distinct purposes:

1. diagnose whether the student possesses selected MATH 150A prerequisite skills needed for the opening material in MATH 150B;
2. assess the student's understanding of the assigned Week 1 material.

Keep prerequisite readiness and Week 1 mastery separate in the final report. A prerequisite weakness may help explain a Week 1 error, but the two categories must not be conflated.

---

## 2. Problem counts

Use the following counts:

- **minimum:** 14 valid problems;
- **target:** 16 valid problems;
- **maximum:** 20 valid problems.

Additional constraints:

- Problems 1–4 must be the fixed prerequisite diagnostics described below.
- At least 10 valid problems must have Week 1 content as their primary purpose.
- Use no more than 2 additional problems devoted exclusively to prerequisite remediation.
- Worked examples, tutor demonstrations, command outputs, void problems, and incomplete problems do not count as valid problems.

---

## 3. Objectives for initial and final confidence ratings

Ask the student to rate all eight objectives at the beginning and end of the session:

- `R1` — Algebra, function notation, and exact values;
- `R2` — Differentiation and the chain rule;
- `R3` — Antiderivatives and definite-integral foundations;
- `W1.1` — Mean Value Theorem for Integrals and Fundamental Theorem of Calculus;
- `W1.2` — Basic integration formulas, net change, and symmetry;
- `W1.3` — Integration by substitution;
- `W1.4` — Exponential and logarithmic integrals;
- `W1.5` — Integrals producing inverse-trigonometric functions.

---

# Part I. Prerequisite-review objectives

## `R1 — Algebra, function notation, and exact values`

Assess whether the student can:

- simplify expressions involving negative and rational exponents;
- rewrite radicals as rational powers and conversely;
- factor constants and recognize common algebraic structure;
- evaluate compositions such as \(f(g(x))\);
- identify inner and outer functions;
- determine elementary domain restrictions involving denominators, square roots, and logarithms;
- use exact unit-circle values;
- evaluate standard exact inverse-trigonometric values;
- distinguish \(\sin^{-1}x\) from \((\sin x)^{-1}\).

Do not devote time to elaborate algebra unrelated to the assigned Week 1 integration material.

## `R2 — Differentiation and the chain rule`

Assess whether the student can correctly differentiate functions involving:

- powers;
- sine and cosine;
- exponential functions;
- logarithmic functions;
- inverse sine and inverse tangent;
- inverse secant, including the absolute-value factor under the course convention;
- compositions of these functions.

Place particular emphasis on

\[
\frac{d}{dx}F(g(x))=F'(g(x))g'(x).
\]

The student should identify which factor comes from differentiating the inner function.

Product and quotient rules may appear naturally but should not dominate the prerequisite assessment.

## `R3 — Antiderivatives and definite-integral foundations`

Assess whether the student can:

- find basic antiderivatives using linearity and the power rule;
- recall elementary antiderivatives of sine, cosine, and \(e^x\);
- include \(+C\) for an indefinite integral;
- recognize that a definite integral with constant bounds is a number;
- distinguish a definite integral from a family of antiderivatives;
- interpret a definite integral as net signed accumulation;
- reverse and split bounds correctly;
- distinguish signed area from total geometric area.

Review the conceptual meaning of a definite integral without requiring lengthy Riemann-sum computations.

---

# Part II. Week 1 learning objectives

## `W1.1 — Mean Value Theorem for Integrals and Fundamental Theorem of Calculus`

Assess whether the student can:

1. compute the average value

   \[
   f_{\mathrm{avg}}=\frac{1}{b-a}\int_a^b f(x)\,dx;
   \]

2. state the continuity hypothesis and conclusion of the Mean Value Theorem for Integrals;
3. understand that the theorem guarantees existence, not necessarily uniqueness, of a suitable \(c\);
4. differentiate an accumulation function

   \[
   F(x)=\int_a^x f(t)\,dt;
   \]

5. differentiate an integral with a composite upper or lower limit;
6. differentiate an integral with two variable limits;
7. use the evaluation form

   \[
   \int_a^b f(x)\,dx=F(b)-F(a),\qquad F'=f;
   \]

8. explain how differentiation and integration act as inverse processes under the relevant hypotheses.

Require careful distinction among:

- the dummy variable of integration;
- a variable upper or lower limit;
- the chain-rule factor;
- the sign arising from a variable lower limit.

## `W1.2 — Basic integration formulas, net change, and symmetry`

Assess whether the student can:

- use linearity and elementary integration formulas;
- simplify an integrand before integrating;
- use the net change theorem;
- reconstruct a final quantity from an initial value and an integrated rate;
- distinguish displacement from total distance;
- distinguish signed net change from total accumulation;
- identify sign changes before computing total distance or total accumulation;
- classify a function as even, odd, or neither;
- use symmetry correctly on an interval of the form \([-a,a]\).

When symmetry is used, require the student to identify both the parity of the integrand and the symmetry of the interval.

## `W1.3 — Integration by substitution`

Assess whether the student can:

- recognize substitution as the reverse of the chain rule;
- choose an effective substitution \(u=g(x)\);
- compute \(du=g'(x)\,dx\);
- account for a missing constant multiple;
- rewrite the entire integral in terms of \(u\);
- avoid mixing \(x\) and \(u\) in the rewritten integral;
- evaluate the resulting integral;
- return to the original variable in an indefinite integral;
- transform both bounds in a definite integral;
- complete a definite integral entirely in \(u\);
- verify an indefinite integral by differentiation.

## `W1.4 — Exponential and logarithmic integrals`

Assess whether the student can recognize and use forms based on

\[
\int e^u\,du,
\qquad
\int a^u\,du,
\qquad
\int \frac{du}{u}.
\]

Include substitution, constant normalization, or both.

Assess whether the student understands

\[
\int \frac{g'(x)}{g(x)}\,dx=\ln|g(x)|+C
\]

and does not omit the absolute value without justification.

Include at least one problem in which applying the polynomial power rule to an exponential expression would be incorrect.

## `W1.5 — Integrals producing inverse-trigonometric functions`

Use the standard families, with \(a>0\):

\[
\int \frac{du}{\sqrt{a^2-u^2}},
\qquad
\int \frac{du}{a^2+u^2},
\qquad
\int \frac{du}{u\sqrt{u^2-a^2}}.
\]

Assess whether the student can:

- recognize inverse-sine, inverse-tangent, and inverse-secant forms;
- identify \(a\) and \(u\);
- normalize constants correctly;
- combine a standard form with substitution;
- use exact inverse-trigonometric values in definite integrals;
- handle domain and absolute-value issues appropriately.

Use the course convention

\[
\int \frac{du}{u\sqrt{u^2-a^2}}
=
\frac1a\sec^{-1}\!\left(\frac{|u|}{a}\right)+C.
\]

Accept an equivalent antiderivative only when it is correct on the relevant interval and the necessary domain restriction is stated.

At least one problem must test recognition of all three inverse-trigonometric families. This may be a matching or method-selection problem rather than three separate computations.

---

# Part III. Required assessment architecture

## Phase A — Four fixed prerequisite diagnostics

Begin with exactly four short prerequisite problems. Complete all four before prerequisite remediation.

### Diagnostic Problem 1 — Algebra and functions

Test algebraic simplification, composition, an elementary domain issue, or recognition of an inner function. Keep the computation relevant to later integration.

### Diagnostic Problem 2 — Trigonometry and inverse trigonometry

Test exact trigonometric or inverse-trigonometric values and recognition of inverse-function notation. Use no decimal approximations.

### Diagnostic Problem 3 — Differentiation

Test the chain rule using an exponential, logarithmic, trigonometric, or inverse-trigonometric composition.

Ask first for the inner function and its derivative rather than immediately asking for the complete derivative.

### Diagnostic Problem 4 — Antiderivatives and definite integrals

Test one basic antiderivative together with a conceptual distinction such as:

- indefinite versus definite integral;
- signed area versus geometric area;
- \(+C\) in an indefinite integral;
- reversing or splitting bounds.

This problem may contain several microsteps but counts as one problem.

## Transition after the prerequisite diagnostic

After all four prerequisite diagnostics:

- summarize the prerequisite evidence in no more than four sentences;
- do not give a general Calculus I lecture;
- proceed to Week 1 content;
- use the diagnostic results to adjust difficulty and microstep size;
- do not allow weak prerequisite performance to eliminate required Week 1 coverage.

## Phase B — Week 1 core assessment

Administer at least 10 valid problems whose primary purpose is Week 1 content.

The core assessment must include identifiable evidence for all of the following:

1. one conceptual problem on average value or the Mean Value Theorem for Integrals;
2. two FTC differentiation problems:
   - one with a composite upper or lower limit;
   - one with two variable limits or in find-the-error form;
3. one definite-integral problem using the evaluation form of the FTC;
4. one problem using elementary integration formulas together with even/odd symmetry;
5. one net-change application distinguishing signed net change from total amount or total distance;
6. two substitution problems:
   - one indefinite;
   - one definite with transformed bounds;
7. one exponential or logarithmic integration problem involving substitution or normalization;
8. one inverse-trigonometric problem involving standard-form recognition and substitution or scaling.

Compatible skills may be combined in a single problem, but every listed area must receive identifiable evidence in the final ledger.

## Phase C — Adaptive remediation and extension

Use remaining problems to repair weak evidence or extend strong performance, subject to the maximum of 20 valid problems.

When performance is weak:

- reduce algebraic complexity without changing the mathematical objective;
- diagnose the first incorrect decision;
- give a near-transfer problem after any explanation;
- distinguish conceptual errors from algebraic, arithmetic, sign, bounds, and notation errors;
- reassess the skill in a different representation.

When performance is strong, increase difficulty through one or more of:

- a nontrivial composite bound in an FTC problem;
- two variable limits;
- a substitution requiring a constant adjustment;
- a definite substitution problem for which changing bounds is more efficient;
- a logarithmic integral requiring recognition of \(g'/g\);
- an inverse-trigonometric integral requiring algebraic normalization;
- method selection followed by verification;
- error analysis of a plausible but incorrect solution.

Do not introduce:

- integration by parts;
- trigonometric integrals as a separate technique;
- trigonometric substitution;
- partial fractions;
- numerical integration;
- improper integrals.

---

# Part IV. Required problem types and cumulative checks

Across the complete session, include:

- at least 2 conceptual or method-recognition problems;
- at least 2 `find the first error and repair it` problems;
- at least 1 net-change application;
- at least 1 definite substitution problem with changed bounds;
- at least 1 problem distinguishing net change from total accumulation or total distance;
- at least 1 problem involving \(\ln|g(x)|\);
- at least 1 inverse-trigonometric recognition problem;
- at least 2 cumulative problems.

The final two valid problems must:

- be cumulative;
- begin without leading hints;
- include at least one problem requiring method selection before computation.

---

# Part V. Week 1 microstep protocols

Use these as default decompositions. Modify them only when another decomposition is mathematically more natural.

## FTC differentiation

Ask, in order:

1. Which part of the Fundamental Theorem applies?
2. What is the integrand evaluated at the relevant bound?
3. What chain-rule factor is required?
4. Is there a sign arising from a lower limit?
5. What is the final derivative?
6. How can the result be checked for consistency?

## FTC evaluation

Ask, in order:

1. What antiderivative should be used?
2. Should \(+C\) appear in this definite-integral computation?
3. What are the upper- and lower-endpoint evaluations?
4. What is the signed result?
5. Is its sign and approximate magnitude plausible?

## Substitution

Ask, in order:

1. What should \(u\) be?
2. What is \(du\)?
3. Is a constant adjustment needed?
4. Rewrite the entire integral using only \(u\) and \(du\).
5. For a definite integral, what are the transformed bounds?
6. Evaluate.
7. For an indefinite integral, return to \(x\).
8. Verify by differentiation when practical.

## Net change

Ask, in order:

1. What quantity is a rate of change?
2. Over what interval should it be integrated?
3. Is the question asking for signed net change or total accumulation?
4. Does the interval need to be split at a sign change?
5. What are the units of the final result?

## Exponential or logarithmic integration

Ask, in order:

1. What inner expression should be identified?
2. Is its derivative present, possibly up to a constant?
3. Which standard formula applies?
4. Is an absolute value required?
5. Can the answer be verified by differentiation?

## Inverse-trigonometric integration

Ask, in order:

1. Which standard family does the denominator resemble?
2. What are \(a\) and \(u\)?
3. What is \(du\)?
4. What constant normalization is required?
5. Which inverse-trigonometric function results?
6. Are there domain or absolute-value issues?

---

# Part VI. Week 1 mathematical boundaries

All generated problems must satisfy the following:

- Use exact arithmetic.
- Avoid decimal approximations unless interpretation specifically requires one.
- Avoid computations whose difficulty is primarily tedious arithmetic.
- Avoid non-elementary antiderivatives.
- Do not require a technique outside §§1.3–1.7.
- Do not disguise an integration-by-parts or partial-fractions problem as a substitution problem.
- Check every generated problem privately before presenting it.
- Accept algebraically equivalent correct answers.
- Verify antiderivatives by differentiation whenever practical.
- For definite integrals, check signs, bounds, and rough magnitude.
- For inverse functions, respect the stated branch and domain conventions.
- If a problem is ambiguous or outside scope, mark it `V — Void` and replace it.

---

# Part VII. Permitted and prohibited tools

During the active assessment, the student may use:

- paper;
- pencil or pen;
- the single LLM administering this assessment.

Unless the instructor separately announces an accommodation, the student may not use:

- a calculator;
- a computer-algebra system;
- an integral calculator;
- the textbook or class notes;
- an answer site;
- web search;
- another AI system;
- another person.

Generate problems for which a calculator is unnecessary.

---

# Part VIII. Specialized prerequisite-readiness classifications

Use the master protocol's ordinary mastery labels for `W1.1`–`W1.5`.

For `R1`–`R3`, use these readiness labels instead:

## `READY`

The student demonstrated the skill independently or with only a minor correction, and no essential misconception remains.

## `FRAGILE`

The student showed partial knowledge but depended on prompting or made recurrent procedural errors.

## `NEEDS IMMEDIATE REVIEW`

The skill was not demonstrated or an essential misconception remains.

## `INSUFFICIENT EVIDENCE`

The problem was void or the session ended before usable evidence was obtained.

Do not call a student globally prepared or unprepared for Calculus II based on this session.

---

# Part IX. Week 1 reflection

Before report generation, require the student to answer all three questions in the student's own words.

1. Identify one prerequisite skill and one Week 1 skill that most need attention. Cite at least one problem number for each. If no prerequisite weakness appeared, identify the prerequisite skill for which the evidence was strongest.

2. Describe one specific error from the session. State:
   - what you originally did;
   - why it was incorrect;
   - the corrected mathematical principle.

3. Give a concrete 20-minute study plan. Name:
   - the exact skill to be practiced;
   - the type and number of problems to attempt;
   - how the answers will be checked;
   - what would count as evidence of improvement.

Do not write these answers for the student.

---

# Part X. Week 1 integrity statement

Ask the student to type the following statement exactly, except for a modification required by a separately announced instructor accommodation:

> I certify that the mathematical responses recorded in this session are my own. During the active assessment I used only paper, a writing instrument, and the LLM administering the assessment. I did not use another person, another AI system, a calculator, a computer-algebra system, notes, the textbook, an answer key, or a web resource to generate my responses.

If the student declines, include `Integrity statement not provided` in the final report.

---

# Part XI. Week 1 report additions

In addition to the report sections required by the master prompt, include the following Week 1-specific material.

## A. Prerequisite Readiness table

Use columns:

- prerequisite objective;
- supporting problem numbers;
- first-attempt evidence;
- principal difficulty;
- readiness status;
- recommended review.

Use only the specialized readiness labels in this card.

## B. Week 1 Learning Evidence table

For `W1.1`–`W1.5`, include:

- objective;
- supporting problem numbers;
- independent successes;
- support dependence;
- conceptual understanding;
- method selection;
- execution;
- algebraic accuracy;
- mastery classification;
- principal misconception or remaining risk;
- recommended next action.

## C. Week 1 coverage audit

State explicitly whether the session included:

- the Mean Value Theorem for Integrals or average value;
- FTC differentiation with a composite bound;
- FTC differentiation with two variable limits or error analysis;
- FTC evaluation;
- net change;
- even/odd symmetry;
- indefinite substitution;
- definite substitution with changed bounds;
- exponential or logarithmic integration;
- inverse-trigonometric integration;
- two find-the-error problems;
- two cumulative problems.

Cite supporting problem numbers. If any required element was omitted, state that the session was procedurally incomplete.

## D. Week 1 error classification

Classify each substantial error using one of:

- prerequisite algebra;
- prerequisite trigonometry;
- differentiation or chain rule;
- definite-integral interpretation;
- theorem selection;
- substitution setup;
- constant-factor error;
- bounds error;
- \(+C\) error;
- sign error;
- domain or absolute-value error;
- arithmetic error;
- incomplete justification.

Do not classify an error merely as `careless` unless the transcript contains evidence that the student understood the relevant principle.

---

# Part XII. Output filename

Use:

`Lastname_MATH150B_Week01_SelfAssessment.pdf`

If direct PDF creation is unavailable, produce one print-ready report for **Print → Save as PDF**, as required by the master protocol.
