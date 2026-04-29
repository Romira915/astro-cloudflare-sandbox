---
title: "Content Collections と動的ルート"
description: "ビルド時に複数ページを展開するAstro流SSGパターン"
pubDate: 2026-04-29
tags: ["astro", "ssg"]
---

`src/content.config.ts` で `glob` ローダとZodスキーマを定義し、`getCollection` で取得した一覧を `getStaticPaths` に渡してビルド時に全ページを生成する。SSG なので最終的な成果物は静的HTMLの集合体。
