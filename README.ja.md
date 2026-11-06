<div align="center">

<img src="assets/images/ai-drama-studio-logo.svg" alt="AI Drama Studio ロゴ" width="480">

**物語をショートドラマに。**

[![Node.js バージョン](https://img.shields.io/badge/Node.js-22.13.0%2B-339933?style=flat&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vue バージョン](https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js)](https://vuejs.org)
[![Electron](https://img.shields.io/badge/Electron-%E3%83%87%E3%82%B9%E3%82%AF%E3%83%88%E3%83%83%E3%83%97%E3%82%A2%E3%83%97%E3%83%AA-47848F?style=flat&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![最新リリース](https://img.shields.io/github/v/release/ComicDrama/ai-drama-studio?display_name=tag)](https://github.com/ComicDrama/ai-drama-studio/releases)
[![ライセンス：BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue?style=flat)](LICENSE)

[English](README.md) · [简体中文](README.zh-CN.md) · **日本語** · [한국어](README.ko.md)

[機能](#features) • [制作の流れ](#workflow) • [画面紹介](#screenshots) • [AI サービス](#models) • [ダウンロード](#download) • [QQ コミュニティ](#community) • [クレジット](#about)

[![Windows x64 版をダウンロード](https://img.shields.io/badge/%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe) [![公式サイト](https://img.shields.io/badge/%E5%85%AC%E5%BC%8F-%E3%82%B5%E3%82%A4%E3%83%88-526B73?style=for-the-badge&logo=googlechrome&logoColor=white)](https://drama.madongdong.com)

</div>

<a id="workflow"></a>
## アイデアからショートドラマの完成まで

物語のアイデアや脚本を出発点に、執筆、ビジュアル開発、演出プラン、動画生成、書き出しまでを一つのワークスペースでつなぎます。ツール間の移動を減らし、物語やショットの表現に集中できます。

1. **脚本を読み込み、整理**してプロジェクトとエピソードを作成します。
2. AI でストーリーや台詞を**書き換え、ブラッシュアップ**します。
3. キャラクター、ロケーション、小道具、キャラクターの音声リファレンスを**共有アセットライブラリ**で管理します。
4. 演出方針、尺のルール、ストーリーボードの説明、動画プロンプトを使って**各エピソードを計画**します。
5. ショット動画を**生成・確認**し、タスクの進捗を追跡してから、クリップを結合しエピソードを書き出します。

<a id="features"></a>
## AI ショートドラマのクリエイター向け

- **制作の流れをひとつに。** 脚本、エピソード、再利用できるアセット、生成タスク、書き出しをプロジェクト単位で管理します。
- **作品のビジュアルに一貫性を。** キャラクター、ロケーション、小道具の参照素材を複数エピソードで再利用できます。キャラクターに音声リファレンスを紐付けると、登場するショットに自動で適用されます。
- **演出の主導権はクリエイターに。** プロジェクト共通のテキスト・画像・動画モデルを設定し、物語に合わせて特定エピソードの演出プランを調整できます。
- **プランから制作へスムーズに。** AI Agent が脚本の推敲、アセット抽出、ストーリーボード分割、プロンプト作成を支援します。創作上の判断はあなたが行えます。
- **生成前にモデルの制約を確認。** 選択した動画モデルの尺やプロンプト要件を事前に確認し、生成を始めてから互換性の問題に気付くリスクを減らします。
- English、简体中文、日本語、한국어の UI に対応しています。

<a id="screenshots"></a>
## 制作ワークスペースを見る

プロジェクト画面を紹介します。各セクションを開くと、設定からエピソード制作までの画面をご覧いただけます。スクリーンショットは英語 UI です。

<p align="center"><img src="assets/images/EN/Project-Main-Interface.png" alt="AI Drama Studio のプロジェクト画面" width="900"></p>

<details>
<summary>プロジェクト設定と創作ツール</summary>

<p><strong>プロジェクトを新規作成</strong></p>
<p align="center"><img src="assets/images/EN/New-Project.png" alt="ショートドラマのプロジェクトを新規作成" width="900"></p>

<p><strong>脚本をインポート</strong></p>
<p align="center"><img src="assets/images/EN/Import-Script.png" alt="プロジェクトに脚本をインポート" width="900"></p>

<p><strong>プロジェクト設定</strong></p>
<p align="center"><img src="assets/images/EN/Project-Settings.png" alt="プロジェクト共通の生成設定" width="900"></p>

<p><strong>AI サービス設定</strong></p>
<p align="center"><img src="assets/images/EN/Settings-AI-Service-Configuration.png" alt="AI サービスとモデルを設定" width="900"></p>

<p><strong>ビジュアルスタイル</strong></p>
<p align="center"><img src="assets/images/EN/Style-Presets.png" alt="ビジュアルスタイルのプリセットを管理" width="900"></p>

<p><strong>Agent 設定</strong></p>
<p align="center"><img src="assets/images/EN/Agent-Configuration.png" alt="AI Agent を設定" width="900"></p>

<p><strong>プロジェクト全体のアセットライブラリ</strong></p>
<p align="center"><img src="assets/images/EN/Full-Production-Asset-Library.png" alt="プロジェクト内のキャラクター、ロケーション、小道具、音声リファレンスを管理" width="900"></p>
</details>

<details>
<summary>エピソード制作の流れ</summary>

<p><strong>ストーリー素材</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Original-Content.png" alt="エピソードのストーリー内容を整理" width="900"></p>

<p><strong>AI リライト</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-AI-Rewriting.png" alt="AI で脚本をリライトして推敲" width="900"></p>

<p><strong>アセット制作</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Asset-Creation.png" alt="キャラクターとシーンのアセットを制作" width="900"></p>

<p><strong>演出プラン</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Director-Planning.png" alt="ストーリーボードと演出方針を計画" width="900"></p>

<p><strong>動画制作</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Production.png" alt="ショット動画を生成して確認" width="900"></p>

<p><strong>タスクリスト</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Task-List.png" alt="生成タスクの進捗を確認" width="900"></p>

<p><strong>動画を書き出す</strong></p>
<p align="center"><img src="assets/images/EN/Workflow-Video-Export.png" alt="エピソード動画を結合して書き出す" width="900"></p>
</details>

<a id="models"></a>
## 好みの AI モデルを接続

利用するサービスのアカウントと API キーを設定し、制作工程ごとにモデルを選べます。単一の内蔵モデルだけに制作を限定しません。

- **文章制作・ストーリー開発：** OpenAI 互換のチャット API、Google Gemini、Volcengine、LK888 モデルハブ。
- **画像生成・編集：** OpenAI 互換の画像 API、Gemini の画像モデル、Volcengine、LK888 の画像モデル。
- **動画生成：** Volcengine Seedance、MiniMax H3、Alibaba Cloud Wan 3.0、AutoDL H3、LK888 の動画モデル。

利用可能なモデル、入力制限、機能はサービス提供元、アカウント権限、地域によって異なります。利用権限のあるサービスとモデルを設定してください。サービスのアカウント、API キー、利用料金は別途必要です。

<a id="download"></a>
## ダウンロード

最初のデスクトップ版は **Windows x64** に対応しています。インストーラーのサイズは約 **143 MiB** です。

[![Windows x64 版をダウンロード](https://img.shields.io/badge/%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89-Windows%20x64-2E8B83?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ComicDrama/ai-drama-studio/releases/download/v0.0.1/AIDramaStudio.Setup.0.0.1.exe)

現在の Windows インストーラーには署名がありません。初回起動時に Windows のセキュリティ警告が表示される場合があります。AI 機能を利用するには、アプリ内で設定するプロバイダーのアカウントと API キーが必要です。利用料金は各プロバイダーの条件に従います。

<a id="about"></a>
## クレジット

作者：[Lumosylva](https://github.com/Lumosylva) · [公式サイト](https://drama.madongdong.com)

[BSD 3-Clause License](LICENSE) のもとで公開されています。

<a id="community"></a>
## QQ コミュニティ

[![QQ コミュニティに参加](https://img.shields.io/badge/QQ-%E3%82%B3%E3%83%9F%E3%83%A5%E3%83%8B%E3%83%86%E3%82%A3%E3%81%AB%E5%8F%82%E5%8A%A0-12B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://qm.qq.com/q/eKbq2KPMXK)

AI Drama Studio の QQ コミュニティで、使用感やご意見を共有し、ほかのクリエイターと交流できます。
