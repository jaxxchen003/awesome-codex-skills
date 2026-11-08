# Codex Design Skills 🎨

> 专注 **Codex / Agent Skills** 的 design 类优秀 skill 合集：网页设计、生图、生视频、动效与设计系统。
> 先聚焦 design，后续再扩到其他方向。
> 仓库：https://github.com/jaxxchen003/awesome-codex-skills

📊 **收录 skill：28** ｜ 🕐 **最后更新：2026-11-09** ｜ 🤖 每日定时更新 ｜ 🌐 **在线预览站：https://jaxxchen003.github.io/awesome-codex-skills/**

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

> Reddit 线本轮覆盖缺口（诚实说明）：2026-11-09 实测 r/ChatGPTCoding、r/OpenAI、r/ClaudeAI、r/webdev、r/Design 的 new RSS 两次尝试全部 403，本轮仍无任何一条 Reddit 原帖直链，未编造。X 线：agent-reach CLI 本轮无法运行（不在 PATH，Python 入口缺 loguru 依赖），改用 web search 扫 X 相关新帖，未发现过去 24 小时内新发布的 design skill 原帖。

---

## 📑 目录

- [🌐 网页设计](#-网页设计)（17）
- [🖼️ 生图](#️-生图)（4）
- [🎬 生视频](#-生视频)（7）
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
- **参考视频**：原帖 39.3 秒演示 https://video.twimg.com/amplify_video/2056751127643734016/vid/avc1/1920x1080/5gmXVphI25MlG.mp4?tag=29 ；README 含 10 个主题成品图，官网 usehallmark.com
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
- **参考视频**：README 18 秒产品演示 https://github.com/user-attachments/assets/9c0b9150-876c-46cf-9f29-7a22a7e907b4 ；4K MP4：https://github.com/EVEDensity/Liquid-Glass-Skill/raw/refs/heads/main/docs/media/liquid-glass-ui-demo.mp4
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
- **参考视频**：原帖 36.2 秒演示 https://video.twimg.com/amplify_video/2079118623243960320/vid/avc1/1280x720/DV5UEEk2hvip2Q.mp4?tag=29 ；Gallery 站 150 个动态预览、Showcase 视频、README 20+ 张镜头示例图
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

## 发现源（只作线索，不当来源）

- GitHub：anthropics/skills、openai/skills、composio-community/awesome-codex-skills（17,242★，60 skills）
- 聚合站：skills.sh、agentsuses.com、open-design.ai（244 skills / 58 仓库）、SkillsMP（200 万+ 索引，每条带 githubUrl 指回源仓库）
- Reddit：r/ChatGPTCoding、r/OpenAI、r/ClaudeAI、r/webdev、r/Design（本轮 RSS 429/403，无直链）

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

*核验日期：2026-11-09。每日定时更新：新增 skill 经核验后入库，0 新增也汇报当日扫描情况。*
