<div align="center">

<img src="assets/images/ai-drama-studio-logo.svg" alt="AI Drama Studio logo" width="480">

**Turn a story into a short drama.**

[![Node Version](https://img.shields.io/badge/Node.js-22.13.0%2B-339933?style=flat&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vue Version](https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js)](https://vuejs.org)
[![Electron](https://img.shields.io/badge/Electron-Desktop%20app-47848F?style=flat&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![Latest Release](https://img.shields.io/github/v/release/ComicDrama/ai-drama-studio?display_name=tag)](https://github.com/ComicDrama/ai-drama-studio/releases)
[![License: BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue?style=flat)](LICENSE)

**English** | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

[Features](#features) • [Workflow](#workflow) • [Screenshots](#screenshots) • [AI providers](#models) • [Download](#download) • [QQ Community](#community) • [About](#about)

[![Download for Windows x64](https://img.shields.io/badge/Download-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe) [![Official website](https://img.shields.io/badge/Official-Website-526B73?style=for-the-badge&logo=googlechrome&logoColor=white)](https://drama.madongdong.com)

</div>

<a id="workflow"></a>
## From first draft to finished episode

Turn a story idea or screenplay into a production-ready short drama. AI Drama Studio connects writing, visual development, directing, video generation, and export in one workspace—so creators can spend less time moving between tools and more time shaping the story.

1. **Import and organize scripts** into projects and episodes.
2. **Rewrite and refine** story material and dialogue with AI.
3. **Build a shared asset library** for characters, locations, props, and character voice references.
4. **Plan each episode** with directing choices, duration rules, storyboard descriptions, and video prompts.
5. **Generate and review shot videos**, track task progress, then combine clips and export the episode.

<a id="features"></a>
## Made for AI short-drama creators

- **Keep the whole production connected.** Scripts, episodes, reusable assets, generation tasks, and exports stay organized by project.
- **Build a consistent visual world.** Reuse character, location, and prop references across episodes, and attach a voice reference to a character for automatic use in matching shots.
- **Direct with intention.** Set project-wide text, image, and video models, then adjust an episode’s directing plan when a story calls for it.
- **Move from plan to production.** AI agents can help rewrite scripts, extract assets, break episodes into storyboards, and draft prompts; you stay in control of the creative decisions.
- **Catch constraints before generation.** Review storyboard duration and prompt requirements against the selected video model before spending generation resources.
- Work in English, 简体中文, 日本語, or 한국어.

<a id="screenshots"></a>
## Explore the workspace

Take a look at the project workspace, then explore the setup and production flow. Expand a section to see more screens.

<p align="center"><img src="assets/images/EN/Project-Main-Interface.png" alt="AI Drama Studio project workspace" width="900"></p>

<details>
<summary>Project setup and creative tools</summary>

<p><strong>Create a project</strong></p>
<p align="center"><img src="assets/images/EN/New-Project.png" alt="Create a new drama project" width="900"></p>

<p><strong>Import a screenplay</strong></p>
<p align="center"><img src="assets/images/EN/Import-Script.png" alt="Import a screenplay into a project" width="900"></p>

<p><strong>Project settings</strong></p>
<p align="center"><img src="assets/images/EN/Project-Settings.png" alt="Configure project-wide generation settings" width="900"></p>

<p><strong>AI service configuration</strong></p>
<p align="center"><img src="assets/images/EN/Settings-AI-Service-Configuration.png" alt="Configure AI service providers and models" width="900"></p>

<p><strong>Visual style presets</strong></p>
<p align="center"><img src="assets/images/EN/Style-Presets.png" alt="Manage visual style presets" width="900"></p>

<p><strong>Agent configuration</strong></p>
<p align="center"><img src="assets/images/EN/Agent-Configuration.png" alt="Configure AI agents" width="900"></p>

<p><strong>Project-wide asset library</strong></p>
<p align="center"><img src="assets/images/EN/Full-Production-Asset-Library.png" alt="Browse characters, locations, props, and voice references across a project" width="900"></p>
</details>

<details>
<summary>Episode production workflow</summary>

<p><strong>Original story content</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Original-Content.png" alt="Review and organize episode story content" width="900"></p>

<p><strong>AI rewriting</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-AI-Rewriting.png" alt="Rewrite and refine a script with AI" width="900"></p>

<p><strong>Asset creation</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Asset-Creation.png" alt="Create character and scene assets" width="900"></p>

<p><strong>Director planning</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Director-Planning.png" alt="Plan storyboards and directing choices" width="900"></p>

<p><strong>Video production</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Production.png" alt="Generate and review storyboard videos" width="900"></p>

<p><strong>Task list</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Task-List.png" alt="Track generation task progress" width="900"></p>

<p><strong>Video export</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Export.png" alt="Combine and export an episode" width="900"></p>
</details>

<a id="models"></a>
## Connect the AI models you want to use

Bring your own provider account and API credentials, then choose the models that fit each part of your production. The app does not lock you into one bundled model catalog.

- **Writing and story development:** OpenAI-compatible chat APIs, Google Gemini, Volcengine, and the LK888 model hub.
- **Image creation and editing:** OpenAI-compatible image APIs, Gemini image models, Volcengine, and LK888 image models.
- **Video generation:** Volcengine Seedance, MiniMax H3, Alibaba Cloud Wan 3.0, AutoDL H3, and LK888 video models.

Model availability, input limits, and capabilities depend on the provider, account permissions, and region. Configure only services and models you can access; provider accounts, API credentials, and usage charges are separate.

<a id="download"></a>
## Download

The first desktop release is for **Windows x64**. The installer is approximately **143 MiB**.

[![Download for Windows x64](https://img.shields.io/badge/Download-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe)

The Windows installer is currently unsigned, so Windows may show a security prompt when you first run it. AI features connect to the provider you configure in the app; provider accounts, API credentials, and usage charges are separate.

<a id="about"></a>
## About

Created by [Lumosylva](https://github.com/Lumosylva) · [Official website](https://drama.madongdong.com)

Licensed under the [BSD 3-Clause License](LICENSE).

<a id="community"></a>
## QQ Community

[![Join the QQ community](https://img.shields.io/badge/QQ-Join%20community-12B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://qm.qq.com/q/eKbq2KPMXK)

Join the AI Drama Studio QQ community to share feedback and connect with other creators.
