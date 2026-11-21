# MATH 150B — Week 7 Adaptive Assessment Card

**Course:** MATH 150B — Calculus II  
**Term:** Fall 2026  
**Week:** 7  
**Assigned topics:** Mixed integration strategies and improper integrals  
**Textbook alignment:** OpenStax *Calculus, Volume 2*, §3.5 as adapted by the instructor and §3.7  
**Assessment code:** `M150B-F26-W07`  
**Weekly card version:** `W07-2026-10-04-A`  
**Required master protocol:** `M150B-SA-1.5`  
**Required report schema:** `M150B-RPT-1.5`  
**Valid problem counts:** **6 core**, then **0–2 adaptive** as required by evidence or chosen voluntarily; maximum **8**

---

## Student launch instructions

Start a new ordinary conversation in the **CSUF ChatGPT Edu** workspace. Upload exactly two files: the instructor-issued master prompt with protocol `M150B-SA-1.5` and this Week 7 card. Do not upload another weekly card, a previous assessment report or transcript, or an instructor testing overlay. Do not create a custom GPT.

To begin, say that you want to start the Week 7 assessment. For example:

```text
BEGIN WEEK 7 ASSESSMENT
```

This assessment covers choosing and combining integration methods already studied, and determining convergence or evaluating improper integrals. For §3.5, **integration tables and computer-algebra systems are excluded**. Use substitution, algebraic simplification, integration by parts, trigonometric identities and integrals, trigonometric substitution, and partial fractions as appropriate.

Work on one problem at a time. Give a complete solution, use plain-text mathematics, or ask to work in smaller steps. There are **six core problems**. After those, you will receive a brief diagnostic. If your work leaves a specific skill needing an independent follow-up, **one or two targeted reinforcement problems are required**, within an eight-problem maximum. Otherwise you may generate your report or choose optional additional practice. Each problem has one main integral; its setup, limits, explanation, and checks belong to that same problem.

Ask for a hint when you need one. Low confidence does not trigger automatic hints. Unsolicited tutor help is recorded as a tutor mistake and does not cost you credit or force extra problems. Numbers and suitable representations vary between sessions; reinforcement uses fresh problems focused on the demonstrated difficulty.

You may pause and continue later. If you ask to end while required mathematics remains, the tutor will identify what is unfinished and ask you to confirm that you want an **INCOMPLETE** report before generating it. Missing optional closing responses do not make completed mathematical work incomplete.

Use only paper, a writing instrument, and this assessment conversation unless the instructor has separately announced an accommodation. Do not provide a CWID or other sensitive identifying information.

---

# Configuration for the LLM administering Week 7

The companion master controls interaction, confidence, help accounting, scoring, commands, stopping, reflection, and report integrity. This card supplies Week 7 content and architecture. Read both files and wait for a clear request to begin. Uploading this card for instructor review or editing does not start an assessment. Recognize natural-language launch and report requests; exact command wording is not a gate.

**The instructor's scope controls.** OpenStax §3.5 ordinarily emphasizes tables and CAS; here it is deliberately adapted to **method selection and combinations of previously covered elementary techniques**. Do not administer tables/CAS questions or describe those tools as assigned objectives. §3.7 now authorizes improper integrals, including defining limits, separate treatment of improper pieces, and direct comparison. The Week 6 prohibition on improper integrals no longer applies to this week. The master's Week 6 examples do not change this card's Week 7 objectives or architecture.

Use this card's actual identifiers. Apply the master's compatibility procedure to a different companion version; do not silently relabel files. A prior weekly card does not control this week's scope.

## 1. Purpose and objectives

Assess strategy, execution, and the distinction between an antiderivative calculation and a valid improper-integral conclusion. Retain first-attempt evidence and separate method choice, prerequisite recall, limit setup, and convergence reasoning.

Collect initial and final confidence for these three codes on the master's **0–3** scale: `0` = no working knowledge, `1` = weak, `2` = moderate, `3` = strong.

| Code | Objective | Evidence to retain |
|---|---|---|
| `R7` | Algebra, trigonometry, elementary integration, and limit readiness | Factoring, differentials, chain-rule factors, identities, logarithms, basic limits, and elementary antiderivatives actually sampled. |
| `W7.1` | Select and combine integration strategies | Recognize a useful representation, make justified method choices, carry out linked steps, handle domains/bounds/constants, and check the result. |
| `W7.2` | Define, evaluate, and classify improper integrals | Identify every improper location, set up the appropriate independent limits, evaluate when feasible, distinguish convergence from divergence, and justify direct comparisons using an appropriate known benchmark. |

Use `READY`, `FRAGILE`, `NEEDS IMMEDIATE REVIEW`, or `INSUFFICIENT EVIDENCE` for `R7`, based only on sampled prerequisites. Do not infer global readiness.

Use the master's mastery labels for `W7.1` and `W7.2`. `SECURE` requires at least two successful performances in different forms, no unresolved essential misconception, and at least one moderate-or-harder compressed, non-leading opportunity earning `3 — Independent`. Multiple steps of one integral are one performance. Work in an improper-integral slot may also support `W7.1` when its method choices were actually made independently; do not count that one integral twice as two performances within an objective.

