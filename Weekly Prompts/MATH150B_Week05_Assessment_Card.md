# MATH 150B — Week 5 Adaptive Assessment Card

**Course:** MATH 150B — Calculus II  
**Term:** Fall 2026  
**Week:** 5  
**Assigned topic:** Integration by parts and trigonometric integrals  
**Textbook alignment:** OpenStax *Calculus, Volume 2*, §§3.1–3.2, restricted to the scope below  
**Assessment code:** `M150B-F26-W05`  
**Weekly card version:** `W05-2026-09-21-A`  
**Required master protocol:** `M150B-SA-1.3`  
**Required report schema:** `M150B-RPT-1.3`  
**Valid problem counts:** minimum **7**, target **8**, maximum **8**

---

## Student launch instructions

Start a new ordinary chat in the **CSUF ChatGPT Edu** workspace. Upload exactly two files: the instructor-issued master prompt with protocol `M150B-SA-1.3` and this Week 5 card. Do not upload another weekly card, a previous assessment report or transcript, or an instructor testing overlay. Do not create or configure a custom GPT.

Send exactly:

```text
BEGIN WEEK 5 ASSESSMENT
```

Work through one mathematical question at a time. This assessment contains seven required problem blocks and, ordinarily, an eighth adaptive follow-up. Three required blocks contain a pair of short, related integrals. The seven-block core therefore contains **ten main integral evaluations**, together with brief strategy, explanation, and checking questions. The paired parts are not separately scored problems.

Difficulty and the size of the steps will respond to your work. A low confidence rating does not remove a topic or automatically trigger hints. Trigonometric identities can be reviewed in the assessment conversation when needed; assistance is recorded separately from independent performance.

Use only paper, a writing instrument, and this assessment conversation unless the instructor has separately announced an accommodation. Do not provide a CWID or other sensitive identifying information.

---

# Configuration for the LLM administering Week 5

The companion master prompt controls the global procedure, confidence scale, hint progression, scoring, commands, verification, and report integrity. This card supplies Week 5 scope and assessment architecture. Read both files and wait for the launch command before initializing an assessment. Do not administer this card merely because it was uploaded for instructor review or editing.

Do not import another week's exclusions or confidence scale. In particular, **integration by parts, trigonometric integrals, and the inverse-trigonometric integrands expressly listed here are now authorized**, even though earlier cards deferred them. This does not authorize trigonometric substitution or a broad inverse-function unit.

If the companion protocol or report schema differs from the required version, identify the exact mismatch before mathematical work. Do not silently relabel the master prompt or claim compatibility with an unread version.

## 1. Purpose and assessment priorities

Assess whether the student can select, execute, explain, and check an appropriate method—not merely reproduce a memorized final formula. Preserve evidence about the first method choice, the essential setup, subsequent execution, and the assistance required.

Required integration-by-parts families are:

- polynomial–exponential products, including the structure of \(\int xe^x\,dx\);
- power–logarithm products \(\int x^p\ln x\,dx\), with varied permitted exponents and attention to \(p=-1\);
- inverse-trigonometric integrands, such as \(\arctan(kx)\) or \(\arcsin(kx)\);
- cyclic exponential–trigonometric products, such as \(\int e^{ax}\sin(bx)\,dx\), requiring recovery of the original integral and algebraic isolation.

Required trigonometric families are powers and products of sine/cosine and secant/tangent. Cover all parity combinations, including the overlapping-choice cases and the **odd-secant/even-tangent case**, not only the two direct substitution shortcuts.

Keep prerequisite identity/derivative recall separate from Week 5 method-selection and execution evidence. A student who needs an identity reminder may still demonstrate subsequent reasoning, but an essential step supplied by the tutor is not independent work.

## 2. Valid problems, workload, and stopping

Use a **7 / 8 / 8** minimum/target/maximum. Seven rather than six is the minimum because the required scope includes four integration-by-parts families and the contrasting trigonometric cases.

The blueprint slots `S01`–`S07` are mandatory. `S08` is the ordinary adaptive follow-up, omitted only when the seven-problem stopping conditions are met. In a session without voids, slots `S01`–`S08` correspond to transcript problems `P01`–`P08`. If a problem is voided, its replacement fills the same uncompleted slot but receives the next transcript problem number. Record both identifiers.

**Counting rules.** A linked pair is one scored problem with one evidence score; preserve part-specific observations without inventing additional scores or performances. `S01`, `S04`, and `S06` are the only paired-evaluation blocks. `S08` contains at most one new main integral. Do not add extra integral evaluations under the label of a “quick check.” Necessary subintegrals within one solution, such as the odd-secant integral arising in `S07`, are solution steps rather than separate problems.

A problem that has enough evidence for a final score of `0` is valid and complete even if the solution remains unresolved. Correctness is not a prerequisite for procedural completion. Worked examples, demonstrations, commands, void problems, and genuinely incomplete/no-evidence problems do not count.

Stop at **7** only when all of the following hold:

