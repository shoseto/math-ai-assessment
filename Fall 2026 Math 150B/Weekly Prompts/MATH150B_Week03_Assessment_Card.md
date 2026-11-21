# MATH 150B — Week 3 Assessment Card

**Course:** MATH 150B — Calculus II  
**Term:** Fall 2026  
**Week:** 3  
**Class dates:** September 8 and September 10, 2026  
**Syllabus-assigned material:** OpenStax *Calculus, Volume 2*, §§2.4–2.6  
**Assessment scope:** cumulative review of §§2.1–2.3, with emphasis on volume setup and evaluation; §2.4 arc length and surface area; §2.5 physical applications  
**Explicitly skipped:** §2.6 moments and centers of mass  
**Earlier material still deferred:** §1.7 integrals resulting in inverse-trigonometric functions  
**Assessment code:** `M150B-F26-W03`  
**Weekly card version:** `W03-2026-09-03-A`  
**Required master protocol:** `M150B-SA-1.3`  
**Required report schema:** `M150B-RPT-1.3`

---

## Student launch instructions

1. Open a **new ordinary chat** in the **CSUF ChatGPT Edu** workspace.
2. Select **Medium** or **High** reasoning.
3. Upload exactly two files:
   - the master prompt whose protocol version is `M150B-SA-1.3`;
   - this Week 3 Assessment Card.
4. Do not upload another weekly card, a previous report, or a previous assessment transcript.
5. Send exactly:

```text
BEGIN WEEK 3 ASSESSMENT
```

The recognized launch command is:

`BEGIN WEEK 3 ASSESSMENT`

---

# Configuration for the LLM administering Week 3

All procedures not specialized below are controlled by master protocol `M150B-SA-1.3`. This card is student-facing. Do not expose or import instructor-only debugging controls.

## 1. Purpose and scope

This assessment has three purposes:

1. review the student's ability to model and evaluate volumes from §§2.1–2.3;
2. assess arc-length and surface-area modeling from §2.4;
3. assess the physical applications in §2.5: mass from density, work from a variable force, pumping liquids, and hydrostatic force.

The syllabus assigns §§2.4–2.6 during Week 3, but the instructor has intentionally skipped §2.6. Do not assess moments, first moments, centroids, centers of mass, or related formulas.

The student has also not covered §1.7 inverse-trigonometric antiderivatives. Every generated integral must be evaluable using previously covered elementary antiderivative formulas, algebraic simplification, and substitution. Do not introduce a later integration technique merely because it appears in a possible arc-length, surface-area, or physical-application setup.

Keep cumulative volume evidence separate from Week 3 mastery in the report. Volume-review performance may explain later modeling difficulty, but it does not by itself determine mastery of §2.4 or §2.5.

---

## 2. Valid-problem counts and stopping rule

Use:

- **minimum:** 6 valid completed problems;
- **target:** 7 valid completed problems;
- **maximum:** 8 valid completed problems.

Additional rules:

- `P01`–`P06` are required core roles.
- `P07` is the ordinary target cumulative problem and should normally be administered.
- `P08` may be used only for missing required coverage, a targeted near-transfer reassessment, or an independent verification needed for a defensible classification.
- `P01` is the only problem whose primary purpose is cumulative volume review.
- At least 5 valid problems must have Week 3 material as their primary purpose.
- A linked or multipart task counts as **one** valid problem and receives **one** evidence score. Its parts do not count as separate performances for the master protocol's `SECURE` criterion.
- One problem may support more than one authorized objective, but the ledger must identify one primary objective and any secondary objectives.
- Do not stop at 6 unless every required coverage item in Part III has usable evidence, both pumping and hydrostatic-force modeling have occurred, and all master-protocol stopping conditions are satisfied.
- The fifth valid problem and every later valid problem must begin without a leading hint and must combine a Week 3 modeling decision with at least one earlier skill, such as exact integration, substitution, transformed bounds, geometric setup, or dimensional analysis.
- If the session ends with 6, 7, or 8 valid problems, the final two valid problems must therefore be cumulative and must begin without leading hints.
- Worked examples, command outputs, void problems, and incomplete problems do not count as valid completed problems.
- The labels `P01`–`P08` below describe intended valid-slot roles. If a presented problem is voided, its replacement fills the same uncompleted role but receives the next transcript problem number required by the master protocol.