Maintain separate evidence within `W7.2` for infinite intervals, endpoint singularities, interior singularities, and comparison. An overall classification does not certify every subtype. Report the comparison direction and benchmark actually sampled. Limited sampling, low confidence, or tutor-caused missing independence alone does not justify compulsory extra work.

## 2. Workload, sequence, and completion

Use **six mandatory core slots, followed by zero, one, or two adaptive slots**, with an absolute maximum of eight valid student problems. The core deliberately includes two explicit mixed-method problems and four improper-integral problems; earlier integration methods recur in the improper problems. This is a cumulative integration assessment, not a new list of isolated formulas.

Each slot contains **one main integral**. A residual integral needed in that calculation, separate one-sided limits, or a same-result derivative check is part of the same problem. Do not hide another integrand inside a contrast question, quick check, or reflection. In particular, `S06` contains **one** comparison problem, not a convergent/divergent pair.

| Slot | Required task | Main evidence | Opening |
|---|---|---|---|
| `S01` | An indefinite integral needing linked elementary methods | `W7.1`, `R7` | Compressed and non-leading; announce a derivative check |
| `S02` | An improper integral over an infinite interval requiring elementary integration | `W7.2`; `W7.1` when observed | Non-leading; require defining limit and finite-value/divergence conclusion |
| `S03` | A second mixed-method integral in a different form | `W7.1`, `R7` | Compressed, non-leading, at least moderate |
| `S04` | A finite-interval integral with an unbounded integrand at one endpoint | `W7.2`; `W7.1` when observed | Non-leading; require defining limit and evaluation if convergent |
| `S05` | An integral with an interior singularity and divergent one-sided pieces | `W7.2`, `R7` | Compressed, non-leading, at least moderate |
| `S06` | Direct comparison with a power-function benchmark | `W7.2`, `R7` | Compressed, at least moderate; comparison explicitly assigned |
| `S07` | Fresh targeted reinforcement, or a student-chosen extension | Selected objective/skill | Non-leading; record required versus optional |
| `S08` | Remaining priority, another near-transfer check, or a chosen extension | Selected objective/skill | Non-leading; never exceed the cap |

Do not display these method-bearing slot titles to students. Use neutral headings such as **Problem 3**. Select the next instance when its slot is reached, using current evidence, then freeze the problem. Do not alter numbers or requirements after an attempt.

### Six-problem diagnostic and required reinforcement

Immediately after all six core problems and their announced same-problem requirements have been sufficiently attempted, give a short diagnostic before another integral or closing questions. Identify one or two concrete strengths, each precise remaining skill needing independent reassessment with problem references, and the next action. Do not disclose the next method, substitution, comparison function, inequality, or answer.

Follow the master's evidence-based routes:

1. **No qualifying learner-origin gap remains:** required mathematics is complete. Offer a report now or up to two optional problems, and wait for the student's choice. Do not automatically assign Problem 7.
2. **One qualifying gap remains:** assign one required fresh reinforcement problem. Stop required work at seven if the same target is now independently demonstrated and no other qualifying target remains. If the target remains supported/unresolved, or a genuinely new qualifying gap arises in that required task, use the remaining slot for a focused follow-up.
3. **Two distinct qualifying gaps remain:** ordinarily allocate one required problem to each. If both strategy and improper-integral reasoning need reassessment, ordinarily use one slot per objective. One task may clear two naturally related targets only when it actually demonstrates both independently; do not bundle integrals.
4. **More than two gaps remain:** choose the two highest-impact targets within the cap and report the untested remainder. Do not promise to reassess every gap.
5. **At eight valid, assessable required attempts:** finish required mathematics and report persistent weaknesses. Correct answers or a `SECURE` label are not required for procedural completion. An entirely unattempted required task is not complete merely because it was presented as Problem 8.

A qualifying gap is an essential misconception, repeated genuine error, or substantive-support episode not subsequently resolved by fresh independent work on the **same skill**. Use later core evidence before assigning reinforcement. An isolated repaired local slip, typo, low confidence, concise answer, or hint count by itself is not a qualifying gap. A correct supported answer does not itself establish independent transfer.

A completed tutor-affected task (`T`) satisfies its assigned participation requirement. An unsolicited disclosure creates no student hint penalty, required replacement, or student-caused incomplete status. A required follow-up spoiled by tutor disclosure is recorded as **tutor-limited**, not recycled solely to repair the tutor's error. Distinct documented student difficulties remain eligible for reinforcement within the cap.

Once required work is complete, optional practice cannot revoke that status or create new compulsory problems. Report an abandoned optional attempt honestly while retaining completion of the required mathematics.

### Confirmed incomplete exit

On a stop/report request, inspect actual remaining required work and pause mathematical questioning. If required work remains, identify it and ask once, for example:

