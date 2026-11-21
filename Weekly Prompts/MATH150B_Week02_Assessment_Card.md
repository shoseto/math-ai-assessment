# MATH 150B — Week 2 Assessment Card

**Course:** MATH 150B — Calculus II  
**Term:** Fall 2026  
**Week:** 2  
**Class dates:** September 1 and September 3, 2026  
**Syllabus-assigned material:** OpenStax *Calculus, Volume 2*, §§2.1–2.3  
**Cumulative reinforcement:** §1.5 integration by substitution and the Chapter 1 integration conventions needed to evaluate the resulting definite integrals  
**Explicitly deferred:** §1.7 inverse-trigonometric antiderivatives and §§2.4–2.6  
**Assessment code:** `M150B-F26-W02`  
**Weekly card version:** `W02-2026-08-28-A`  
**Required master protocol:** `M150B-SA-1.3`  
**Required report schema:** `M150B-RPT-1.3`

---

## Student launch instructions

1. Open a **new ordinary chat** in the **CSUF ChatGPT Edu** workspace.
2. Select **Medium** or **High** reasoning.
3. Upload exactly two files:
   - the master prompt whose runtime protocol is `M150B-SA-1.3`;
   - this Week 2 Assessment Card.
4. Do not upload another weekly card, a previous report, or a previous assessment transcript.
5. Send exactly:

```text
BEGIN WEEK 2 ASSESSMENT
```

The recognized launch command is:

`BEGIN WEEK 2 ASSESSMENT`

---

# Configuration for the LLM administering Week 2

All procedure not specialized below is controlled by master protocol `M150B-SA-1.3`. This card is student-facing. Do not expose or infer instructor-only debug controls.

## 1. Purpose and scope

This assessment has three purposes:

1. reinforce a slightly more advanced use of substitution without introducing an integration technique beyond Chapter 1;
2. assess whether the student can translate a planar or three-dimensional geometric description into a correct definite-integral setup;
3. assess method selection among vertical and horizontal area slices, general slicing, disks, washers, and cylindrical shells.

The Week 2 material is §§2.1–2.3:

- area between curves, including compound regions and integration with respect to either variable;
- volume by known cross-sections, disks, and washers;
- volume by cylindrical shells and comparison of available volume methods.

The cumulative substitution component is reinforcement, not a second full Week 1 assessment. Do not assess §1.7 inverse-trigonometric antiderivatives. Do not introduce integration by parts, trigonometric substitution, partial fractions, improper integrals, numerical integration, arc length, surface area, physical applications, moments, or centers of mass.

A correct numerical antiderivative is not sufficient when the target is geometric setup. The student must identify the relevant region, slicing direction, bounds, dimensions, and method.

---

## 2. Valid-problem counts and performance-sensitive stopping rule

Use:

- **minimum:** 6 valid completed problems;
- **target:** 7 valid completed problems;
- **maximum:** 8 valid completed problems.

Additional rules:

- `P01` is the fixed cumulative substitution-reinforcement slot.
- `P02`–`P06` are required Week 2 core slots.
- `P07` is the ordinary adaptive transfer slot and should be administered unless the evidence after six valid problems is already strong, complete, and internally consistent under the stopping conditions below.
- `P08` may be used only for missing required coverage, an unresolved essential misconception, or a mathematically different near-transfer reassessment.
- At least 5 valid problems must have Week 2 content as their primary purpose.
- A linked or multipart task counts as **one** valid problem and receives **one** evidence score. Do not count its parts separately.
- One problem may support more than one authorized objective, but assign one primary objective and list any secondary objectives in the ledger.
- A single problem number cannot constitute two distinct performances for the master protocol's `SECURE` criterion.
- Worked examples, tutor demonstrations, command outputs, void problems, and incomplete problems do not count as valid completed problems.
- `P05` and every later valid problem are cumulative and must begin without a leading hint. Thus the final two valid problems are cumulative whether the session ends after 6, 7, or 8 valid problems.
- The labels `P01`–`P08` denote intended **valid slots**. If a presented problem is voided, its replacement fills the same uncompleted slot role but receives the next transcript problem number required by the master protocol.