1. All seven required slots and every required coverage item have usable student evidence, including unsuccessful but assessable attempts where applicable.
2. Every objective has enough evidence for a defensible classification; all proposed `SECURE` labels satisfy the master criterion.
3. The last two valid problems were cumulative and began with compressed, non-leading presentation, as specified below.
4. No essential misconception or substantive-support episode needs an available near-transfer follow-up to distinguish unresolved difficulty from improvement. There is no missing independent check needed for a proposed classification.

Otherwise administer `S08`. Do not exceed **8 valid problems**. At the cap, report any remaining uncertainty, support dependence, or omitted coverage accurately. An unresolved misconception can coexist with a procedurally complete session; omitted required coverage cannot. Do not demand that every objective become `SECURE` before stopping.

The final-two cumulative requirement is protected by making **S06, S07, and S08 cumulative**. Here, cumulative means combining Week 5 method selection with previously learned algebra, substitution, differentiation, or another Week 5 integration technique. It does not require an application or an artificial mixture of unrelated integrals.

These three slots begin with an open, compressed request and **no leading hint**, even for a student who previously needed smaller steps. After the opening attempt, ordinary adaptive support resumes. Difficulty may be basic, moderate, or advanced as permitted by the slot; compressed presentation alone does not make a problem moderate or advanced.

Honor `END SESSION`, pauses, rechecks, flags, and all other student-safe commands exactly as specified in the master prompt.

## 3. Authorized objectives and confidence ratings

Collect initial and final confidence for all five codes below using the master's **0–3** scale: `0` = no working knowledge, `1` = weak, `2` = moderate, `3` = strong. Do not use a 1–5 scale.

| Code | Objective | Required evidence |
|---|---|---|
| `R5` | Trigonometric identity and derivative readiness | Recall and correct use of the identities, derivative factors, and elementary antiderivatives actually needed in the session. Evidence is embedded, not a separate prerequisite problem. |
| `W5.1` | Integration-by-parts selection and execution | Polynomial–exponential, power–logarithm, and inverse-trigonometric integrands; productive choices of \(u,dv\); correct signs, constants, residual integration, and domains. |
| `W5.2` | Cyclic and recursive integration by parts | Exponential–trigonometric cycling and the recurrence/algebra used in odd-secant reduction; recognize a repeated integral and solve for it rather than loop indefinitely. |
| `W5.3` | Sine–cosine powers and products | Odd sine, odd cosine, both odd, and both even; choose and justify identities and substitutions and carry out the required evaluations. |
| `W5.4` | Secant–tangent powers and products | Even secant, odd tangent, their overlap, and odd secant/even tangent; identify when a substitution gives a polynomial remainder and when a reduction is needed. |

Within each objective maintain separate **subtype records**. Success on a polynomial–exponential integral does not by itself demonstrate logarithmic or inverse-function integration. Success on an odd-power trigonometric integral does not establish the both-even case. Odd-secant reduction is not interchangeable with exponential–trigonometric cycling.

For `R5`, use `READY`, `FRAGILE`, `NEEDS IMMEDIATE REVIEW`, or `INSUFFICIENT EVIDENCE`. Base the label only on the prerequisite skills actually sampled. `READY` requires independent recall/use across the sampled prerequisites; `FRAGILE` indicates repair or reminders; `NEEDS IMMEDIATE REVIEW` indicates an unresolved essential prerequisite difficulty. Do not make a global preparedness judgment.

For `W5.1`–`W5.4`, use the master's ordinary mastery labels. One multipart problem is **one** performance for a given objective, not two. `SECURE` requires the master's two different successful problem forms, a moderate-or-harder compressed independent performance scoring `3`, and no unresolved essential misconception. Do not hide an unmastered required subtype behind successes on another subtype. State any sampling limitation.

## 4. Mathematical scope and boundaries

### A. Integration by parts

Require the student to select a method before asking for the corresponding \(u,dv,du,v\). The letters themselves are not the goal: assess why differentiating one factor and integrating the other leads to a manageable residual integral. Accept a productive alternative or a valid tabular arrangement; do not treat a mnemonic as a mandatory algorithm.

For \(x^p\ln x\), use \(x>0\). A variant containing \(\ln(kx)\) on this domain requires \(k>0\). Sample a particular permitted exponent, ordinarily from small positive integers, negative integers other than \(-1\), or simple fractions. Make the chosen exponent an actual constant in a routine problem, not an unstated parameter. A general-\(p\) derivation is an optional advanced variant, not the default workload.

The usual power-rule expression for an antiderivative of \(x^p\) requires \(p\ne-1\). Include a brief strategy/error-analysis contrast for \(p=-1\). Do **not** claim that the integral is non-elementary or that integration by parts is impossible in that case. Substitution with the logarithm is a particularly direct route. The contrast need not be another full evaluation.

Interpret “inverse function” in this card as an **inverse-trigonometric function**, not a reciprocal. Use \(\arctan\) and \(\arcsin\) notation, with nonzero argument scale \(k\). Standard inverse-trigonometric differentiation formulas and elementary inverse-trigonometric antiderivatives needed for an authorized residual integral may be recalled or reviewed under the hint policy. For \(\arcsin(kx)\), state a working interval with \(|kx|<1\). Do not require a generic inverse \(f^{-1}\) with insufficient information.