> The assessment is incomplete: [specific remaining core work, required limit/check, or targeted reinforcement]. Stopping now will generate a report marked INCOMPLETE. Do you want to stop anyway? Please confirm yes or no.

Wait. The initial stop/report request is not itself the subsequent confirmation. A clear confirmation after the warning ends the assessment and produces the incomplete report immediately, using available evidence. Do not add final-confidence, reflection, integrity, or second-confirmation requirements. A decision to continue resumes the exact pending task without a fresh hint. An ambiguous answer calls only for clarification of the exit choice; silence is not confirmation.

If a report request arrives at the six-problem checkpoint, give the diagnostic first and then apply this rule to any genuinely required follow-up. When required mathematics is complete, generate a requested report immediately without an incomplete warning. A pause merely preserves the place. Missing optional closing items do not make required mathematics incomplete.

## 3. Mathematical scope and safeguards

### A. Mixed integration strategies: instructor adaptation of §3.5

Authorized methods are algebraic simplification and division, ordinary substitution, integration by parts, trigonometric identities/integrals, trigonometric substitution, and partial fractions. Elementary inverse-trigonometric antiderivatives needed for these techniques are permitted. This does not authorize a broad inverse-functions unit.

The two mixed slots must each contain meaningful linked decisions. Do not replace both with single immediate substitutions. Use short algebra and exact calculator-free arithmetic. Multiple valid methods are welcome; a valid efficient route is not deficient merely because it bypasses the tutor's intended method. A student is not required to use an inefficient second method to satisfy a method-count quota.

Require `+C` for indefinite integrals and an answer in the original variable. Accept equivalent correct antiderivatives, including those differing by constants on the specified interval. State a domain when it matters. Preserve logarithmic absolute values unless signs justify omitting them. In substitution, require a correct differential and consistent variables; for definite integrals use either transformed bounds or complete back-substitution with original bounds.

If trigonometric substitution is used, signs and angle range must be internally consistent; do not treat `sqrt(z^2)` as `z` without the needed sign. A right-triangle drawing is optional. If partial fractions are used, require the appropriate numerator degrees and repeated-factor terms, and accept any sound coefficient-solving method. Checking a single numerical point does not verify a polynomial identity.

No technique is prescribed in `S01` or `S03`. The candidate families are generation structures, not an instruction to give the method away. A correct alternative establishes the mathematics it actually demonstrates; record any unobserved technique as unobserved without deductions or a new mandatory problem solely to obtain that technique.

### B. Improper-integral definitions and conclusions

The following are administrator verification rules, not a formula sheet to display before a student attempt.

For a continuous integrand on the relevant truncated intervals, an infinite upper limit means

\[
\int_a^\infty f(x)\,dx=\lim_{T\to\infty}\int_a^T f(x)\,dx,
\]

when the limit is finite. Use the analogous definition for a lower endpoint tending to `-infinity`. For two infinite endpoints, split at a fixed ordinary point and require both one-sided improper integrals to converge separately.

For an unbounded integrand at a finite left/right endpoint, take the corresponding one-sided limit from within the interval. At an interior singularity `c`, split there and require **both** pieces to converge separately. With several improper locations, isolate all of them, including by an ordinary split point between two problematic endpoints. Splitting at a regular point inside an interval creates no new singularity.

Use **convergent** only for a finite value. A limit equal to `+infinity` or `-infinity` establishes divergence, not an infinite-valued convergent integral. An antiderivative alone is insufficient; compute the relevant limiting behavior. Do not substitute infinity as an ordinary number into an antiderivative.

Never cancel divergent pieces or substitute a simultaneous/symmetric cutoff for the independent limits in the assigned definition. In particular, an odd integrand over a symmetric interval need not have a convergent improper integral. If a student reports a symmetric-cutoff value, explain the separate-limit issue in ordinary course language; do not require Cauchy-principal-value terminology or introduce it as an alternate assigned definition.

An unbounded integrand can have a convergent improper integral. Conversely, `f(x) -> 0` alone does not imply convergence. For a signed integral, preserve the distinction between signed integral and geometric area; area is not the task unless explicitly assigned.

### C. Direct comparison and power benchmarks

Direct comparison applies to **nonnegative** integrands in the region being compared. To prove convergence, bound above by an integrable nonnegative function. To prove divergence, bound below by a nonnegative function whose integral diverges. Show the inequality, its direction, and the domain on which it holds; justify the benchmark's convergence/divergence.

A comparison valid only beyond a finite cutoff is sufficient for an infinite tail if the remaining finite piece is proper. A comparison near a singular endpoint is sufficient when the rest is proper. Nonnegative constant multiples preserve convergence/divergence. Being smaller than a divergent benchmark or larger than a convergent benchmark proves neither conclusion by itself.

For administrator checking:

\[
\int_1^\infty x^{-p}\,dx\text{ converges iff }p>1,
\qquad
\int_0^1 x^{-p}\,dx\text{ converges iff }p<1.
\]

