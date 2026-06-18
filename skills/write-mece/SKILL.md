---
name: write-mece
description: Write, rewrite, review, and structure texts using MECE consulting logic. Use when Codex needs to create or improve Russian or English business artifacts such as task descriptions, Jira-style issues, technical requirements, ТЗ, product or feature descriptions, executive summaries, decision memos, project notes, decompositions, work breakdowns, documentation, or stakeholder-facing explanations; especially when the user asks for MECE, mutually exclusive collectively exhaustive structure, consulting-style writing, Pyramid Principle, issue trees, clear decomposition, concise task wording, acceptance criteria, or structured documents.
---

# Write MECE

## Core Workflow

Use this sequence for every artifact unless the user asks only for a tiny edit:

1. Define the governing question: what decision, task, or understanding must the reader get from the text?
2. State the answer first: put the main conclusion, requested action, or target outcome before supporting detail.
3. Choose one structure type: pyramid, issue tree, task card, requirements document, executive summary, decision memo, or work breakdown.
4. Make the first-level branches MECE: use one classification criterion per level, remove overlaps, close gaps, and avoid vague buckets such as "other" unless the scope explicitly requires them.
5. Write branches in parallel form: same abstraction level, same grammatical shape, comparable detail.
6. Check the output against the source: preserve user wording, numbers, scope, stakeholder framing, constraints, and arithmetic chains unless the user asks to change them.
7. Run a short quality gate before finalizing: answer-first, no duplicated points, no mixed levels, no hidden gaps, testable next steps where relevant.

## Consulting Writing Rules

- Prefer conclusion-first text over chronological narration.
- Build paragraphs and bullets as top-down pyramids: point first, evidence after.
- Use SCQ when the artifact needs framing: Situation, Complication, Question, then Answer.
- Use issue trees for decomposition: each tree answers exactly one "why", "how", or "what must be true" question.
- Keep each level based on a single split criterion, such as actor, workflow stage, cause category, component, option, risk type, or metric driver.
- Replace weak buckets with named categories. If a residual bucket is unavoidable, define its boundary explicitly.
- Separate facts, assumptions, decisions, open questions, and next actions instead of mixing them in one list.
- For stakeholder text, keep the user's tone and key phrases; improve structure without laundering away intent.

## Task And Requirement Rules

- For tasks, include outcome, context, in-scope work, out-of-scope boundaries, acceptance criteria, dependencies, risks or open questions, and next owner/action when known.
- For product descriptions, separate user problem, target users, proposed behavior, value, constraints, and success signals.
- For requirements, write observable behavior instead of vague intent. Prefer testable acceptance criteria.
- Use Given-When-Then for interaction scenarios and EARS-style clauses for precise system requirements when useful.
- Use INVEST as a backlog quality check: Independent, Negotiable, Valuable, Estimable, Small, Testable.
- Use SMART as a task/action quality check: Specific, Measurable, Achievable, Relevant, Time-boxed.

## Working With Missing Context

- Ask only when missing information materially changes the artifact, such as target audience, decision to support, hard scope boundary, or required format.
- If a reasonable default exists, proceed and state assumptions briefly.
- Do not add invented facts, dates, metrics, owners, or commitments. Mark them as placeholders or open questions.
- If the source material conflicts, preserve both sides and make the conflict explicit.

## Resource Selection

Read `references/artifact-patterns.md` when the user asks for a specific artifact type, a fuller template, a rewrite from rough notes, or a MECE review checklist.