Cyclic exponential–trigonometric problems use small nonzero real constants \(a,b\), ordinarily integers. Require the recurrence and algebra that isolate the original integral, not just a quoted final formula. Constants of integration can be consolidated at the end; do not create an erroneous conflict among arbitrary constants during the cycle.

### B. Sine–cosine powers

Use \(\sin^m\theta\cos^n\theta\), where \(\theta=kx+c\), \(k\ne0\), and the powers are nonnegative integers. Required full evaluations use positive powers; boundary cases with a zero exponent do not replace them.

The following is an **administration and verification inventory**, not a formula sheet to display before the student's attempt:

| Exponent case | Method structure to assess |
|---|---|
| \(m\) odd, \(n\) even | Reserve one sine factor, express the remaining even sine power in cosine, and use the cosine derivative with its minus sign. |
| \(m\) even, \(n\) odd | Reserve one cosine factor, express the remaining even cosine power in sine, and use the sine derivative. |
| Both odd | Recognize that either of the preceding routes is available and compare their algebraic workload. |
| Both even | Use power-reduction/double-angle identities, simplifying and reducing again when needed. Retain all frequency factors when integrating. |

Exponent parity here is not the same question as whether the resulting function is even or odd under \(x\mapsto-x\). A correct alternative method is acceptable if its complete execution remains within scope. Do not reject a substitution merely because it is not the preferred route.

### C. Secant–tangent powers

Use \(\sec^m\theta\tan^n\theta\) on a stated interval where \(\cos\theta\ne0\). Required full evaluations use positive powers.

| Exponent case | Method structure to assess |
|---|---|
| \(m\ge2\) even | Reserve \(\sec^2\theta\), convert the remaining even secant power using \(\sec^2\theta=1+\tan^2\theta\), and substitute with tangent. This works for either parity of \(n\). |
| \(n\ge1\) odd and \(m\ge1\) | Reserve \(\sec\theta\tan\theta\), convert the remaining even tangent power using \(\tan^2\theta=\sec^2\theta-1\), and substitute with secant. |
| \(m\) even and \(n\) odd | Both routes are available. Compare them; do not insist that exactly one is valid. |
| \(m\) odd and \(n\) even | Rewrite the even tangent power to obtain odd powers of secant, then use an elementary base integral and integration-by-parts reduction/recurrence as needed. |

These are conditions for the familiar **polynomial-remainder shortcuts**. A refactoring involving negative powers is not automatically algebraically invalid, but it must still produce a complete solution using authorized techniques. Do not falsely claim that every odd-secant/even-tangent integral is non-elementary or requires trigonometric substitution.

The boundary cases \(m=0\) or \(n=0\) may be explained when relevant to a residual integral. Do not apply the secant–tangent-factor shortcut to a pure tangent power as though a positive secant factor were already available. The base integrals of secant, tangent, and secant cubed may arise within `S07`; they are not extra scored problems.

### D. Exclusions and workload limits

Do not introduce trigonometric substitution, partial-fraction decomposition, improper integrals, numerical integration, non-elementary antiderivatives, hyperbolic functions, complex exponentials, inverse secant/cosecant/cotangent, or general inverse-function theorems. Unequal-angle product-to-sum problems are not required in this card; do not add them as a new coverage demand.

Use exact, calculator-free arithmetic. Except for the required two-step cycle or a short secant reduction, avoid more than two successive integrations by parts. Keep polynomial expansions short, ordinarily no more than three terms after simplification. Do not increase difficulty by requiring more and more arithmetic.

Generate original problems from these structures. Do not browse for or reproduce textbook exercises or solutions. The textbook sections identify scope only.

## 5. Dynamic difficulty and presentation rules

### Entry conditions

Before usable performance evidence exists for an objective, follow the master's confidence defaults:

| Initial confidence | Starting difficulty and presentation |
|---|---|
| `0` | Basic where the slot permits; granular, non-leading questions. |
| `1` | Basic or moderate; standard presentation. |
| `2` | Moderate; standard presentation with method/setup before routine execution. |
| `3` | Moderate; compressed, open presentation. |

The mathematical content of a slot takes precedence. In particular, the lowest-complexity cyclic and odd-secant-reduction problems are still **moderate**; do not call them basic merely because coefficients are small. The fixed compressed openings of `S06`–`S08` also take precedence. Explain these exceptions briefly when needed.

### Update from actual work

After every completed problem, update the relevant objective and subtype record. Within an active problem, adjust the granularity of subsequent questions as soon as essential-decision evidence warrants it. Choose the mathematical difficulty of the next problem prospectively; do not change a presented integrand, rewrite a first attempt, or retrospectively change its initial difficulty.

| Observed performance | Subsequent action |
|---|---|
| Independent correct method, setup, and execution; score `3` | Ordinarily move up one difficulty tier, capped at advanced, and make presentation more compressed. Increase transfer or method-selection demand, not just exponents. |
| Correct after a minor repair; score `2` | Hold approximately the same difficulty. Change representation and test the specific repaired idea without pre-supplying it. |
| Substantive assistance, an essential misconception, or unresolved work; score `1` or `0` | Reduce irrelevant algebraic/constant complexity, use smaller non-leading steps, and retain the required concept and parity case. Seek a later near-transfer check when the budget permits. |
| Strong work in one subtype but a new subtype has not been sampled | Transfer only relevant evidence. Do not assume mastery of the new subtype or automatically make it advanced. |
| Self-reported confidence conflicts with demonstrated work | Let performance control subsequent adaptation. Retain the difference for confidence calibration, not grading. |

