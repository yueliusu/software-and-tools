# AI 编程工具

[← 返回总览](../README.md)

编辑器、编程扩展、在线开发，以及 AI 配置管理、模型网关与用量监控工具。编程 Agent 见[智能体与助手](../07-智能体与助手/README.md#coding-agents)，传统 IDE 见[开发与虚拟机](../01-桌面软件/README.md#development)。

共 **14 项**。

<a id="contents"></a>

## 本页目录

| 分类 | 工具 / 入口 |
| --- | --- |
| [编辑器与开发平台](#coding-tools) | [Cursor](#tool-cursor) · [Kiro](#tool-kiro) · [Trae](#tool-trae) · [GitHub Copilot](#tool-github-copilot) · [Replit](#tool-replit) |
| [配置与账号管理](#configuration-management) | [CC Switch](#tool-cc-switch) · [Magpie](#tool-magpie) · [Antigravity Tools](#tool-antigravity-tools) |
| [模型路由与 API 网关](#model-gateways) | [Claude Code Router](#tool-claude-code-router) · [CLIProxyAPI](#tool-cliproxyapi) · [New API](#tool-new-api) · [LiteLLM](#tool-litellm) |
| [用量与额度监控](#usage-monitoring) | [CodexBar](#tool-codexbar) · [ccusage](#tool-ccusage) |

<a id="coding-tools"></a>

## 编辑器与开发平台

<a id="tool-cursor"></a>

### Cursor

**官网：[https://cursor.sh/](https://cursor.sh/)**

**简介**：基于 VS Code 深度集成的 **AI 原生 IDE**，内置大模型代码补全、重构与对话能力，支持上下文理解与整仓库分析，适用于高效软件开发。

<details>
<summary>查看截图</summary>

![Cursor 截图](https://i-blog.csdnimg.cn/direct/56e5ec4992044e99b02ba1a937d88ce0.png)

</details>

<a id="tool-kiro"></a>

### Kiro

**官网：[https://kiro.dev/](https://kiro.dev/)**

**简介**：面向开发者打造的 **AI 编程助手 IDE**，支持自然语言生成代码、调试与项目理解，强调协作式编程体验与自动化工作流支持。

<details>
<summary>查看截图</summary>

![Kiro 截图](https://i-blog.csdnimg.cn/direct/d8022ba50ba84455a3a4c7d7c3b9d635.png)

</details>

<a id="tool-trae"></a>

### Trae

**官网：[https://www.trae.ai/](https://www.trae.ai/)**

**简介**：字节推出的 **AI 智能编程工具**，集成代码生成、修改与理解能力，支持多语言开发环境，提升开发效率与交互式编程体验。

<details>
<summary>查看截图</summary>

![Trae 截图](https://i-blog.csdnimg.cn/direct/f7aaabace6054f4fa6b8a20922e6fec2.png)

</details>

<a id="tool-github-copilot"></a>

### GitHub Copilot

**官网：[https://github.com/features/copilot](https://github.com/features/copilot)**

**简介**：GitHub 推出的 **AI 编程开发环境**，结合 Copilot 代码生成能力与项目级理解，支持从需求到代码的自动化生成与协作开发。

<details>
<summary>查看截图</summary>

![GitHub Copilot 截图](https://i-blog.csdnimg.cn/direct/ffc7e9148b214395b5819a71a4c63499.png)

</details>

<a id="tool-replit"></a>

### Replit

**官网：[https://replit.com/](https://replit.com/)**

**简介**：基于云端的 **AI 编程 IDE**，支持在线开发与实时协作，内置 AI 代码生成、调试与部署能力，适合快速原型与团队协作。

<details>
<summary>查看截图</summary>

![Replit 截图](https://i-blog.csdnimg.cn/direct/c55e0bd04a6c40e8ac5da25d96aff59e.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)

<a id="configuration-management"></a>

## 配置与账号管理

<a id="tool-cc-switch"></a>

### CC Switch

**入口**：[官网](https://ccswitch.io/) · [GitHub 仓库](https://github.com/farion1231/cc-switch) · [下载安装](https://github.com/farion1231/cc-switch/releases/latest)

**简介**：CC Switch 是面向 Claude Code、Codex、Gemini CLI 等 AI 编程工具的开源桌面管理器，支持通过图形界面切换 **API 服务商与模型配置**。它还可以集中管理 MCP、Skills 和提示词，适合同时使用多个编程助手或多个服务商、需要经常切换配置的用户。

<details>
<summary>查看官方截图</summary>

![CC Switch 主界面](https://raw.githubusercontent.com/farion1231/cc-switch/main/assets/release-notes/v4.0.0/main-zh.png)

</details>

<a id="tool-magpie"></a>

### Magpie

**入口**：[官网](https://usemagpie.ai/) · [GitHub 仓库](https://github.com/yetone/magpie) · [下载安装](https://github.com/yetone/magpie-releases/releases/latest) · [使用文档](https://usemagpie.ai/docs/start)

**简介**：Magpie 是一款开源的 **AI 模型接入与服务管理工具**，通过本地网关把多个模型服务商、订阅账号与本地模型接入 Claude Code、Codex、Gemini CLI 等工具。它支持模型切换、多账号管理、额度与用量监控，并可在配置了备用账号或路由组时自动切换，适合集中管理多个 AI 工具和服务。

<details>
<summary>查看官方截图</summary>

![Magpie 模型与 Agent 管理界面](https://raw.githubusercontent.com/yetone/magpie/main/site/public/img/agents-light.png)

</details>

<a id="tool-antigravity-tools"></a>

### Antigravity Tools

**入口**：[项目主页](https://lbjlaq.github.io/Antigravity-Manager/) · [GitHub 仓库](https://github.com/lbjlaq/Antigravity-Manager) · [下载安装](https://github.com/lbjlaq/Antigravity-Manager/releases/latest)

**形态**：桌面应用（Windows、macOS、Linux）。

**简介**：Antigravity Tools 是面向 Antigravity 的第三方账号管理工具，支持集中查看账号状态、剩余额度并切换账号。它也提供本地 API 代理、协议转换和模型路由功能，适合需要管理多个账号并连接其他 AI 客户端的用户。

<details>
<summary>查看官方截图</summary>

![Antigravity Tools 账号与额度看板](https://raw.githubusercontent.com/lbjlaq/Antigravity-Manager/main/docs/images/dashboard-light.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)

<a id="model-gateways"></a>

## 模型路由与 API 网关

<a id="tool-claude-code-router"></a>

### Claude Code Router

**入口**：[官方文档](https://ccrdesk.top/) · [GitHub 仓库](https://github.com/musistudio/claude-code-router) · [下载安装](https://github.com/musistudio/claude-code-router/releases/latest)

**形态**：桌面应用（Windows、macOS、Linux）、命令行工具，也可部署为服务。

**简介**：Claude Code Router（CCR）为 Claude Code、Codex 等编程助手提供统一的本地模型入口，集中管理服务商、模型与路由规则。它支持按请求条件选择模型、配置备用模型、查看请求日志与费用估算，适合需要灵活组合多个模型服务的开发者。

<details>
<summary>查看官方截图</summary>

![Claude Code Router 桌面控制台](https://raw.githubusercontent.com/musistudio/claude-code-router/main/blog/images/claude-code-router.png)

</details>

<a id="tool-cliproxyapi"></a>

### CLIProxyAPI

**入口**：[官方文档](https://help.router-for.me/) · [GitHub 仓库](https://github.com/router-for-me/CLIProxyAPI) · [下载发布包](https://github.com/router-for-me/CLIProxyAPI/releases/latest)

**形态**：可在本地或服务器运行的 API 代理服务。

**简介**：CLIProxyAPI 将多个 AI 服务来源接入统一代理，提供 OpenAI、Claude、Gemini 等兼容接口，便于已有客户端或程序调用。它支持多账号接入、轮询负载均衡、流式响应与工具调用，适合希望统一管理模型连接、把多个服务接到同一套应用中的用户。

<a id="tool-new-api"></a>

### New API

**入口**：[官网](https://www.newapi.ai/) · [GitHub 仓库](https://github.com/QuantumNous/new-api) · [部署指南](https://docs.newapi.ai/en/docs/installation)

**形态**：可自行部署的网关服务与网页管理控制台。

**简介**：New API 将多个模型服务统一接入，并通过网页控制台管理模型路由、访问权限、额度、使用记录和费用。适合需要给应用或团队统一提供模型接口、管理多个上游服务的开发者。

<details>
<summary>查看官方截图</summary>

![New API 中文管理看板（官方模拟数据）](https://raw.githubusercontent.com/QuantumNous/new-api/main/assets/screenshots/dashboard.zh-CN.jpg)

</details>

<a id="tool-litellm"></a>

### LiteLLM

**入口**：[官方文档](https://docs.litellm.ai/docs/) · [GitHub 仓库](https://github.com/BerriAI/litellm) · [网关部署入门](https://docs.litellm.ai/docs/proxy/docker_quick_start)

**形态**：Python SDK，以及可自行部署的网关服务与网页管理界面。

**简介**：LiteLLM 让应用通过统一接口调用不同厂商的模型，并提供模型路由、负载均衡、虚拟密钥、预算与费用统计。适合需要把多模型调用集成进应用，或为团队集中管理模型访问的开发者。

<details>
<summary>查看官方截图</summary>

![LiteLLM 虚拟密钥管理界面](https://docs.litellm.ai/assets/ideal-img/litellm_ui_create_key.528a8da.640.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)

<a id="usage-monitoring"></a>

## 用量与额度监控

<a id="tool-codexbar"></a>

### CodexBar

**入口**：[官网](https://codexbar.app/) · [GitHub 仓库](https://github.com/steipete/CodexBar) · [下载安装](https://github.com/steipete/CodexBar/releases/latest)

**形态**：桌面监控应用与命令行工具（macOS、Linux）。

**简介**：CodexBar 集中显示 Codex、Claude Code 等 AI 服务的订阅额度、重置倒计时与用量，方便随时查看剩余可用量。它还可根据支持的数据源展示费用与历史趋势，适合经常使用多个 AI 服务、希望在菜单栏或桌面上关注额度的用户。

<details>
<summary>查看官方截图</summary>

![CodexBar 用量与额度面板](https://raw.githubusercontent.com/steipete/CodexBar/main/docs/codexbar.png)

</details>

<a id="tool-ccusage"></a>

### ccusage

**入口**：[官网](https://ccusage.com/) · [GitHub 仓库](https://github.com/ccusage/ccusage) · [安装说明](https://ccusage.com/guide/installation)

**形态**：命令行工具（Windows、macOS、Linux）。

**简介**：ccusage 读取 Claude Code、Codex、OpenCode 等工具生成的本地记录，按日、周、月和会话汇总 Token 使用量与费用估算。支持表格和 JSON 输出，适合分析哪些项目或会话消耗较多；费用按模型价格估算，可用于了解本地用量趋势。

<details>
<summary>查看官方截图</summary>

![ccusage 命令行用量统计](https://raw.githubusercontent.com/ccusage/ccusage/main/docs/public/screenshot.png)

</details>

[↑ 返回本页目录](#contents) · [返回总览](../README.md)
