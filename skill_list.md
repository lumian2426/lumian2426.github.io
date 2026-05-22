# skills-manager 中央仓库 — 全量技能清单

> 自动生成: 2026-05-22

## 浏览器与自动化

| Name | Source | Description |
|------|--------|-------------|
| **agent-browser** | Store | AI智能体的浏览器自动化CLI工具。用于与网页交互，包括页面导航、填写表单、点击按钮、截图、数据抓取、Web应用测试等浏览器自动化场景。 |
| **browser-cdp** | Store | 启动、停止和管理持久化本地Chrome实例（CDP远程调试端口）。适用于需要复用已登录的长生命周期浏览器会话（Cookie和本地存储）且无需浏览器扩展的场景。典型触发词：用9222/CDP控制浏览器、常驻浏览器、启动CDP浏览器、检查CDP状态、复用登录态浏览器。 |
| **pcc_zqname** | Store | 拼多多店铺名称批量查询。通过 CDP 浏览器（Edge）逐个访问拼多多移动端店铺链接，从页面标题提取店铺名称，回填到 Excel。内置多级防反爬策略（随机延时、模拟滚动、中场休息、断点续查）。用户提到查询店铺名称、批量查店铺名、拼多多店铺名时使用。 |
| **playwright-scraper-skill** | Store | 基于Playwright的网页爬虫技能，内置反爬保护机制。已在复杂站点（如Discuss.com.hk）验证通过。 |

## AI 与智能体

| Name | Source | Description |
|------|--------|-------------|
| **agent-reach** | Store | > |
| **agent-team-manager** | Store | 多智能体团队管理。创建、查看、修改、删除 CountBot 的多智能体团队，管理团队成员（角色）和团队级自定义模型配置。当用户要新建 Pipeline/Graph/Council 团队、调整成员分工、修改依赖关系、开关技能系统、设置团队专属模型时使用。 |
| **baidu-search** | Store | 百度 AI 搜索。支持网页搜索、百度百科、秒懂百科、AI 智能生成四种模式。自动包含当前日期上下文。当用户要求搜索信息、查询百科、获取最新资讯、搜索新闻、查找资料时使用。 |
| **find-skills** | Store | 最高优先级的技能发现流程。当用户要求查找或安装技能时必须触发此技能。对于中文用户，优先使用SkillHub（更快且合规），无匹配时回退到ClawHub。 |
| **gh-cli** | Store | GitHub CLI 完整参考手册。覆盖仓库、Issue、Pull Request、Actions、Projects、Releases、Gists、Codespaces、组织管理、扩展等所有 GitHub 命令行操作。当用户需要操作 GitHub 仓库、管理 Issue/PR、配置 CI/CD、部署 Release 时使用。 |
| **html-anything** | Store | 智能 HTML 编辑器——让 AI Agent 生成精美 HTML 页面的本地 Web 应用。内置 75 个可组合技能模板，覆盖杂志文章、演示文稿、简历、小红书卡片、海报、数据报告、视频超帧等 9 种交付形态。支持 Claude Code、Cursor、Codex 等 8 种 Agent CLI。 |
| **humanizer** | Store | 去除AI生成文本痕迹，让文字读起来更自然、更像人类书写。可检测并修复空洞的象征性语言、营销腔、浅层-ing分析、模糊引文、长破折号滥用、三点式结构、AI高频词汇、否定平行结构、过度连词短语等模式。 |
| **ima-skill** | Store | 统一的 IMA OpenAPI 技能，支持笔记管理和知识库操作。当用户提到知识库、笔记、备忘录，或需要上传文件、添加网页到知识库、搜索知识库内容、搜索/浏览/创建/编辑笔记时使用。 |
| **kdocs** | Store | "操作金山文档（WPS 云文档 / Kdocs / 365.kdocs.cn / www.kdocs.cn）云文档的官方 Skill。核心能力覆盖云端新建、读取、编辑、搜索、分享、整理在线文档（智能文档、Word、Excel、PDF、PPT、演示文稿、智能表格、多维表格）及个人知识库。当用户的任务涉及云文档操作时使用，包括但不限于：写周报/日报/工作汇报、处理合同/发票、创建报名表/登记表、网页剪藏、接龙转表格、信息收集、文档总结与内容生成、改写仿写、翻译、AI PPT生成、PDF拆分导出、标签分类归档、收藏管理、碎片笔记整理、表格美化、回收站还原、知识库管理。" |
| **self-improvement** | Store | 捕获学习经验、错误和修正，实现持续自我改进。适用于命令或操作意外失败、用户纠正、请求不可用能力、外部API失败、发现知识过时、发现更好方法等场景。 |
| **skill-creator** | Store | 创建、修改、优化和评测技能的工具。支持从零创建新技能、编辑优化已有技能、运行评估测试、基准测试与方差分析、优化技能描述以提高触发准确率。 |
| **skillhub-preference** | Store | 技能发现/安装/更新时优先使用SkillHub，不可用或无匹配时回退到ClawHub。当用户询问技能、插件或功能扩展时使用。 |