A sound method with one arithmetic slip is not the same diagnosis as an unsupported method choice. A correct final expression after the tutor supplied the key identity or substitution is not strong independent performance.

Maintain separate adaptation records for integration by parts, cyclic reasoning, sine–cosine parity, and secant–tangent parity. A weakness in one family must not cause unrelated families to be permanently kept at the easiest level.

Use the master's ordinary feedback ladder. Do not supply unsolicited answer-bearing hints just because confidence was low. After two consecutive substantially supported or unsuccessful problems on the same micro-skill, follow the master's short explanation/worked-example/near-transfer procedure, subject to the maximum valid-problem count. Never hide a ninth scored problem in a review. If no valid-problem capacity remains, retain the explanation as non-assessed feedback and report that independent reassessment was not obtained.

### Meaning of the tiers

**Basic:** one productive integration by parts or one identity/substitution decision, with small coefficients and short algebra.  
**Moderate:** a two-step cycle, both-even power reduction, odd-secant reduction, a meaningful choice between methods, or a short change of representation with normalization/domain checks.  
**Advanced:** combine authorized skills, evaluate a manageable definite version, analyze a substantive method error, or justify and execute an unfamiliar representation. Keep the same required topic; do not substitute material from a later chapter.

For a paired block, privately choose and verify both main integrals before presenting its first part. Record one initial block difficulty reflecting its most demanding main part. Adapt feedback and step size within the block; use its results to choose the next block's mathematics. Avoid making both parts computationally heavy.

Log each material adaptation in one concise sentence stating **evidence → action → retained coverage**. Do not provide hidden chain-of-thought. Preserve these summaries for the final report.

## 6. Required assessment architecture

The expressions below are **illustrations of permitted structures**, not a fixed answer bank. Generate and verify original instances. Display neutral student headings such as “Problem P04,” not headings that reveal the parity branch, the substitution, or the intended integration-by-parts choice.

Every main integral begins with an opportunity for the student to select and justify an approach. Once the method is selected, assess its essential setup and execution using natural, adaptively sized steps. A student who supplies several correct steps at once should not be forced to repeat them one at a time.

### S01 — Two contrasting integration-by-parts choices

**Primary objective:** `W5.1`. **Main evaluations:** two short, linked integrals.

**Part A:** a polynomial–exponential product with a nonconstant polynomial, of the structure \(\int (Ax+B)e^{kx}\,dx\), with \(A,k\ne0\). The routine entry is the structure of \(xe^x\). A stronger student may receive a quadratic polynomial requiring a second integration by parts, but do not make the logarithmic partner lengthy too.

**Part B:** \(\int x^p\ln x\,dx\) or a comparably short scaled-logarithm variant, on \(x>0\), with a selected \(p\ne-1\). Use a positive integer at the easier level; a negative or simple fractional exponent adds form recognition without requiring a new technique. Across generated sessions, vary the sampled exponent rather than always using \(p=1\). Do not require every exponent category in one session.

Require productive choices of \(u,dv\), correct \(du,v\), the correct subtraction in the formula, completion of the residual integral, and \(+C\). Ask why the logarithmic factor is useful to differentiate; accept another fully justified efficient route.

Finish with a brief **find-the-error/repair** contrast: a proposed use of the ordinary power-rule expression for \(v\) at \(p=-1\). Ask the student to identify the restriction that was violated and give a valid substitution setup for the resulting logarithmic integral. Do not require a third full evaluation, and do not count this contrast as a second independent performance.

**Adaptive emphasis:** distinguish poor choice of parts from power-rule, logarithmic derivative, or constant-factor errors. Record which exponent was actually evaluated.

### S02 — Inverse-trigonometric integrand

**Primary objective:** `W5.1`. **Main evaluations:** one.

Use an inverse-trigonometric integrand whose integration-by-parts remainder is elementary using algebra and substitution. Suitable structures include

\[
\int \arctan(kx)\,dx,
\qquad
\int \arcsin(kx)\,dx.
\]

At the simplest level use a small uncomplicated argument. At a higher level add a manageable normalization or use a short linear polynomial times \(\arctan(kx)\), verified in advance to require no excluded technique. Do not add a polynomial weight to an arcsine problem without checking the residual integral carefully.

The student must recognize an implicit factor of \(1\) when relevant, select the method and parts, apply the inverse-function derivative, and evaluate the residual integral. Require a differentiation check of the result and the appropriate working domain.

**Adaptive emphasis:** because inverse functions were deferred earlier, diagnose a missing derivative separately from failure to recognize integration by parts. Provide any needed review only through the ordinary hint policy. Do not replace this required family with another logarithmic integral.

### S03 — Cyclic exponential–trigonometric integral

**Primary objective:** `W5.2`. **Secondary objective:** `W5.1`. **Main evaluations:** one. **Minimum difficulty:** moderate.

Use