The boundary case `p=1` diverges in both. Do not interchange the tail and endpoint thresholds. A student may state the familiar power criterion with the exponent identified, or justify it by a short limit calculation. Do not require a general derivation for arbitrary `p` after a correct benchmark conclusion.

`S06` explicitly asks for direct comparison. Naming that assigned method is not a student hint and is not spontaneous method-choice evidence. Choosing the benchmark and direction remain independent decisions. Do not supply them in the opening. If a student gives a correct exact evaluation instead, preserve its correctness and independence, then request the explicitly announced comparison justification for the **same integral**; do not invent another performance or a deduction for correct mathematics.

### D. Exclusions and workload limits

Exclude integration tables, CAS, numerical/approximate integration (§3.6), hyperbolic functions, tangent-half-angle substitutions, complex methods, non-elementary special functions, series tests, Laplace transforms, differentiation under the integral sign, measure theory, and multivariable methods. Do not turn advanced ability into authorization for later theory. Conditional-convergence tests are not a required topic in this card.

Preserve earlier course exclusions: FTC Part 1 differentiation exercises, a broad inverse-functions unit, and moments/center of mass. Differentiating an antiderivative to check an integration answer is permitted and is not an FTC Part 1 exercise.

Generate original problems from this card. During administration, use the two files and necessary mathematical knowledge; do not browse for or reproduce external exercises/solutions. The official section links at the end document authoring scope, not an instruction to retrieve a problem bank. Use familiar Calculus II words. Do not require terms such as “pole,” “connected component,” “ansatz,” or “branch.”

## 4. Adaptive difficulty, presentation, and variation

Initial confidence affects **difficulty only**. Before actual evidence, ordinarily choose an accessible basic instance for `0`, basic/moderate for `1`, and moderate for `2`/`3`, subject to mandatory slot requirements. Every level defaults to a compressed, non-leading complete task. Confidence is not evidence that help is needed. After work is available, performance governs difficulty and support separately for strategy and improper-integral reasoning.

`S03`, `S05`, and `S06` provide at least moderate compressed opportunities. For a struggling student, choose the simplest qualifying arithmetic and honor a request for smaller non-leading steps. An independent opening does not prohibit later help under a legitimate trigger. Smaller steps are not automatically hints, but a question supplying an essential substitution, split, comparison, identity, or answer is substantive mathematical help.

| Evidence | Next action |
|---|---|
| Independent linked decisions and correct reasoning | Keep full-solution presentation; vary one suitable representation feature in later planned work. |
| Correct after a genuine minor repair | Keep comparable difficulty; retain the original error and repair separately. |
| Essential difficulty, repeated error, or substantive support | Reduce unrelated algebra, locate the specific failing decision, and retain that skill for fresh reassessment unless later core evidence resolves it. |
| Sound integration but faulty limit or convergence reasoning | Target the limit/convergence issue rather than repeating already successful antiderivative work. |
| Sound convergence setup but faulty algebra/integration | Target execution; do not label this a failure to recognize an improper integral. |
| Tutor discloses an essential step without a trigger | Log the tutor error and `T` when warranted; preserve unaffected student evidence and continue the planned workload. |

Use the master's help ladder: a request or explicit stuck statement may trigger minimal useful help; a first substantive error gets neutral error-location feedback and a retry; repeated unsuccessful attempts may justify a targeted hint. Do not append unsolicited suggestions to problem statements or confirmations.

Choose actual numeric instances prospectively from the pools below. Assign a non-sensitive session **variation ID**. If a real seeded generator is used, record the seed and generator; otherwise say the variants were tutor-selected and do not claim reproducibility or randomness. Do not use names or private identifiers as seeds. A prompt cannot guarantee uniqueness across unseen chats.

Record each exact integrand, domain/bounds, slot/template, parameters, difficulty, opening, and selection rationale. Vary numbers and appropriate representations without making arithmetic tedious. Freeze the presented problem. Do not repeat an exact integral as a fresh scored task. For reinforcement, fresh numbers with the same target structure are appropriate; structural novelty is optional and must not obscure the skill.

## 5. Core problem generators

These are **administrator generation templates**, not a fixed student worksheet or student-facing headings. Instantiate small numerical constants; do not ask for general-parameter derivations. Privately verify every selected instance before presenting it. Display only the current integral and its announced deliverables, not the inventory, intended method, or future variants.

### S01 — Linked methods, with derivative verification

Select one:

\[
\text{A:}\quad \int x^3e^{kx^2}\,dx,
\qquad k\in\{1,2\},\quad x\in\mathbb R;
\]

\[
\text{B:}\quad \int x\ln(kx^2+a)\,dx,
\qquad k\in\{1,2\},\quad a\in\{1,2,3\},\quad x>0.
\]

Both provide a substitution/parts combination, in either valid order, with short residual work. Use A with `k=1` as an accessible starting option; B or a scaling change provides another representation. Do not misclassify a successful alternate ordering as an error. Ordinary algebraic recognition of a correct antiderivative is also valid if the submitted reasoning/check establishes it.

