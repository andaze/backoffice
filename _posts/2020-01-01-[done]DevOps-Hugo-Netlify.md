---
title: "Hugo + NetlifyをAzure DevOpsで使う"
---

Azure DevOps のリポジトリから、Hugo で Netlify へデプロイする手順です。

# 仕様

## デプロイの流れ

- Azure DevOps > Hugo > Netlify

## リポジトリ

- \$/Andaze/Docs とする（D は大文字）

## テーマ

- Docsy by Google
- [デモサイト](https://www.docsy.dev/)
- [Hugo の Docsy 紹介ページ](https://themes.gohugo.io/docsy/)
- [Github のページ](https://github.com/google/docsy)

## デプロイする場所

- docs.andaze.com

# 関連するプラグイン

- [Azure DevOps の Hugo プラグイン](https://marketplace.visualstudio.com/items?itemName=giuliovdev.hugo-extension)

- [Azure DevOps の Netlify プラグイン](https://marketplace.visualstudio.com/items?itemName=aliencube.netlify-cli-extensions)

## 関連するブログ

- 設定についての質問 [Netlify コミュニティ Azure DevOps+Netlify+Hugo](https://community.netlify.com/t/azure-devops-netlify-hugo/2205)