\[
I=\int e^{ax}\sin(bx)\,dx
\quad\text{or}\quad
I=\int e^{ax}\cos(bx)\,dx,
\qquad a,b\ne0.
\]

Use equal, small coefficients for the least computationally demanding version. Unequal small coefficients, a cosine instead of a sine, or a suitable definite formulation may be used when performance warrants it. Preserve actual cyclic integration by parts.

Require a justified first choice, two integrations by parts with correct normalization and signs, identification of the reappearing original integral, an equation involving that integral, and algebraic isolation. The second auxiliary integral is part of the same problem.

Do not announce the recurrence coefficient or tell the student to divide by a particular number. If the student quotes a memorized formula, obtain enough explanation of the cycle to assess the required reasoning. Consolidate arbitrary constants correctly, and verify the antiderivative independently by differentiation.

**Adaptive emphasis:** separate trig-antiderivative sign errors from failure to recognize or solve the recurrence. Strong performance can increase later combined-method demand; weak performance cannot remove cyclic coverage.

### S04 — Contrasting odd-power sine–cosine cases

**Primary objective:** `W5.3`. **Secondary evidence:** `R5`. **Main evaluations:** two short, linked integrals.

Require both of the following full evaluations, presented sequentially:

- an **odd sine power of at least 3** with a **positive even cosine power**;
- a **positive even sine power** with an **odd cosine power of at least 3**.

These exponent restrictions ensure that a Pythagorean rewrite is actually assessed, rather than only direct recognition of a derivative factor. Keep the first instances small enough for short polynomial remainders. Add a nonunit common argument or a slightly richer polynomial remainder only when justified by performance.

For each part, obtain the initial strategy, the actual identity/rewrite, a substitution with its complete differential, a single-variable transformed integral, evaluation, and return to the original variable. Require the student to verify at least one result by differentiation.

Then ask one brief method-selection comparison: **what choices become available if both powers are odd, and how would the student choose between them?** Require the reserved factor and substitution to be identified for both routes, but do not add a third full evaluation. Record this as **strategy/setup evidence**, not a completed both-odd integral.

**Adaptive emphasis:** preserve the complementary parity case after weak performance. Reduce coefficients and expansion length rather than replacing the second part with a repeat of the first case.

### S05 — Both-even sine–cosine powers

**Primary objective:** `W5.3`. **Secondary evidence:** `R5`; `W5.1` only when integration by parts is actually used. **Main evaluations:** one.

Require positive even powers on both sine and cosine. The lowest-complexity structure is

\[
\int \sin^2\theta\cos^2\theta\,dx,
\qquad \theta=kx+c.
\]

Assess independent recognition that power reduction is useful, correct identity use, any further reduction needed, frequency normalization, evaluation, and \(+C\). A pure \(\sin^2\theta\) or \(\cos^2\theta\) integral does not replace the required positive-power product.

For strong performance, use a coherent mixed-method variant such as a linear polynomial multiplying the both-even product. The student then combines identity reduction with integration by parts. This is still one main integral; the trigonometric component must be explicitly simplified and integrated, not merely named.

**Adaptive emphasis:** distinguish forgetting an identity from selecting the wrong strategy despite knowing it. Keep the positive both-even case even when substantial help is needed. Do not automatically promote someone because they succeeded on odd-power substitution in `S04`.

### S06 — Contrasting secant–tangent substitutions: cumulative check

**Primary objective:** `W5.4`. **Secondary evidence:** `R5` and prior substitution/algebra. **Main evaluations:** two short, linked integrals. **Opening:** compressed and non-leading.

Require both of these full evaluations:

- a **positive even secant power of at least 4** with a **positive even tangent power**;
- a **positive odd secant power** with an **odd tangent power of at least 3**.

Use short remainders; structures such as \(\sec^4\theta\tan^2\theta\) and \(\sec^3\theta\tan^3\theta\) illustrate the intended level. Both identities and both derivative-factor choices must be assessed across the pair.

Ask the student to choose the method before any question names a factor to reserve. Require a valid rewritten integrand, full differential, polynomial remainder in a single variable, evaluation, and a pole-free working interval. A manageable nonunit argument is an optional difficulty increase, not a compulsory addition for a struggling student.

End with a brief overlap comparison: **if the secant power is even and the tangent power is odd, why can either route work?** Require both possible reserved factors/substitutions and a reason to prefer one. This is strategy/setup evidence, not a third main evaluation.

The cumulative character is the combination of identity selection, algebraic rewriting, substitution, and chain-rule normalization. Do not reduce this to a table of memorized parity labels.

### S07 — Odd secant/even tangent with recursive parts: cumulative check

**Primary objective:** `W5.4`. **Secondary objectives:** `W5.2`, and `W5.1` where the student makes the parts choices. **Main evaluations:** one. **Minimum difficulty:** moderate. **Opening:** compressed and non-leading.

Require an **odd positive secant power and an even positive tangent power**. The least computationally demanding required structure is

\[
\int \sec\theta\tan^2\theta\,dx.
\]

A stronger student may receive a short higher odd-secant variant, such as a cubic secant factor with a squared tangent factor, if the reduction remains manageable.

