# Maintenance rules

- `README.md` is the single registration point for all skills.
  Keep source and purpose; installation requirements stay upstream.
  Maintain the matching Chinese translation without creating local third-party SKILL.md.
- Order the primary categories by work stage: research, requirements, architecture
  and planning, implementation, verification, delivery, and knowledge retention.
  Keep Agent orchestration separate from skill authoring and library maintenance.
  Give each skill one primary category and order related entries by their usual
  use within that stage. Explain cross-stage uses and alternatives in brief notes.
  Change categories intentionally and keep both README languages aligned.
- `docs/source-repositories.md` and `docs/research/` preserve dated research evidence. Reviewed
  commits are historical references, not versions that require synchronization.
- Update broken paths, migration destinations and outdated purpose descriptions.
  Skill contents and installed copies are updated outside this curated directory.
- Register every skill in the README category tables with an explicit Source.
  For this repository's skills, retain task evaluation status in skill references.
  Category changes do not move or duplicate source directories.
- All local skills live directly in `skills/<name>/`, including maintenance skills. Source directories
  must remain independent of the host Agent's installation and discovery paths.
- Learn patterns from private inputs without saving company identifiers, internal
  URLs, people, customers, real metrics or project timelines in reusable skill files.
- Use draft status until positive, negative and missing-dependency tasks are reviewed.
- Write repository-owned documentation, skills and templates in English except
  `README.zh-CN.md`, which translates the default English catalog.
- Original work uses the repository license. Third-party adaptations require their
  source attribution and applicable license.
- No runtime, generated catalog, vendor directory, lockfile or build pipeline is
  required. Check Markdown references and Git whitespace differences before delivery.

## Evaluation record

Draft. Repository documentation and structure have been checked.
Independent positive, negative and missing-dependency Agent tasks have not been evaluated.
