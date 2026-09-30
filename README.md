# Apply Lab

Apply Lab explains the multi-agent AI workflow behind my resume. I directed its design and refinement, working with AI agents on implementation, drafting and review.

The goal is to turn a job description and a curated library of career evidence into a relevant, accurate resume, with human judgment throughout. If you arrived here from my resume, this is how it was prepared.

This first release shares the process in this README. The underlying workflow is used privately; its code and application materials are not part of this release.

## How the resume workflow works

Agents have distinct responsibilities and pass written outputs to the next stage:

1. **Research the role.** A Role Analyst interprets the job description and researches the company and relevant product or team. Separate briefs record requirements, context, sources and unknowns.
2. **Map the evidence.** A Skill Mapper connects those requirements to my career library. It recommends which contributions to emphasize, distinguishes transferable experience from missing qualifications, and identifies questions that could strengthen the evidence.
3. **Draft the resume.** A Resume Builder selects and writes supported material for the role, produces an editable document and PDF, and records the sources behind its claims.
4. **Review the draft.** A separate reviewer agent checks claims against the supplied sources, assesses relevance and writing, and inspects the rendered pages. Findings go back for revision.
5. **Review personally.** I review the resume, correct details and make the final editorial decisions before using it. Final approval stays with me.

## The career evidence library

The library organizes experience, accomplishments, dates and source records. Agents use it alongside the role research to decide which evidence belongs in a particular resume. Writing preferences and agent instructions are kept separate from career facts.

Tailoring changes selection, emphasis and wording. Claims still need support from the underlying evidence. Missing outcomes stay unknown, conflicting details need resolution, and a requirement in a job description does not become a candidate qualification.

## What I designed and refined

My work has focused on the decisions that make the workflow useful:

- Giving each agent a clear responsibility, required inputs and a reviewable output.
- Carrying both role requirements and company context through evidence mapping and writing.
- Keeping claims traceable to source material and asking focused questions when evidence is incomplete.
- Reviewing factual accuracy, editorial quality and the rendered layout as separate concerns.
- Using feedback to distinguish a correction to one resume from a reusable improvement to the workflow.

For example, company context became an explicit handoff into mapping and writing. Review also expanded beyond checking facts to checking whether the opening communicates the role's main need and whether the strongest supported contributions are easy to find.

These changes came from reviewing actual drafts and refining the responsibilities of the agents involved. Recorded decisions help preserve the reasons for changes; they do not, on their own, prove that a change improved the result.

## Scope and next steps

This README describes the workflow and my role in developing it. It does not provide a runnable demo or benchmark results. Agent review checks consistency with supplied evidence; personal review remains necessary.

Future additions may include a walkthrough using fictional candidate data, example agent handoffs, code and evaluations. For now, this page is the complete public release.
