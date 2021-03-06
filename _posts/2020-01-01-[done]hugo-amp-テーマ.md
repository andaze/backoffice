---
title: "Hugoで一番いいAMPテーマの選び方とその結果"
categories: freee
---

Hugo の AMP でテーマを選ぶ方法について書きます。

次の情報を参考としました。

## AMP の概要

SEO ラボ [AMP とは？AMP の導入方法から SEO 効果まで解説！](https://seolaboratory.jp/25666/#p01c)

## AMP のテーマ

公式に 3 の AMP サイトが紹介されている [AMP テーマ](https://themes.gohugo.io/tags/amp/)

2017 年の日本人ブログで紹介されていた AMP 対応テーマ [Robust](https://github.com/dim0627/hugo_theme_robust)

## Hugo の AMP 対応

Output フォーマットのブログ [Hugo v0.20 で AMP が扱いやすくなりました](https://42-design.work/technology/hugo-supported-output-formats/)

Output フォーマット公式 [Custom Output Formats](https://gohugo.io/templates/output-formats/)

テーマに AMP 出力を追加するブログ [AMP 対応テンプレートを作成する](https://nasust.com/hugo/create_template/amp/)

## スタンドアロン AMP について

AMP だけで構成するサイト。カノニカル AMP、ネイティブ AMP とも呼ばれる。AMP と非 AMP のコンテンツが混在するサイトは、検索から最初にたどり着いた AMP ページは速いが、その後の内部リンクは通常ページのため速度が遅くなる。スタンドアロン AMP なら、すべてが AMP ページなのでリンクを含めてサイト全体で速くなる。

[レスポンシブな AMP ページを作成する](https://amp.dev/ja/documentation/guides-and-tutorials/develop/style_and_layout/responsive_design/)

スタンドアロン AMP について簡単に説明 [スタンドアロン AMP ページのつくりかた](https://miii.me/2622.html)

AMP のメリット解説 [EC サイトは Canonical AMP にすべし](https://ischool.co.jp/2018-06-06/)

[AMP 対応したページだけを Google に公開しても問題なし、別 URL 構成のモバイルサイトでは PC 向けページに rel=amphtml を設置](https://www.suzukikenichi.com/blog/creating-amp-only-pages-is-fine/)

AMP で作られたデスクトップサイト [amp.dev](https://amp.dev)

[リアルガチにヤバい AMP Start](https://qiita.com/am_/items/20b7478e9fb86d2acbfd)

[フル AMP の WordPress テーマを公開した件](https://qiita.com/lqd_jp/items/9017f4919fcdcaf5eabf) [liquid amp テーマ wordpress](https://lqd.jp/wp/liquid_amp.html)

hugo-lamp で作った日本語サイト [シリコンバレーのエンジニアですって言いたい人のブログ](https://blog.cleverdog.me/) [AMP チェッカー](https://search.google.com/test/amp)でも有効と判定。

|                   | モバイル | デスクトップ |
| ----------------- | -------- | ------------ |
| PageSpeed Insites | 97       | 100          |

## テーマの人気比較

| テーマ名           | Star | Fork | デモ                                                     |
| ------------------ | ---- | ---- | -------------------------------------------------------- |
| Amperage           | 22   | 9    | [デモ](https://themes.gohugo.io/theme/amperage/)         |
| Doors              | 7    | 3    | [デモ](https://themes.gohugo.io/theme/hugo-theme-doors/) |
| hugo-lamp          | 37   | 22   | [デモ](https://themes.gohugo.io/hugo-lamp/)              |
| amp                | 52   | 30   | なし                                                     |
| robust             | 128  | 62   | なし                                                     |
| GOHUGO AMP TOOLBOX | 181  | 51   | [デモ](https://gohugo-amp.gohugohq.com/)                 |

2020 年 2 月現在

## 結論

[テーマ Hugo Lamp](https://themes.gohugo.io/hugo-lamp/)でいい。スタンドアローン AMP。robust はたぶん非スタンドアロンの AMP サイト。
