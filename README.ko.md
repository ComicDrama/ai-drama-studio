<div align="center">

<img src="assets/images/ai-drama-studio-logo.svg" alt="AI Drama Studio 로고" width="480">

**이야기를 숏드라마로 만드세요.**

[![Node.js 버전](https://img.shields.io/badge/Node.js-22.13.0%2B-339933?style=flat&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vue 버전](https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js)](https://vuejs.org)
[![Electron](https://img.shields.io/badge/Electron-%EB%8D%B0%EC%8A%A4%ED%81%AC%ED%86%B1%20%EC%95%B1-47848F?style=flat&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![최신 릴리스](https://img.shields.io/github/v/release/ComicDrama/ai-drama-studio?display_name=tag)](https://github.com/ComicDrama/ai-drama-studio/releases)
[![라이선스: BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue?style=flat)](LICENSE)

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · **한국어**

[기능](#features) • [제작 과정](#workflow) • [화면 소개](#screenshots) • [AI 서비스](#models) • [다운로드](#download) • [QQ 커뮤니티](#community) • [소개](#about)

[![Windows x64 다운로드](https://img.shields.io/badge/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe) [![공식 웹사이트](https://img.shields.io/badge/%EA%B3%B5%EC%8B%9D-%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8-526B73?style=for-the-badge&logo=googlechrome&logoColor=white)](https://drama.madongdong.com)

</div>

<a id="workflow"></a>
## 이야기 구상부터 숏드라마 완성까지

이야기 아이디어나 대본에서 출발해 집필, 비주얼 개발, 연출 기획, 영상 생성, 내보내기까지 하나의 작업 공간에서 이어 가세요. 도구 사이를 오가는 시간은 줄이고 이야기와 장면 표현에 더 집중할 수 있습니다.

1. 대본을 **가져오고 정리**해 프로젝트와 에피소드를 만듭니다.
2. AI로 이야기와 대사를 **다듬고 다시 씁니다**.
3. 캐릭터, 장소, 소품, 캐릭터 음성 참고 자료를 **공유 에셋 라이브러리**에서 관리합니다.
4. 연출 의도, 길이 규칙, 장면 설명, 영상 프롬프트로 **에피소드를 계획**합니다.
5. 장면별 영상을 **생성하고 검토**하며 작업 진행을 확인한 뒤, 클립을 합쳐 에피소드를 내보냅니다.

<a id="features"></a>
## AI 숏드라마 창작자를 위한 기능

- **제작 과정을 하나로 연결합니다.** 대본, 에피소드, 재사용 에셋, 생성 작업과 내보내기를 프로젝트별로 정리합니다.
- **작품의 비주얼을 일관되게 유지합니다.** 캐릭터, 장소, 소품 참고 자료를 여러 에피소드에서 재사용하고, 캐릭터 음성 참고 자료를 연결해 해당 캐릭터가 등장하는 장면에 자동 적용할 수 있습니다.
- **연출의 주도권은 창작자에게 있습니다.** 프로젝트 기본 텍스트·이미지·동영상 모델을 설정하고, 이야기에 따라 특정 에피소드의 연출 계획을 조정할 수 있습니다.
- **기획에서 제작으로 자연스럽게 이어집니다.** AI Agent가 대본 다듬기, 에셋 추출, 스토리보드 분할, 프롬프트 작성을 돕지만 창작 방향은 직접 결정합니다.
- **생성 전에 모델 제한을 확인합니다.** 선택한 동영상 모델의 길이와 프롬프트 요구 사항을 미리 점검해 생성 요청 후 호환성 문제를 발견할 가능성을 줄입니다.
- English, 简体中文, 日本語, 한국어 UI를 지원합니다.

<a id="screenshots"></a>
## 작업 공간 둘러보기

프로젝트 화면을 먼저 살펴보고, 각 섹션을 열어 설정부터 에피소드 제작까지의 화면을 확인해 보세요. 스크린샷은 영어 UI입니다.

<p align="center"><img src="assets/images/EN/Project-Main-Interface.png" alt="AI Drama Studio 프로젝트 작업 공간" width="900"></p>

<details>
<summary>프로젝트 설정 및 창작 도구</summary>

<p><strong>새 프로젝트 만들기</strong></p>
<p align="center"><img src="assets/images/EN/New-Project.png" alt="숏드라마 프로젝트 만들기" width="900"></p>

<p><strong>대본 가져오기</strong></p>
<p align="center"><img src="assets/images/EN/Import-Script.png" alt="프로젝트에 대본 가져오기" width="900"></p>

<p><strong>프로젝트 설정</strong></p>
<p align="center"><img src="assets/images/EN/Project-Settings.png" alt="프로젝트 공통 생성 설정 구성" width="900"></p>

<p><strong>AI 서비스 설정</strong></p>
<p align="center"><img src="assets/images/EN/Settings-AI-Service-Configuration.png" alt="AI 서비스 제공업체와 모델 설정" width="900"></p>

<p><strong>비주얼 스타일 프리셋</strong></p>
<p align="center"><img src="assets/images/EN/Style-Presets.png" alt="비주얼 스타일 프리셋 관리" width="900"></p>

<p><strong>Agent 설정</strong></p>
<p align="center"><img src="assets/images/EN/Agent-Configuration.png" alt="AI Agent 구성" width="900"></p>

<p><strong>프로젝트 전체 에셋 라이브러리</strong></p>
<p align="center"><img src="assets/images/EN/Full-Production-Asset-Library.png" alt="프로젝트의 캐릭터, 장소, 소품 및 음성 참고 자료 관리" width="900"></p>
</details>

<details>
<summary>에피소드 제작 과정</summary>

<p><strong>원본 스토리 내용</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Original-Content.png" alt="에피소드 스토리 내용 정리" width="900"></p>

<p><strong>AI 대본 수정</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-AI-Rewriting.png" alt="AI로 대본 수정 및 다듬기" width="900"></p>

<p><strong>에셋 제작</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Asset-Creation.png" alt="캐릭터와 장면 에셋 제작" width="900"></p>

<p><strong>연출 기획</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Director-Planning.png" alt="스토리보드와 연출 방향 계획" width="900"></p>

<p><strong>영상 제작</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Production.png" alt="장면별 영상 생성 및 검토" width="900"></p>

<p><strong>작업 목록</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Task-List.png" alt="생성 작업 진행 상황 확인" width="900"></p>

<p><strong>영상 내보내기</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Export.png" alt="에피소드 영상 결합 및 내보내기" width="900"></p>
</details>

<a id="models"></a>
## 원하는 AI 모델 연결

사용할 서비스 계정과 API 키를 설정하고 제작 단계별로 적합한 모델을 선택하세요. 특정 내장 모델 하나에 제작을 제한하지 않습니다.

- **글쓰기 및 스토리 개발:** OpenAI 호환 채팅 API, Google Gemini, Volcengine, LK888 모델 허브.
- **이미지 생성 및 편집:** OpenAI 호환 이미지 API, Gemini 이미지 모델, Volcengine, LK888 이미지 모델.
- **동영상 생성:** Volcengine Seedance, MiniMax H3, Alibaba Cloud Wan 3.0, AutoDL H3, LK888 동영상 모델.

사용 가능한 모델, 입력 제한 및 기능은 서비스 제공업체, 계정 권한, 지역에 따라 다릅니다. 이용 권한이 있는 서비스와 모델만 설정하세요. 서비스 계정, API 키, 사용 요금은 별도입니다.

<a id="download"></a>
## 다운로드

첫 데스크톱 버전은 **Windows x64**를 지원합니다. 설치 파일 크기는 약 **143 MiB**입니다.

[![Windows x64 다운로드](https://img.shields.io/badge/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe)

현재 Windows 설치 파일은 서명되지 않았으므로 처음 실행할 때 Windows 보안 경고가 표시될 수 있습니다. AI 기능은 앱에서 설정한 서비스 제공업체에 연결됩니다. 제공업체 계정, API 키, 사용 요금은 별도입니다.

<a id="about"></a>
## 소개

제작: [Lumosylva](https://github.com/Lumosylva) · [공식 웹사이트](https://drama.madongdong.com)

[BSD 3-Clause License](LICENSE)를 따릅니다.

<a id="community"></a>
## QQ 커뮤니티

[![QQ 커뮤니티 참여](https://img.shields.io/badge/QQ-%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%EC%B0%B8%EC%97%AC-12B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://qm.qq.com/q/eKbq2KPMXK)

AI Drama Studio QQ 커뮤니티에서 사용 경험과 의견을 나누고 다른 창작자들과 교류해 보세요.