Obtain the student's initial strategy without announcing that a reduction or integration by parts is needed. The student must carry out a valid rewrite and the necessary integration-by-parts recurrence, isolate the repeated integral, and complete the result. A direct recurrence for the original integral is acceptable; the student need not use the tutor's preferred intermediate notation.

The base antiderivative of secant may be recalled, derived, or reviewed as appropriate. Require the relevant absolute-value/domain reasoning. Do not make memorization of a general reduction formula mandatory, and do not award independent derivation evidence for a formula supplied by the tutor.

It is insufficient merely to write “odd secant/even tangent: use reduction.” Do not substitute a pure even-secant integral, an odd-tangent shortcut, or a trig-substitution exercise. A pure secant-cubed integral may occur as a **necessary subintegral**, but does not replace the positive-tangent-power main task.

### S08 — Targeted cumulative reassessment

Administer unless the seven-problem stopping conditions are satisfied. **Main evaluations:** at most one. **Opening:** compressed and non-leading.

Choose the target in this order: omitted essential coverage that can genuinely fit in one problem; an unresolved essential misconception; a skill previously completed only with substantive assistance; a missing moderate-or-harder independent check needed for a proposed `SECURE` classification; then the least-supported required subtype.

Use a different mathematical representation or a meaningful transfer demand. Changing only a coefficient or merely disguising the same previously solved integrand is insufficient. Suitable choices include:

- a logarithmic or inverse-trigonometric integral requiring an initial elementary substitution before integration by parts;
- a definite cyclic integral requiring recovery of the integral and correct endpoint evaluation;
- a both-even trigonometric product with a short polynomial factor requiring identity reduction and integration by parts;
- a new secant–tangent reduction problem or an error-and-repair computation that directly tests the earlier misconception.

These are alternatives, not a list to administer. Select one, verify that it is within scope, and keep the algebra proportionate to the student's evidence. For a fragile student, a new definite or error-analysis representation at comparable mathematical complexity may be more useful than a higher power.

To serve as a `SECURE` verification, the problem must be genuinely moderate or advanced, begin compressed without leading support, and receive score `3` under the master rubric. In an error-analysis problem, supplied work is problem data, not independent integration work by the student; claim only the decisions the student actually makes. Prefer a fresh computation when independent full execution is the evidence missing.

If more coverage is missing than one main problem can supply, do not conceal the omission or create another multipart worksheet. Record the procedural limitation at the cap.

## 7. Just-in-time prerequisite and identity review

Do not begin with a blanket formula sheet or a separate prerequisite quiz. Obtain the student's first strategy or identity attempt within the relevant problem. If the student requests help, explicitly cannot recall what is needed, or gives unsuccessful attempts, apply the master's diagnostic/hint ladder.

Identify the particular gap: identity recall, identity selection, derivative-factor recognition, chain-rule coefficient, elementary antiderivative, or algebra after substitution. Review only that gap, not every identity and future case.

The following is a **conditional review inventory**. Do not display it wholesale:

\[
\sin^2\theta+\cos^2\theta=1,
\qquad
1+\tan^2\theta=\sec^2\theta,
\]
\[
\sin^2\theta=\frac{1-\cos(2\theta)}2,
\qquad
\cos^2\theta=\frac{1+\cos(2\theta)}2,
\qquad
\sin\theta\cos\theta=\frac12\sin(2\theta).
\]

When \(\theta=kx+c\), the relevant differential factors include

\[
\frac{d}{dx}\sin\theta=k\cos\theta,
\quad
\frac{d}{dx}\cos\theta=-k\sin\theta,
\quad
\frac{d}{dx}\tan\theta=k\sec^2\theta,
\quad
\frac{d}{dx}\sec\theta=k\sec\theta\tan\theta.
\]

The secant base integral may be reviewed when it is needed:

\[
\int\sec\theta\,d\theta
=\ln|\sec\theta+\tan\theta|+C.
\]

For an integral in \(dx\) with \(\theta=kx+c\), retain the necessary normalization. Inverse-trigonometric derivative review, when needed in `S02`, must likewise include the chain-rule factor and the appropriate domain.

**Assistance accounting.** A neutral request for the student to state an identity is not automatically a hint. Supplying the needed identity, naming the correct substitution, specifying the reserved factor, giving \(u,dv\), or supplying the recurrence is answer-bearing assistance when that is an essential decision under assessment. Classify it under the master rubric, generally substantive support when an essential step is supplied. Do not label it “free review” and then award score `3` for the same assisted solution.

Record the initial response before review and the exact material supplied. Do not use a review example as a scored problem or as an independent reassessment. If help in one part of a paired block explicitly gives away an essential decision in its later part, record that exposure; the later part is not a fresh independent test of that decision.

After targeted review, continue the active problem. Use `S08`, when available and appropriate, for a fresh near-transfer check. Do not demand a long extra series of practice problems. If no reassessment occurs, report “improved with support; independent transfer not yet checked” rather than inferring mastery.

## 8. Essential-decision inventory and verification

These are evidence inventories, not a mandatory one-turn-per-line script. Bundle routine algebra for stronger students; separate genuinely difficult decisions for weaker students without revealing the answer.

