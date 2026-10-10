---
layout: post
title: 这个博客如何工作
date: 2026-10-10
excerpt: 用 Markdown 写作、用 Jekyll 生成静态页面，并由 GitHub Actions 发布。
tags:
  - 学习
---

这个博客的文章保存在 `_posts/` 文件夹中，每篇文章都是带有 Front Matter 的 Markdown 文件。标题、日期、摘要和标签写在文件开头，正文从 Front Matter 结束后开始。

## 从 Markdown 到网页

Jekyll 会读取文章和页面模板，把它们生成普通的 HTML。页面样式由项目里的 CSS 文件控制，因此文章内容与页面外观可以分别维护。

## 发布

仓库中的 GitHub Actions workflow 使用 Jekyll 构建网站，再把生成的静态文件发布到 GitHub Pages。构建发生在 GitHub 上；本项目不需要 Node.js、npm、前端框架或外部 CDN。
