# hiro-hrtk.github.io

個人サイト。GitHub Pages で `https://hiro-hrtk.github.io/` に公開している。

## 構成

| パス | 内容 |
| --- | --- |
| `/` | トップページ |
| `/gcal/` | gcal（Google カレンダー操作ツール）のホームページ |
| `/gcal/privacy.html` | gcal のプライバシーポリシー |

## 用途

`/gcal/` 配下の2ページは、Google Cloud の OAuth 同意画面に登録する
**ホームページ URL** と **プライバシーポリシー URL** として使っている。
本番公開（publishing status: In production）にはこの2つの URL が必須で、
そのドメインは Google Search Console で所有権を確認しておく必要がある。

記載内容はツールの実際の挙動と一致させること。挙動を変えたら
プライバシーポリシーも直す。