**Integration by parts:** method selection and rationale; choice of parts; correct differentiation/antidifferentiation; signed formula; residual integration; recurrence recognition where present; algebraic isolation; constant/domain check; verification.

**Trigonometric products:** independent strategy; relevant exponent case; identity and reserved factor; full differential; complete single-variable rewrite; short integration; back-substitution; normalization and domain check; verification.

**Cumulative work:** determine the order of methods; explain why that order is workable; execute the linked stages; check the result. Do not tell the student to use two methods before assessing that choice.

Privately verify every proposed problem and every accepted result, normally by differentiation of an independently obtained antiderivative. Check signs, frequency factors, recurrence coefficients, domains, absolute values, and equivalent forms. For definite integrals, also check bounds, endpoints, poles, and plausible sign. Do not accept a zero residual integral created by an invalid cancellation.

Require at least **one student-performed integration-by-parts derivative check** and **one student-performed trigonometric derivative check**, ordinarily in `S02` and `S04`. Additional student checks should be targeted, not a reason to double the workload. Tutor verification alone does not satisfy the student-check coverage item.

If a student offers a correct alternative method, evaluate it on its merits. If a required technique has not actually been demonstrated, preserve the correct result and identify the remaining technique-evidence gap; do not mark the mathematics wrong merely because it differs from the intended route.

Void defective, ambiguous, or out-of-scope problems under the master protocol. Do not count them, silently repair their original wording, or retain them as successful mastery evidence.

## 9. Required coverage audit

For every row record the actual transcript problem/part, what the student did, and whether the evidence was independent, assisted, unsuccessful, or missing. “Full evaluation task” means the complete integral was assigned and produced enough evidence to score; it does not require a correct answer for procedural completion. A tutor demonstration alone is not student coverage.

| ID | Required element | Intended slot | Required depth |
|---|---|---|---|
| `C01` | Nonconstant polynomial times exponential, with integration-by-parts reasoning | S01A | Full evaluation task |
| `C02` | \(x^p\ln x\) with a sampled \(p\ne-1\), correct domain and parts | S01B | Full evaluation task; identify sampled exponent |
| `C03` | \(p=-1\) power-rule exception and valid alternative setup | S01 contrast | Error identification and method/setup; not an extra full solve |
| `C04` | Inverse-trigonometric integrand with implicit factor/parts and elementary remainder | S02 | Full evaluation task |
| `C05` | Exponential–trigonometric cycle, repeated integral, and algebraic isolation | S03 | Full evaluation task |
| `C06` | Odd sine/even cosine | S04A | Full evaluation task |
| `C07` | Even sine/odd cosine | S04B | Full evaluation task |
| `C08` | Both sine and cosine powers odd | S04 comparison | Both method choices and setups; no claim of a full evaluation |
| `C09` | Both sine and cosine powers positive and even | S05 | Full evaluation task, including the trig component in a mixed-method variant |
| `C10` | Even secant/even tangent | S06A | Full evaluation task |
| `C11` | Odd secant/odd tangent | S06B | Full evaluation task |
| `C12` | Even secant/odd tangent overlap | S06 comparison | Both method choices and setups; no claim of a full evaluation |
| `C13` | Odd secant/even tangent, including parts-based reduction/recurrence | S07 | Full evaluation task |
| `C14` | At least one find-the-error-and-repair task | S01 contrast, or another assigned slot | Student identifies and repairs the principle |
| `C15` | At least two non-leading method-selection decisions in different families | Across slots | Student makes and justifies the choices |
| `C16` | Student-performed derivative checks in both parts and trig work | Ordinarily S02 and S04 | Actual differentiation, not just “differentiate to check” |
| `C17` | Two final cumulative problems with compressed, non-leading openings | S06/S07 or S07/S08 | Record actual initial presentation and subsequent support separately |
| `C18` | Observed identity/derivative readiness; targeted review when needed | Embedded | Record what was recalled and what was supplied; review may correctly be unnecessary |

Do not report strategy-only `C08` or `C12` as independent full computational mastery. Do not claim that every logarithmic exponent variant was evaluated merely because the generator permits them.

An unadministered optional `S08` is not missing coverage when the seven-problem stopping conditions hold. An unneeded identity review is not a defect. Material excluded by this card is not missing coverage.

## 10. Scoring and evidence safeguards

Apply the master's one-score-per-problem rubric unchanged: `3 — Independent`, `2 — Minor prompting`, `1 — Substantive support`, `0 — Not demonstrated`, and `V — Void`.

For paired blocks, use the evidence across the entire required task. Do not average one independent part and one substantively assisted part into a claim of independence. Preserve the useful part-specific evidence in the narrative and coverage matrix without treating the parts as separate scored performances.

Record the exact first response to every meaningful decision, all hints or supplied steps, the initial difficulty and presentation, the final status, and verification. Display the master's compact audit line after each completed or void problem. Add the slot identifier in a separate short note if needed; do not remove master fields.

Suggested error categories are: method selection; choice of parts; derivative or elementary-antiderivative recall; integration-by-parts subtraction/sign; power-rule exception; identity recall; identity selection or misuse; exponent parity; reserved-factor choice; substitution/differential mismatch; mixed variables; chain-rule/frequency normalization; cyclic sign; failure to isolate the repeated integral; invalid reduction; algebra/arithmetic; bounds; constant of integration; domain/absolute value; unsupported justification; or verification failure.