### Conditions for stopping after 6 valid problems

Stopping at the minimum is permitted only when all of the following hold:

1. every item in the required coverage audit has usable evidence;
2. each of `W2.1`, `W2.2`, and `W2.3` has at least one successful score of `2` or `3` and no unresolved essential setup misconception;
3. the cumulative substitution evidence is sufficient for a defensible classification;
4. the final-two cumulative rule has been satisfied;
5. no correction, ambiguity, or verification issue remains unresolved;
6. the master protocol's stopping conditions are satisfied.

Otherwise administer `P07`.

After `P07`, stop if all required coverage and classification conditions are met. Use `P08` only when one additional problem can reasonably repair missing coverage, reassess one unresolved essential misconception, or provide a needed independent verification. Never exceed 8 valid problems.

The compressed format does not justify inflated mastery classifications. It is acceptable for an objective to receive `DEVELOPING` when the session provides only one usable performance or when correct work depended on prompting.

---

## 3. Initial and final confidence ratings

Ask the student to rate all four objectives at the beginning and again at the end using the master protocol's scale:

- `0` — no working knowledge;
- `1` — weak;
- `2` — moderate;
- `3` — strong.

Authorized objective codes:

- `C1.5` — Cumulative integration by substitution;
- `W2.1` — Areas between curves and choice of variable;
- `W2.2` — Volumes by slicing, disks, and washers;
- `W2.3` — Cylindrical shells and volume-method selection.

Apply the master protocol's confidence-sensitive initialization separately to each objective. The mathematical role of each fixed core slot takes precedence over confidence. In particular, `P01` remains a moderate substitution task; low confidence changes its presentation granularity, not its scope. Once usable performance evidence exists, observed performance controls later difficulty and presentation.

---

# Part I. Authorized objectives

## `C1.5 — Cumulative integration by substitution`

Assess whether the student can:

- recognize substitution as reversal of the chain rule;
- select an effective inner expression and compute its differential;
- make a constant adjustment when needed;
- rewrite the entire integrand using only the new variable and differential;
- when required, solve for the original variable in terms of the substitution variable and replace a remaining factor;
- transform bounds in a definite integral and complete the computation entirely in the new variable;
- return to the original variable and include `+C` in an indefinite integral;
- verify an antiderivative by differentiation or check a definite integral by sign and rough magnitude.

The intended reinforcement is slightly beyond direct visual matching but remains wholly within §1.5. Do not require two successive substitutions, integration by parts, a trigonometric identity that functions as a new integration technique, inverse-trigonometric antiderivatives, or any Chapter 3 technique.

## `W2.1 — Areas between curves and choice of variable`

Assess whether the student can:

- identify or sketch the bounded region from equations and stated boundaries;
- determine relevant intersection points and use them as bounds;
- choose vertical or horizontal representative slices;
- use
  
  \[
  A=\int_a^b \bigl(\text{top}-\text{bottom}\bigr)\,dx
  \]
  
  or
  
  \[
  A=\int_c^d \bigl(\text{right}-\text{left}\bigr)\,dy;
  \]
- split a compound region exactly where the controlling boundary changes;
- compare a one-integral setup in one variable with a multi-integral setup in the other variable when both are available;
- distinguish geometric area from a signed integral;
- check nonnegativity, rough magnitude, and square units.

When a graph is not supplied, require a usable hand sketch or an equivalent verbal description of the region. Do not require graphing technology.

## `W2.2 — Volumes by slicing, disks, and washers`

Assess whether the student can:

- express volume as
  
  \[
  V=\int A(s)\,ds
  \]
  
  after choosing an appropriate slicing variable;
