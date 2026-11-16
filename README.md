# Design Portfolio Screening

A Codex skill for reviewing candidate design portfolios and making evidence-based next-round interview recommendations. It prioritizes actual visual quality and typography/layout over résumé breadth, project count, and polished case-study packaging.

## Use

Add this skill folder to the skills directory supported by your Codex-compatible agent, then invoke `$design-portfolio-screening` with the role brief and candidate portfolio files. For fair comparison, provide the same job requirements for all candidates. The skill can assess PDFs or image portfolios when the host can visually inspect them; it should state limitations when it cannot.

## Decisions

Each candidate receives one recommendation: `推进面试`, `备选`, or `不推进`, with concrete portfolio evidence, concerns, confidence, and interview verification points where applicable. The skill is decision support; hiring teams make final decisions.

## Files

- `SKILL.md` — workflow and output requirements
- `references/evaluation-rubric.md` — role assumptions, visual criteria, and decision gates


## Calibration note

The rubric is not a guarantee of reproducing a particular team's historical decisions. Organization-specific alignment requires testing against prior decisions; candidate identities and portfolio files should stay out of public repositories.