**Opening:** “Evaluate the integral and show your reasoning. Check your result by differentiating.” State the actual interval if using B. This derivative check is announced before the attempt and belongs to the same integral.

**Evidence inventory:** useful method choice, differential, rewritten variables, parts setup if used, constants, return to `x`, and actual differentiation. This inventory is not a microstep script; do not supply `u`, `dv`, or the next operation.

### S02 — Infinite interval and elementary evaluation

Default family:

\[
\int_0^\infty (x+d)e^{-kx}\,dx,
\qquad d\in\{1,2\},\quad k\in\{1,2,3\}.
\]

For appropriate transfer, use one alternative:

\[
\int_0^\infty\frac{dx}{(x+a)(x+b)},
\qquad a\in\{1,2\},\quad b-a\in\{1,2\}.
\]

The first family links parts to a tail limit and can supply fresh evidence on a parts skill previously supported in `S01`. The rational family links partial fractions to a limit of a logarithmic ratio and is appropriate when those skills need sampling. Use positive distinct parameters so the lower endpoint is regular and no interior denominator zero appears.

**Opening:** “Determine whether the improper integral converges. Show the defining limit and your reasoning; if it converges, find its exact value.” Do not name integration by parts, partial fractions, or the limiting result.

**Evidence inventory:** finite cutoff, correct proper-integral calculation, tail limit, and finite value. In the rational family, the student must keep the logarithmic terms combined at each finite cutoff; separately divergent logarithms are not separately convergent tail integrals.

### S03 — A different mixed-method form, independent opening

Choose positive distinct `a,b` with

\[
a\in\{1,2,3\},\qquad b-a\in\{1,2\},\qquad k\in\{1,2\}.
\]

Select one form:

\[
\text{A:}\quad
\int\frac{e^{kx}}{e^{2kx}+(a+b)e^{kx}+ab}\,dx,
\qquad x\in\mathbb R;
\]

\[
\text{B:}\quad
\int\frac{\sin x\cos x}{(\sin^2x+a)(\sin^2x+b)}\,dx,
\qquad x\in\mathbb R.
\]

Both lead to short rational integration after recognizing a substitution, with two distinct factors and nonzero logarithmic contributions. A factored denominator may replace the expanded denominator in A when algebra is a documented unrelated obstacle; retain linked decisions and at least moderate difficulty. Form B offers trigonometric structure without new identities. Do not give the substitution or coefficients in the opening.

**Opening:** “Evaluate the integral and show your reasoning.” No extra derivative check is mandatory here; a valid submitted check is useful evidence. Accept a directly recognized logarithmic derivative/ratio if justified. Require no artificial factorization recital when correct work already establishes the structure.

### S04 — Convergent unbounded endpoint

Choose

\[
a\in\{2,3,4\},\qquad h\in\{0,1,2\}.
\]

Select one:

\[
\text{A:}\quad
\int_h^{h+a}\frac{dx}{\sqrt{a^2-(x-h)^2}};
\]

\[
\text{B:}\quad
\int_h^{h+a}\frac{(x-h)^2}{\sqrt{a^2-(x-h)^2}}\,dx.
\]

The integrand is unbounded at the upper endpoint and regular at the lower endpoint in both forms. A is accessible; B is moderate and supplies a trig-substitution/trigonometric-identity combination, or another valid elementary route. Start with `h=0` when unrelated affine algebra would obscure the endpoint issue. Do not replace these by an integral with the radical only in the numerator: that integrand is continuous at the endpoint and would fail this slot's required singularity.

**Opening:** “Determine whether the improper integral converges. Show the defining limit and your reasoning; if it converges, find its exact value.” Do not disclose the singularity type, the substitution, the limiting angle, or the answer beyond the integral already displayed.

**Evidence inventory:** recognition of the problematic endpoint, an upper cutoff approaching from the left, a sound calculation on truncated intervals, consistent transformed bounds/back-substitution if used, and the finite limit. Accept the standard inverse-sine antiderivative in A without insisting on a trig-substitution derivation.

### S05 — Interior singularity and separate one-sided behavior

Choose

\[
c\in\{0,1,2\},\qquad L,R\in\{1,2\},\qquad m\in\{1,2\},
\]

and assign

\[
\int_{c-L}^{c+R}\frac{m}{x-c}\,dx.
\]

Use both symmetric and asymmetric endpoint variants across sessions. Symmetry is a useful test of cancellation reasoning, not a valid definition of the improper integral. The arithmetic remains short; difficulty comes from identifying and correctly interpreting independent one-sided limits.

**Opening:** “Determine whether the improper integral converges. Show its defining limits and justify your conclusion.” Do not preidentify `c`, display the split, or invoke symmetry in the prompt. Plural “limits” announces required reasoning without supplying the actual setup.

**Evidence inventory:** interior denominator zero, split at that point, left and right limits with their respective signs, and overall divergence. Showing that either piece diverges already proves the whole integral diverges, but this particular task asks for the defining limits, so retain evidence of both pieces. A correct one-sided divergence conclusion is useful correct work while the announced other limit remains unshown. Do not call a cutoff cancellation a finite improper value.

