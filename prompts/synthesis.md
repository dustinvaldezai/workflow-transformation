# Synthesis Prompt

Use this only after extraction, classification, and evidence validation are complete.

## Prompt

Create a concise research synthesis using only the validated claims provided.

Requirements:

1. Lead with the most decision-relevant finding.
2. Group supporting evidence by theme rather than by source order.
3. Preserve uncertainty, disagreement, and unresolved questions.
4. Distinguish clearly between:
   - supported findings
   - interpretation
   - proposed next actions
5. Do not introduce new facts, metrics, or causal claims.
6. If evidence is insufficient for a conclusion, say what is missing instead of guessing.
7. Include the relevant claim IDs beside major findings so a reviewer can trace them back to evidence.

Return:

- Key finding
- Supporting themes and evidence
- Conflicts or uncertainty
- Open questions
- Proposed next actions, if warranted by the evidence
- Human-review status: Pending

## Output principle

The synthesis should reduce reading load without hiding uncertainty. It is a draft for human review, not an autonomous decision.
