# Apply Lab

The multi-agent workflow behind this resume.

Apply Lab tailors resumes to job requirements while keeping claims grounded in documented career experience.

## How it works

The workflow starts with a job description and a career library: a structured collection of roles, accomplishments and source records.

1. **Research.** An analyst studies the role and company, producing briefs on requirements and context.
2. **Map.** A mapper ranks relevant career evidence and flags gaps.
3. **Write.** A writer creates the resume and records the sources supporting its claims.
4. **Review.** A separate reviewer checks accuracy, relevance, writing and page layout, then returns findings for revision.

Written handoffs help trace problems to research, evidence selection or writing. Claims stay linked to their sources, and evidence gaps are flagged for clarification. The final resume requires personal review.

## Feedback and evaluation

Feedback stays attached to the exact resume version and is marked as one of two types:

- **Resume feedback:** changes to that document's content, wording or layout.
- **Harness feedback:** improvements to agent instructions, handoffs or review criteria across future runs.

Proposed harness changes require review and approval. The harness records decisions and outcomes.

Role-analysis experiments used saved job descriptions, criteria set before generation and fresh agents without expected answers. Final resumes receive separate checks for factual support, relevance and layout.

## Recorded results

| Check | Result |
| --- | --- |
| Role analysis | Revised briefs provided useful, distinct guidance for two roles. Review also corrected overly strict expectations about wording. [Record](docs/decision-log.md#entry-061) |
| Resume revision | Six resumes completed separate agent reviews; 12 PDF pages were inspected and all 59 existing comments preserved. [Record](docs/decision-log.md#entry-071) |
| Feedback controls | Separate Resume and Harness feedback passed 21 automated tests and browser checks; all 44 existing comments were preserved. [Record](docs/decision-log.md#entry-068) |

These are development results. The two-role comparison was iterative; the six-resume pass also changed source evidence and reused agents. The results do not isolate the effect of instruction changes. [Later feedback](docs/decision-log.md#entry-077) still identified improvements to opening emphasis and wording.

The [full decision log, with redactions](docs/decision-log.md) covers all 82 recorded entries through September 30, 2026, 06:55 Pacific, including proposals, corrections and pending outcomes. Private career details and internal identifiers are marked where removed.
