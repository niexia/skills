# Skills for Engineers

**English** · [简体中文](README.zh-CN.md)

[Authoring](docs/skill-authoring.md) ·
[Source repositories](docs/source-repositories.md) · [Contributing](CONTRIBUTING.md)

## Skill catalog

- [Research and data analysis](#research)
- [Goals and requirements](#product)
- [Architecture and implementation planning](#architecture)
- [Engineering and code quality](#engineering)
- [Frontend design and implementation](#frontend)
- [Testing, diagnosis and review](#testing)
- [Security and auditing](#security)
- [CI and delivery](#delivery)
- [Documents and reporting](#documents)
- [Content and growth](#marketing)
- [Knowledge management and productivity](#knowledge)
- [Agent context and orchestration](#orchestration)
- [Skill authoring and library maintenance](#meta)

Browse in work order: gather evidence → clarify goals → design and plan →
implement → verify and review → deliver → document and retain knowledge.
Each skill has one primary category. Security, documentation and Agent
orchestration also apply throughout the work.

Choose a main skill for the current task, then add supporting skills as needed.
The sequences below are suggested routes, not mandatory pipelines; skip stages
that already have sufficient inputs.

| Task | Suggested route |
| --- | --- |
| New feature | `brainstorming` → `writing-plans` → implementation → `verification-before-completion` |
| Architecture change | `improve-codebase-architecture` → `api-and-interface-design` → `writing-plans` → implementation and verification |
| Bug investigation | `systematic-debugging` → fix and regression checks → `verification-before-completion` |
| Frontend work | `frontend-design` → `frontend-ui-engineering` → `webapp-testing` → `web-design-guidelines` |
| Weekly report | Progress evidence → `weekly-report-writing` → document format if needed |

<a id="research"></a>
### Research and data analysis

Gather evidence before choosing a direction. Spreadsheet analysis is under
[Documents and reporting](#documents).

| Skill | Source | Purpose |
| --- | --- | --- |
| [last30days](https://github.com/mvanhorn/last30days-skill/tree/main/skills/last30days) | mvanhorn/last30days-skill | Research discussions from the last 30 days across platforms. |
| [literature-review](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/literature-review) | K-Dense-AI/scientific-agent-skills | Search and synthesize academic literature. |

<a id="product"></a>
### Goals and requirements

Clarify the problem and tradeoffs, prioritize outcomes, then record requirements.
Use a PRD for product requirements or a specification for engineering behavior.

| Skill | Source | Purpose |
| --- | --- | --- |
| [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) | obra/superpowers | Clarify requirements and design scope. |
| [grilling](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) | mattpocock/skills | Test design assumptions and tradeoffs through decision-tree interviews. |
| [prioritize-features](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/prioritize-features) | phuryn/pm-skills | Assess feature value and priority. |
| [outcome-roadmap](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/outcome-roadmap) | phuryn/pm-skills | Organize roadmaps around business outcomes. |
| [create-prd](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/create-prd) | phuryn/pm-skills | Write concise PRDs that support decisions. |
| [to-spec](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-spec) | mattpocock/skills | Turn discussions into specifications. |

<a id="architecture"></a>
### Architecture and implementation planning

Define boundaries and contracts, record decisions, then plan implementation or
split the specification into tickets.

| Skill | Source | Purpose |
| --- | --- | --- |
| [domain-modeling](https://github.com/mattpocock/skills/tree/main/skills/engineering/domain-modeling) | mattpocock/skills | Define domain vocabulary and models. |
| [codebase-design](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design) | mattpocock/skills | Establish vocabulary for module depth and interface design. |
| [improve-codebase-architecture](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | mattpocock/skills | Identify architectural friction and opportunities to deepen modules. |
| [api-and-interface-design](https://github.com/addyosmani/agent-skills/tree/main/skills/api-and-interface-design) | addyosmani/agent-skills | Design stable APIs and interface contracts. |
| [deprecation-and-migration](https://github.com/addyosmani/agent-skills/tree/main/skills/deprecation-and-migration) | addyosmani/agent-skills | Plan compatible migrations and deprecation. |
| [documentation-and-adrs](https://github.com/addyosmani/agent-skills/tree/main/skills/documentation-and-adrs) | addyosmani/agent-skills | Write architecture decisions and technical documentation. |
| [writing-plans](https://github.com/obra/superpowers/tree/main/skills/writing-plans) | obra/superpowers | Write executable implementation plans. |
| [to-tickets](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-tickets) | mattpocock/skills | Break specifications into tasks. |

<a id="engineering"></a>
### Engineering and code quality

Apply coding constraints, implement behavior, then simplify and optimize when
needed. The two TDD entries offer alternative workflows; choose one for a task.

| Skill | Source | Purpose |
| --- | --- | --- |
| [coding-standards](https://github.com/affaan-m/ECC/tree/main/skills/coding-standards) | affaan-m/ECC | Apply coding standards in Agent engineering projects. |
| [karpathy-guidelines](https://github.com/multica-ai/andrej-karpathy-skills/tree/main/skills/karpathy-guidelines) | multica-ai/andrej-karpathy-skills | Avoid overengineering and define verifiable minimal changes. |
| [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) | obra/superpowers | Implement behavior through test-driven development. |
| [tdd](https://github.com/mattpocock/skills/tree/main/skills/engineering/tdd) | mattpocock/skills | Practice TDD around module interfaces. |
| [mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) | anthropics/skills | Build MCP servers and API integrations. |
| [code-simplification](https://github.com/addyosmani/agent-skills/tree/main/skills/code-simplification) | addyosmani/agent-skills | Reduce code complexity. |
| [performance-optimization](https://github.com/addyosmani/agent-skills/tree/main/skills/performance-optimization) | addyosmani/agent-skills | Improve performance through measurement. |

<a id="frontend"></a>
### Frontend design and implementation

Choose a visual direction, design components, implement interactions, then tune
performance. UI review and browser testing are under [Testing, diagnosis and review](#testing).

| Skill | Source | Purpose |
| --- | --- | --- |
| [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) | anthropics/skills | Establish a distinctive visual direction. |
| [composition-patterns](https://github.com/vercel-labs/agent-skills/tree/main/skills/composition-patterns) | vercel-labs/agent-skills | Design composable React components. |
| [frontend-ui-engineering](https://github.com/addyosmani/agent-skills/tree/main/skills/frontend-ui-engineering) | addyosmani/agent-skills | Implement frontend interfaces and interactions. |
| [animate](https://github.com/emilkowalski/skills/tree/main/skills/animate) | emilkowalski/skills | Build purposeful, interruptible animations. |
| [react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) | vercel-labs/agent-skills | Apply React and Next.js performance practices. |
| [animation-performance](https://github.com/emilkowalski/skills/tree/main/skills/animation-performance) | emilkowalski/skills | Improve animation performance. |

<a id="testing"></a>
### Testing, diagnosis and review

Use this category to investigate failures or validate changes. Plan runtime
evidence early when needed; verify again after addressing review feedback.

| Skill | Source | Purpose |
| --- | --- | --- |
| [observability-and-instrumentation](https://github.com/addyosmani/agent-skills/tree/main/skills/observability-and-instrumentation) | addyosmani/agent-skills | Plan logs, metrics and runtime evidence. |
| [systematic-debugging](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) | obra/superpowers | Diagnose failures through hypotheses and evidence. |
| [webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) | anthropics/skills | Test local web applications with Playwright. |
| [web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) | vercel-labs/agent-skills | Review interface conventions and accessibility. |
| [requesting-code-review](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review) | obra/superpowers | Prepare and request code review. |
| [receiving-code-review](https://github.com/obra/superpowers/tree/main/skills/receiving-code-review) | obra/superpowers | Verify and address review feedback. |
| [verification-before-completion](https://github.com/obra/superpowers/tree/main/skills/verification-before-completion) | obra/superpowers | Verify results before claiming completion. |

<a id="security"></a>
### Security and auditing

Apply during design, implementation and review as the task requires.

| Skill | Source | Purpose |
| --- | --- | --- |
| [security-threat-model (historical)](https://github.com/openai/skills/tree/49f948faa9258a0c61caceaf225e179651397431/skills/.curated/security-threat-model) | openai/skills | Model threats to code and systems. |
| [security-and-hardening](https://github.com/addyosmani/agent-skills/tree/main/skills/security-and-hardening) | addyosmani/agent-skills | Perform engineering security checks and hardening. |
| [differential-review](https://github.com/trailofbits/skills/tree/main/plugins/differential-review/skills/differential-review) | trailofbits/skills | Review code changes for security risks. |

<a id="delivery"></a>
### CI and delivery

Establish delivery automation, resolve CI failures, then prepare the branch and
release notes.

| Skill | Source | Purpose |
| --- | --- | --- |
| [ci-cd-and-automation](https://github.com/addyosmani/agent-skills/tree/main/skills/ci-cd-and-automation) | addyosmani/agent-skills | Design CI/CD and automation workflows. |
| [gh-fix-ci (historical)](https://github.com/openai/skills/tree/49f948faa9258a0c61caceaf225e179651397431/skills/.curated/gh-fix-ci) | openai/skills | Inspect failed GitHub Actions logs. |
| [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) | obra/superpowers | Prepare a development branch for delivery. |
| [changelog-generator](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator) | ComposioHQ/awesome-claude-skills | Generate release notes from commit history. |

<a id="documents"></a>
### Documents and reporting

Organize evidence and narrative, then use the required file format. These tools
also support research inputs and documentation during implementation.

| Skill | Source | Purpose |
| --- | --- | --- |
| [weekly-report-writing](skills/weekly-report-writing/SKILL.md) | This repository | Turn progress updates into weekly or biweekly reports organized by business, business area and project. |
| [doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | anthropics/skills | Collaboratively write structured documents. |
| [scientific-writing](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-writing) | K-Dense-AI/scientific-agent-skills | Structure scientific manuscripts. |
| [humanizer](https://github.com/blader/humanizer/tree/main) | blader/humanizer | Make writing sound more natural. |
| [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) | anthropics/skills | Create and analyze spreadsheets. |
| [docx](https://github.com/anthropics/skills/tree/main/skills/docx) | anthropics/skills | Create and edit Word documents. |
| [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) | anthropics/skills | Create and edit slide presentations. |
| [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) | anthropics/skills | Extract, generate and process PDFs. |

<a id="marketing"></a>
### Content and growth

Plan content, write copy, then investigate search visibility as needed.

| Skill | Source | Purpose |
| --- | --- | --- |
| [content-strategy](https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy) | coreyhaines31/marketingskills | Plan content themes and growth paths. |
| [copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) | coreyhaines31/marketingskills | Write product copy around user goals. |
| [seo-audit](https://github.com/coreyhaines31/marketingskills/tree/main/skills/seo-audit) | coreyhaines31/marketingskills | Diagnose SEO and indexing problems. |

<a id="knowledge"></a>
### Knowledge management and productivity

Organize materials, preserve notes, then connect reusable knowledge.

| Skill | Source | Purpose |
| --- | --- | --- |
| [file-organizer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/file-organizer) | ComposioHQ/awesome-claude-skills | Organize personal files by content. |
| [obsidian-markdown](https://github.com/kepano/obsidian-skills/tree/main/skills/obsidian-markdown) | kepano/obsidian-skills | Write Obsidian Markdown extensions. |
| [json-canvas](https://github.com/kepano/obsidian-skills/tree/main/skills/json-canvas) | kepano/obsidian-skills | Create JSON Canvas knowledge maps. |

<a id="orchestration"></a>
### Agent context and orchestration

Prepare context and choose an execution workflow before starting substantial
work. Add isolation or parallel agents when tasks justify them; use one main
orchestration workflow rather than stacking competing process instructions.

| Skill | Source | Purpose |
| --- | --- | --- |
| [context-engineering](https://github.com/addyosmani/agent-skills/tree/main/skills/context-engineering) | addyosmani/agent-skills | Organize Agent task context. |
| [using-superpowers](https://github.com/obra/superpowers/tree/main/skills/using-superpowers) | obra/superpowers | Enter the global Superpowers workflow. |
| [using-git-worktrees](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) | obra/superpowers | Create isolated workspaces for parallel development. |
| [dispatching-parallel-agents](https://github.com/obra/superpowers/tree/main/skills/dispatching-parallel-agents) | obra/superpowers | Delegate independent tasks to parallel agents. |
| [subagent-driven-development](https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development) | obra/superpowers | Implement and inspect work through subagents. |

<a id="meta"></a>
### Skill authoring and library maintenance

Turn repeatable work into a skill, evaluate its behavior, then maintain the
catalog. The two authoring entries offer alternative approaches.

| Skill | Source | Purpose |
| --- | --- | --- |
| [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) | anthropics/skills | Author, evaluate and improve custom skills. |
| [writing-skills](https://github.com/obra/superpowers/tree/main/skills/writing-skills) | obra/superpowers | Author skills through evaluation scenarios. |
| [maintain-skill-library](skills/maintain-skill-library/SKILL.md) | This repository | Maintain curated references, skill files and repository conventions. |

## Repository structure

```text
README.md
README.zh-CN.md
docs/
  skill-authoring.md        # Writing and evaluating skills
  source-repositories.md    # Sources and dated research records
  research/                 # Initial discovery evidence
skills/
  weekly-report-writing/
    SKILL.md
    assets/
    references/
  maintain-skill-library/
    SKILL.md
    references/
CONTRIBUTING.md
AGENTS.md
.github/                    # Issue and pull request templates
```

Categories live in this README. Every local skill has one folder directly under
`skills/`, regardless of its category or whether it maintains the repository.

## Using skills

Open the source and follow its current installation and dependency instructions.
A catalog link does not load a skill or update an installed copy.

To author a skill, create `skills/<name>/SKILL.md` using the minimal example in the
[authoring guide](docs/skill-authoring.md), add specialized procedures and register it
under the relevant category with Source set to This repository.

## Updates and licensing

Upstream authors maintain third-party content. This library updates source links,
migration notes and recommendations when needed. Stars and reviewed commits are
dated historical research, not live rankings, installation counts or version locks.
Entries marked historical come from the deprecated OpenAI skills source; check
[openai/plugins](https://github.com/openai/plugins) for current alternatives.

Original repository content uses [MIT](LICENSE). Linked third-party content remains
subject to its upstream license.
