# Private Pool Search Workflow

This workflow defines how a private SC64 Member Network Agent should prioritize trusted, approved sources before broader market expansion.

## Search Mode 1: Private Pool Search

Private Pool Search looks first at member-approved and SC64-reviewed records.

Examples:

- approved target companies
- approved people and relationship paths
- known recruiters or search partners
- trusted groups and communities
- member-provided notes
- approved CRM, spreadsheet, or workspace records

## Search Mode 2: Open Market Expansion

Open Market Expansion is used only when the private pool does not answer the question well enough.

Any open-market result should be marked as:

- AI-suggested
- unverified
- needs human review
- not yet part of the trusted pool

## Guardrails

The agent should not:

- scrape private sources without approval
- expose private relationship data publicly
- message anyone without explicit approval
- treat AI-suggested data as verified
- add people to the trusted pool without review

## Output

A private-pool search should produce:

- the best trusted matches
- why each match matters
- what signal triggered the recommendation
- confidence level
- recommended next step
- whether human approval is required