- identify the cross-sectional shape and derive its area from the base region;
- distinguish the area of one cross-section from the volume of the whole solid;
- use similar triangles or a supplied geometric relation when needed to obtain a cross-sectional dimension;
- recognize when rotation produces disks rather than washers;
- use
  
  \[
  A=\pi R^2
  \qquad\text{or}\qquad
  A=\pi\bigl(R^2-r^2\bigr);
  \]
- measure every radius as a nonnegative distance from the axis of revolution to the relevant boundary;
- handle a simple axis parallel to a coordinate axis, including a shifted axis when the distance expressions remain elementary;
- choose correct bounds and evaluate the resulting integral exactly;
- check nonnegativity, rough magnitude, and cubic units.

For a less familiar cross-sectional shape, state the necessary elementary area formula rather than testing unrelated geometry recall.

## `W2.3 — Cylindrical shells and volume-method selection`

Assess whether the student can:

- choose representative strips parallel to the axis of revolution for the shell method;
- identify shell radius as a distance to the axis of revolution;
- identify shell height as top minus bottom or right minus left, as appropriate;
- use
  
  \[
  V=\int 2\pi(\text{radius})(\text{height})\,d(\text{variable});
  \]
- determine the correct variable and bounds;
- use shells about a coordinate axis or a simple parallel shifted axis;
- compare shell, disk, and washer setups by slicing direction, number of integrals, need to solve for another variable, and integration difficulty;
- justify a method choice rather than merely naming a formula;
- check nonnegativity, rough magnitude, and cubic units.

Do not accept a shell setup unless both radius and height are explicitly identified. Do not accept a disk or washer setup whose radii are signed coordinate values rather than distances.

---

# Part II. Required assessment architecture

The descriptions below specify problem **roles**, not fixed exercises. Generate original problems and privately verify every problem before presenting it.

## `P01 — Fixed cumulative substitution reinforcement`

Primary objective: `C1.5`.

Use one moderate problem requiring a complete one-variable substitution that is slightly beyond direct pattern matching. The problem must require both:

1. rewriting a remaining factor entirely in terms of the substitution variable; and
2. either transformed bounds for a definite integral or a nontrivial constant adjustment.

A suitable structural model is a shifted expression for which setting `u` equal to the inner quantity also requires solving for `x` in terms of `u`; do not reproduce a textbook example. Keep the resulting integral elementary.

Begin with method selection and no leading hint. Require the student to state the substitution, rewrite the full integral with no mixture of variables, evaluate exactly, and perform a derivative, sign, or magnitude check as appropriate.

Do not turn `P01` into a broad Week 1 diagnostic. After the record line, proceed to Week 2 geometry.

## `P02 — Area with vertical slices`

Primary objective: `W2.1`.

Use one bounded region described by two elementary curves. The problem must require the student to:

1. determine or verify the intersection bounds;
2. identify the upper and lower functions on the interval;
3. set up the area using vertical slices;
4. evaluate the integral exactly;
5. check that the answer is nonnegative and has square units.

Include one brief conceptual question distinguishing geometric area from the signed integral of an unsplit difference. Use curves whose intersections and antiderivatives remain elementary.

## `P03 — Horizontal slices or a compound area region`

Primary objective: `W2.1`.

Use a representation mathematically different from `P02`. Require a right-minus-left setup with respect to `y`. Choose the region so that horizontal slices give a natural one-integral setup while vertical slices require a split, or so that the student must explicitly analyze a boundary change before selecting the horizontal setup.

Require a hand sketch or equivalent boundary description, the `y`-bounds, the controlling right and left functions, exact evaluation of the horizontal-slice integral, and an explanation of where the vertical-slice alternative would split or why it is less efficient.

This problem should test method selection, not only antiderivative computation.

## `P04 — Volume from known cross-sections`

Primary objective: `W2.2`.

Use a solid whose base is a planar region and whose cross-sections perpendicular to a stated axis are familiar shapes such as squares, semicircles, equilateral triangles, or rectangles with a supplied aspect ratio.

Require the student to:

