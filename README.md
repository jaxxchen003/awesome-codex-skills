# Codex Design Skills 🎨

> 专注 **Codex / Agent Skills** 的 design 类优秀 skill 合集：网页设计、生图、生视频、动效与设计系统。
> 先聚焦 design，后续再扩到其他方向。
> 仓库：https://github.com/jaxxchen003/awesome-codex-skills

📊 **收录 skill：41** ｜ 🕐 **最后更新：2026-11-13** ｜ 🤖 每日定时更新 ｜ 🌐 **在线预览站：https://jaxxchen003.github.io/awesome-codex-skills/**

---

## 📖 收录标准与溯源规则

这是本库和一般聚合站最大的区别：

| 标记 | 含义 |
|------|------|
| ✅ | 双核验：X 原帖作者本人 + GitHub 原仓库都已核验 |
| 🟡 | GitHub 原仓库已核验，X 首发原帖未定位到作者本人 |

- **来源只写原始作者，不写聚合站。** skills.sh / agentsuses / awesome-codex 合集等只当发现线索，入库时必须追到 GitHub 原仓库或 X 原帖作者本人。聚合站转贴的一条 skill，如果找不到原作者，不入库。
- **每个 case 都带参考图或参考视频。** 优先收原帖自带的演示视频（video.twimg.com 直链）、仓库 README 截图、官网 Showcase。
- **只收真实 skill / 真实仓库。** 有 SKILL.md 或明确的 Codex 安装方式；纯文章、纯视频不附链接。
- **生图 / 生视频要拆口径：** 分“代码生成”（SVG / HTML / Remotion 渲染，不调图片视频模型）和“模型生成”（调 Nano Banana / gpt-image / Veo / Sora 等）两类，入库时标注清楚，不混着说。
- **Stars 口径：** 文中 stars 均为 2026-11-08 GitHub API / 仓库页核验值；合集型仓库的 stars 是整个仓库的，不是单个 skill 的，已注明。

> Reddit 线本轮有缺口：2026-11-13 实测 www.reddit.com/new RSS 五个分区首轮 429×3 / 403×2（403 体为 Reddit 拦截页、非 RSS），重试一次全部 429；old.reddit.com 返回 302、api.reddit.com 403——三个路由均未取到帖子列表，本轮 Reddit 覆盖缺失，不编链接。X 线：web search 两轮未发现过去 24 小时内新发布的 design skill 原帖。GitHub Search 本轮 7 次查询（codex design skill / "design skill" codex / motion design skill / logo design skill codex / design skill 三页）共 100 余候选，核验 30 余个仓库后 5 条入库；GitHub API core 配额中途用尽（共享出口 IP 60/小时），abeerkhalique/design-critique-skill 因无 README 且 API 限流未能核验内容，留待下轮。skills.sh 首页已取到（200），今晚候选条目未现身；agentsuses /new 返回 404；open-design.ai 与 SkillsMP 首页未见今晚候选条目；Bles Software Designer Stack 仍无公开 GitHub 原仓库（官网 zip 下载），继续暂缓。

---

## 📑 目录