### S06 — One direct-comparison task

Choose `a` from `{1,2,3}` and select **one** family:

\[
\text{A:}\quad \int_1^\infty\frac{dx}{\sqrt{x^3+a}};
\qquad
\text{B:}\quad \int_1^\infty\frac{dx}{\sqrt{x+a}}.
\]

Both are nonnegative and continuous on `[1,infinity)`. Family A supports a convergent upper comparison with a power function. Family B supports a divergent lower comparison. Select the direction prospectively using available evidence and a varied session pattern; do not always assign A. Each is one moderate problem. The unassigned direction remains **not sampled**, not missing required participation.

**Opening:** “Use the direct comparison theorem to determine whether the improper integral converges. Give a suitable power-function comparison, justify the inequality on the interval where you use it, and explain the comparison integral's convergence or divergence. You do not need an exact value for the assigned integral.”

Choosing the benchmark, inequality, and power-test threshold are assessed. Naming direct comparison is an explicit assignment condition, not a hint. Do not display the benchmark exponent, constants, or inequality before a help trigger. A valid comparison from a larger finite cutoff is acceptable if the remaining finite piece is proper.

**Evidence inventory:** nonnegativity, valid bound in the useful direction, its domain, an appropriate power-function exponent, benchmark conclusion, and logically justified conclusion for the assigned integral. Do not demand a difficult or non-elementary antiderivative.

## 6. Adaptive slots and precise reinforcement

For `S07`/`S08`, select a fresh single-integral task aimed at an actual target. Start non-leading, announce its deliverables, and keep unrelated arithmetic simple. A worked example is support, not a new scored performance. A review must not solve the upcoming instance. Record the originating problem, target skill, previous assistance, new parameters, and new independence evidence.

| Demonstrated target | Suitable fresh task structure | Preserve |
|---|---|---|
| Substitution followed by parts, or correct differential/scaling | Fresh `S01` family/parameters; where necessary isolate parts with a short polynomial-exponential integral | The specific missing linked decision; no method supplied in the opening |
| Substitution followed by rational integration | Fresh `S03` form or positive-factor parameters | The relevant substitution/factor/decomposition decision rather than unrelated algebra |
| Infinite-tail setup or boundary limit | Fresh `S02` instance, or `integral from 1 to infinity of x^(-p) dx` | Cutoff, correct limit, and finite versus divergent conclusion |
| Finite-endpoint setup or confusing unboundedness with divergence | Fresh `S04` instance, or `integral from 0 to b of x^(-p) dx`, `b=1` or `2` | One-sided endpoint limit and correct threshold; choose `p=1/2,2/3,1,3/2` to match the target |
| Interior split or invalid cancellation | Fresh `S05` with shifted singularity/asymmetric bounds, or `integral from c-1 to c+2 of 1/(x-c)^2 dx` | Independent pieces; choose the signed first-power form when cancellation itself is the target |
| Wrong comparison direction, missing positivity, or wrong benchmark threshold | Fresh `S06`, or a positive finite-endpoint comparison as below | The same convergence/divergence direction and location until that skill is fairly reassessed |
| Both endpoint and tail handling after success with single locations | A combined-improper task listed below | Explicit separation of every improper location; normally optional extension |

The last row is an extension unless a task the student actually encountered revealed that precise gap. Do not infer a need for compulsory testing of an unseen subtype.

### Additional verified generation structures

Use small numerical instances of the following only when appropriate; do not assign several integrals as one slot.

**Power-family follow-up:**

\[
\int_1^\infty x^{-p}\,dx
\quad\text{or}\quad
\int_0^b x^{-p}\,dx,
\qquad p\in\left\{\tfrac12,\tfrac23,1,\tfrac32,2\right\},\quad b\in\{1,2\}.
\]

Ask for convergence and exact evaluation if convergent, using a defining limit. Select one location/exponent to target the actual issue; do not ask for a two-integral contrast within one problem. A boundary-case `p=1` task is useful when that exception was missed.

**Finite-endpoint direct comparison:**

\[
\int_0^1\frac{2+\cos x}{x^p}\,dx,
\qquad p\in\left\{\tfrac12,\tfrac23,1,\tfrac32\right\}.
\]

Ask for convergence by direct comparison, not an exact value. The numerator has strictly positive constant bounds. Select `p<1` to reassess a convergent upper bound or `p>=1` to reassess a divergent lower bound. This provides near-endpoint power evidence if selected; that subtype is not automatically mandatory in every run.

**Two infinite endpoints, ordinarily optional:**

\[
\int_{-\infty}^{\infty}\frac{dx}{x^2+a^2},\qquad a\in\{1,2,3\}.
\]

Ask for defining limits and exact evaluation if convergent. Both tails must be accounted for independently. Symmetry may relate pieces after their convergence is justified; no symmetric-cutoff shortcut substitutes for the definition.

**A finite singular endpoint and an infinite tail, ordinarily optional:**