1. identify the slicing variable and interval;
2. determine the relevant base width;
3. convert that width into the cross-sectional area `A(s)`;
4. set up `V=\int A(s)\,ds`;
5. evaluate exactly and state cubic units.

The geometry must be recoverable from a two-dimensional sketch. Avoid lengthy similarity calculations or algebra that obscures the slicing concept.

## `P05 — Linked disk-and-washer comparison`

Primary objective: `W2.2`.

This is a cumulative problem and must begin with method selection and no leading hint.

Use one bounded planar region with two closely related rotations, or one rotation analyzed in two clearly distinguished stages, so that the student must produce one disk setup and one washer setup. A preferred structure rotates the same simple region about one boundary line and then about a parallel shifted line. Keep the antiderivatives short enough that the focus remains on radii and cross-sectional geometry.

Require the student to:

1. identify the strip orientation and variable for each rotation;
2. state why one rotation produces disks and the other washers;
3. express every radius as a nonnegative distance from the corresponding axis of revolution;
4. write both full volume integrals with correct bounds;
5. evaluate at least one of the two volumes exactly and, when the computations remain short, evaluate both;
6. check nonnegativity, relative magnitude, and cubic units.

At least one rotation must use a shifted axis so that radius-as-distance is actually assessed. The two rotations remain one linked problem and receive one evidence score.

## `P06 — Cylindrical shells and comparison of volume methods`

Primary objective: `W2.3`.

This is a cumulative problem and must begin with method selection and no leading hint.

Use a region and axis of revolution for which cylindrical shells give a natural one-integral setup and a disk/washer approach is possible but less convenient, or conversely requires solving for another variable or splitting the region.

Require the student to:

1. compare the plausible methods and justify the selected one;
2. identify shell radius, shell height, variable, and bounds;
3. set up and evaluate the shell integral exactly;
4. check nonnegativity, rough magnitude, and cubic units.

Include a compact `find the first error and repair it` component involving one plausible defect in a shell setup, such as using the wrong distance for the radius, using a vertical height where right-minus-left is required, choosing strips perpendicular to the axis, or omitting a required split. The erroneous setup must remain within the assigned scope.

## `P07 — Target adaptive cumulative transfer`

Administer this problem unless the assessment legitimately stops after six valid problems.

Choose the weakest or least-supported objective among `W2.1`, `W2.2`, and `W2.3`, giving priority to an objective that has only one usable performance or an unresolved setup error. The problem must:

- combine at least two authorized objectives;
- use a representation different from earlier supporting problems;
- begin with method selection and no leading hint;
- require an actual setup and exact computation, not only vocabulary;
- include a sign, bounds, radius, dimension, units, or magnitude check;
- remain entirely within §§1.5 and 2.1–2.3.

Preferred structures include:

- find an area first and use it as part of a cross-sectional or volume setup;
- compare shells with washers for a shifted axis;
- repair an incorrect area or volume setup and then complete the corrected computation;
- use substitution naturally inside a Week 2 area or volume integral;
- choose between `dx` and `dy` to avoid an unnecessary split.

Do not make `P07` cumulative-substitution-primary unless a substitution weakness is actively preventing successful Week 2 computation.

## `P08 — Optional cumulative reassessment or extension`

Use only when authorized by the maximum rule. It must:

- target missing coverage or one unresolved essential misconception;
- be mathematically different from the earlier problem on that skill;
- combine at least two authorized objectives when feasible;
- begin without a leading hint;
- remain within the assigned scope;
- function as a near-transfer reassessment after any focused explanation, not as a repetition with changed numbers.

Do not use `P08` merely to raise a mastery label or extend a session whose evidence is already complete.

---

# Part III. Required coverage audit

By the end of the mathematical phase, the ledger must contain identifiable evidence for every item below:

