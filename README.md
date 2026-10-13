# xte12329 个人主页

使用原生 HTML 和 CSS 编写的静态个人主页，部署在 GitHub Pages。没有前端框架或构建步骤。

## 目录结构

- `index.html`、`styles.css`：主页结构与样式。
- `article.css`：文章页共用样式。
- `writing/`：四篇文章，包括 Creator Toolbox、整合包档案馆、学习经历和小黑盒运营。
- `assets/`：主页头像、首屏图及文章配图。
- `about/`、`projects/`：旧地址跳转到新版主页对应栏目。
- `docs/`：项目文章撰写说明。

旧博客生成的归档、分类、标签和 AI 绘画页面已从当前项目移除。公开身份为 `xte12329`；首屏图片为原创生成的校园氛围图，不是深圳大学实景。

## 本地预览

在仓库根目录运行：

```sh
python -m http.server 8000
```

然后访问 `http://localhost:8000/`。新增文章可参考 `writing/learning-journey/index.html`，项目文章说明见 `docs/项目作品文章撰写说明.md`。
