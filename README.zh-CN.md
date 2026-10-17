# Skills for Engineers

[English](README.md) · **简体中文**

[创作指南](docs/skill-authoring.md) · [来源仓库](docs/source-repositories.md) ·
[贡献指南](CONTRIBUTING.md)

## 技能目录

- [研究与数据分析](#research)
- [目标与需求澄清](#product)
- [架构设计与实施规划](#architecture)
- [工程开发与代码质量](#engineering)
- [前端设计与实现](#frontend)
- [测试、诊断与审查](#testing)
- [安全与审计](#security)
- [CI 与交付](#delivery)
- [文档与汇报](#documents)
- [内容与增长](#marketing)
- [知识管理与个人效率](#knowledge)
- [Agent 上下文与执行编排](#orchestration)
- [技能创作与库维护](#meta)

按工作顺序浏览：收集证据 → 明确目标 → 设计与规划 → 实施 →
验证与审查 → 交付 → 文档与知识沉淀。
每个技能只登记一个主要分类。安全、文档和 Agent 编排也适用于工作全过程。

为当前任务选择一个主技能，再按需补充配套技能。
以下是建议路径，不是必须逐项执行的流水线；已有充分输入的阶段可以跳过。

| 任务 | 建议路径 |
| --- | --- |
| 新功能 | `brainstorming` → `writing-plans` → 实施 → `verification-before-completion` |
| 架构调整 | `improve-codebase-architecture` → `api-and-interface-design` → `writing-plans` → 实施与验证 |
| 故障排查 | `systematic-debugging` → 修复与回归检查 → `verification-before-completion` |
| 前端开发 | `frontend-design` → `frontend-ui-engineering` → `webapp-testing` → `web-design-guidelines` |
| 周报 | 进展证据 → `weekly-report-writing` → 按需选择文档格式 |

<a id="research"></a>
### 研究与数据分析

在选择方向前收集证据。电子表格分析见[文档与汇报](#documents)。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [last30days](https://github.com/mvanhorn/last30days-skill/tree/main/skills/last30days) | mvanhorn/last30days-skill | 跨平台研究最近 30 天的讨论。 |
| [literature-review](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/literature-review) | K-Dense-AI/scientific-agent-skills | 检索与整理学术文献。 |

<a id="product"></a>
### 目标与需求澄清

澄清问题与取舍，确定结果优先级，再记录需求。
产品需求可使用 PRD，工程行为可使用规格文档。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) | obra/superpowers | 梳理需求与设计范围。 |
| [grilling](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling) | mattpocock/skills | 通过决策树访谈检验设计假设与取舍。 |
| [prioritize-features](https://github.com/phuryn/pm-skills/tree/main/pm-product-discovery/skills/prioritize-features) | phuryn/pm-skills | 评估功能价值与优先级。 |
| [outcome-roadmap](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/outcome-roadmap) | phuryn/pm-skills | 以业务结果组织路线图。 |
| [create-prd](https://github.com/phuryn/pm-skills/tree/main/pm-execution/skills/create-prd) | phuryn/pm-skills | 编写精简且支持决策的 PRD。 |
| [to-spec](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-spec) | mattpocock/skills | 将讨论整理为规格。 |

<a id="architecture"></a>
### 架构设计与实施规划

定义边界与契约，记录决策，再规划实施或将规格拆分为任务。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [domain-modeling](https://github.com/mattpocock/skills/tree/main/skills/engineering/domain-modeling) | mattpocock/skills | 梳理领域词汇与模型。 |
| [codebase-design](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design) | mattpocock/skills | 建立模块深度与接口设计词汇。 |
| [improve-codebase-architecture](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | mattpocock/skills | 识别架构摩擦与模块深化机会。 |
| [api-and-interface-design](https://github.com/addyosmani/agent-skills/tree/main/skills/api-and-interface-design) | addyosmani/agent-skills | 设计稳定的 API 与接口契约。 |
| [deprecation-and-migration](https://github.com/addyosmani/agent-skills/tree/main/skills/deprecation-and-migration) | addyosmani/agent-skills | 规划兼容迁移与弃用流程。 |
| [documentation-and-adrs](https://github.com/addyosmani/agent-skills/tree/main/skills/documentation-and-adrs) | addyosmani/agent-skills | 编写架构决策记录与技术文档。 |
| [writing-plans](https://github.com/obra/superpowers/tree/main/skills/writing-plans) | obra/superpowers | 编写可执行的实施计划。 |
| [to-tickets](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-tickets) | mattpocock/skills | 将规格拆分为任务。 |

<a id="engineering"></a>
### 工程开发与代码质量

先应用编码约束，再实现行为，按需简化代码与优化性能。
两个 TDD 条目提供不同工作流，同一任务选择一个即可。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [coding-standards](https://github.com/affaan-m/ECC/tree/main/skills/coding-standards) | affaan-m/ECC | 为 Agent 工程项目应用编码规范。 |
| [karpathy-guidelines](https://github.com/multica-ai/andrej-karpathy-skills/tree/main/skills/karpathy-guidelines) | multica-ai/andrej-karpathy-skills | 避免过度设计，定义可验证的最小变更。 |
| [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) | obra/superpowers | 围绕行为实施测试驱动开发。 |
| [tdd](https://github.com/mattpocock/skills/tree/main/skills/engineering/tdd) | mattpocock/skills | 围绕模块接口实施 TDD。 |
| [mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) | anthropics/skills | 创建 MCP 服务与 API 集成。 |
| [code-simplification](https://github.com/addyosmani/agent-skills/tree/main/skills/code-simplification) | addyosmani/agent-skills | 降低代码复杂度。 |
| [performance-optimization](https://github.com/addyosmani/agent-skills/tree/main/skills/performance-optimization) | addyosmani/agent-skills | 基于测量优化性能。 |

<a id="frontend"></a>
### 前端设计与实现

选择视觉方向，设计组件，实现交互，再优化性能。
界面审查和浏览器测试见[测试、诊断与审查](#testing)。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) | anthropics/skills | 建立有辨识度的视觉方向。 |
| [composition-patterns](https://github.com/vercel-labs/agent-skills/tree/main/skills/composition-patterns) | vercel-labs/agent-skills | 设计可组合的 React 组件。 |
| [frontend-ui-engineering](https://github.com/addyosmani/agent-skills/tree/main/skills/frontend-ui-engineering) | addyosmani/agent-skills | 实现前端界面与交互。 |
| [animate](https://github.com/emilkowalski/skills/tree/main/skills/animate) | emilkowalski/skills | 构建有目的且可中断的动画。 |
| [react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) | vercel-labs/agent-skills | 应用 React 与 Next.js 性能实践。 |
| [animation-performance](https://github.com/emilkowalski/skills/tree/main/skills/animation-performance) | emilkowalski/skills | 优化动画性能。 |

<a id="testing"></a>
### 测试、诊断与审查

用于排查故障或验证改动。按需提前规划运行时证据；
处理审查反馈后再次验证。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [observability-and-instrumentation](https://github.com/addyosmani/agent-skills/tree/main/skills/observability-and-instrumentation) | addyosmani/agent-skills | 规划日志、指标与运行时证据。 |
| [systematic-debugging](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) | obra/superpowers | 基于假设与证据诊断故障。 |
| [webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) | anthropics/skills | 使用 Playwright 验证本地 Web 应用。 |
| [web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) | vercel-labs/agent-skills | 审查界面规范与可访问性。 |
| [requesting-code-review](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review) | obra/superpowers | 准备并请求代码审查。 |
| [receiving-code-review](https://github.com/obra/superpowers/tree/main/skills/receiving-code-review) | obra/superpowers | 验证并处理审查反馈。 |
| [verification-before-completion](https://github.com/obra/superpowers/tree/main/skills/verification-before-completion) | obra/superpowers | 在声明完成前验证结果。 |

<a id="security"></a>
### 安全与审计

根据任务需要，在设计、实施和审查阶段使用。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [security-threat-model（历史参考）](https://github.com/openai/skills/tree/49f948faa9258a0c61caceaf225e179651397431/skills/.curated/security-threat-model) | openai/skills | 建立代码与系统威胁模型。 |
| [security-and-hardening](https://github.com/addyosmani/agent-skills/tree/main/skills/security-and-hardening) | addyosmani/agent-skills | 执行工程安全检查与加固。 |
| [differential-review](https://github.com/trailofbits/skills/tree/main/plugins/differential-review/skills/differential-review) | trailofbits/skills | 针对代码变更执行安全审查。 |

<a id="delivery"></a>
### CI 与交付

建立交付自动化，解决 CI 失败，再整理分支与发布说明。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [ci-cd-and-automation](https://github.com/addyosmani/agent-skills/tree/main/skills/ci-cd-and-automation) | addyosmani/agent-skills | 设计 CI/CD 与自动化流程。 |
| [gh-fix-ci（历史参考）](https://github.com/openai/skills/tree/49f948faa9258a0c61caceaf225e179651397431/skills/.curated/gh-fix-ci) | openai/skills | 检查 GitHub Actions 失败日志。 |
| [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) | obra/superpowers | 整理开发分支并准备交付。 |
| [changelog-generator](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator) | ComposioHQ/awesome-claude-skills | 从提交历史生成发布说明。 |

<a id="documents"></a>
### 文档与汇报

组织证据与内容，再选用所需文件格式。
这些工具也支持研究材料处理与实施过程中的文档工作。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [weekly-report-writing](skills/weekly-report-writing/SKILL.md) | 本仓库 | 将进度更新整理为周报或双周报，按业务、业务方向与项目组织。 |
| [doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) | anthropics/skills | 协作编写结构化文档。 |
| [scientific-writing](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-writing) | K-Dense-AI/scientific-agent-skills | 组织科学论文写作。 |
| [humanizer](https://github.com/blader/humanizer/tree/main) | blader/humanizer | 改进表达的自然度。 |
| [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) | anthropics/skills | 创建与分析电子表格。 |
| [docx](https://github.com/anthropics/skills/tree/main/skills/docx) | anthropics/skills | 创建与编辑 Word 文档。 |
| [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) | anthropics/skills | 创建与编辑幻灯片。 |
| [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) | anthropics/skills | 提取、生成与处理 PDF。 |

<a id="marketing"></a>
### 内容与增长

规划内容，编写文案，再按需诊断搜索可见性。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [content-strategy](https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy) | coreyhaines31/marketingskills | 制定内容主题与增长路径。 |
| [copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) | coreyhaines31/marketingskills | 围绕用户目标编写产品文案。 |
| [seo-audit](https://github.com/coreyhaines31/marketingskills/tree/main/skills/seo-audit) | coreyhaines31/marketingskills | 诊断 SEO 与索引问题。 |

<a id="knowledge"></a>
### 知识管理与个人效率

整理材料，保留笔记，再连接可复用知识。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [file-organizer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/file-organizer) | ComposioHQ/awesome-claude-skills | 按内容组织个人文件。 |
| [obsidian-markdown](https://github.com/kepano/obsidian-skills/tree/main/skills/obsidian-markdown) | kepano/obsidian-skills | 编写 Obsidian 扩展 Markdown。 |
| [json-canvas](https://github.com/kepano/obsidian-skills/tree/main/skills/json-canvas) | kepano/obsidian-skills | 创建 JSON Canvas 知识画布。 |

<a id="orchestration"></a>
### Agent 上下文与执行编排

在开始复杂工作前准备上下文并选择执行流程。
任务需要时再增加隔离工作区或并行代理；选择一套主编排流程，避免叠加相互冲突的过程指令。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [context-engineering](https://github.com/addyosmani/agent-skills/tree/main/skills/context-engineering) | addyosmani/agent-skills | 整理 Agent 任务上下文。 |
| [using-superpowers](https://github.com/obra/superpowers/tree/main/skills/using-superpowers) | obra/superpowers | 进入 Superpowers 全局工作流。 |
| [using-git-worktrees](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) | obra/superpowers | 为并行开发创建隔离工作区。 |
| [dispatching-parallel-agents](https://github.com/obra/superpowers/tree/main/skills/dispatching-parallel-agents) | obra/superpowers | 将独立任务交给并行代理。 |
| [subagent-driven-development](https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development) | obra/superpowers | 通过子代理实施并检查工作。 |

<a id="meta"></a>
### 技能创作与库维护

将可重复的工作沉淀为技能，评估行为，再维护目录。
两个技能创作条目提供不同方法。

| 技能 | 来源 | 用途 |
| --- | --- | --- |
| [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) | anthropics/skills | 编写、评估与改进自定义技能。 |
| [writing-skills](https://github.com/obra/superpowers/tree/main/skills/writing-skills) | obra/superpowers | 用评估场景驱动技能编写。 |
| [maintain-skill-library](skills/maintain-skill-library/SKILL.md) | 本仓库 | 维护精选引用、技能文件与仓库约定。 |

## 仓库结构

```text
README.md
README.zh-CN.md
docs/
  skill-authoring.md        # 技能编写与评估
  source-repositories.md    # 来源与历史研究记录
  research/                 # 初次发现的证据
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
.github/                    # Issue 与 PR 模板
```

分类在 README 中维护。每个本仓库技能直接放在 `skills/` 下，
不因分类或维护用途建立额外层级。

## 使用技能

打开来源，按最新安装与依赖说明使用。目录链接不会自动加载技能，
也不会更新已安装副本。

创建技能时，参照 [创作指南](docs/skill-authoring.md) 的最小示例，
编写 `skills/<name>/SKILL.md` 并补充专用流程，在对应分类登记，来源注明本仓库。

## 更新与许可

上游作者维护来源内容；本仓库按需更新链接、迁移说明和推荐。
Stars 与核查 commit 是带日期的历史研究，不是实时排名、安装量或版本锁。
标为历史参考的条目来自已弃用的 OpenAI skills 来源；
当前替代方案见 [openai/plugins](https://github.com/openai/plugins)。

本仓库原创内容使用 [MIT](LICENSE)。链接所指的第三方内容遵循上游许可证。