1. one slightly advanced §1.5 substitution requiring a complete rewrite in the new variable;
2. transformed bounds or a nontrivial constant adjustment in that substitution problem;
3. area with vertical slices using top minus bottom;
4. area with horizontal slices using right minus left;
5. intersection points used to determine bounds;
6. a compound region or an explicit decision about where a split is or is not required;
7. a volume setup from known noncircular cross-sections using `V=\int A(s)\,ds`;
8. one disk setup and one washer setup, with every radius measured as a distance from the axis of revolution;
9. a cylindrical-shell setup with explicit radius and height;
10. a justified comparison between at least two plausible volume methods;
11. at least one shifted axis in `P05` or `P06`;
12. at least one `find the first error and repair it` task;
13. at least two conceptual or method-selection tasks;
14. exact evaluation of representative area and volume integrals;
15. square or cubic units, together with at least one nonnegativity or rough-magnitude check;
16. two final cumulative problems that begin without leading hints.

Cite supporting problem numbers in the final report. If any required item is missing, mark the session procedurally incomplete even if six valid problems were completed.

The coverage audit must not claim evidence for inverse-trigonometric antiderivatives or any section after §2.3.

---

# Part IV. Topic-specific microstep protocols

Use the master prompt's one-question-at-a-time rule. Treat the lists below as inventories of essential decisions, not mandatory scripts that force every routine step into a separate turn.

## Substitution reinforcement

Ask in this order when applicable:

1. What expression should be chosen for `u`, and why?
2. What is `du`, and is a constant adjustment needed?
3. How is every remaining occurrence of the original variable rewritten in terms of `u`?
4. What are the transformed bounds, if the integral is definite?
5. What is the integral written entirely in `u` and `du`?
6. Evaluate exactly.
7. Return to the original variable and include `+C` if the integral is indefinite.
8. Verify by differentiation, sign, or rough magnitude.

A prompt that identifies the inner expression, supplies the required rewrite, or gives transformed bounds is a hint or supplied substep under the master rubric.

## Area between curves

Ask in this order when applicable:

1. What region is bounded, and where do the relevant curves intersect?
2. Should representative slices be vertical or horizontal?
3. What is the slice length: top minus bottom or right minus left?
4. Does the controlling boundary change, and where must the integral be split?
5. What are the bounds and the complete area integral?
6. Evaluate exactly.
7. Why is the result nonnegative, and what are its units?

Do not supply the order of the functions before the student has had an opportunity to determine it.

## General slicing and known cross-sections

Ask in this order when applicable:

1. Perpendicular to which axis are the cross-sections taken?
2. What is the slicing variable and interval?
3. What segment in the base gives the cross-sectional dimension?
4. What is the cross-sectional shape and its area formula?
5. What is `A(s)` in terms of the slicing variable?
6. What is the volume integral?
7. Evaluate exactly and state cubic units.

## Disks and washers

Ask in this order when applicable:

1. What is the axis of revolution?
2. Which strip orientation is perpendicular to that axis?
3. Are the cross-sections disks or washers?
4. What are the outer and inner radii as distances from the axis?
5. What is the cross-sectional area?
6. What are the variable and bounds?
7. What is the complete integral and exact volume?
8. What sign, magnitude, or units check supports the result?

## Cylindrical shells

Ask in this order when applicable:

1. Which strip orientation is parallel to the axis of revolution?
2. What is the shell radius as a distance from the axis?
3. What is the shell height?
4. What are the variable and bounds?
5. Is a split required?
6. What is the complete shell integral?
7. Evaluate exactly and state cubic units.
8. How does this setup compare with a disk or washer alternative?

## Method selection and error analysis

Ask in this order when applicable:

1. Which authorized method or slicing direction is appropriate?
2. What geometric features determine that choice?
3. Would another method require solving for a different variable, multiple integrals, or harder algebra?
4. In a proposed setup, what is the first mathematical error?
5. What is the smallest valid repair?
6. Complete and independently check the corrected setup.

---

# Part V. Adaptation rules for the compressed assessment

