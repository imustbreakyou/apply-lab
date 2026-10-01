# Workflow examples

Selected development artifacts show what changed and what remains unproven. Case labels replace employer names; square brackets mark substitutions. The feedback example uses synthetic test data. No candidate career records are included. Public examples omit personal names, employers, target companies, customers, contact details, private paths and identifying career metrics; neutral case labels stand in for real applications.

## Sharper role analysis

**Problem.** A role brief described the mandate accurately, but its opening gave limited guidance on the behaviors that made this hire distinctive.

**Change.** The analyst instruction now asks for three or four defining behaviors, grounded in the posting, with observable proof to seek and explicit writing guidance.

**Before.** The brief summarized the overall mandate but gave downstream agents limited guidance about which evidence mattered most.

**After.** The brief connected its ranked priorities to observable evidence and writing guidance. Job-specific wording and hiring criteria are omitted from this public example.

**Limit.** This is a more specific handoff, not evidence that the eventual resume improved. Instructions were tuned on two known roles, with one output per condition; live research and some assignment wording also varied. An unseen role and downstream resume review remain necessary.

Source: saved baseline and final role briefs from the two-role analyst experiment. [Experiment record](decision-log.md#entry-056).

## Correcting the evaluator

**Problem.** The coordinator penalized an output for wording and placement that the agreed rubric did not require.

**Before.** A requirement was covered, but the evaluator treated its absence from the opening as a failure.

**Change.** After the user challenged that interpretation, the coordinator separated coverage from editorial placement and assessed meaning rather than a literal phrase match.

**After.** The same output met the original criteria. The initial assessment was retained so the correction remained visible.

The correction applied to both outputs:

| Completeness and emphasis | Initial assessment | Corrected assessment |
| --- | --- | --- |
| Baseline brief | Partial | Met |
| Revised brief | Partial | Met |

**Limit.** The outputs did not change during this reassessment. This corrects the evaluation; it is not a new performance gain or independent validation. The initial assessment and independent baseline review were retained.

Source: frozen criteria, initial coordinator assessment and amended assessment. [Correction record](decision-log.md#entry-061).

## Separating feedback

**Problem.** A single comment action did not record whether feedback concerned the current resume or future workflow behavior.

**Change.** The reviewer chooses the scope when saving. Existing comments remain unclassified rather than being assigned an inferred intent.

| Interface | Before | After |
| --- | --- | --- |
| Save action | Add comment | Add Comment for CV / Add Comment for Harness |
| Exported scope | No scope field | CV, Harness or Unclassified |

**After — excerpts from the saved synthetic browser-test export:**

```text
Scope: Unclassified
Legacy synthetic comment, preserve unchanged.

Scope: CV
CV native click

Scope: Harness
Harness native keyboard
```

The original comment object was preserved. New comments retained the exact resume version, hash and anchor. A simulated save failure also preserved the draft and pin for retry.

**Limit.** These checks demonstrate local feedback storage and interaction behavior. They do not show that harness feedback improves future resumes. Labeling a comment does not apply an instruction change.

Source: interface and export formatter before and after the change, plus the saved synthetic export and browser verification. Export excerpts omit source, hash, anchor, status and timestamps. [Verification record](decision-log.md#entry-068).

The [decision-log extract](decision-log.md) provides additional history. These excerpts are selected evidence, not a complete benchmark or an independent audit.
