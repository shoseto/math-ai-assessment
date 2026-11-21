# AI-Assisted Calculus Self-Assessment

Instructor-designed formative assessments for **MATH 150B (Calculus II)** at **California State University, Fullerton**.

These materials guide a large language model (LLM) through problem presentation, feedback, adaptive practice, and diagnostic reporting. The central goal is to make students' mathematical reasoning visible and distinguish independent understanding from work completed with assistance.

**[Open the Playlab assessment](https://www.playlab.ai/project/cmwfcymf2095xj40x4qkvavkm)** · **[Try the self-contained Exam 3 card](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Exam3_Practice_Exam_Card.md)**

## Start here

### Try an assessment

The **Exam 3 practice card** is the simplest starting point because it contains its own administration instructions and needs no separate master prompt.

1. Open the [Exam 3 practice card](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Exam3_Practice_Exam_Card.md) and download the raw Markdown file.
2. Upload that file to a new ChatGPT or Gemini conversation that supports file uploads.
3. Send: `BEGIN EXAM 3 PRACTICE`.
4. Choose to see all questions at once or one question at a time. Work through the assessment; typed solutions and readable handwritten uploads are supported by the instructions.
5. Request a report when finished. The card specifies a print-ready fallback when the platform cannot create a PDF directly.

For a weekly assessment, upload **one master prompt and one matching weekly card** to a fresh conversation, then send the launch message printed on the card. See the version table below. Students completing a course assignment should use the files and platform assigned by their instructor.

### Review the design

Start with the [v1.5 master prompt](Fall%202026%20Math%20150B/Master%20Prompts/MATH150B_Adaptive_Self_Assessment_Master_Prompt_v1_5.md) and the [Week 7 card](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week07_Assessment_Card.md), which explicitly targets that version. The master describes interaction and reporting rules; the card supplies mathematical scope, problem structure, and coverage requirements.

## Educational design

- **Reasoning before answers.** Students are asked to explain methods and justify conclusions; correct final answers alone may provide limited evidence of understanding.
- **Independent and assisted work are distinct.** The instructions record substantive help and subsequent revisions separately from independent attempts.
- **Confidence is not performance.** A low confidence rating alone does not justify giving away a method or answer.
- **Tutor errors are recorded separately.** Unsolicited disclosures and defective problems must not be treated as student failures or independent student success.
- **Practice responds to evidence.** Follow-up work targets demonstrated gaps within the card's stated workload limits.
- **Reports can be reviewed.** The protocols specify records of problems, student work, assistance, scores or status flags, and corrections. Students can request re-evaluation of disputed judgments.

These are specified behaviors. Their reliability depends on the model, platform, and interaction and requires evaluation.

## Materials and versions

The current public collection contains three master prompts, six weekly cards, and two exam cards. It is a selection of course materials, not a complete weekly sequence.

| Location | Contents |
| --- | --- |
| [Master Prompts](Fall%202026%20Math%20150B/Master%20Prompts/) | General protocols v1.3 and v1.5, plus the v1.3-E1.1 diagnostic extension. |
| [Weekly Prompts](Fall%202026%20Math%20150B/Weekly%20Prompts/) | Weeks 1, 2, 3, 5, 6, and 7, plus Exam 2 review and Exam 3 practice. |

**Choose the companion named by the card:**

| Assessment card | Master protocol named in the card |
| --- | --- |
| [Week 1](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week01_Assessment_Card.md) | v1.2; that historical master is not included. See the compatibility note below. |
| [Week 2](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week02_Assessment_Card.md), [Week 3](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week03_Assessment_Card.md), [Week 5](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week05_Assessment_Card.md), and [Week 6](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week06_Assessment_Card.md) | [v1.3](Fall%202026%20Math%20150B/Master%20Prompts/MATH150B_Adaptive_Self_Assessment_Master_Prompt_v1_3.md) |
| [Week 7](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Week07_Assessment_Card.md) | [v1.5](Fall%202026%20Math%20150B/Master%20Prompts/MATH150B_Adaptive_Self_Assessment_Master_Prompt_v1_5.md) |
| [Exam 2 review](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Exam02_Assessment_Card.md) | [v1.3-E1.1](Fall%202026%20Math%20150B/Master%20Prompts/MATH150B_Master_Prompt_v1.3-E1.1.md), which includes the diagnostic scoring extension |
| [Exam 3 practice](Fall%202026%20Math%20150B/Weekly%20Prompts/MATH150B_Exam3_Practice_Exam_Card.md) | None; this card is self-contained. |

**Compatibility note:** Section 2 of v1.5 permits use with earlier weekly cards under explicit conditions: acknowledge and record the mismatch, retain the card's identifier, and apply v1.5's governing interaction and reporting rules. This offers a route for the historical Week 1 card; it does not mean that the card itself has been updated. Unresolved scope or configuration requires instructor clarification. For an initial demonstration with a matching pair, use Week 7 and v1.5.

## Status and limitations

This release documents assessment design and instructions. It does not yet include published sample session reports, an automated compliance auditor, or a benchmark dataset. The repository does not establish measured gains in student learning or measured rates of model compliance.

Models can still make mathematical mistakes, misinterpret handwriting, disclose answers prematurely, or misapply a rubric. Instructor review remains important. Generated practice scores are diagnostic and should not be interpreted as official course grades or validated exam predictions.

Prompt files are readable by anyone who downloads them, including any embedded verification material. They are intended for formative assessment and practice, not secure exam delivery. Model-generated problem variation is not a guarantee of reproducibility or uniqueness across separate conversations.

## Development priorities

- Add a clearly labeled synthetic demonstration, its diagnostic report, and an instructor audit.
- Document observed successes and failures in following the assessment rules.
- Develop repeatable evaluation cases for mathematical correctness, appropriate help, and scoring consistency.

## Feedback and reuse

Educators and researchers are welcome to explore and adapt the materials. To report a problem, [open an issue](https://github.com/shoseto/math-ai-assessment/issues) and include the relevant file/version, model if known, expected behavior, and observed behavior. Use synthetic or appropriately redacted examples; do not post identifiable student work.

## Author and license

**Shoo Seto** — Associate Professor of Mathematics, California State University, Fullerton.

Educational goals, course alignment, and pedagogical decisions by Shoo Seto; materials developed iteratively with AI assistance.

[Email](mailto:shoseto@fullerton.edu) · [ORCID](https://orcid.org/0009-0005-6276-7949) · [GitHub profile](https://github.com/shoseto)

Released under the [MIT License](LICENSE).
