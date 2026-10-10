# SillyTavern 插件精选（开发者视角）

Hark 为你挑的一批 SillyTavern 插件项目，按"值得读源码学什么"分类。星标数和更新时间截至 2026-10-10。

> 只收链接，不拷贝代码：部分项目没有声明许可证（标为"未声明"），借鉴代码前先确认授权。官方仓库多为 AGPL-3.0，直接复用会带上传染性条款。

## 1. 起步与脚手架

| 项目 | ★ | 语言 | 许可 | 为什么值得看 |
|---|---|---|---|---|
| [SillyTavern/Extension-ReactTemplate](https://github.com/SillyTavern/Extension-ReactTemplate) | 17 | JS | AGPL-3.0 | 官方 React + Webpack 模板，想用组件化写 UI 就从这里起步 |
| [SillyTavern/Extension-PromptInspector](https://github.com/SillyTavern/Extension-PromptInspector) | 54 | JS | AGPL-3.0 | 体量小，演示如何在发送前拦截、修改 prompt，理解生成管线的最佳入门 |
| [SillyTavern/Extension-CodeRunner](https://github.com/SillyTavern/Extension-CodeRunner) | 14 | JS | AGPL-3.0 | 在聊天代码块里跑 JS / STscript，学消息渲染钩子和 slash command 交互 |

## 2. 平台级 / 基础设施

| 项目 | ★ | 语言 | 许可 | 为什么值得看 |
|---|---|---|---|---|
| [N0VI028/JS-Slash-Runner（酒馆助手）](https://github.com/N0VI028/JS-Slash-Runner) | 1317 | TS | 自定义 | 中文圈最大的插件，给角色卡提供脚本运行环境和大量 API，几乎是"插件里的框架"，必读 |
| [bmen25124/SillyTavern-MCP-Client](https://github.com/bmen25124/SillyTavern-MCP-Client) | 97 | TS | MIT | 把 MCP 工具接进酒馆，学 tool calling 和服务端插件配合 |
| [AyeeMinerva/SillyTavern-Extension-ChatBridge](https://github.com/AyeeMinerva/SillyTavern-Extension-ChatBridge) | 48 | Python | AGPL-3.0 | WebSocket 双向桥，事件监听 + 流式转发，做外部应用联动的参考 |
| [SillyTavern/Extension-WebLLM](https://github.com/SillyTavern/Extension-WebLLM) | 24 | JS | AGPL-3.0 | 官方示范：插件如何给其他插件暴露能力（浏览器内模型） |

## 3. 记忆与上下文（最卷的赛道）

| 项目 | ★ | 语言 | 许可 | 为什么值得看 |
|---|---|---|---|---|
| [SenriYuki/SillyTavern-Horae](https://github.com/SenriYuki/SillyTavern-Horae) | 198 | JS | 未声明 | 中文记忆增强插件，看国内用户真实需求怎么落地 |
| [bal-spec/sillytavern-character-memory](https://github.com/bal-spec/sillytavern-character-memory) | 73 | JS | 未声明 | 自动抽取结构化记忆写进 Data Bank 走向量检索，思路清晰 |
| [bmen25124/SillyTavern-WorldInfo-Recommender](https://github.com/bmen25124/SillyTavern-WorldInfo-Recommender) | 130 | TS | MIT | 用 Connection Profiles 调 LLM 管理世界书，TS 工程化写法好 |

## 4. 生成流程增强

| 项目 | ★ | 语言 | 许可 | 为什么值得看 |
|---|---|---|---|---|
| [cierru/st-stepped-thinking](https://github.com/cierru/st-stepped-thinking) | 172 | JS | MIT | 角色"先思考再回复"，学如何在一次回复里插入额外生成步骤 |
| [bmen25124/SillyTavern-Magic-Translation](https://github.com/bmen25124/SillyTavern-Magic-Translation) | 35 | TS | MIT | 用 LLM 翻译聊天，代码短小，适合学消息改写 |

## 5. 游戏化 / 状态追踪 / UI

| 项目 | ★ | 语言 | 许可 | 为什么值得看 |
|---|---|---|---|---|
| [SpicyMarinara/rpg-companion-sillytavern](https://github.com/SpicyMarinara/rpg-companion-sillytavern) | 320 | JS | 自定义 | 角色、任务、背包状态追踪，复杂 UI 面板的完整案例 |
| [prolix-oc/SillyTavern-SimTracker](https://github.com/prolix-oc/SillyTavern-SimTracker) | 63 | JS | 未声明 | 把消息里的 JSON 渲染成卡片，模板 + 宏系统集成值得借鉴 |
| [Bronya-Rand/Prome-VN-Extension](https://github.com/Bronya-Rand/Prome-VN-Extension) | 63 | JS | AGPL-3.0 | 视觉小说模式，学大幅改造聊天界面 |

## 延伸

- 社区整理的总表：[Min3Mast3r4653/SillyTavern-Extensions-and-Themes](https://github.com/Min3Mast3r4653/SillyTavern-Extensions-and-Themes)
- 官方插件全集：[github.com/SillyTavern](https://github.com/SillyTavern)（以 `Extension-` 开头的仓库）
