# Progress update editorial rules

## Fact ledger

| Field | Recording rule |
| --- | --- |
| Project and area | Use the primary project; split components without counting duplicate projects |
| Source and date | Include source text, relevant comments and confirmations; separate event and edit dates |
| Actual stage | State the achieved stage and coverage |
| Period changes | New capabilities, results, decisions or blockers since the prior report |
| Metrics | Period, unit, granularity, scope, baseline, sample and comparability |
| Next steps | Action, delivery or acceptance result, known date and owner |
| Risks and confirmation gaps | Impact, dependencies, evidence and unresolved conflicts |

Leave unsupported fields blank or mark them for confirmation. Do not infer owners
from roles or actual completion dates from release plans.

## From ledger to report

Prioritize this period's changes and actual stage; add only the background needed
to understand them. Reduce development schedules to current completions, blockers
and the next milestone. Do not reproduce long historical calendars.

Group by business, then business area and project. Merge product and technical
updates for the same capability within its project, preserving component states
and dependencies. Learn only the sample section the user specifies. Do not import
other businesses' sections, global stability chapters or unrelated target tables.
Preserve a technical area within its business when it is part of the supplied grouping.

Start a business with a brief metric update when supported. Use a two-column
Business area / Key progress table. Ordinary projects need background and progress.
For complex projects, add completed and remaining capabilities, customer tests,
results, next steps and risks only when the materials support them.

Continue tracking adoption, actual use, data quality and outcomes after release.
Without new updates, state that the stage is unchanged and outcomes remain
unverified when supported; avoid repeating full background.
Distinguish missing risk information from confirmed absence of a specific risk.

## Dates, status and scope

| Input | Report wording |
| --- | --- |
| Development complete, end-to-end testing ongoing | Testing; state remaining paths and planned date |
| Code deployed to a subset of users | Released, limited rollout; state scope |
| Release complete, actual use data missing | Released, outcomes pending verification |
| Some modules fully rolled out, others limited | State module-specific status rather than overall full rollout |
| Planned date passed without a completion record | Original plan overdue; actual result needs confirmation |
| Pause suggested but not confirmed | Decision pending, rather than paused |
| A later comment explicitly corrects one project date | Correct that date and retain other facts' original definitions |

## Metrics and conclusions

Attainment = current cumulative value / target with the same definition.
Relative change = (current value − baseline) / baseline.
Subtracting two rates gives a percentage-point difference; dividing the difference
by the baseline rate gives relative change. Multiply these ratios by 100 when
expressing them as percentages. Do not calculate relative change with a zero
baseline or incompatible definitions.
Do not calculate attainment when the target is zero or missing; report the
supplied values and identify the undefined calculation.

For multiple customers, subcases or test pairs, distinguish recruitment,
configuration, actual use, comparable testing and final outcome reporting.
Upstream funnel completion counts are not automatically valid sample counts.
Describe observational data as observed. Note when configuration, sample or
traffic differences prevent attribution.

Use the agreed statistical standard. When the standard, sample size or test is
missing, report direction and limits only. Expected direction alone does not
establish success.

## De-identification

Extract structures and decision rules; do not store original reports or source
excerpts. Remove organizations, brands, internal abbreviations, real project names,
people, customers, private domains, accounts or tokens, distinctive geographic
combinations, financial values, precise plans and image metadata.
Use clearly marked, independently fictional examples.

Temporary sources belong only to the current task. For de-identified reports,
establish consistent generic labels, then check titles, tables, links, image
captions, attachment names and hidden references.