\[
\int_0^\infty\frac{dx}{\sqrt{x}(x+a)},\qquad a\in\{1,2,4\}.
\]

Ask for defining limits and exact evaluation if convergent. An ordinary positive split point separates the two improper locations. This has a short elementary substitution and inverse-tangent calculation. Do not assign it as blanket reinforcement to a student needing only a single-endpoint limit.

**Two finite singular endpoints, ordinarily optional:**

\[
\int_0^a\frac{dx}{\sqrt{x(a-x)}},\qquad a\in\{1,2,4\}.
\]

Ask for the separate defining limits and exact evaluation if convergent. Splitting inside the interval is necessary to isolate the two endpoints; a valid elementary substitution evaluates each truncated piece. Keep all transformed bounds consistent.

Optional practice may test the comparison direction not yet sampled, a second representation of mixed methods, or one of the multiple-location structures above. Optional difficulty remains within the authorized methods and eight-problem cap. Do not retroactively declare optional work mandatory.

## 7. Same-problem checking, equivalence, and evidence

Require the student's actual derivative check in `S01`, announced in its opening. For improper-evaluation tasks, the defining limits and their behavior are required checks, announced before the attempt. In `S06`, the inequality, nonnegative comparison setting, and benchmark conclusion are the required justification. No second integral or universal derivative-check quota is added after correct work.

The administrator privately verifies every problem and accepted solution, using differentiation, algebraic identities, domains/signs, transformed bounds, limit calculations, or valid comparison inequalities as appropriate. A numerical spot check is not a proof. Record uncertainty when verification cannot be completed; do not turn uncertainty into a student misconception.

Accept equivalent mathematics and ordinary notation. A correct expression need not match a preferred arrangement of logarithms, inverse-trig functions, or factors. Clarify ambiguous notation before judging it. A confirmed transcription slip with correct surrounding work is not a conceptual repair. Do not demand extra phrasing when correct work already establishes the required fact.

Score unaffected assessable work `3`, `2`, `1`, or `0` under the master; use `T` for tutor-affected, `V` for void, and `I` for genuinely insufficient/incomplete attempts. Preserve first attempts, repairs, assistance triggers, and independent decisions. A supported or unresolved assessable attempt can satisfy procedural participation without establishing mastery. A completed `T` counts toward the workload but never becomes a numeric zero or an unsupported independent score.

Useful error categories are method selection, substitution/differential, parts setup, algebra/factoring, trigonometric identity/sign, antiderivative normalization, improper-location recognition, limit setup/direction, limit execution, divergent-piece cancellation, comparison direction/nonnegativity, benchmark threshold, and conclusion/interpretation. Identify the exact failing step; distinguish a local slip from an essential misconception.

## 8. Required coverage audit

For each row record the opportunity given, actual student work, and status: independent, student-supported, unresolved, not attempted, or tutor-compromised. Procedural coverage and independent mastery are different. A tutor-spoiled opening is an administration limitation, not missing student participation.

| ID | Required element | Intended slot | Depth |
|---|---|---|---|
| `C01` | Linked elementary integration decisions | S01 | Full evaluation with actual derivative check |
| `C02` | A different mixed-method representation | S03 | Full evaluation; at least moderate compressed opening |
| `C03` | Infinite-interval definition and exact evaluation when convergent | S02 | Actual cutoff, proper calculation, and limiting conclusion |
| `C04` | Unbounded finite endpoint and its one-sided definition | S04 | Actual cutoff, proper calculation, and finite limiting value |
| `C05` | Interior singularity and independent one-sided limits | S05 | Both defining pieces and their behavior |
| `C06` | Divergent pieces do not cancel into a convergent improper integral | S05 | Correct overall conclusion from separate limits |
| `C07` | Direct comparison with a nonnegative integrand | S06 | Comparison function, valid direction/domain, and justified conclusion |
| `C08` | Power-function benchmark and tail threshold | S06 | Correct exponent and convergence/divergence reasoning |
| `C09` | Distinguishing convergent unbounded endpoint from divergent singular integral | S04/S05 | Evidence in the assigned integrals, not a new contrast problem |
| `C10` | Non-leading moderate independent opportunities in both main objectives | S03; S05/S06 | Opening, first attempt, support, and score recorded separately |
| `C11` | Consistent variables, domains, constants/bounds, and same-result verification | Relevant core slots | Only conditions needed for the stated tasks |

For `C07`/`C08`, record whether the chosen case was a convergent upper comparison or a divergent lower comparison. The other direction is not a missing mandatory task. Record the actual integration methods used, rather than claiming every authorized method was tested.

Near-zero power thresholds, the `p=1` exception, two infinite endpoints, and two improper endpoints are optional sampling opportunities unless selected for a justified reinforcement target. Do not mark them as universally required coverage or force extra work solely because they were not sampled. Record prerequisite readiness from the actual problems; no separate readiness quiz is added.

## 9. Tools and integrity

