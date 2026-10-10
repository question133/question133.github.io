# question133 · 个人博客

这是一个使用 Markdown、Jekyll 和 GitHub Pages 的静态个人博客。文章写在 `_posts/` 中，页面使用 HTML 和 CSS；GitHub Actions 负责构建和发布。

## 内容维护

- 新文章：在 `_posts/` 中新增 `YYYY-MM-DD-title.md`，沿用现有文章的 Front Matter。
- 首页和项目：编辑 `index.html`。
- 关于页：编辑 `about.md`。
- 配置、站点标题和 URL：编辑 `_config.yml`。
- 配色与排版：编辑 `assets/style.css`。

## 发布

仓库中的 `.github/workflows/pages.yml` 会在 `main` 分支更新后运行 Jekyll，并部署到 GitHub Pages。仓库的 Pages Source 已设为 **GitHub Actions**。

预期网址：<https://question133.github.io/>

本地不需要安装 Node.js、npm、前端框架、外部 CDN 或额外构建工具。
