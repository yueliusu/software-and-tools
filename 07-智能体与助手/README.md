# 智能体与助手

[← 返回总览](../README.md)

按通用助手与编程 Agent 分组。编辑器和编程扩展见 [AI 编程工具](../06-AI编程工具/README.md)。

共 **8 项**。

<a id="contents"></a>

## 本页目录

| 分类 | 工具 / 入口 |
| --- | --- |
| [通用助手](#general-agents) | [OpenClaw（龙虾）](#tool-openclaw-龙虾) · [Hermes Agent](#tool-hermes-agent) · [MiniMax Agent](#tool-minimax-agent) |
| [编程 Agent](#coding-agents) | [Claude Code](#tool-claude-code) · [Codex / Codex CLI](#tool-codex-codex-cli) · [Gemini CLI](#tool-gemini-cli) · [Antigravity](#tool-antigravity) · [OpenCode](#tool-opencode) |

<a id="general-agents"></a>

## 通用助手

<a id="tool-openclaw-龙虾"></a>

### OpenClaw（龙虾）

**官网：[https://openclaw.ai/](https://openclaw.ai/)**

**简介**：OpenClaw 是一款 **开源 AI 个人助手/智能体系统**，主打“能真正替你执行任务”的自动化能力，可运行在本地设备上，并接入 飞书、钉钉、WhatsApp、Telegram、Discord、iMessage 等多种聊天平台，支持文件处理、浏览器操作、消息发送与多渠道工作流协同，也可结合 Claude、GPT 及本地模型使用。

<details>
<summary>查看截图</summary>

![OpenClaw（龙虾） 截图](https://i-blog.csdnimg.cn/direct/d951693161f947d5980e0ed851ed157a.png)

</details>

<a id="tool-hermes-agent"></a>

### Hermes Agent

**官网：[https://hermes-agent.nousresearch.com/](https://hermes-agent.nousresearch.com/)**

**简介**：Hermes Agent 是一款由 **Nous Research** 推出的 **开源自主 AI 智能体系统**，主打长期记忆、自我进化与自动化任务执行能力，可部署在本地或自有服务器上，并接入 Telegram、Discord 等消息平台。它支持工具调用、技能系统、MCP 扩展和多模型接入，可结合 OpenAI、Anthropic、Google、Hugging Face、Nous Portal 等模型使用，适合个人助理、项目协作、知识管理与自动化工作流场景。

<details>
<summary>查看截图</summary>

![Hermes Agent 截图](https://i-blog.csdnimg.cn/direct/b3025d0ce0fb4c7dab0a56a17b85a4d6.png)

</details>

<a id="tool-minimax-agent"></a>

### MiniMax——MiniMax Agent

**官网链接：[https://agent.minimax.io/](https://agent.minimax.io/)**

**简介**：**MiniMax**推出了包含 **MiniMax Agent、海螺AI** 等在内的一系列 AI 产品，覆盖智能助手、视频生成、语音和开发平台等方向。

<details>
<summary>查看截图</summary>

![MiniMax Agent 截图](https://i-blog.csdnimg.cn/direct/76563817eb45412980fdbeec8ba90071.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)

<a id="coding-agents"></a>

## 编程 Agent

<a id="tool-claude-code"></a>

### Claude Code

**官网链接：[https://claude.com/product/claude-code](https://claude.com/product/claude-code)**

**简介**：Claude Code 是 Anthropic 推出的 **AI 编程 Agent / 代码库助手**，可以在终端、IDE、桌面端等环境中使用。它能够理解整个代码库、读取项目上下文、编辑文件、执行多文件修改、运行命令和测试，并帮助开发者完成 bug 修复、功能开发、重构和 PR 工作。它的定位更偏向“让 Claude 直接进入你的代码仓库干活”。

<details>
<summary>查看截图</summary>

![Claude Code 截图](https://i-blog.csdnimg.cn/direct/969667cd17d246cc925a5fcaf16575af.png)

</details>

<a id="tool-codex-codex-cli"></a>

### Codex / Codex CLI

- [Codex CLI 文档](https://developers.openai.com/codex/cli)

- [Codex 官网](https://chatgpt.com/zh-Hans-CN/codex/)

- [GitHub 仓库](https://github.com/openai/codex)

**简介**：Codex / Codex CLI 是 OpenAI 推出的 **本地命令行 AI 编程助手**，可以运行在 macOS、Windows 和 Linux 上。它主要用于在本地代码仓库中进行交互式开发：读取项目、修改文件、运行命令、解释代码、修复错误、生成测试等。和 Claude Code 类似，它也是一个 coding agent，但背后接入的是 OpenAI 的模型和生态。

<details>
<summary>查看截图</summary>

![Codex / Codex CLI 截图 1](https://i-blog.csdnimg.cn/direct/665a3f84e2e643939559fceb1ac738e6.png)

![Codex / Codex CLI 截图 2](https://i-blog.csdnimg.cn/direct/ad51e7b3275345d9a06d86fe8a2b675c.png)

</details>

<a id="tool-gemini-cli"></a>

### Gemini CLI

**官网：[https://geminicli.com/](https://geminicli.com/)**

**简介**：Gemini CLI 是 Google 推出的 **开源命令行 AI Agent**，把 Gemini 模型能力直接带到终端里。它可以帮助用户进行代码理解、代码生成、文件处理、命令行自动化和项目辅助开发。相比 Claude Code 和 Codex，它更强调“轻量、开源、直接在终端调用 Gemini”，适合已经在 Google / Gemini 生态里工作的开发者。

<details>
<summary>查看截图</summary>

![Gemini CLI 截图](https://i-blog.csdnimg.cn/direct/2906fd372dff4ef28c65867695b325cf.png)

</details>

<a id="tool-antigravity"></a>

### Antigravity

**官网链接：[https://antigravity.google/](https://antigravity.google/)**

**简介**：Antigravity 是 Google 推出的 **AI 编程 Agent / Agent-first 开发平台**，定位不是单纯的代码补全工具，而是让 AI Agent 进入开发流程中，帮助开发者完成规划、编码、调试、验证和迭代。它提供类似 IDE 的编辑环境，并支持 Agent 使用编辑器、终端和浏览器来执行任务；定位更偏向“把开发任务交给 AI Agent 编排和执行”，适合功能开发、代码修改、项目验证、自动化测试和多步骤工程任务。

<details>
<summary>查看截图</summary>

![Antigravity 截图](https://i-blog.csdnimg.cn/direct/8148404bbf334773b1f6e306bbbd33e8.png)

</details>

<a id="tool-opencode"></a>

### OpenCode

**官网链接：[https://opencode.ai/](https://opencode.ai/)**

**简介**：opencode 是一款 **开源 AI coding agent**，主打开放、多模型和可定制。它类似 Claude Code、Codex 这类工具，可以在终端或开发环境中辅助读代码、改文件、运行命令、完成开发任务；不同之处在于它不强绑定某一家模型，通常可以接入多种 LLM provider，也提供面向 coding agent 优化的模型选择。适合想要开源方案、可换模型、可控性更强的开发者。

<details>
<summary>查看截图</summary>

![OpenCode 截图](https://i-blog.csdnimg.cn/direct/d3cf0f765034448c9ab508e686469700.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)
