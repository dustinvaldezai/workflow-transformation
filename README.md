# Workflow Transformation

AI-assisted research workflow for faster synthesis, verification, and human-reviewed decision support.

## The problem

Research-heavy work can become slow, repetitive, and difficult to synthesize consistently when teams are working across many documents, notes, and qualitative inputs.

This project explores a structured AI-assisted workflow for reducing that manual burden while preserving human judgment and verification.

## What the system does

The workflow separates the work into distinct stages:

1. Source intake
2. Structured extraction
3. Thematic classification
4. Evidence validation
5. Synthesis
6. Human review
7. Decision-ready output

The goal is not to automate judgment. The goal is to make the research process faster, more consistent, and easier to review.

## Why I built it this way

I wanted to avoid one large prompt trying to do everything at once.

Breaking the workflow into stages makes it easier to:

- inspect intermediate outputs
- catch errors earlier
- verify claims against source material
- preserve human review where interpretation matters
- improve one part of the workflow without rebuilding the entire system

## Human review

Human review remains a required part of the system.

AI can help extract, organize, and synthesize information, but a person still reviews evidence, checks conclusions, and decides what is important enough to use.

## What I learned

The strongest results came from treating AI as part of a workflow rather than as a single answer engine.

Reliability improved when the system used clear stages, structured outputs, and explicit review checkpoints.

## What to inspect first

If you are reviewing this as a portfolio project, start here:

1. [Workflow architecture](./docs/architecture.md) — how the stages connect and where human review can send work back for revision.
2. [Synthetic source input](./examples/sample-source.md) — a small fictional research set used to demonstrate the workflow.
3. [Synthetic structured output](./examples/sample-structured-output.md) — how that source material becomes traceable claims, themes, open questions, and a draft synthesis.
4. [Verification checklist](./docs/verification-checklist.md) — the checks used before an output is treated as decision-ready.

## Repository map

### `docs/`

- [Workflow overview](./docs/workflow-overview.md)
- [Workflow architecture](./docs/architecture.md)
- [Verification checklist](./docs/verification-checklist.md)

### `prompts/`

- [Structured extraction](./prompts/structured-extraction.md)
- [Thematic classification](./prompts/thematic-classification.md)
- [Synthesis](./prompts/synthesis.md)

### `examples/`

- [Synthetic source input](./examples/sample-source.md)
- [Synthetic structured output](./examples/sample-structured-output.md)
- [Full workshop walkthrough](./examples/synthetic-workshop-research.md)

## Scope

This repository is a public, sanitized portfolio demonstration. The example material is synthetic, and the workflow is presented to show the system design, review logic, and decision process without exposing confidential source material.
