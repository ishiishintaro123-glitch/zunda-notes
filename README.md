# zunda-notes

「ずんだもんAI」YouTube動画の概要欄に貼るための、Gemini Notebook（NotebookLM）読み込み用テキストを配信する最小構成の静的サイト。

## 使い方

`public/n/<番号>.txt` に動画ごとの解説マークダウンを置く。ビルド不要で、Cloudflare Pagesがそのまま配信する。

```
https://zunda-notes.pages.dev/n/1.txt
```

## デプロイ

```
npx wrangler pages deploy public --project-name=zunda-notes
```