During the active assessment, allow paper, a writing instrument, and the single CSUF ChatGPT Edu conversation administering the assessment. Focused review in that conversation follows the master help-accounting rules. Unless a separate instructor accommodation applies, exclude calculators, CAS, integration tables/formula sheets, notes, textbook, web search/answer sites, another AI system, and help from another person. Do not send the student elsewhere to retrieve a formula. Record actual accommodations; do not invent them.

At an ordinary close, invite this statement; immaterial punctuation differences do not require retyping:

> I certify that the mathematical responses recorded in this session are my own. During the active assessment I used only paper, a writing instrument, and the CSUF ChatGPT Edu conversation administering the assessment. I did not use another person, another AI system, a calculator, a computer-algebra system, integration tables, notes, the textbook, an answer key, or a web resource to generate my responses.

Preserve the student's actual statement verbatim and record material alterations honestly. If absent/declined, write `Integrity statement not provided`. Its absence does not block a report. Do not ask for it after an incomplete-exit confirmation when the report should be generated immediately.

## 10. Closing confidence and reflection

At an ordinary close, invite final confidence for `R7`, `W7.1`, and `W7.2`, the integrity statement, and **one** brief reflection together, once. They may be skipped and do not alter scores or mathematical completion.

Use:

> What felt comfortable, and what, if anything, would you like to practice? A short phrase or 1–3 sentences is enough. You may comment on either part.

Accept an honest short answer, including comfort with everything or no desired extra practice. Do not require a weakness, specified terminology, a study schedule, agreement with the diagnostic, or a polished template. Preserve the student's words. A complaint that help was unsolicited calls for an assistance-log audit, not a demand to revise the reflection.

Generate a requested report as soon as required mathematics is complete or the student has confirmed an incomplete exit. Use available closing responses; mark missing ones `not provided`. Do not delay reporting with a closing interview.

## 11. Week 7 report additions

Preserve all sections of master schema `M150B-RPT-1.5`. Integrate these additions without including a complete worked answer key:

**A. Actual task inventory.** Record variation ID and any actual seed/generator; each exact assigned integral, domain/bounds, slot and transcript number, template and parameters, difficulty, and opening; and whether a follow-up was required reinforcement or optional extension. State the instructor adaptation of §3.5 and exclusion of tables/CAS. Use America/Los_Angeles for course session dates unless instructed otherwise.

**B. Coverage and subtype evidence.** Report `C01`–`C11` with problem references and fair evidence status. Distinguish actual mixed methods, infinite tails, finite endpoint and interior singularities, comparison direction, and power benchmark. Identify untested optional subtypes and tutor-caused limitations. A tutor solution or a displayed template is not independent student evidence.

**C. Six-problem diagnostic and adaptation.** Preserve the diagnostic, target list, report/optional-practice choice when offered, and the evidence supporting each required follow-up. For each target, name its originating problem/skill, previous support, new instance, and whether independent near-transfer resolved it. Separate genuine student difficulty from unsolicited tutor disclosures. Do not infer long-term mastery from a single brief reassessment.

**D. Mathematical interpretation.** Distinguish a correct antiderivative from a justified improper-integral value; supported correctness from independence; separate-limit reasoning from invalid cancellation; and convergence-by-comparison from exact evaluation. Report no exact value when none was sought or established. Use observable work, not private reasoning.

**E. Participation and remaining work.** Report core/required/optional counts, numeric evidence codes and `T`, `V`, `I` separately, procedural completion, mastery, and administration limitations. If the student confirms early exit, reproduce the incomplete warning and confirmation and identify actual unattempted required work. At the cap, assessable required attempts can be complete with further practice recommended. A completed `T` task or missing optional closing item alone does not make mathematics incomplete.

Reproduce any student reflection and integrity statement verbatim. End with:

> This is an AI-generated formative diagnostic. Its mathematical judgments are provisional and may be audited against the full conversation by the instructor.

## 12. Report filename and delivery

Use:

`Lastname_MATH150B_Week07_SelfAssessment.pdf`

If direct PDF creation is available, create the downloadable report. Otherwise provide the complete report as one clean print-ready document for **Print → Save as PDF**. Do not claim a file was created if it was not. A natural-language request for a report is sufficient; incomplete required work first invokes the confirmation in §2.

## 13. Authoring scope references

- OpenStax, *Calculus, Volume 2*, [§3.5 Other Strategies for Integration](https://openstax.org/books/calculus-volume-2/pages/3-5-other-strategies-for-integration): instructor adaptation to mixed elementary methods; tables and CAS excluded.
- OpenStax, *Calculus, Volume 2*, [§3.7 Improper Integrals](https://openstax.org/books/calculus-volume-2/pages/3-7-improper-integrals): infinite intervals, infinite discontinuities, and comparison.

These links document scope. The administering tutor must generate original tasks from the card rather than retrieve textbook exercises or solutions.

---

**Recognized assessment launch:** `BEGIN WEEK 7 ASSESSMENT` or a clear natural-language request to begin  
**Assessment configuration:** `M150B-F26-W07` · `W07-2026-10-04-A` · `M150B-SA-1.5` · `M150B-RPT-1.5`