- [🌐 网页设计](#-网页设计)（26）
- [🖼️ 生图](#️-生图)（6）
- [🎬 生视频](#-生视频)（9）
- [🤝 参与方式](#-参与方式)
- [⚠️ 免责声明](#️-免责声明)

---

## 🌐 网页设计

### 1. Anatomy — 一句话画出可交互等距剖视图 ✅
- **作者**：Ryan（@wheresryan22）
- **原帖**：https://x.com/wheresryan22/status/2108948624004526516（2026-10-10，18,212 赞 / 2.68M 浏览）
- **仓库**：https://github.com/wheresryan22/anatomy（约 25,710★，MIT，根目录 SKILL.md）
- **一句话**：一句话描述一台机器，变成可旋转、可拆解的交互式等距线框图，带 WebGL 火 / 水 / 等离子 shader 与真实 3D 运动。
- **参考视频**：原帖 38.9 秒演示视频 https://video.twimg.com/amplify_video/2108946813889675264/vid/avc1/1920x1080/etLTvFpDLdf7-z6D.mp4?tag=29 ；52 个可交互实例：https://skills.wheresryan.sh/anatomy/collection
- **类型**：代码生成（SVG / WebGL / 3D，不调图片模型）

### 2. unslop — 把“AI 味”仪表盘改成克制设计 ✅
- **作者**：Damir Sokolovsky（@heydamir）
- **原帖**：https://x.com/heydamir/status/2115063463063998736（2026-10-27，16,307 赞 / 2.0M 浏览）；发布帖 https://x.com/heydamir/status/2116158176336970008（2026-10-30）
- **仓库**：https://github.com/heydamir/unslop（CC BY 4.0）
- **一句话**：9.8 秒前后对比，把紫渐变 + 发光 + emoji 标签的仪表盘改成深色克制设计；skill 适用于落地页、看板与移动应用，支持 Codex。
- **参考视频**：原帖 9.8 秒前后对比 https://video.twimg.com/amplify_video/2114009309126299648/vid/avc1/2168x2160/ir9g5tra15711hQD.mp4?tag=29
- **类型**：网页设计；可选模型生图（fal / Replicate / OpenAI images / Higgsfield）

### 3. Stageshow — 逼真的仿产品 UI 静帧 / 动效 ✅
- **作者**：Benji Taylor（@benjitaylor，X 与 SpaceXAI 设计负责人）
- **原帖**：https://x.com/benjitaylor/status/2116593247854453244（2026-10-31，14,391 赞 / 1.57M 浏览 / 26,383 收藏）
- **仓库**：https://github.com/benjitaylor/skills（skill 名 stageshow，仓库 API 实测 2,379★）
- **一句话**：让 agent 做出更好的 faux UI 静帧、动画、bento grid，先讲故事再拍片再修。
- **参考视频**：原帖演示视频 https://video.twimg.com/amplify_video/2116591037816971264/vid/avc1/2784x1944/CQhIlZl1gbvNSIkA.mp4?tag=29 ；官网大量有 / 无 skill 前后对比：https://benji.org/stageshow
- **类型**：代码生成

### 4. ai-design-skills / landing-page-design — 落地页设计 ✅
- **作者**：Elaya（@elayadesigns，8 年产品设计师）
- **原帖**：https://x.com/elayadesigns/status/2114049200749175174（2026-10-24，11,197 赞 / 879K 浏览）
- **仓库**：https://github.com/elayadesign/ai-design-skills（MIT，13k+★，含 landing-page-design 与 design-to-motion）
- **一句话**：过去两个月所有落地页都用 Higgsfield + Claude + Cursor + 自研 AI 设计师 skill 做出来，skill 已开源，Codex 可用。
- **参考视频**：原帖 14.7 秒作品混剪 https://video.twimg.com/amplify_video/2114048823970643968/vid/avc1/1752x1080/zoo2YAjtfZQZ007L.mp4?tag=29
- **类型**：网页设计；模型生图（Higgsfield 出视觉资产）

### 5. Hallmark — 开源反 AI-slop 设计 skill ✅
- **作者**：Nutlope（@nutlope）
- **原帖**：https://x.com/nutlope/status/2056754959819915459（2026-05-19，5,488 赞 / 894K 浏览）
- **仓库**：https://github.com/Nutlope/hallmark（50,106★，2026-11-08 核验，`skills/hallmark/SKILL.md`）
- **一句话**：50 个主题材质 + 分层门控 + 真实浏览器 sloplint 检查 + 755 张 Wikimedia 授权照片，让 UI 与落地页默认就好看，支持 Codex。
- **参考视频**：原帖 39.3 秒演示 https://video.twimg.com/amplify_video/2056751127643734016/vid/avc1/1920x1080/5gmXVphI25MlGBvJ.mp4?tag=27 ；README 含 10 个主题成品图，官网 usehallmark.com
- **类型**：网页设计

### 6. frontend-design（Anthropic 官方）🟡
- **作者**：Anthropic
- **仓库**：https://github.com/anthropics/skills（188,557★，全仓库，2026-11-06 最后推送；`skills/frontend-design/SKILL.md`）
- **一句话**：公认的 baseline 审美护栏：先定大胆视觉方向再写代码，禁 Inter / Roboto / Arial / Space Grotesk 等俗字体。
- **参考图/视频**：无（纯规则文档型 skill）
- **备注**：大量复刻的正源，只收官方版；X 上无单条作者发布帖。

### 7. ui-ux-pro-max 🟡
- **作者**：nextlevelbuilder
- **仓库**：https://github.com/nextlevelbuilder/ui-ux-pro-max-skill（146,474★，2026-11-07 最后推送）
- **一句话**：67 种 UI 风格、161 条行业规则、161 套配色、57 组字体搭配的设计智能库。
- **参考视频**：agentsuses 标注 0:26 演示视频（聚合站线索，原仓库待补 demo 直链）
- **类型**：网页设计 / UI-UX；`design` 子技能需生图服务

### 8. taste-skill / design-taste-frontend 🟡
- **作者**：Leon Lin（Leonxlnx）
- **仓库**：https://github.com/Leonxlnx/taste-skill（111,530★，全仓库 11 个 skill，2026-11-07 最后推送）
- **一句话**：三个 1–10 档位（布局变化 / 动效强度 / 视觉密度）调参式反俗套前端品味，从 247 个精选站点研究的 20 个艺术方向中每次发 3 个方向。
- **参考视频**：agentsuses 标注 0:39 视频
- **备注**：X 上流传的是 @rammcodes 的演示帖，非作者本人发布帖，故标 🟡。

### 9. impeccable 🟡
- **作者**：Paul Bakaus（pbakaus）
- **仓库**：https://github.com/pbakaus/impeccable（105,331★，2026-11-07 最后推送，Apache-2.0）
- **一句话**：“给 agent 的设计词汇表”：23+ 命令 + 59 条 AI 痕迹检测规则 + 浏览器实时迭代，分 brand / product 双模式。
- **参考图**：agentsuses 配图；Subframe 实测四款 skill 中唯一 visibly 改变页面外观的一款。
- **备注**：首发在 Hacker News（2026-01-12），非 X；Reddit 间接证据：Subframe 编码的 1,002 个 Reddit 讨论串中出现在 78/511 个实质串中，常为首选答案（无逐条原帖链接，不编）。

### 10. frontend-ui-engineering（Addy Osmani）🟡
- **作者**：Addy Osmani
- **仓库**：https://github.com/addyosmani/agent-skills（113,858★，全仓库；`skills/frontend-ui-engineering/SKILL.md`）
- **一句话**：设计系统 token + 响应式 + 无障碍（WCAG 2.1 AA）+ 加载 / 空 / 错状态的生产级前端实施指南。
- **参考图/视频**：未核验

### 11. emilkowalski/skills — 动效与 UI 打磨 🟡
- **作者**：Emil Kowalski
- **仓库**：https://github.com/emilkowalski/skills（54,324★，全仓库；`skills/emil-design-eng/SKILL.md`）
- **一句话**：动效决策框架（该不该动、目的、缓动、时长 <300ms）+ review-animations / improve-animations 等评审 skill。
- **参考图/视频**：agentsuses 缩略图

### 12. web-design-guidelines（Vercel 官方）🟡
- **作者**：Vercel Labs
- **仓库**：https://github.com/vercel-labs/agent-skills（33,682★，全仓库；`skills/web-design-guidelines/SKILL.md`）
- **一句话**：按 Vercel《Web Interface Guidelines》做无障碍与交互审查，逐条报 file:line 的评审型 skill。
- **参考图/视频**：无（规则审查型）

### 13. frontend-skill（OpenAI 官方 Codex skill）🟡
- **作者**：OpenAI
- **仓库**：https://github.com/openai/skills（28,579★，全仓库）
- **一句话**：OpenAI 官方 Codex 前端 skill：无卡片布局、全幅 hero、品牌优先层级、克制动效、≤2 字体 + 1 强调色。
- **备注**：SKILL.md 路径本轮因 GitHub API 限流未核验，下轮补。

### 25. Liquid-Glass-Skill — 交互式液态玻璃控件 🟡
- **作者**：EVEDensity
- **仓库**：https://github.com/EVEDensity/Liquid-Glass-Skill（4★，MIT，2026-11-09 GitHub Search API 核验；创建 2026-11-03，2026-11-08 更新）
- **一句话**：设计折射按钮、开关、滑杆、分段控件等液态玻璃控件：本地编辑器调形状 / 文字 / 图标 / 材质，Copy for AI 粘贴进 agent 落到现有页面，支持 Codex 与 Claude Code。
- **参考视频**：README 18 秒产品演示附件已失效（2026-11-12 复测 404），改用 4K MP4：4K MP4：https://github.com/EVEDensity/Liquid-Glass-Skill/raw/refs/heads/main/docs/media/liquid-glass-ui-demo.mp4
- **类型**：代码生成（CSS glass / WebGL2 折射，不调图片模型）

### 26. premium-frontend-director — 高端前端艺术指导 🟡
- **作者**：AVL05
- **仓库**：https://github.com/AVL05/premium-frontend-director（0★，MIT，2026-11-09 核验；创建 2026-11-04，2026-11-08 更新；`skills/premium-frontend-director/SKILL.md`）
- **一句话**：把创意简报变成有艺术指导的独特前端：创意方向提案 → 现有框架落地 → 浏览器实查 → 证据优先交接，Codex / Claude Code 可用。
- **参考图/视频**：官网 Showcase（独立电影感展示站）：https://the-art-of-direction.netlify.app
- **类型**：网页设计

### 27. variant-design-skill — 一份简报出三个设计方向 🟡
- **作者**：YuqingNicole
- **仓库**：https://github.com/YuqingNicole/variant-design-skill（47★，2026-11-09 核验；创建 2026-03-11，2026-11-08 更新；根目录 SKILL.md）
- **一句话**：同一份简报在项目内生成 A/B/C 三个完整可比的设计方向，各有取舍说明，改动先快照、可回滚；另含设计系统、组件、UX 评审等路由。
- **参考图**：README 三张示例图（assets/sample-A-editorial.png 等）；A/B/C 案例站：https://variant-design-skill.vercel.app/cases
- **类型**：代码生成

### 28. diagram-design — 品牌级图表 / 信息图 🟡
- **作者**：cathrynlavery
- **仓库**：https://github.com/cathrynlavery/diagram-design（65,818★，MIT，2026-11-09 GitHub Search API 核验；创建 2026-04-16，2026-11-08 更新；`skills/diagram-design/SKILL.md`）
- **一句话**：45 种图表类型画成品牌一致的自包含 HTML+SVG 单文件（不用 Mermaid 糙图），支持 Codex / Claude Code，附品牌 token 注册表。
- **参考图**：README hero 图 + 截图画廊；官网 https://diagramdesign.dev ；画廊站 https://cathrynlavery.github.io/diagram-design/
- **类型**：代码生成（HTML+SVG）

### 29. nordic-civic-design-skill — 赫尔辛基设计系统公共服务网页 skill 🟡
- **作者**：capsrock
- **仓库**：https://github.com/capsrock/nordic-civic-design-skill（1★，2026-11-10 GitHub Search API 核验；创建 2026-11-09；根目录 SKILL.md）
- **一句话**：以赫尔辛基设计系统（HDS 6.0.7）为底的公共服务网页设计 skill：直角、强色、大留白，含现成设计 token，明确支持 Codex。
- **参考图**：README 三张示例图——首页 https://raw.githubusercontent.com/capsrock/nordic-civic-design-skill/main/assets/jp/home.png ；申请表单 https://raw.githubusercontent.com/capsrock/nordic-civic-design-skill/main/assets/jp/form.png ；管理后台 https://raw.githubusercontent.com/capsrock/nordic-civic-design-skill/main/assets/jp/table.png
- **类型**：代码生成（设计系统 token）
- **备注**：非官方 skill，README 已声明与赫尔辛基市无关、不得冒用市徽与 logo。

### 31. neopop-design-skill — CRED NeoPOP 设计语言 UI skill 🟡
- **作者**：Satyam085
- **仓库**：https://github.com/Satyam085/neopop-design-skill（0★，Apache-2.0，2026-11-11 核验；创建 2026-11-10；`neopop-design/SKILL.md`）
- **一句话**：教 agent 用 CRED 开源设计语言 NeoPOP 做 UI：硬边 3D“plunk”按钮、黑底主色、大胆字体与小写文案，支持 Codex / Claude Code / Cursor 等。
- **参考图**：README 示例图——仅用 skill 的 CSS 做的账单支付界面 https://raw.githubusercontent.com/Satyam085/neopop-design-skill/main/preview.png
- **类型**：代码生成（CSS 设计语言）
- **备注**：非官方 skill（NeoPOP 为 CRED 开源设计语言，本仓库未获 CRED 官方背书）。

### 32. cloudmamba-design-skill — 云曼巴品牌设计语言 skill 🟡
- **作者**：KEVqwe
- **仓库**：https://github.com/KEVqwe/cloudmamba-design-skill（0★，许可证未声明，2026-11-11 核验；创建 2026-11-10；根目录 SKILL.md）
- **一句话**：把云曼巴品牌语言（配色与字体 token、9 个 logo SVG、6 个角色 SVG、毛边细节对照）用于官网、产品工作台、PPT、海报与社交封面，明确支持 Codex。
- **参考图**：README 毛边细节对照 https://raw.githubusercontent.com/KEVqwe/cloudmamba-design-skill/main/assets/previews/texture-comparison.png
- **类型**：网页设计 / 设计系统（品牌 token）
- **备注**：单一公司品牌的设计语言 skill，通用性窄于通用设计系统。

### 33. digital-go-design-skill — 日本数字厅设计系统公共服务网页 skill 🟡
- **作者**：capsrock
- **仓库**：https://github.com/capsrock/digital-go-design-skill（1★，2026-11-11 核验；创建 2026-11-09；根目录 SKILL.md）
- **一句话**：以日本数字厅设计系统（DADS β版）为底的公共服务网页设计 skill：易读文字、高对比、黄色与黑色焦点框，含现成设计 token，明确支持 Codex。
- **参考图**：README 四张示例图——首页 https://raw.githubusercontent.com/capsrock/digital-go-design-skill/main/assets/jp/home.png ；申请表单 https://raw.githubusercontent.com/capsrock/digital-go-design-skill/main/assets/jp/form.png ；管理后台 https://raw.githubusercontent.com/capsrock/digital-go-design-skill/main/assets/jp/table.png
- **类型**：代码生成（设计系统 token）
- **备注**：非官方 skill；2026-11-09 创建，昨日 GitHub 搜索未命中，今晚补录（与第 29 条同作者同类 skill）。

### 34. motion-design — LottieFiles 官方动效设计 skill 🟡
- **作者**：LottieFiles
- **仓库**：https://github.com/LottieFiles/motion-design-skill（2,927★，MIT，2026-11-11 核验；创建 2026-03-12；`skills/motion-design/SKILL.md`）
- **一句话**：通用动效设计原则 skill：先定节奏、缓动、编排与情绪意图再写动画代码，覆盖入场、状态反馈、加载、滚动触发与多元素编排，支持 Codex 等 40+ agent。
- **参考视频**：README 顶部 dotLottie 动效演示 https://lottie.host/cdb5e749-f393-4333-ad23-8200f121e8d3/Z4sIS9xKDC.svg?v=1
- **类型**：代码生成（CSS / Framer Motion / GSAP / Lottie 动效）
- **备注**：原仓库创建于 2026-03-12；本轮由当日新建的同名复刻仓库（syahdestiny/skill-motion-design，非 fork）追溯到原作者后入库，复刻仓库本身不另收。

### 37. finesse — 应用 UI 打磨 skill 包 🟡
- **作者**：delevski
- **仓库**：https://github.com/delevski/finesse（0★，MIT，2026-11-13 核验；创建 2026-11-12；`skills/finesse/SKILL.md`）
- **一句话**：让 coding agent 少出“灰盒子 + 死按钮”的默认 UI：状态优先（pending / 骨架 / 错误重试）、语义 token、带意图的动效、原生 RTL（逻辑属性 + 希伯来字体），面向 Next.js + shadcn/ui + Tailwind + Framer Motion 的应用界面，支持 Codex CLI / OpenCode。
- **参考视频**：README 演示 GIF + 完整 demo 视频 https://raw.githubusercontent.com/delevski/finesse/main/docs/assets/demo.mp4 ；在线前后对比画廊：https://delevski.github.io/finesse/
- **类型**：代码生成

### 38. mochen-website-design — 个人网站设计 skill 🟡
- **作者**：陌晨（mochenai）
- **仓库**：https://github.com/mochenai/mochen-website-design（0★，PolyForm Noncommercial 1.0.0，2026-11-13 核验；创建 2026-11-12；`skills/mochen-website-design/SKILL.md`）
- **一句话**：把文章 / 笔记 / 履历 / 作品做成可浏览、可交互的个人网站：纸白网格、炭黑大字、浅黄强调、可拖动小狗交互，纯 Python 标准库生成静态站，支持 Codex 全局安装。
- **参考图**：README 示例截图 https://raw.githubusercontent.com/mochenai/mochen-website-design/main/docs/screenshots/mochen-home.png ；在线完整示例：https://mochenai.github.io/mochen-website-design/
- **类型**：代码生成
- **备注**：仅限非商用（PolyForm Noncommercial 1.0.0）；设计语言参考 oiloil.org，小狗组件来自 Mr-xue/Gaze-Dog。

### 39. mobile-app-designer — 移动应用端到端设计 skill 🟡
- **作者**：Chrollo（chrollo-03）
- **仓库**：https://github.com/chrollo-03/mobile-app-designer（1★，MIT，2026-11-13 核验；创建 2026-11-12；`skills/mobile-app-designer/SKILL.md`）
- **一句话**：一句话需求走完移动应用设计全流程：简报 → 设计系统 → iOS/Android 双端界面 → 可点原型 → 图标 → 137 项检查 → 打包交接，含 RTL 支持，支持 Codex 等 Agent Skills 兼容工具。
- **参考视频**：Barwise 举重应用完整案例片（1:02）https://raw.githubusercontent.com/chrollo-03/mobile-app-designer/main/examples/barwise/video/barwise-film.mp4 ；16 屏总览 https://raw.githubusercontent.com/chrollo-03/mobile-app-designer/main/examples/barwise/screens/_overview.png
- **类型**：网页设计 / UI 设计（移动应用端到端）

### 40. ui-designer — AI 原生 UI 设计器（工具型）🟡
- **作者**：Jinzhu.Zhang（freeheart）
- **仓库**：https://github.com/freeheart/ui-designer（1★，MIT，2026-11-13 核验；创建 2026-11-12；根目录 SKILL.md）
- **一句话**：浏览器里像 Figma 一样拖拽界面，一句话让 AI 改稿 / 品评，设计稿即 design.json，可导出单文件 HTML/CSS、React + Tailwind 或设计 token；主走 DSH skill，Codex CLI 不装 DSH 也可用。
- **参考图**：README 编辑器截图 https://raw.githubusercontent.com/freeheart/ui-designer/main/docs/screenshots/editor.png
- **类型**：网页设计 / UI 设计
- **备注**：工具型（浏览器可视化设计器 + agent skill），非纯指令型 skill。

---

## 🖼️ 生图

### 14. baoyu-design — Claude Design 本地化 🟡
- **作者**：JimLiu
- **仓库**：https://github.com/JimLiu/baoyu-design（6,206★，仓库页实测）
- **一句话**：把 claude.ai 的 Design Artifact 本地化为 Agent Skill：UI mockup / 原型、deck、设计系统、dashboard、motion film 五个可编辑器打开的 artifact 类型，全部自包含 HTML。支持 Codex。
- **参考图/视频**：README 含 5 张编辑器截图 + 3 个 promo mp4（baoyu-design-promo.mp4 等）
- **类型**：网页设计 + 生视频（motion film 可导出 MP4 / GIF）

### 15. codex-ui-design — 图先行 UI 管线 🟡
- **作者**：gwelinder
- **仓库**：https://github.com/gwelinder/pi-extension-pack（`skills/codex-ui-design/SKILL.md`，2★）
- **一句话**：走本地 Codex app-server + 已登录的 ChatGPT / Codex 订阅调 gpt-image-2 先出界面 mockup，再转成 build spec 落代码，不用 fal.ai key。
- **参考图/视频**：未核验
- **类型**：模型生图（gpt-image-2）

### 16. logo-design-skill 🟡
- **作者**：kaankiziltug
- **仓库**：https://github.com/kaankiziltug/logo-design-skill（6,244★，2026-11-06 最后推送）
- **一句话**：从 brief 到 SVG 成品 + 品牌规范的完整 logo 设计流程，附 1,400+ logo 参考库。
- **参考图**：1,400+ logo 参考库
- **类型**：代码生成（SVG）

### 17. ComfyUI — 本地生图 / 生视频后端（工具型）🟡
- **作者**：Comfy-Org
- **仓库**：https://github.com/Comfy-Org/ComfyUI（145,565★，GPL-3.0，API 实测）
- **一句话**：最强模块化本地生图 / 生视频：节点式扩散模型 GUI + API + 后端，自有 GPU 零单张成本跑开源模型。
- **备注**：它是 skill 的“生图后端”而非 SKILL.md 本身，标注为“工具型”而非“指令型”。
- **类型**：模型生图 + 生视频

### 35. danlogo-swisstech — 以字为标的瑞士风 logo 体系 skill 🟡
- **作者**：dan-cube
- **仓库**：https://github.com/dan-cube/danlogo-swisstech（0★，MIT，2026-11-12 核验；创建 2026-11-11；根目录 SKILL.md）
- **一句话**：以字为标的 logo 身份系统 skill：中英文字形从零构造、字成一体再取字成符，九阶段流程（简报 → 概念 → 原型 → 精修 → 定稿 → 体系 → 场景 → 提案 → 总结），明确支持 Codex。
- **参考图**：README hero 图 + EonPoint「首尾」案例图：https://raw.githubusercontent.com/dan-cube/danlogo-swisstech/main/cases/eonpoint-shouwei/images/00-hero.png
- **类型**：代码生成（定制字形几何构造，不调图片模型）

### 36. chanmeng-logo-as-code — 手绘 logo 转可编辑 SVG 🟡
- **作者**：ChanMeng666
- **仓库**：https://github.com/ChanMeng666/chanmeng-logo-as-code（0★，MIT，2026-11-12 核验；创建 2026-06-06，2026-11-06 最后推送；根目录 SKILL.md）
- **一句话**：把手绘 / 扫描 logo 沿真实轮廓拟合成光滑三次贝塞尔曲线，产出可编辑 SVG + 配色 / 版式变体矩阵 + 交互对比画廊 + PNG/ICO/favicon 导出，支持 Codex。
- **参考图**：README 示例 SVG——手绘猴子 logo 转码后效果：https://raw.githubusercontent.com/ChanMeng666/chanmeng-logo-as-code/main/examples/chan-monkey/out/monkey/chan-meng-monkey-black-on-white.svg
- **类型**：代码生成（SVG 矢量化）
- **备注**：补录：SkillSpot 2026-11-04 上架，仓库 2026-06 创建、11-06 最后推送，本轮由聚合站线索追溯到原作者后入库。

---

## 🎬 生视频

### 18. HyperFrames — Agent 写 HTML 渲染帧精确 MP4 ✅
- **作者**：HeyGen（@HeyGen，官方）
- **原帖**：https://x.com/HeyGen/status/2057123793907458232（2026-05-20，字幕 skill 发布帖，1,127 赞 / 384K 浏览）
- **仓库**：https://github.com/heygen-com/hyperframes（80,455★，Apache-2.0，含 `.codex-plugin/`）
- **一句话**：Agent 写 HTML / CSS / JS 场景，渲染成帧精确 MP4；9 个 skill、约 450 个现成 blocks。
- **参考视频**：原帖 43.4 秒演示视频；README 有 HyperFrames Studio GIF、10 张模板图、Showcase 成品视频；agentsuses 0:56 视频
- **类型**：代码生成（HTML 渲染视频）
- **备注**：此原帖是字幕 skill 发布帖，非整个套件发布帖，口径已注明。

### 19. video-shotcraft — 电影感产品宣传片 ✅
- **作者**：Vincent Wei（@VincentWei93）
- **原帖**：https://x.com/VincentWei93/status/2079118667074376114（2026-07-20，1,558 赞 / 318K 浏览，中文原帖）
- **仓库**：https://github.com/Vincentwei1021/video-shotcraft（17,614★，Apache-2.0）
- **一句话**：用真实页面截图 + 124 张镜头配方卡 / 150 个动态预览，按节拍剪辑 + 音效设计，Remotion 渲染 1080p MP4，可导出剪映草稿。明确支持 Codex。
- **参考视频**：原帖演示视频直链已失效（2026-11-12 复测 404），改用 README 工作流动图 https://raw.githubusercontent.com/Vincentwei1021/video-shotcraft/main/assets/readme/workflow.gif ；Gallery 站 150 个动态预览、Showcase 视频、README 20+ 张镜头示例图
- **类型**：代码生成（Remotion 渲染）

### 20. brag — 一句话把项目变 launch 视频 🟡
- **作者**：latent-spaces
- **仓库**：https://github.com/latent-spaces/brag（20,650★，MIT，含 `.codex-plugin/`）
- **一句话**：一句话把刚做完的项目变成带音乐 / 动效 / 分享文案的短 launch 视频（底层 HyperFrames），产物为 brag.mp4。
- **参考视频**：launch 站循环视频就是给本仓库自己做的；letsbrag.app 在线版
- **类型**：代码生成
- **备注**：作者 X 账号未确认，首发原帖未定位，故标 🟡。

### 21. Remotion skills — React 写视频 🟡
- **作者**：Remotion 团队
- **仓库**：https://github.com/remotion-dev/skills（6,533★，12 个 skill；README 明确支持 Codex）
- **一句话**：用 React 写视频：标题卡、地图动画、字幕、SaaS 集成等，Studio 预览 + 渲染成片。
- **参考视频**：成品示例在 remotion.dev 官网（本轮未点开）
- **类型**：代码生成

### 22. pixelfx — 像素风特效库 + skill ✅
- **作者**：Rehan Sheikh（@rehan_shei，Patch.gg CEO）
- **原帖**：https://x.com/rehan_shei/status/2116062680121540611（2026-10-30，1,227 赞 / 110K 浏览 / 1,539 收藏）
- **仓库**：https://github.com/patch-gg/pixelfx（MIT，232→244 个特效）
- **一句话**：用 Opus 5.5 写像素特效——写、渲染、看帧、修到满意为止，232 个特效全是代码、零图片，已全部开源连同 skill。
- **参考视频**：原帖 40.1 秒特效混剪 https://video.twimg.com/amplify_video/2116062497082146816/vid/avc1/1920x1080/PAazJQS5-OOBF95y.mp4?tag=29
- **类型**：代码生成

### 23. anidoodle — 手绘风插画 / 短片 ✅
- **作者**：Alex Greenshpun（@alexgreensh）
- **原帖**：https://x.com/alexgreensh/status/2102458223638810739（2026-09-22）
- **仓库**：https://github.com/alexgreensh/anidoodle（Apache-2.0，32 种手绘风格；`codex plugin marketplace add alexgreensh/anidoodle`）
- **一句话**：手绘风插画 / 短片 skill，全片逐帧手绘代码生成 + 配乐。
- **参考视频**：仓库 README 顶部 77 秒发布片 anidoodle-launch-github.mp4（原帖本身无媒体）
- **类型**：代码生成（纯代码确定性绘制，无图片模型调用）

### 24. design-to-motion — 静态设计转动效展示 ✅
- **作者**：Elaya（@elayadesigns）
- **原帖**：https://x.com/elayadesigns/status/2114806587466604676（2026-10-26，108 赞）
- **仓库**：https://github.com/elayadesign/ai-design-skills（同仓库内 design-to-motion skill）
- **一句话**：把静态设计变成可在 X 等平台分享的动画展示（Figma / 截图 → MP4 + GIF）。
- **参考图**：原帖附图 https://pbs.twimg.com/media/HVlMzI1b0AA-sgn.png?name=orig ；视频演示见第 4 条原帖
- **类型**：代码生成

### 30. idea-to-motion — 一句话想法变带配乐旁白的动效视频 🟡
- **作者**：Georges MOMO（georgesmomo）
- **仓库**：https://github.com/georgesmomo/idea-to-motion（0★，2026-11-10 核验；创建 2026-11-09；`skills/idea-to-motion/SKILL.md`，MIT）
- **一句话**：一句话想法变成带 3D、动效、配乐、旁白的动效视频：14 种风格、16 种体裁，本地渲染、零 API key，明确支持 Codex。
- **参考视频**：README 所列 showreel GIF + 7 条演示视频附件均已失效（2026-11-12 复测 404），待作者重新上传
- **类型**：代码生成（HyperFrames + three.js + GSAP 渲染，无图片模型）

### 41. one-prompt-video — 一句话出一支带配乐字幕的短视频 🟡
- **作者**：JiMiL、vivhuang（li2092）
- **仓库**：https://github.com/li2092/one-prompt-video（0★，MIT，2026-11-13 核验；创建 2026-11-12；`one-prompt-video/SKILL.md`）
- **一句话**：一句话 → 大模型填一张 video.json → 一条命令生成 20–90 秒带配乐和字幕的 MP4：九种版式、18 套主题，1080p 十几秒出片，不用显卡、不用浏览器，明确支持 Codex。
- **参考视频**：README 42 秒宣传片 https://github.com/user-attachments/assets/bbe739b1-32a2-4042-b0e6-c4116cb0daa9 ；18 套主题轮换 GIF（已验 200）：https://raw.githubusercontent.com/li2092/one-prompt-video/main/docs/styles.gif
- **类型**：代码生成（逐帧代码渲染，不调视频生成模型；旁白为豆包 TTS、配乐为库乐队采样，需自备密钥 / 仅 macOS）
- **备注**：宣传片 user-attachments 直链本机 curl 复测 404（GitHub 附件为签发链接，需浏览器会话；仓库页 HTML 内含该视频元素），故卡片用站内 GIF。

---

## 暂不收录（已查到，缺源头或未核验）

- **taste-skill 的 X 首发**：流传的是 @rammcodes 演示帖，非作者本人，不作 X 来源。
- **vibe-creating-skill**：标题仓库 mystijk/vibe-creating-skill 与 README 内 clone 地址 Alisa0808/vibe-creating-skill 不一致，归属存疑，待核对现用仓库名。
- **Hypit**：agentsuses 22.3k★、1:03 视频，但源头仓库作者未点开确认，源头待追溯。
- **Superdesign / Mowgli**：仅单站提及，stars、仓库页、demo 均未核验。
- **video-generation / video-director**：SKILL.md 页面此前可抓取，但 GitHub Search API 两次无返回，可能改名 / 删库，收录前须人工点开复核。
- **ai-ready-sites**（tsvetaeff-den，创建 2026-11-08）：SKILL.md 已核验（`skills/ai-ready-sites/SKILL.md`，Apache-2.0，明确支持 Codex），但 README 全文（8,959 字）无任何参考图 / 视频（仅 CI badge），按铁律暂不入库，待作者补 demo 后再收。
- **ui-review-loop**（millxing，创建 2026-11-08）：SKILL.md 已核验（根目录，明确支持 Codex，多评审人打分 + 问题台账），但 README 无参考图 / 视频，暂不入库，待作者补 demo 后再收。
- **ai-skills-marketplace**（T-Sunm，创建 2026-11-08）：合集型仓库，非单个 design skill，不入库。
- **unslop-frontend-design**（rldzkl，创建 2026-11-09）：改写自 Anthropic frontend-design 的反 AI 味前端 skill，SKILL.md 已核验、明确支持 Codex，但 README 全文无任何参考图 / 视频（唯一视频链接是致谢里的 TikTok 原视频，非本 skill 演示），按铁律暂不入库，待作者补 demo 后再收。
- **systra-taste**（systra-tools，创建 2026-11-09）：三合一设计品味 skill（build / review / repair），SKILL.md 已核验、明确支持 Codex，但 README 唯一图片是 skills.sh 徽章，示例文档（hero-repair / review-report）也无任何参考图 / 视频，暂不入库。
- **design-skills-pack-en**（nattagidgig-hash，创建 2026-11-09）：9 个 UI/UX design skill 合集，README 无参考图 / 视频，暂不入库。
- **atelier-ui**（caicaichuangzhao，创建 2026-11-09）、**claude-code-ui-design**（inchwormz，创建 2026-11-09）、**website-builder-toolkit**（tobiashaas，创建 2026-11-09）、**design-director**（romanroff，创建 2026-11-09）：SKILL.md 已核验、均明确支持 Codex，但 README 均无参考图 / 视频，暂不入库。
- **am-will/codex-skills 的 frontend-design**：合集型仓库，内含的 frontend-design 系直接导入 Anthropic 官方版（本库第 6 条已收），不重复收录。
- **gyeol-design**（kimdol1045-hash，创建 2026-11-10）：SKILL.md 已核验（`skills/gyeol-design/SKILL.md`，MIT），Design Lab 展示站已核验可打开，但 README 与 SKILL.md 均未提及 Codex 支持、README 无参考图 / 视频，暂不入库。
- **lumos-design**（IDEVA-AI，创建 2026-11-10）：SKILL.md 已核验（`skills/lumos-design/SKILL.md`），明确支持 Codex，但 README 全文无任何参考图 / 视频，暂不入库，待作者补 demo 后再收。
- **futuristic-web-design-skills**（mukulmunda41-create，创建 2026-11-10）：明确支持 Codex，但 README 全文（14,383 字）无任何参考图 / 视频，暂不入库。
- **prd-to-demo**（ELLIEZHANG893，创建 2026-11-10）：SKILL.md 已核验，未提及 Codex，README 无参考图 / 视频，暂不入库。
- **motion_design_skill**（txusillo，创建 2026-11-10）：HyperFrames 竖版 Reels 解说视频 skill，README 无参考图 / 视频、SKILL.md 路径未定位，暂不入库。
- **editorial-design-agent-skill**（KaigorodovTuskul，创建 2026-11-10）：SKILL.md 已核验，未提及 Codex，README 无参考图 / 视频，暂不入库。
- **hiaaryan/motion-design**（创建 2026-11-10）：代码生成 motion film skill，README 无参考图 / 视频、SKILL.md 路径未定位，暂不入库。
- **nefr0/custom-design**（创建 2026-11-10）：impeccable fork + Apple HIG，SKILL.md 已核验、提及 Codex，但 README 无参考图 / 视频，且主体为已收录 impeccable 的 fork，暂不入库。
- **leyen-me/DesignSkills**（创建 2026-11-10）：通用设计智能框架，SKILL.md 已核验，未提及 Codex，README 无参考图 / 视频，暂不入库。
- **gzh-design-skill**（FelixMaofei，创建 2026-11-10）：isjiamu 原项目的修改版（微信公众号排版），超出本库网页设计 / 生图 / 生视频范围，暂不入库。
- **syahdestiny/skill-motion-design**（创建 2026-11-10）：非 fork 的同名复刻，原作者为 LottieFiles（2026-03 创建），已按原作者入库（第 34 条），复刻仓库本身不另收。
- **Jervyyyy/Design-Skills、Ya-MiC/ymzz-wenrun-design-skill、Vuek0/vueko-design-skill、hypnagogic-hallucinations/airy-coastal-ui**（创建 2026-11-10）：README 缺失、过短或无参考图 / 视频，暂不入库。
- **shopify_skill**（copyFish18650，创建 2026-11-11）：8 个 Codex skill 的安装包合集，其中 6 个为本库已收 skill 的复刻（design、design-taste-frontend、frontend-design、ui-ux-pro-max、web-design-engineer、web-design-guidelines），新增的 shopify-theme-redesign / shopify-policy-pages 为 Shopify 主题装修 skill；合集型仓库且 README 全文无任何参考图 / 视频，暂不入库。
- **uk-skill**（JDebDesign，创建 2026-11-11）：美式邮件/网页文案转英式本地化 skill，SKILL.md 已核验、提及 Codex，README 含 3 张示例图，但明确不改字体/样式/布局，属文案本地化、超出本库网页设计 / 生图 / 生视频范围，暂不入库。
- **afterglow**（Maxime282002，创建 2026-11-11）：法语描述的 motion design 视频 skill，但仓库为空、无 README、无 SKILL.md，暂不入库。
- **claude-code-skills**（rithikanupam-hub，创建 2026-11-11）：112 个 skill 合集（含 video / motion / design），README 全文无参考图 / 视频，合集型暂不入库。
- **dsh-skills-pack**（adithyanraj03，创建 2026-11-11）：DeepSeek Harness 插件、36 个 skill 合集，未提及 Codex，暂不入库。
- **Bles Software Designer Stack**（swestack.bles-software.com）：8 个免费 MIT skill（motion-story / showreel-motion / promo-motion / tastegate 等），支持 Codex，官网有 29 秒 launch 视频；但未找到公开 GitHub 原仓库（官网 zip 下载）、发布时间未核验，暂不入库，待追溯到原作者仓库或 X 原帖后再收。2026-11-13 复查：仍无公开仓库。
- **N3wb13GG/web-interaction-design-skill**（创建 2026-11-12）：Codex 明确支持（iOS Safari tint / 长按 / 模态焦点等移动端交互），SKILL.md 已核验，但 README 全文无任何参考图 / 视频，暂不入库。
- **Bee-yyds/pc-design-qa**（创建 2026-11-12）：PC 端设计验收 Codex Skill（Figma 对照 + 在线协作报告），SKILL.md 已核验，但 README 无参考图 / 视频，暂不入库。
- **lejar14/atlas-design-system-skill**（创建 2026-11-12）：Atlas（ASYST）设计系统 skill，提及 Codex，但 README 无参考图 / 视频，暂不入库。
- **moonwalk6688/norman-design-psychology**（创建 2026-11-12）：诺曼《设计心理学》四册整理的 Codex 设计诊断 skill，SKILL.md 已核验，但 README 无参考图 / 视频，且偏设计诊断、超出网页设计 / 生图 / 生视频范围，暂不入库。
- **Link-up-co/mobile-design-system**（创建 2026-11-12）：移动端 B2C 网页 / PWA 设计系统 + agent skill，提及 Codex，但 README 无参考图 / 视频（仅在线组件预览站），暂不入库。
- **suiyang-meta/sui-motion-graphic-reel**（创建 2026-11-12）：代码做动画 Reel 的 skill，README 有 15 秒开场联络表参考图，但仅提及 Claude Code、未提及 Codex，暂不入库。
- **gollodev/onboarding-paywall-designs**（创建 2026-11-12）：应用 onboarding / 订阅付费墙设计图（PNG）生成 skill，README 含示例图，但仅 Claude Code / claude.ai / Copilot、未提及 Codex，暂不入库。
- **khizerahmadchohan/elite-design-director**（创建 2026-11-12）：Claude Code 网页设计 skill，README 含示例图，但未提及 Codex，暂不入库。
- **efalov/super-design**（创建 2026-11-12）：Claude Code 前端设计 skill，有 SKILL.md，但仓库无 README、页面全文未提及 Codex，暂不入库。
- **abeerkhalique/design-critique-skill**（创建 2026-11-12）：仓库无 README（main/master 均 404），内容未核验；本轮 GitHub API core 配额用尽未能复核，留待下轮。
- **hanpage-ai/leonxlnx-design-taste-frontend-skill**（创建 2026-11-12）：第 8 条 taste-skill 的韩文复刻 / 翻译，非原作者，不另收。
- **adymire/CraftLayer、doko89/design-skills、furkansenturk/claude-skills、tuanesxyz/skills、jmackow/skills、neromtoobad/creator-skills、dewwc/webdev-playbook、Kaifrizwan12/nazar-studio、jijinglong/skills**（创建 2026-11-12）：合集型仓库（内含多个 skill），不单条入库；其中 jijinglong/skills 的 ai-video-directing（Seedance 提示词 + AI 视频导演）可后续专项核验。
- **dlrs108/Reverse1999_UI_skill、Shashank33549/stickman-animation、Enghc1115/video-costume-design、eb-ekeledo/feel-skill、issei-fujimoto-accelia/uiux_design_skill、murilohennemannuphold/design-critique-jam、vicyap/design-sprites、UtomoAbimail/ui-ux-design-principle、greatopomu/claude-assets、ReL4xi0n/m3-forge、AwsGames-byte/cinematic-glass-web-vitrine**（创建 2026-11-12）：未提及 Codex 和 / 或 README 无参考图 / 视频，暂不入库（其中 cinematic-glass-web-vitrine 有封面图与两条演示视频，但未提及 Codex）。
- **drozak01/kinetix-ai**（创建 2026-11-12）：Cinema-Grade AI Motion Design 平台，无 SKILL.md、未提及 Codex，暂不入库。
- **mango-leo/arch-draw**（创建 2026-11-12）：代码 / 基建文档转 SVG 架构图，超出网页设计 / 生图 / 生视频范围，暂不入库。
- **MochiPiyo/design-decision-record**（创建 2026-11-12）：设计决策记录 Codex skill，超出范围，暂不入库。
- **54370495scj-dotcom/codex-practical-skills**（创建 2026-11-12）：7 skill 合集（游戏 Wiki / 产品 IP 设计），合集型且超出范围，暂不入库。

> 2026-11-11 复查：11-10 暂缓的 9 条（ai-ready-sites、ui-review-loop、unslop-frontend-design、systra-taste、design-skills-pack-en、atelier-ui、claude-code-ui-design、website-builder-toolkit、design-director）README 仍无参考图 / 视频，继续暂缓。

## 发现源（只作线索，不当来源）

- GitHub：anthropics/skills、openai/skills、composio-community/awesome-codex-skills（17,242★，60 skills）
- 聚合站：skills.sh、agentsuses.com、open-design.ai（244 skills / 58 仓库）、SkillsMP（200 万+ 索引，每条带 githubUrl 指回源仓库）
- Reddit：r/ChatGPTCoding、r/OpenAI、r/ClaudeAI、r/webdev、r/Design（2026-11-13 RSS 三路由均被拦：www.reddit.com 429/403、old.reddit.com 302、api.reddit.com 403，本轮覆盖缺失）

---

## 🤝 参与方式

发现新的 design skill？欢迎提 Issue，附上：
1. 原作者 / 原仓库链接（不要只贴聚合站）
2. X 原帖直链（如果有）
3. 参考图 / 视频链接
4. 一句话用途 + 属于哪个子类

## ⚠️ 免责声明

- 本库只收录公开 skill 与公开分享，stars 与互动数为核验日快照，后续会变。
- 每个 skill 的许可证、安装方式以原仓库为准；使用前请读原仓库 README。
- 参考视频直链来自原帖 / 原仓库，版权归原作者所有。

---

*核验日期：2026-11-13。每日定时更新：新增 skill 经核验后入库，0 新增也汇报当日扫描情况。*
