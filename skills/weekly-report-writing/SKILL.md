---
name: weekly-report-writing
description: Turn progress updates into weekly or biweekly meeting reports. Use when writing periodic reports or consolidating project updates. Do not use for meeting transcripts or PRDs.
---

# Weekly Report Writing

Organize updates by business → business area → project. Consolidate product,
engineering, testing and outcome information under the corresponding project.
Write in the user's language. Help readers assess this period's changes, actual
stage, evidence strength, next steps and decisions needed.

## Inputs and scope

1. Read supplied report samples, the period, latest updates and the prior report.
   Samples establish structure and style, not current facts. If the user specifies
   a reference section, learn only that section.
2. Accept text, files or accessible document links. Use existing document-reading
   capabilities without binding the skill to a platform, account or tool name.
   Ask only for essential missing material that affects conclusions.
3. Use the sample as a layout baseline and updates as factual evidence. Read
   relevant comments for date corrections, challenges and confirmations.
   Unconfirmed discussions do not establish decisions.
4. Identify start and end dates, information cutoff, covered projects and audience.
   Mark unknown fields for confirmation. Distinguish this period, current status,
   cumulative values and historical context. Exclude post-cutoff facts from this period.

## Consolidation

Follow the [editorial rules](references/editorial-rules.md) to build a temporary
fact ledger with project, source date, actual stage, changes, metric definitions,
blockers, next steps and evidence. Use it for checking; do not include it in the
report by default or store it in reusable skill sources.

- Merge duplicate updates across teams, stages and sections under the primary project.
- Resolve recency through event dates and explicit confirmations, not document edit dates alone.
- Apply clear, newer confirmations to outdated progress. Flag unresolved conflicts;
  do not choose a value without evidence.
- Compress unchanged reviews and development schedules into background. Continue
  post-release tracking when outcomes remain unverified.
- Summarize the problem and value briefly, then present current progress. Avoid
  organizing the report as a chronology of people or messages.

## Report organization

Use the [report template](assets/report-template.md), removing optional fields
according to the supplied sample. Keep the user's established business order and
grouping. Take business and area names from current inputs.

1. **Business metrics**: At the start of the relevant business, briefly state
   target, cumulative result, attainment and elapsed time when reliable data exists.
   Omit this field when unsupported; do not create a global metrics table.
2. **Business areas and projects**: Group projects by the user's areas within each
   business. Default to a two-column table, Business area / Key progress.
   One area may contain several projects. Use headings and short lists for long
   projects instead of crowding nested content into a wide table.
3. **Project content**:
   - Project name and actual status; handle supplied project links according to output requirements.
   - Background: the problem and period scope, usually one or two sentences.
   - Key progress: usually two to four items, emphasizing actual changes, stage and results.
   - Next steps: action, acceptance result and known target date. Include owners only when supplied.
   - Risks or decisions: facts, impact and dependencies when present. Do not fill unsupported fields with "no risk."
4. **Customer testing and results**: Keep these within the corresponding project.
   Distinguish recruitment, configuration, actual use, completed tests and comparable
   results. State conclusions and observation limits.
5. **Technical work**: Place it under the business and project it serves. Preserve
   a technical area only when the user's grouping includes one. State the scope of
   shared capabilities without automatically adding a separate stability chapter.

For ordinary projects, Background / Key progress is sufficient. Add next steps,
test results or risks only when supported. Complex projects may separate completed
capabilities, remaining capabilities, results and next steps. State each component's
stage so one overall status does not hide unfinished work.

Do not append a global overview, risk register or action table by default.
Keep unrelated content within its own business.

## Status, metrics and conclusions

- Distinguish not started, in progress, dependency pending, delayed, released,
  limited rollout, full rollout and paused. Ready for testing, a successful demo
  and a planned launch do not mean released. Code deployment does not mean full rollout.
- Distinguish planned, actual and observation dates. Flag overdue plans without
  completion evidence. Convert relative dates only when their reference date is reliable.
- Include metric period, granularity, scope, unit and comparison baseline. Do not
  mix aggregate and subcase metrics, customer and test-group counts, attribution
  definitions or different rollout scopes.
- Calculate attainment, growth or target gaps only with complete, comparable inputs.
  Label derived values. Distinguish percentages from percentage points.
  Do not invent benefits, owners, ETAs or statistical significance.
- Observed improvement does not establish experimental benefit. Proxy improvement
  does not establish final business outcomes. State limits from missing outcome
  reporting, controls, comparable samples or statistical evidence; retain hypotheses as hypotheses.
- Decisions such as paused, stopped, accepted or significantly positive require
  explicit sources. Do not inherit unsupported conclusions from a sample.

## De-identification and output

Deliver usable Markdown with necessary confirmation items. Honor specified formats
and file requests. External document writing or publication requires authorization.

Reusable skill instructions, templates, references and evaluation materials must
exclude organization names, private business codes, real people or customers,
private links or tokens, screenshots, actual financial data and internal roadmaps.
Apply the same exclusions to reports when the user requests de-identification.
For ordinary tasks, use source materials within the specified audience and authorization;
do not copy them into the skill library or long-term memory.

Use abstractions such as Project A, dependency team and customer sample. Do not
recreate real project combinations, exact metrics or timelines by merely renaming
them. State when images could not be verified; never infer their values.

## Delivery check

Apply the [evaluation criteria](references/evaluation.md): traceable facts,
consistent dates and stages, comparable metrics, merged duplicates, actionable
steps, clear risks and confirmation gaps, and appropriate de-identification.
Deliver the report directly after checking. Keep internal consolidation procedures
and lengthy writing-process explanations out of the report.