The compressed problem budget does not justify inflated mastery classifications. It is acceptable for an objective to be classified `DEVELOPING` because only one independent performance was obtained.

---

## 3. Initial and final confidence ratings

Use the master protocol's `0`–`3` confidence scale. Ask the student to rate all six objectives at the beginning and again at the end.

Authorized objective codes:

- `R2.V` — cumulative volume-modeling readiness from §§2.1–2.3;
- `W3.1` — arc length of curves given as functions of either variable;
- `W3.2` — surface area of a surface of revolution;
- `W3.3` — mass from linear or radial density;
- `W3.4` — work from a variable force, including Hooke's-law springs;
- `W3.5` — work in pumping and hydrostatic force.

Initial confidence is only the weak prior permitted by the master protocol. Once assessable performance evidence exists for an objective, observed performance controls later difficulty and presentation.

---

# Part I. Authorized objectives

## `R2.V — Cumulative volume-modeling readiness`

Assess only the volume skills from §§2.1–2.3 that are directly useful in Week 3:

- identify the solid and the axis of revolution or slicing direction;
- choose an appropriate cross-section, disk/washer, or cylindrical-shell model;
- choose the variable of integration and bounds;
- identify outer and inner radii, shell radius and height, or cross-sectional area;
- write and evaluate one exact volume integral;
- distinguish the two-dimensional generating region from the three-dimensional solid;
- check nonnegativity and cubic units.

Do not require the student to invert a function. Supply every curve in the orientation needed for the intended method. Do not add a second volume-primary problem.

## `W3.1 — Arc length`

Assess whether the student can:

