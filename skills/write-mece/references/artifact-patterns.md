# Artifact Patterns

Use these patterns as compact starting points. Adapt headings to the user's requested language, audience, and level of formality.

## MECE Quality Gate

- Governing question: the text answers one clear reader question.
- Answer-first: the first sentence or section gives the main point.
- Mutually exclusive: sibling bullets do not repeat, overlap, or use different split criteria.
- Collectively exhaustive: the structure covers the stated scope without hidden gaps.
- Same level: sibling items have comparable abstraction and detail.
- Parallel wording: headings and bullets use the same grammatical shape.
- Source fidelity: numbers, scope, stakeholder wording, and constraints are preserved.
- Actionability: tasks and requirements have observable acceptance criteria or next steps.

## Task Or Jira-Style Issue

```markdown
# [Outcome-oriented title]

## Goal
[What must become true and why it matters.]

## Context
[Facts, source request, business/user reason, links if provided.]

## Scope
- [In-scope work item 1]
- [In-scope work item 2]
- [In-scope work item 3]

## Out Of Scope
- [Explicit boundary 1]
- [Explicit boundary 2]

## Acceptance Criteria
- [Observable result or behavior]
- [Edge case or constraint]
- [Verification method]

## Dependencies
- [People, systems, data, decisions, or blockers]

## Open Questions
- [Only questions that block implementation or acceptance]
```

Quality checks:
- Title names the outcome, not only the activity.
- Acceptance criteria are testable by inspection, command, demo, or metric.
- Dependencies are not mixed with scope.

## Feature Or Product Description

```markdown
# [Feature name]

## Summary
[Answer-first description of what changes for whom.]

## User Problem
[Target user, pain, current workaround, impact.]

## Proposed Behavior
- [User-visible behavior]
- [System behavior]
- [Admin/operator behavior if relevant]

## Value
- User value: [specific benefit]
- Business value: [specific benefit]
- Operational value: [specific benefit, if relevant]

## Constraints
- [Technical, product, legal, pricing, timeline, or rollout constraint]

## Success Signals
- [Metric or qualitative signal]
- [Guardrail or balancing signal]
```

Quality checks:
- Do not mix problem, solution, and success metric in one paragraph.
- Keep user groups mutually exclusive when listing audiences.
- Preserve explicit non-goals.

## Technical Requirements Or TZ

```markdown
# [Document title]

## Objective
[Decision or implementation outcome this document enables.]

## Current State
[Relevant current behavior, data, process, or limitation.]

## Target State
[Desired behavior and boundaries.]

## Functional Requirements
- [The system/user can...]
- [The system/user can...]

## Non-Functional Requirements
- Performance: [requirement or open question]
- Reliability: [requirement or open question]
- Security/privacy: [requirement or open question]
- Observability/support: [requirement or open question]

## Acceptance Criteria
- Given [context], when [action/event], then [observable result].
- While [state], when [trigger], the system shall [required response].

## Risks And Dependencies
- [Risk/dependency and impact]

## Open Questions
- [Question and why it matters]
```

Quality checks:
- Functional and non-functional requirements are separate.
- Requirements describe observable behavior.
- Acceptance criteria can be verified without interpreting intent.

## Executive Summary

```markdown
# [Topic]

## Bottom Line
[One to three sentences with the conclusion, recommendation, or status.]

## Why It Matters
- [Impact 1]
- [Impact 2]
- [Impact 3]

## Evidence
- [Fact, number, example, or source]
- [Fact, number, example, or source]

## Decision Or Ask
[What the reader should approve, decide, do, or understand next.]

## Caveats
- [Material uncertainty, dependency, or limitation]
```

Quality checks:
- Put recommendation before analysis.
- Keep caveats material; do not dilute the answer with minor disclaimers.
- Separate evidence from interpretation.

## Issue Tree Or Decomposition

```markdown
# Governing Question
[What must be explained or solved?]

## Branch 1: [Criterion-consistent category]
- [Sub-issue]
- [Sub-issue]

## Branch 2: [Criterion-consistent category]
- [Sub-issue]
- [Sub-issue]

## Branch 3: [Criterion-consistent category]
- [Sub-issue]
- [Sub-issue]
```

Quality checks:
- Every branch answers the same question type.
- Each level uses one split criterion.
- Branch labels are explanatory, not generic buckets.
- Stop decomposing when items are actionable or testable.

## Decision Memo Or Options Analysis

```markdown
# Decision: [Decision to make]

## Recommendation
[Chosen option and reason.]

## Decision Criteria
- [Criterion 1]
- [Criterion 2]
- [Criterion 3]

## Options
| Option | Fit To Criteria | Upside | Risk | Effort |
| --- | --- | --- | --- | --- |
| [A] | [Assessment] | [Upside] | [Risk] | [Effort] |
| [B] | [Assessment] | [Upside] | [Risk] | [Effort] |
| [C] | [Assessment] | [Upside] | [Risk] | [Effort] |

## Rationale
[Why the recommendation wins against the stated criteria.]

## Next Steps
- [Action, owner if known, timing if known]
```

Quality checks:
- Criteria are defined before options are judged.
- Options are genuinely distinct.
- Recommendation is not hidden after the comparison.

## Source-Backed Practice Notes

- Pyramid Principle: use a top-down answer, supporting groups, and reader-question logic. Reference: https://www.barbaraminto.com/
- Inverted pyramid: put the most important information first for faster scanning. Reference: https://www.nngroup.com/articles/inverted-pyramid/
- User stories and acceptance criteria: use story conversations and conditions of satisfaction. Reference: https://www.atlassian.com/agile/project-management/user-stories
- INVEST and SMART: use as quality checks for backlog stories and tasks. Reference: https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/
- EARS: use constrained requirement syntax when precision matters. Reference: https://alistairmavin.com/ears/