## 搜索与资讯

| Name | Source | Description |
|------|--------|-------------|
| **map** | Store | 高德地图路线规划与 POI 搜索。支持驾车、步行、骑行、公交路线规划，以及景点、餐厅搜索。当用户询问路线、行程规划、景点推荐、餐厅推荐时使用。 |
| **news** | Store | 新闻与资讯查询。获取中文新闻和全球 AI 技术资讯，支持按分类查询（时政、财经、科技、社会、国际、体育、娱乐、AI 技术、AI 社区）。当用户询问最新新闻、AI 动态、行业资讯时使用。 |

## 文档处理

| Name | Source | Description |
|------|--------|-------------|
| **html-ppt** | Store | HTML PPT Studio——使用纯静态HTML制作专业演示文稿。支持多种样式、布局和动画效果，全部由模板驱动。当用户要求制作演示文稿、PPT、幻灯片、演讲稿、分享稿、小红书图文、技术分享PPT等场景时使用。 |
| **huashu-md-html** | Store | 花叔的「md/html/docx 多向流水线」skill，四个能力 + 两种模式：(1) 用Microsoft markitdown把任意文件（PDF/DOCX/PPTX/XLSX/HTML/图片/音频/YouTube/EPub/ZIP）转成干净的md；(2) 用Pandoc + 4套精挑模板把md加工成出色的html——**兜底模式**（不耗token，pandoc 一键套版）+ **视觉艺术设计师模式**（AI 读懂内容、推荐 3 个差异化方向、为内容定制视觉表达），继承huashu-design的反AI slop审美；(3) 用html-to-markdown + trafilatura把html或URL无损转回md；(4) 用python-docx把md加工成出版社级docx（专业排版+自动嵌图+封面目录页眉页脚，专用于纸质书审校/投稿/出版交付）。落地花叔的「md生产，多端消费」方法论。触发词：md转html、html转md、pdf转md、docx转md、pptx转md、xlsx转md、文件转md、URL转md、文档转md、转markdown、做html、生成html、网页转md、import文档、导入md、导出html、md to html、html to md、any to md、md转docx、md to docx、生成docx、做word文档、出版社审校、投稿、纸质书、出版稿、交付docx、book、出色的html、定制html设计、做个好看的网页、设计师模式、几种风格、推荐设计方向、markitdown、pandoc、python-docx。即使用户只是说「这个PDF变md」「这篇md做成网页」「这个网页存下来」「把这些md做成可投稿的word」「给出版社一份审校稿」「给这个md做个出色的html」「让我看看几种风格」也应触发。 |
| **kami** | Store | 专业文档排版工具。支持简历、一页纸、白皮书、信函、作品集、幻灯片等文档类型。暖色调羊皮纸风格，墨蓝色强调色，衬线字体层级。中文仓耳今楷，英文Charter，日文YuMincho。 |
| **markitdown** | Store | 文件与办公文档转Markdown格式转换器。支持PDF、DOCX、PPTX、XLSX、图片（OCR识别）、音频（语音转录）、HTML、CSV、JSON、XML、ZIP压缩包、YouTube链接、EPub电子书等多种格式。 |
| **minimax-docx** | Store | > |
| **minimax-pdf** | Store | > |
| **PDF Generator** | Store | 从Markdown、HTML、数据或代码生成专业PDF文档。支持报告、发票、合同、文档等类型，遵循最佳实践。 |
| **pptx-generator** | Store | "Generate, edit, and read PowerPoint presentations. Create from scratch with PptxGenJS (cover, TOC, content, section divider, summary slides), edit existing PPTX via XML workflows, or extract text with markitdown. Triggers: PPT, PPTX, PowerPoint, presentation, slide, deck, slides." |
| **summarize** | Store | 快速摘要 CLI 工具。支持对网页 URL、PDF 文档、图片、音频文件、YouTube 链接等内容一键生成摘要。当用户需要快速获取网页/文档/视频的核心内容摘要时使用。 |
| **web-design** | Store | 网页设计与部署。生成精美的单页 HTML 网页（报告、落地页、数据可视化等），支持一键部署到 Cloudflare Pages。使用 Tailwind CSS + Chart.js + Font Awesome 技术栈。当用户要求制作网页、生成报告页面、创建落地页、数据可视化展示、部署网页到线上时使用。 |

