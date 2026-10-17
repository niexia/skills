# Contribution guidelines

Keep `README.md` as the default English catalog and update its Chinese translation
in `README.zh-CN.md` alongside catalog changes. Preserve matching categories,
entries, source links and purposes.

The README is the skill registry; `skills/<name>/` contains portable source files.
`docs/skill-authoring.md` covers authoring, while `docs/source-repositories.md`
and dated files in `docs/research/` preserve historical discovery evidence.
Installation and updates to installed copies belong to their host environments.

## Third-party references

Edit `README.md` directly. Every entry needs the original GitHub skill folder,
a source label and short purpose. Choose one primary category.
Skills with similar names may coexist when their workflows differ; explain the difference.

1. Read the author's current `SKILL.md` and documentation. Verify the path and maintenance status.
2. Link normal entries to the skill folder on the upstream default branch.
3. Read dependency requirements and follow current upstream installation instructions.
   Keep those requirements upstream rather than duplicating them in the catalog.
4. Mark deprecated sources as historical and provide a migration destination.
   Use a commit link when needed to preserve a historical example.
5. Register new repositories in `docs/source-repositories.md`. Date any stars snapshot;
   continuous refresh is not required.
   Preserve collection dates and query scope; reviewed commits are historical
   evidence rather than installation locks.

Keep third-party content upstream. Source references do not require a full license
copy here; users must still read the applicable license when installing or adapting content.

## Local skills

Use the minimal example in `docs/skill-authoring.md` and put specialized procedures in
`skills/<name>/SKILL.md`. Match the name to its parent folder and explicitly
register category, source and purpose in `README.md`. Record status and evaluation
scope in the skill's references.

Personal workflows and repository maintenance skills share this flat root.
Keep source folders independent of host installation paths.
Start with Draft status; use Evaluated only after actual Agent task evaluation.
Any proposed adaptation must identify its source and applicable license; this
library curates third-party references rather than copied skill definitions.

When learning from work materials, retain only generic structures, rules and
independently fictional scenarios. Exclude organizations, private project codes,
real people or customers, internal links and actual data from reusable skill materials.
Write repository-owned content in English except `README.zh-CN.md`.

## Submission and checks

- Check local Markdown paths and new or changed external source links.
- Check skill frontmatter, relative resources and relevant task examples.
- Run new or changed task-specific scripts once if any are introduced.
- Run `git diff --check`; curation requires no build, Python or dependency installation.
- Explain the purpose, Before/After and validation results.

Restore repository documents or local skills through Git. Restore installed
third-party copies in their actual host environment.
