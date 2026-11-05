<div align="center">

<img src="assets/images/ai-drama-studio-logo.svg" alt="AI Drama Studio 项目标志" width="480">

**把一个故事，拍成一部短剧。**

[![Node.js 版本](https://img.shields.io/badge/Node.js-22.13.0%2B-339933?style=flat&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vue 版本](https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js)](https://vuejs.org)
[![Electron](https://img.shields.io/badge/Electron-%E6%A1%8C%E9%9D%A2%E5%BA%94%E7%94%A8-47848F?style=flat&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![最新版本](https://img.shields.io/github/v/release/ComicDrama/ai-drama-studio?display_name=tag)](https://github.com/ComicDrama/ai-drama-studio/releases)
[![许可证：BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue?style=flat)](LICENSE)

[English](README.md) · **简体中文** · [日本語](README.ja.md) · [한국어](README.ko.md)

[功能特性](#features) • [制作流程](#workflow) • [AI 服务接入](#models) • [下载](#download) • [QQ 社群](#community) • [关于](#about)

[![下载 Windows x64 版](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe) [![官方网站](https://img.shields.io/badge/%E5%AE%98%E6%96%B9-%E7%BD%91%E7%AB%99-526B73?style=for-the-badge&logo=googlechrome&logoColor=white)](https://drama.madongdong.com)

</div>

<a id="workflow"></a>
## 从一个故事，到一集短剧

从故事灵感或现有剧本出发，在同一工作空间里完成创作、视觉开发、导演规划、视频生成和导出。少一些工具间来回切换，多一些时间打磨故事与镜头表达。

1. **导入并整理剧本**，创建项目和剧集。
2. **借助 AI 改写和润色**故事内容与对白。
3. **建立全剧资产库**，管理角色、场景、道具和角色音色参考。
4. **规划每集内容**，设置导演意图、时长规格、分镜描述和视频提示词。
5. **生成并检查分镜视频**，跟踪任务进度，再合并片段并导出本集。

<a id="features"></a>
## 为 AI 短剧创作者而设计

- **让制作环节彼此衔接。** 按项目整理剧本、剧集、可复用资产、生成任务和导出内容。
- **建立统一的视觉世界。** 在不同剧集中复用角色、场景和道具参考；角色音色可绑定到角色，并在其出现在分镜时自动带入。
- **保留导演的创作主导权。** 设置全项目的文本、图片和视频模型，也可因特殊情节调整单集导演规划。
- **从规划顺畅进入制作。** AI Agent 可协助改写剧本、提取资产、拆分分镜和撰写提示词，创意取舍仍由你决定。
- **生成前检查模型约束。** 根据所选视频模型检查分镜时长和提示词要求，减少提交生成后才发现不兼容的情况。
- 支持简体中文、English、日本語和한국어界面。

<a id="models"></a>
## 接入你选择的 AI 模型

使用你自己的服务商账号和 API 密钥，为创作流程的不同环节选择合适模型。平台不把创作限制在单一内置模型中。

- **文本创作与故事开发：** OpenAI 兼容的聊天接口、Google Gemini、火山引擎及 LK888 模型中心。
- **图片生成与编辑：** OpenAI 兼容的图片接口、Gemini 图片模型、火山引擎及 LK888 图片模型。
- **视频生成：** 火山引擎 Seedance、MiniMax H3、阿里云 Wan 3.0、AutoDL H3 及 LK888 视频模型。

模型是否可用、输入限制和具体能力取决于服务商、账号权限与所在区域。请只配置你有权使用的服务和模型；服务商账号、API 密钥及使用费用需另行准备。

<a id="download"></a>
## 下载

首个桌面版本支持 **Windows x64**，安装包约 **143 MiB**。

[![下载 Windows x64 版](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe)

当前 Windows 安装包尚未签名，首次运行时 Windows 可能显示安全提示。AI 功能会连接你在应用中配置的服务商；服务商账号、API 密钥和使用费用需另行准备。

<a id="about"></a>
## 关于

作者：[Lumosylva](https://github.com/Lumosylva) · [官方网站](https://drama.madongdong.com)

本项目采用 [BSD 3-Clause License](LICENSE) 授权。

<a id="community"></a>
## QQ 社群

[![加入 QQ 社群](https://img.shields.io/badge/QQ-%E5%8A%A0%E5%85%A5%E7%A4%BE%E7%BE%A4-12B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://qm.qq.com/q/eKbq2KPMXK)

加入 AI Drama Studio QQ 社群，与创作者交流使用体验和建议。
