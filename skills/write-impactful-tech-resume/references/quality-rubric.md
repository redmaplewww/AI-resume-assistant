# Technical resume quality rubric

Score each dimension from 0 to 4. Report evidence for every score and prioritize fixes that improve both relevance and credibility.

## Table of contents

- Scoring dimensions
- Interpretation
- Red flags
- Final editing pass

## Scoring dimensions

| Dimension | 0 | 2 | 4 |
|---|---|---|---|
| Target clarity | Target is unclear | Role is inferable | Role, seniority, and application/infra/algorithm lane are immediately clear |
| Relevance | Mostly unrelated detail | Mixed relevance | Strongest target-role evidence leads |
| Ownership | Contribution is obscured | Some ownership verbs | Individual and team ownership are precise |
| Technical depth | Technology names only | Some mechanisms | User need, constraints, decisions, mechanisms, and tradeoffs form a coherent chain |
| Impact | Duties only | Some outcomes | Results are quantified or otherwise validated |
| Metric integrity | Unsupported or contradictory | Plausible but underspecified | Baselines, units, conditions, and attribution are defensible |
| Structure | Legacy template controls the story | Generally readable | User-designed hierarchy reflects target evidence and project importance |
| Concision | Repetitive, generic, or mechanically uniform | Minor redundancy or model-like phrasing | Every line earns space and sounds individually defensible |
| Consistency | Dates/terms/style conflict | Minor issues | Dates, tense, units, punctuation, and naming are consistent |
| Interview defensibility | Claims invite credibility concerns | Most claims explainable | Every major claim supports a credible deep dive |

Maximum score: 40.

## Interpretation

- 34–40: strong; tailor and polish.
- 27–33: credible but uneven; strengthen positioning, evidence, or compression.
- 19–26: duty-heavy or generic; rebuild major sections from an evidence ledger.
- 0–18: unreliable or poorly targeted; re-establish facts and structure before line editing.

Do not treat the total as scientific. A score of 0 in metric integrity or interview defensibility is a release blocker even when the total is high.

Before scoring credibility, read [anti-patterns.md](anti-patterns.md). Keep job mismatch out of the integrity score unless the resume falsely relabels the background. Do not lower technical-resume quality because of protected characteristics, school prestige alone, email provider, photo style, or missing salary expectations.

## Red flags

- Numbers with no unit, baseline, denominator, condition, or plausible measurement path.
- Percentage improvements whose before/after values do not match.
- “主导” repeated for work described elsewhere as participation.
- Individual credit for organization-wide results without an attribution boundary.
- A technology stack longer than the evidence demonstrating its use.
- Dense paragraphs containing architecture, implementation, operations, and impact with no hierarchy.
- Generic claims: “提升效率”, “保障质量”, “效果显著”, “熟悉各种”.
- Unsupported superlatives: first, only, leading, core, expert, industry-best.
- Dates that overlap without explaining concurrent projects or internal transfers.
- Public links, rankings, awards, or repository statistics that cannot be verified or dated.
- Confidential customer names, internal identifiers, security details, or proprietary metrics.
- Project openings that reveal only a framework or architecture, not the user task and unmet need.
- Role portfolios that mix application, infrastructure, and algorithm claims without a dominant hiring thesis.
- Improvements measured against an unusable zero baseline rather than a fair comparison or defined final attainment.
- Final text that cannot be traced to user-written content or a user-confirmed local edit.
- A new resume that preserves the old section order, project grouping, or bullet boundaries without an explicit reason.
- Repeated cadence, identical subheadings, uniform bullet length, or the same problem-solution-result template across projects.
- Generic abstraction and JD keyword stitching that erase the user's technical vocabulary and distinctive incidents.

Classify these as signals, not automatic proof. Escalate to high risk only under the evidence standard in [anti-patterns.md](anti-patterns.md).

## Final editing pass

1. Read only project titles and opening lines; verify that the user task, need, dominant role lane, and career story are coherent.
2. Circle every ownership verb; verify its factual strength.
3. Underline every metric; verify definition, arithmetic, condition, and attribution.
4. Highlight every technology name; remove names that do not explain a decision or satisfy role searchability.
5. Remove duplicated claims and filler adjectives.
6. Normalize dates, punctuation, units, capitalization, and Chinese/English spacing.
7. Check that the document is ATS-readable: simple headings, selectable text, no critical content in images, and no reliance on icons alone.
8. Generate interview probes for the three strongest bullets; weaken or qualify any claim the candidate cannot defend.
9. Verify authorship provenance for every final line before PDF generation.
10. Verify the user designed the reconstructed framework and that no legacy structure was inherited by default.
11. Read representative lines aloud; return wording the user would not naturally explain to the coaching loop.