## 图片与媒体

| Name | Source | Description |
|------|--------|-------------|
| **gif-sticker-maker** | Store | \ |
| **image-analysis** | Store | 图片分析与识别，可分析本地图片、网络图片、视频、文件。适用于 OCR、物体识别、场景理解等。当用户发送图片或要求分析图片时必须使用此技能。 |
| **vision-analysis** | Store | > |

## 知识库与笔记

| Name | Source | Description |
|------|--------|-------------|
| **ima-knowledge-base** | Store | 通过 IMA OpenAPI 处理知识库任务。支持知识库内容搜索、命中详情查看、条目浏览、列出知识库、上传文件、导入网页。用户提到知识库、资料库、上传到知识库、导入网页、搜知识库时使用。 |
| **ima-notes** | Store | 通过 IMA OpenAPI 处理笔记任务。支持搜索笔记、读取笔记、列出笔记、新建笔记、追加笔记。用户提到笔记、备忘录、记一下、追加到某篇笔记时使用。 |
| **minimax-music-gen** | Store | > |
| **minimax-music-playlist** | Store | > |
| **minimax-xlsx** | Store | "Open, create, read, analyze, edit, or validate Excel/spreadsheet files (.xlsx, .xlsm, .csv, .tsv). Use when the user asks to create, build, modify, analyze, read, validate, or format any Excel spreadsheet, financial model, pivot table, or tabular data file. Covers: creating new xlsx from scratch, reading and analyzing existing files, editing existing xlsx with zero format loss, formula recalculation and validation, and applying professional financial formatting standards. Triggers on 'spreadsheet', 'Excel', '.xlsx', '.csv', 'pivot table', 'financial model', 'formula', or any request to produce tabular data in Excel format." |

## 开发与构建

| Name | Source | Description |
|------|--------|-------------|
| **android-native-dev** | Store | Android native application development and UI design guide. Covers Material Design 3, Kotlin/Compose development, project configuration, accessibility, and build troubleshooting. Read this before Android native application development. |
| **cron-manager** | Store | 定时任务管理。创建、查看、修改、删除定时任务，管理任务会话数据。当用户需要设置提醒、定时执行任务、管理调度计划时使用。 |
| **flutter-dev** | Store | \ |
| **frontend-dev** | Store | \ |
| **fullstack-dev** | Store | \ |
| **ios-application-dev** | Store | \ |
| **mcp-builder** | Store | 高质量MCP（模型上下文协议）服务器构建指南。使大语言模型能通过精心设计的工具与外部服务交互。适用于构建集成外部API或服务的MCP服务器，支持Python（FastMCP）或Node/TypeScript（MCP SDK）技术栈。 |
| **react-native-dev** | Store | \ |
| **shader-dev** | Store | Comprehensive GLSL shader techniques for creating stunning visual effects — ray marching, SDF modeling, fluid simulation, particle systems, procedural generation, lighting, post-processing, and more. |

## 工具与命令行

| Name | Source | Description |
|------|--------|-------------|
| **git-commit** | Store | 约定式提交辅助工具。自动分析代码变更 diff，智能判断提交类型（feat/fix/docs 等）和范围，生成符合规范的提交信息。支持交互式自定义覆盖。当用户输入 /commit 或要求提交代码时使用。 |
| **mmx-cli** | Store | Use mmx to generate text, images, video, speech, and music via the MiniMax AI platform. Use when the user wants to create media content, chat with MiniMax models, perform web search, or manage MiniMax API resources from the terminal. |

## 其他工具

| Name | Source | Description |
|------|--------|-------------|
| **buddy-sings** | Store | > |
| **site-memory** | Store | \ |

---

**总计**: 49 | **来源**: skills-manager central repository
