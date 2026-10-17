# Skill authoring

## Create and register

Create `skills/<name>/SKILL.md` using the minimal example below.
Write task-specific instructions without imposing a fixed body structure.
Register the skill in the relevant category of the
[README catalog](../README.md#skill-catalog). Set Source to This repository
and record its evaluation status in the skill's references.

```text
skill-name/
├── SKILL.md
├── references/   # Long material loaded when needed
├── scripts/      # Necessary repeatable, deterministic operations
└── assets/       # Output templates and static resources
```

Create optional folders only when needed. Authoring requires no registration
script or Python environment. A task-specific script may use the language its task requires.

## Format and content

Start `SKILL.md` with YAML frontmatter:

```markdown
---
name: api-contract-review
description: Review API contracts. Use when assessing compatibility or interface changes. Do not use for general code review.
---

Review the supplied API changes for compatibility with existing consumers.
Identify breaking changes and cite the affected contract or usage.
```

Use 1–64 lowercase letters, digits and single hyphens for the name, matching
the parent folder. Begin and end with a letter or digit; avoid consecutive hyphens.
The description states what the skill does, when to invoke it and where it does
not apply. Prefer a single unquoted line; avoid colon-space YAML ambiguity.

Write instructions in English and keep the main body well under 500 lines.
Describe specific inputs, specialized steps, outputs and failure handling.
Link long material in `references/` through relative paths. Focus on personal
contracts, decision rules, fixed output formats and reliable procedures.

## Evaluation

| Scenario | What to verify |
| --- | --- |
| Positive task | Correct invocation and the required result |
| Adjacent negative task | No inappropriate invocation or intervention |
| Missing tools or inputs | Accurate limits and continued independent progress |

Start with Draft status in the skill's evaluation reference. After actual Agent task
evaluation, record Evaluated status, the host, task scope and date there. Structure checks
alone do not establish task quality. Run any new or changed script once and
record its result.

## Installation and source handling

Install the evaluated skill folder according to host instructions. Personal and
maintenance sources both live in `skills/<name>/`; installation paths are separate.

Extract abstract rules and generic templates from work materials. Exclude
organizations, private project codes, real people or customers, internal links and
actual data. Clearly mark evaluation inputs as independently fictional; replacing
names in a real source is insufficient.

Keep third-party skills as upstream references. Any separately authorized adaptation
must record its source, license, Before/After and validation scope; upstream license
obligations do not become MIT automatically.

Format reference: [Agent Skills specification](https://agentskills.io/specification).
Tool and installation support depend on the Agent's current documentation.
