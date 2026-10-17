---
name: maintain-skill-library
description: Maintain curated skill links and personal skills. Use when adding GitHub skill references, editing categories, or creating custom skills in this repository.
---

# Maintain Skill Library

Read [the maintenance rules](references/maintenance.md), then inspect `CONTRIBUTING.md`.

1. Identify whether the task changes third-party references or personal instructions.
2. For third-party additions, read the original skill and current upstream README.
   Update both README languages with its category, source link, source label and
   purpose. Keep dependency instructions upstream. Point normal links to the default branch.
3. Mark deprecated sources as historical and provide the migration destination.
   Treat source stars and reviewed commits as dated research, not live rankings
   or installation locks.
4. For local authoring, create `skills/<name>/SKILL.md` using the minimal example
   in `docs/skill-authoring.md`.
   Add only specialized procedures and needed resources. Explicitly register the
   skill under its README category with Source set to This repository.
   Record draft/evaluation status in the skill's references.
5. Keep host installation separate from source directories. Repository maintenance
   workflows share `skills/<name>/` with personal skills, independent of host roots.
   Keep private source documents and organization information out of skill instructions,
   templates and evaluation examples. Retain only reusable abstractions.
   Write repository-owned content in English except the Chinese README translation.
6. Check changed local links, source paths and personal skill frontmatter. Evaluate
   new procedures in representative tasks, and run `git diff --check`.

Do not copy third-party skills, add synchronization systems or require Python for
catalog maintenance. Preserve user authorization for external actions. Do not
claim task evaluation passed when only document structure was checked.