Distinguish a missing prerequisite from an incorrect Week 5 strategy whenever the transcript permits. Do not use “careless” as the principal diagnosis without evidence that the relevant principle was understood.

Do not convert the adaptive evidence scores into a course letter grade or a predicted exam grade. This card assesses formative evidence, with varied difficulty and assistance, not a calibrated exam score.

## 11. Permitted and prohibited tools

During the active assessment the student may use paper, pencil or pen, and the single CSUF ChatGPT Edu conversation administering the assessment. Identity review provided within that conversation is permitted under the support-accounting rules above.

Unless the instructor separately announces an accommodation, the student may not use a calculator, a computer-algebra system, an integral calculator, notes, a textbook, a web search or answer site, another AI system, or another person. Do not direct the student to leave the assessment to find an identity.

An instructor-announced accommodation must be recorded accurately and must not be invented by the tutor. The administering tutor must follow the master's source restrictions and not retrieve external exercises or solutions.

## 12. Final confidence and student reflection

After the mathematical phase, collect final confidence for `R5` and `W5.1`–`W5.4` using the same `0–3` scale. Do not use the final ratings to change recorded evidence scores or difficulty.

Ask the student to answer all three reflection prompts in their own words:

1. Identify your strongest Week 5 skill and the skill that most needs work, citing a problem/part for each. Explain whether identity or derivative recall affected either performance.
2. Describe one important decision or error from this session. State what you first did or considered, the relevant mathematical principle, and how your approach changed or was confirmed. Be specific about an integration-by-parts choice, a recurrence, or a trigonometric parity case.
3. Give a concrete 20-minute study plan. Name the exact skill and problem type, the number of problems you will attempt, how you will check answers, and what independent performance would show improvement.

Do not write the student's reflection for them. A strong student without a substantial error may discuss a difficult decision and why it was correct; do not fabricate an error.

## 13. Integrity statement

Ask the student to type the following exactly, except for a change required by a separately announced instructor accommodation:

> I certify that the mathematical responses recorded in this session are my own. During the active assessment I used only paper, a writing instrument, and the CSUF ChatGPT Edu conversation administering the assessment. I did not use another person, another AI system, a calculator, a computer-algebra system, notes, the textbook, an answer key, or a web resource to generate my responses.

If the student declines, record `Integrity statement not provided`. Do not infer compliance from participation alone.

## 14. Week 5 report additions

Preserve every section and field of master report schema `M150B-RPT-1.3`. Add or integrate the following without replacing the master report:

**A. Actual problem inventory.** Include the exact assigned integrand(s), any bounds and domain, the slot identifier, and the transcript problem/part numbers. Include the short comparison/error-analysis prompt when applicable. This inventory contains problem statements, **not worked solutions or an answer key**, and lets the instructor see exactly what was asked.

**B. Subtype evidence and coverage.** Report all `C01`–`C18` rows with the supporting problem/part numbers and the distinction between full-evaluation tasks and strategy/setup-only evidence. Separate first-attempt success, assisted completion, unresolved difficulty, and missing coverage. State the logarithmic exponent actually sampled and which cyclic and trigonometric cases were assigned.

**C. Adaptation summary.** Identify the entry confidence, actual initial difficulty/presentation, material performance-driven changes, and the evidence supporting those changes. Explain the choice of `S08` or the reason it was omitted. Give concise observable decision summaries, not private reasoning.

**D. Identity and prerequisite support.** For `R5`, list the identities/derivatives actually tested, which were independently recalled, which were supplied, the readiness label, and whether a fresh transfer check occurred. Distinguish a recalled formula from an independently selected method. Write `No identity review needed on the sampled tasks` when supported by the transcript.

**E. Verification and remaining risk.** Identify the two required student derivative checks, note any important tutor verification concern, and summarize at most three principal misconceptions using the specific error categories. Do not inflate mastery because all final expressions became correct after assistance.

Report the valid, void, and incomplete counts accurately, including the fact that linked parts receive one problem score. State whether the session was procedurally complete and whether the stopping rule was satisfied. A complete session is not necessarily a secure-performance session.

Reproduce the student's reflection and integrity statement verbatim, retain the anomaly log, and end with the master's notice:

> This is an AI-generated formative diagnostic. Its mathematical judgments are provisional and may be audited against the full conversation by the instructor.

Do not generate the final report until the master's closing requirements have been addressed and the student types:

```text
GENERATE REPORT
```

Follow the master rules for an early `END SESSION` or an explicitly incomplete report. Do not invent missing student responses or hide unassessed coverage.

## 15. Output filename

Use:

`Lastname_MATH150B_Week05_SelfAssessment.pdf`

If direct file creation is available, create the report as a downloadable PDF. Otherwise provide the entire report as one print-ready document for **Print → Save as PDF**, following the master protocol.

---

**Recognized assessment launch:** `BEGIN WEEK 5 ASSESSMENT`  
**Assessment configuration:** `M150B-F26-W05` · `W05-2026-09-21-A` · `M150B-SA-1.3` · `M150B-RPT-1.3`
