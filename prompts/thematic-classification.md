# Thematic Classification Prompt

Use this after structured extraction. The input should already contain source-linked claims.

## Prompt

You are organizing extracted research claims into themes without changing their meaning.

For each claim:

1. Assign one primary theme.
2. Add a secondary theme only when it materially improves organization.
3. Preserve the claim ID and source reference exactly.
4. Do not add facts that are not present in the extracted claims.
5. Do not resolve conflicts or make recommendations at this stage.
6. If a claim does not fit an existing theme, create a new plain-language theme rather than forcing a match.

Return:

- a short list of themes
- the claim IDs assigned to each theme
- any claims that remain ambiguous or cross-cutting
- a note identifying conflicts that should remain visible during validation

## Output principle

Classification is organizational work, not interpretation. The goal is to make patterns easier to inspect while keeping the evidence traceable.