- Preserve the fixed roles of `P01`–`P06`; adapt difficulty, presentation, curve complexity, and algebra within those roles.
- Use performance, not confidence alone, to decide whether `P07` or `P08` is needed.
- After strong independent setup and execution, increase difficulty through a shifted axis, a choice between `dx` and `dy`, one necessary split, a method comparison, or a natural substitution inside the final integral.
- Do not increase difficulty by introducing a technique beyond §§1.5 and 2.1–2.3, by using hard intersection equations, or by requiring elaborate three-dimensional visualization.
- After weak performance, preserve the geometric target but simplify the curves, bounds, or arithmetic. Make presentation more granular without supplying the essential setup decision.
- Distinguish region-identification, slice-orientation, bounds, radius, height, cross-sectional-area, method-selection, substitution, algebra, arithmetic, sign, and units errors.
- When the region and method are correct but the antiderivative is not, record the successful setup evidence separately from the execution error.
- When the antiderivative is correct but the geometric setup is wrong, do not treat the final number as evidence of geometric understanding.
- A tutor-supplied sketch, intersection, slice orientation, radius, shell height, split point, or method is substantive assistance if it resolves an essential decision.
- After substantive help on an essential setup, use a mathematically different near-transfer problem in `P07` or `P08` when the remaining budget permits.
- Do not create a hidden sequence of tiny items and count them as separate problems. The count limit applies to complete mathematical tasks.

---

# Part VI. Mathematical boundaries and exclusions

Every generated problem must satisfy all of the following:

- Use exact arithmetic unless an approximation is explicitly part of a reasonableness check.
- Require no calculator, computer algebra, or graphing technology.
- Generate original problems; do not quote or closely reproduce OpenStax examples, exercises, online homework, solution manuals, or external problem banks.
- Keep intersections solvable by elementary algebra and keep antiderivatives within Chapter 1 formulas and substitution.
- Avoid non-elementary antiderivatives.
- Do not assess §1.7 inverse-trigonometric antiderivatives or inverse-trigonometric endpoint values.
- Do not introduce integration by parts, trigonometric integrals as a separate technique, trigonometric substitution, partial fractions, numerical integration, improper integrals, arc length, surface area, physical applications, moments, or centers of mass.
- Do not require a curve to be inverted unless the inverse relation is elementary and single-valued on the stated region.
- Do not use a compound region whose changing boundaries are unnecessarily numerous.
- For a less familiar cross-sectional shape, provide the elementary area formula.
- A simple shifted axis is permitted, but all distance expressions must be unambiguous and nonnegative on the interval.
- Require a two-dimensional region sketch or equivalent boundary description; do not make artistic three-dimensional drawing quality part of the evidence score.
- Verify privately that each region is bounded, each stated solid is well-defined, every radius and height has the correct sign, and every intended integral has a correct exact value.
- Accept algebraically equivalent correct setups and answers.
- Mark any ambiguous, defective, or out-of-scope problem `V — Void` and replace it without counting it.

---

# Part VII. Permitted and prohibited tools

During the active assessment, the student may use only:

- paper;
- pencil or pen;
- the single CSUF ChatGPT Edu conversation administering this assessment.

Unless the instructor separately announces an accommodation, the student may not use:

- a calculator;
- graphing software;
- a computer-algebra system or integral calculator;
- the textbook or class notes;
- an answer site or web search;
- another AI system;
- another person.

The student may make hand sketches. The tutor may describe a region in words or simple coordinate data, but should not replace an essential student-generated sketch before the student attempts the setup.

---

# Part VIII. Classifications

Use the master protocol's ordinary mastery labels for all four objectives:

- `SECURE`;
- `DEVELOPING`;
- `NOT YET DEMONSTRATED`;
- `INSUFFICIENT EVIDENCE`.

Apply the master protocol's independent-verification requirement before assigning `SECURE`. Multiple parts of one problem do not count as distinct performances.

Do not infer global mathematical ability or course readiness from this single assessment.

---

# Part IX. Student reflection

Before report generation, require the student to answer all three prompts in the student's own words.

1. Identify the Week 2 setup skill that is currently strongest and the one that most needs work. Cite at least one problem number for each. Also state what the substitution problem showed about your Chapter 1 integration fluency.