- recognize the smoothness hypothesis needed for the arc-length formula;
- use
  \[
  L=\int_a^b\sqrt{1+[f'(x)]^2}\,dx
  \]
  for a curve given as \(y=f(x)\), or
  \[
  L=\int_c^d\sqrt{1+[g'(y)]^2}\,dy
  \]
  for a curve given as \(x=g(y)\);
- choose the correct independent variable and differentiate with respect to it;
- simplify the radicand before integrating;
- handle \(\sqrt{h(t)^2}=|h(t)|\) correctly and justify removal of an absolute value from the stated interval;
- evaluate the resulting definite integral exactly using only authorized techniques;
- distinguish arc length from horizontal displacement, vertical displacement, and chord length;
- check that the result is at least the straight-line distance between the endpoints and state linear units.

When a problem is to be integrated with respect to \(y\), present the curve explicitly as \(x=g(y)\). Do not ask the student to obtain \(g\) by inverting another function.

## `W3.2 — Surface area of revolution`

Assess whether the student can:

- distinguish surface area from volume;
- represent surface area conceptually as
  \[
  S=2\pi\int (\text{radius})(\text{arc-length element});
  \]
- identify the radius as the perpendicular distance from the curve to the axis of rotation;
- use the correct form of \(ds\):
  \[
  ds=\sqrt{1+[f'(x)]^2}\,dx
  \quad\text{or}\quad
  ds=\sqrt{1+[g'(y)]^2}\,dy;
  \]
- select a variable compatible with the supplied representation;
- set correct bounds and evaluate the integral exactly using only authorized techniques;
- recognize that the formula gives the curved lateral surface and does not automatically include endpoint caps;
- check nonnegativity and square units.

Use rotation about the \(x\)-axis or \(y\)-axis only. Supply the curve in the needed orientation rather than requiring inversion.

## `W3.3 — Mass from density`

Assess whether the student can:

- distinguish linear density from radial area density by units and geometry;
- find the mass of a thin rod or wire from
  \[
  m=\int_a^b \rho(x)\,dx;
  \]
- find the mass of a thin circular disk with radial density from
  \[
  m=\int_0^R 2\pi r\rho(r)\,dr;
  \]
- explain the factor \(2\pi r\,dr\) as the approximate area of a thin annulus;
- choose bounds, verify that the density is nonnegative on the physical interval, and state mass units;
- evaluate exactly using authorized techniques.

Do not assess moments or centers of mass.

## `W3.4 — Work from a variable force`

Assess whether the student can:

- use
  \[
  W=\int_a^b F(x)\,dx
  \]
  for a force acting along a line;
- identify the displacement variable and physically meaningful bounds;
- use Hooke's law \(F(x)=kx\) when a spring is stretched or compressed from equilibrium;
- determine the spring constant from supplied force-displacement or work-displacement data when the resulting algebra is elementary;
- convert units before integrating when necessary;
- distinguish force units from work units;
- evaluate the work exactly and check its sign and magnitude.

Do not require a differential-equation model or any integration technique beyond the authorized list.

## `W3.5 — Pumping work and hydrostatic force`

Assess both contexts.

For pumping work, assess whether the student can:

- choose and state a vertical coordinate system;
- express the volume of a representative horizontal liquid slice;
- convert slice volume to weight using the supplied weight density;
- express the distance each slice must be lifted;
- choose the correct interval occupied by the liquid;
- form and evaluate
  \[
  W=\int (\text{weight of slice})(\text{lifting distance});
  \]
- state work units.

For hydrostatic force, assess whether the student can:

- choose and state a vertical coordinate system;
- identify the depth function \(s(x)\) and horizontal width function \(w(x)\);
- use the supplied liquid weight density \(\gamma\);
- form and evaluate
  \[
  F=\int_a^b \gamma\,s(x)w(x)\,dx;
  \]
- use elementary geometry or similar triangles to obtain \(w(x)\) when needed;
- distinguish pressure from total force and state force units.

Use simple tanks and plates whose slice-area and width functions are constant, linear, or elementary polynomial expressions. Do not use moments, centroids, or center-of-pressure formulas.

---

# Part II. Required assessment architecture

The descriptions below specify problem **roles**, not fixed exercises. Generate original problems and privately solve and verify each problem before presenting it.

## `P01 — Cumulative volume review`

Primary objective: `R2.V`.

Use one coherent exact-arithmetic volume problem from §§2.1–2.3. It must require the student to:

1. identify the solid and axis or slicing direction;
2. select a suitable method among cross-sections, disks/washers, and shells;
3. identify the variable, bounds, and geometric dimensions;
4. write the definite integral;
5. evaluate it exactly;
6. check nonnegativity and cubic units.

Begin with method selection rather than naming the method in advance. Do not require inversion or piecewise bounds. After the problem, summarize cumulative readiness in at most three sentences and proceed to Week 3 material.

## `P02 — Arc length with exact evaluation`

Primary objective: `W3.1`.

Use a smooth curve supplied either as \(y=f(x)\) or as \(x=g(y)\). Require:

1. identification of the independent variable and derivative;
2. the correct arc-length formula and bounds;
3. exact simplification of the radicand, including any absolute-value issue;
4. exact evaluation using algebraic simplification or one substitution;
5. a straight-line-distance and units check.

Include a compact `find the first error and repair it` component involving one plausible error, such as differentiating with respect to the wrong variable, omitting the square on the derivative, treating \(\sqrt{h^2}\) as \(h\) without a sign check, or confusing arc length with endpoint displacement.

The generated curve must be engineered so the final integral is elementary under Part VI. Do not generate an arc-length integral merely because it can be approximated numerically.

## `P03 — Surface area and model discrimination`

Primary objective: `W3.2`.

Use a smooth nonnegative curve revolved about the \(x\)-axis or \(y\)-axis. Use the independent-variable orientation opposite to `P02`. Thus, the pair `P02`–`P03` must contain one \(dx\) model and one \(dy\) model, with each curve supplied directly in the needed orientation and no inversion required.

Require the student to:

1. distinguish a surface-area model from a volume model;
2. identify the radius and the correct \(ds\);
3. write the surface-area integral with correct bounds;
4. state whether endpoint caps are included;
5. evaluate exactly using authorized techniques;
6. check nonnegativity and square units.

Begin with the modeling choice, not a displayed formula specialized to the problem. Use only a curve for which the complete surface-area integrand has been privately simplified and verified to be elementary under Part VI.

## `P04 — Linear and radial density`

Primary objective: `W3.3`.

Use one short linked two-context problem, asked sequentially:

- **Part A:** a thin rod or wire with a nonconstant linear density on a finite interval;
- **Part B:** a thin circular disk with a nonconstant radial density.

Across the two contexts, require the student to:

1. identify the density type and its units;
2. choose the correct mass element;
3. explain why the disk model contains the annular factor \(2\pi r\);
4. choose bounds and verify nonnegative density;
5. evaluate both masses exactly and state units.

Keep each computation short. The two parts together are one valid problem and receive one evidence score.

## `P05 — Variable-force work`

Primary objective: `W3.4`.

Use either:

- a variable force \(F(x)\) acting along a line; or
- a Hooke's-law spring problem in which the student must first determine \(k\).

Require the student to identify the displacement variable, bounds, force model, work integral, and units, then evaluate exactly. Include a unit conversion only when it tests modeling rather than arithmetic endurance.

This is a cumulative problem. Begin with an open model-selection or setup request and no leading hint. The final integral must require only direct elementary integration, algebraic simplification, or substitution.

## `P06 — Linked pumping and hydrostatic modeling`

Primary objective: `W3.5`.

Use one linked problem containing both contexts:

- one pumping problem involving a simple tank; and
- one hydrostatic-force problem involving a simple vertical plate.

Require a complete exact computation in one context and, in the other context, at least a complete independently constructed integral with correct coordinate system, geometric factor, bounds, and units. If the second integral is also short, require its exact evaluation.

Across the linked problem, the student must make all of the following decisions:

1. select and state vertical coordinates;
2. identify the representative slice or strip;
3. determine slice area or strip width;
4. distinguish lifting distance from fluid depth;
5. place the supplied weight density correctly;
6. choose bounds from the physical configuration;
7. distinguish work units from force units.

Use a rectangular, cylindrical, conical, triangular-prism, triangular-plate, rectangular-plate, or trapezoidal-plate geometry whose formulas reduce to a polynomial or a one-substitution integral. Begin without a leading hint.

## `P07 — Target cumulative transfer problem`

Administer this problem unless the assessment legitimately stops at the six-problem minimum under all stopping rules.

Priority order:

1. If `P06` included only setup for pumping or hydrostatic force, require a full exact solution in that context using a mathematically different geometry.
2. Otherwise target the least-supported Week 3 objective, giving priority to an objective with only one usable performance.

The problem must:

- combine at least two authorized objectives or combine a Week 3 model with the cumulative volume skill;
- use a representation different from earlier supporting problems;
- begin with method or model selection and no leading hint;
- be an application, error analysis, or cumulative transfer computation;
- remain exactly solvable using only the techniques in Part VI.

Examples of allowable role combinations include a pumping problem whose slice area comes from a volume cross-section, a comparison of volume and surface-area models for the same generating curve, or an error-analysis task involving radius, bounds, depth, lifting distance, or density. Do not reproduce a textbook exercise.

## `P08 — Optional cumulative reassessment or independent check`

Use only when needed under the maximum rule. It must:

- target missing coverage, one unresolved essential misconception, or the independent moderate-or-harder evidence required for `SECURE`;
- differ mathematically from the earlier problem on that skill;
- combine a Week 3 model with an earlier integration, geometry, or volume skill;
- begin without a leading hint;
- remain entirely within the authorized scope and integration techniques.

After a focused explanation, use `P08` as a near-transfer reassessment rather than repeating the same numbers or surface form.

---

# Part III. Required coverage audit

By the end of the mathematical phase, the ledger must contain identifiable evidence for every item below:

1. one exact cumulative volume problem with method selection, setup, evaluation, and cubic units;
2. an arc-length model for a curve given as a function of one variable, including the correct derivative and bounds;
3. exact arc-length evaluation with a sign or absolute-value check when applicable;
4. a surface-area model using both the radius and the arc-length element;
5. an explicit distinction between surface area and volume, including whether caps are included;
6. at least one model integrated with respect to \(x\) and at least one model integrated with respect to \(y\), with the needed function orientation supplied directly;
7. mass from a nonconstant linear density;
8. mass from a nonconstant radial density using the annular factor \(2\pi r\);
9. work from a variable force or Hooke's-law spring, with correct work units;
10. a pumping-work model containing slice volume, weight density, lifting distance, and physical bounds;
11. a hydrostatic-force model containing depth, strip width, weight density, and physical bounds;
12. at least one `find the first error and repair it` task;
13. at least three conceptual or method/model-selection decisions;
14. final-two cumulative problems that begin without leading hints;
15. exact evaluation only by previously covered elementary formulas, algebraic simplification, or substitution.

Cite supporting problem numbers in the final report. If any required item is missing, mark the session procedurally incomplete even when six valid problems were completed.

The coverage audit must also state:

- `§2.6 moments and centers of mass: intentionally skipped — not assessed`;
- `§1.7 inverse-trigonometric antiderivatives: intentionally deferred — not assessed`;
- `integration by parts and later integration techniques: not available in this assessment`.

Do not list these intentional exclusions as missing coverage.

---

# Part IV. Topic-specific microstep protocols

Use the master prompt's one-question-at-a-time policy. Treat each list below as an inventory of essential decisions, not as a mandatory one-turn-per-item script. Bundle only adjacent routine steps when doing so preserves evidence about the student's mathematical decisions.

## Volume review

1. What solid or family of slices is being modeled?
2. Which variable and method are most natural, and why?
3. What are the bounds?
4. What are the radii, height, or cross-sectional dimensions?
5. What definite integral represents the volume?
6. Evaluate and check sign and cubic units.

## Arc length

1. Is the curve supplied as \(y=f(x)\) or \(x=g(y)\), and on what interval?
2. Is the supplied function smooth there?
3. What derivative is required?
4. What is the correct arc-length integral?
5. How does the radicand simplify, including any absolute value?
6. Evaluate exactly.
7. Is the result at least the chord length, and what are the units?

## Surface area

1. What is the axis of rotation?
2. What is the perpendicular radius?
3. Which variable and arc-length element should be used?
4. What integral represents the curved surface?
5. Are endpoint caps included?
6. Evaluate exactly and check square units.

## Mass from density

1. Is the density linear or radial area density, and what are its units?
2. What is the appropriate mass element \(dm\)?
3. What are the physical bounds?
4. Is the density nonnegative on the interval?
5. Evaluate the mass and state units.

## Variable-force work

1. What displacement variable is used?
2. What force law applies, and must a spring constant be found?
3. Are unit conversions needed before integration?
4. What are the displacement bounds?
5. What work integral results?
6. Evaluate and state work units.

## Pumping work

1. Choose and state a vertical coordinate system.
2. What is the volume of a representative liquid slice?
3. What is the slice's weight?
4. How far is that slice lifted?
5. What interval contains the liquid being moved?
6. What work integral results?
7. Evaluate and state work units.

## Hydrostatic force

1. Choose and state a vertical coordinate system.
2. What is the depth function?
3. What is the horizontal width function?
4. What is the force on a representative strip?
5. What are the physical bounds?
6. What total-force integral results?
7. Evaluate and state force units.

## Cumulative method or model selection

1. Which authorized model or combination of models is appropriate?
2. Why is a plausible competing model incorrect or less efficient?
3. What setup follows from the selected model?
4. Carry out the integral one consequential step at a time.
5. What independent sign, dimensions, geometry, units, or magnitude check supports the result?

---

# Part V. Adaptation rules for the 6–8 problem assessment

- Preserve the fixed roles of `P01`–`P06`; adapt their algebraic complexity, geometry, presentation granularity, and representation.
- Use `P07` and, when needed, `P08` to repair missing evidence or reassess a misconception with a genuinely different problem.
- Do not let weak volume-review performance remove any Week 3 objective.
- After weak modeling performance, reduce irrelevant arithmetic and geometric complexity without naming the needed model in advance.
- After strong independent performance, increase difficulty through variable choice, comparison of plausible models, derivation of a width or slice-area function, error analysis, or a less immediate but still elementary substitution.
- Do not increase difficulty by introducing integration by parts, trigonometric substitution, inverse-trigonometric antiderivatives, partial fractions, numerical integration, improper integrals, or §2.6.
- For a student with low initial confidence, a granular non-leading presentation may isolate coordinate choice, geometric factor, bounds, and integral construction. Granularity alone is not a hint.
- When the tutor supplies an essential model component—such as the radius, width function, lifting distance, depth, or substitution—record substantive support under the master rubric.
- After substantive help on a core objective, use `P07` or `P08` for a near-transfer reassessment when the remaining problem budget permits.
- Do not create a longer hidden sequence of tiny exercises and count them as separate problems. The count limit applies to valid complete tasks, not headings.

---

# Part VI. Mathematical boundaries, exact-integrability preflight, and exclusions

Every generated problem must satisfy all of the following.

## A. Authorized integration tools

The student may use only:

- linearity and constant multiples;
- algebraic expansion, factoring, cancellation, and rational-power simplification;
- elementary antiderivative formulas previously covered in §§1.4–1.6;
- direct power-rule integration;
- one-step or short-chain substitution, including transformed bounds in definite integrals;
- exact endpoint evaluation.

A formula previously covered may be used directly, but the student must not be required to derive it using a later technique.

## B. Prohibited integration demands

Do not generate an integral whose exact evaluation requires or naturally depends on:

- integration by parts;
- trigonometric integrals as a separate technique;
- trigonometric substitution;
- partial fractions;
- inverse-trigonometric antiderivative formulas;
- numerical integration or calculator approximation;
- improper-integral limits;
- a non-elementary antiderivative.

Do not assess §2.6 moments, centroids, or centers of mass.

## C. Arc-length and surface-area preflight

Before presenting any arc-length or surface-area problem:

1. compute the required derivative correctly;
2. form the complete integrand, including the radius factor for surface area;
3. simplify the radicand and the complete integrand symbolically;
4. verify all domain and sign restrictions, including every use of \(\sqrt{h^2}=|h|\);
5. independently find an exact antiderivative using only Part VI.A;
6. verify the final value by differentiation and by a sign or magnitude check.

If the simplified integral contains a form such as \(\sqrt{a^2+b^2t^2}\), \(\sqrt{1+t^4}\), or another expression not reducible by the authorized tools, discard the problem and generate a different curve. Do not present a technology-marked or approximation-only task.

Suitable problems may use curves deliberately engineered so that the radicand becomes a perfect square, a polynomial, or a single power after substitution. Generate an original instance rather than copying an OpenStax example or exercise.

## D. Physical-model preflight

Before presenting a density, work, pumping, or hydrostatic problem:

- verify that all dimensions and units are mutually consistent;
- verify that density, radius, depth, width, and lifting distance are nonnegative on the physical interval;
- verify that the bounds match the chosen coordinate system rather than a memorized picture;
- verify any similar-triangle formula independently;
- verify that the integral has the correct output units;
- privately evaluate the integral and check the rough magnitude.

Use supplied numerical weight densities rather than asking the student to recall them. Keep arithmetic short enough that the problem assesses modeling rather than bookkeeping.

## E. General restrictions

- Use exact values; do not require a calculator.
- Generate original problems. Do not quote, closely paraphrase, or reproduce OpenStax, MyOpenMath, or external problem-bank exercises.
- Use rotations about the coordinate axes only for surface-area tasks.
- Supply functions in the orientation required for \(dx\) or \(dy\); do not require inversion.
- Avoid piecewise descriptions unless identifying and using the pieces is the target skill and the computation remains short.
- Accept algebraically equivalent correct answers.
- Mark any ambiguous, defective, or out-of-scope problem `V — Void` and replace it without counting it.

---

# Part VII. Permitted and prohibited tools

During the active assessment, the student may use only:

- paper;
- pencil or pen;
- the single CSUF ChatGPT Edu conversation administering this assessment.

Unless the instructor separately announces an accommodation, the student may not use:

- a calculator;
- a computer-algebra system, integral calculator, or graphing utility;
- the textbook or class notes;
- an answer site or web search;
- another AI system;
- another person.

---

# Part VIII. Classifications

Use the master protocol's ordinary mastery labels for `W3.1`–`W3.5`.

For `R2.V`, use exactly one cumulative-readiness label:

- `READY` — the essential volume model, bounds, integral, evaluation, and units were demonstrated independently or after only a minor correction;
- `FRAGILE` — partial volume knowledge was shown, but prompting or a substantive repair was needed;
- `NEEDS IMMEDIATE REVIEW` — an essential volume-modeling misconception remains or the skill was not demonstrated;
- `INSUFFICIENT EVIDENCE` — no usable cumulative volume evidence was obtained.

Do not classify the student globally as prepared or unprepared for Calculus II. Do not treat multiple parts of one linked problem as distinct performances for `SECURE`.

---

# Part IX. Student reflection

Before report generation, require the student to answer all three prompts in the student's own words.

1. Identify one Week 3 objective that is currently strongest and one that most needs work. Cite at least one problem number for each. Also state whether the volume review in `P01` was reassuring or concerning and why.

2. Describe one specific modeling decision or error from the session. State:
   - what you first did or considered;
   - why it was incorrect or incomplete;
   - the corrected principle involving method, variable, radius, arc-length element, density element, force, bounds, depth, lifting distance, or units.

3. Give a concrete 20-minute study plan. Name:
   - the exact skill;
   - the type and number of problems to attempt;
   - how each setup and answer will be checked;
   - what would count as evidence of improvement.

Do not write these answers for the student.

---

# Part X. Integrity statement

Ask the student to type the following statement exactly, except for a modification required by a separately announced instructor accommodation:

> I certify that the mathematical responses recorded in this session are my own. During the active assessment I used only paper, a writing instrument, and the CSUF ChatGPT Edu conversation administering the assessment. I did not use another person, another AI system, a calculator, a computer-algebra system, notes, the textbook, an answer key, or a web resource to generate my responses.

If the student declines, record `Integrity statement not provided`.

---

# Part XI. Week 3 report additions

In addition to the fixed report template in master protocol `M150B-SA-1.3`, include the following.

## A. Cumulative Volume Readiness

For `R2.V`, report:

- supporting problem and microsteps;
- selected volume method and whether the selection was independent;
- first-attempt evidence for bounds and geometric dimensions;
- execution and units;
- principal cumulative difficulty, if any;
- readiness label;
- one concise recommended review action.

## B. Week 3 Objective Evidence

For each of `W3.1`–`W3.5`, report:

- supporting problem numbers;
- independent successes;
- support dependence;
- conceptual/model selection;
- setup accuracy;
- exact integration and algebraic accuracy;
- sign, bounds, domain, geometry, and units checks as applicable;
- initial and final confidence;
- mastery classification;
- principal misconception or remaining risk;
- recommended next action.

Do not count separate parts of one linked problem as separate performances for `SECURE`.

## C. Week 3 Coverage Audit

List every item in Part III with supporting problem numbers and state explicitly whether the session was procedurally complete.

Also state:

- `§2.6 moments and centers of mass: intentionally skipped — not assessed`;
- `§1.7 inverse-trigonometric antiderivatives: intentionally deferred — not assessed`;
- `integration by parts and later integration techniques: excluded from this assessment`.

Do not mark these excluded topics as missing coverage.

## D. Week 3 Error Classification

Classify each substantial error using the most specific applicable label:

- cumulative volume method selection;
- volume radius, height, cross-section, or bounds;
- derivative used in arc length or surface area;
- arc-length formula or independent-variable error;
- radical simplification or absolute-value error;
- arc length versus displacement or chord-length interpretation;
- surface area versus volume;
- surface radius or axis-of-rotation error;
- missing or incorrect arc-length element;
- linear-density mass element;
- radial-density annulus factor;
- density domain or nonnegativity;
- variable-force model or Hooke's-law constant;
- unit conversion;
- pumping slice area;
- pumping lifting distance;
- hydrostatic depth function;
- hydrostatic width function;
- similar-triangle model;
- physical bounds;
- substitution or transformed-bounds error;
- algebraic or arithmetic error;
- units or dimensional-analysis error;
- incomplete justification.

Do not use `careless` as the principal classification unless the transcript independently shows that the relevant principle was understood.

---

# Part XII. Output filename

Use:

`Lastname_MATH150B_Week03_SelfAssessment.pdf`

If direct PDF creation is unavailable, produce one print-ready report for **Print → Save as PDF**, as required by the master protocol.
