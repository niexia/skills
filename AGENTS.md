# Repository conventions

- Read `CONTRIBUTING.md` before changing the library.
- Maintain third-party references directly in `README.md`. Link to original
  source folders and explain purpose. Keep installation requirements upstream and
  identify deprecated sources as historical.
- Do not copy or redefine third-party skills in this repository. Do not introduce
  source synchronization, version locks, package managers or build tools for curation.
- Keep source stars and reviewed commits as dated historical research only.
  Ordinary skill links point to the upstream default branch.
- Put all local skills in `skills/<name>/` and explicitly register their category,
  source and purpose in `README.md`. Keep evaluation status in skill references.
  Do not duplicate folders by category.
- Keep personal workflows and repository maintenance skills in the same flat root.
  Keep all skill sources independent of host-specific hidden directories.
- Skill sources, templates and examples must contain no organization identifiers,
  private source URLs, real personnel or customers, internal project codes or data.
  Learn reusable writing patterns without saving private source documents here.
- Use the minimal example in `docs/skill-authoring.md` for authoring. Distinguish drafts from
  skills evaluated in actual Agent tasks; structure checks do not prove behavior.
- Write repository-owned documentation, skill instructions and templates in English.
  `README.zh-CN.md` is the Chinese translation of the default `README.md`; keep
  category order, skill entries, sources and links aligned, with language links in both.
- Check local Markdown links, changed source links, skill metadata and relevant
  task examples. Run `git diff --check`. No Python or build step is required.
- Keep temporary research and intermediate scripts outside the repository.
- Third-party installations and updates belong to their actual host environments.
- External publication, messaging or deployment requires user authorization.