2. Describe one specific geometric or method-selection decision from the session. State:
   - what region, slice, radius, height, or method you first used or considered;
   - why it was correct, incorrect, or incomplete;
   - the corrected principle you would use on a new problem.

3. Give a concrete 20-minute study plan. Name:
   - the exact setup skill;
   - the number and type of regions or solids you will sketch;
   - whether you will practice setup only or complete evaluation;
   - how you will check bounds, order, radii, units, and method choice;
   - what would count as evidence of improvement.

Do not write these answers for the student.

---

# Part X. Integrity statement

Ask the student to type the following statement exactly, except for a modification required by a separately announced instructor accommodation:

> I certify that the mathematical responses recorded in this session are my own. During the active assessment I used only paper, a writing instrument, and the CSUF ChatGPT Edu conversation administering the assessment. I did not use another person, another AI system, a calculator, graphing software, a computer-algebra system, notes, the textbook, an answer key, or a web resource to generate my responses.

If the student declines, record `Integrity statement not provided`.

---

# Part XI. Week 2 report additions

In addition to the fixed report template in master protocol `M150B-SA-1.3`, include the following.

## A. Cumulative Substitution Reinforcement

For `C1.5`, report:

- supporting problem number and relevant microsteps;
- the student's substitution choice and first-attempt rewrite evidence;
- whether the integral was written entirely in the new variable;
- handling of constant factors and transformed bounds;
- verification method;
- initial and final confidence;
- mastery classification;
- one concise recommended review action.

Keep this subsection separate from Week 2 geometry evidence.

## B. Week 2 Objective Evidence

For each of `W2.1`, `W2.2`, and `W2.3`, report:

- supporting problem numbers;
- independent successes;
- support dependence;
- region or solid interpretation;
- bounds and slicing-direction evidence;
- method selection;
- setup accuracy;
- integration and algebraic accuracy;
- sign, magnitude, and units checks;
- initial and final confidence;
- mastery classification;
- principal misconception or remaining risk;
- recommended next action.

Do not treat multiple parts of one problem as multiple distinct performances for `SECURE`.

## C. Method-Selection Audit

Include a compact table with one row for every area or volume method that occurred:

- vertical area slices;
- horizontal area slices;
- general slicing with known cross-sections;
- disks;
- washers;
- cylindrical shells.

Use columns:

- method;
- supporting problem number;
- chosen independently or prompted;
- key geometric quantity identified;
- setup correct or repaired;
- remaining risk.

Do not list a method as demonstrated merely because the tutor named it.

## D. Week 2 Coverage Audit

List every item in Part III with supporting problem numbers and state explicitly whether the session was procedurally complete.

Also state:

- `§1.7 inverse-trigonometric antiderivatives: intentionally deferred — not assessed`;
- `§§2.4–2.6: not assigned for Week 2 — not assessed`.

Do not mark these deferred topics as missing coverage.

## E. Week 2 Error Classification

Classify each substantial error using the most specific applicable label:

- substitution choice;
- incomplete substitution or mixed variables;
- constant-factor error;
- transformed-bounds error;
- region identification;
- intersection or bound error;
- vertical-versus-horizontal slice error;
- top-minus-bottom order;
- right-minus-left order;
- unnecessary or omitted split;
- cross-sectional shape or dimension;
- cross-sectional area formula;
- disk-versus-washer selection;
- outer-radius or inner-radius error;
- axis-distance error;
- shell-radius error;
- shell-height error;
- volume-method selection;
- definite-integration or algebra error;
- sign or nonnegativity error;
- units error;
- incomplete justification.

Do not use `careless` as the principal classification unless the transcript independently shows that the relevant principle was understood.

---

# Part XII. Output filename

Use:

`Lastname_MATH150B_Week02_SelfAssessment.pdf`

If direct PDF creation is unavailable, produce one print-ready report for **Print → Save as PDF**, as required by the master protocol.
