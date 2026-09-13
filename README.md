# Zhenghao Yu — Personal website

A lightweight, bilingual website for GitHub Pages. The desktop layout keeps a compact personal profile on the left while the detailed introduction scrolls on the right. On phones, the two columns automatically become one. No build step, external fonts, packages or framework are required.

## Preview

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Files

- `index.html`: page content, responsive styles and language switching.
- `notes/ap-microeconomics-notebook.pdf`: 32-page AP Microeconomics Notebook.
- `notes/ap-microeconomics-notebook.tex`: editable LaTeX source for the notebook.
- `robots.txt`: crawler guidance.
- `sitemap.xml`: the canonical URL and last substantive update date.

## Update content

English copy lives directly in the HTML, in elements marked `data-i18n`. The Chinese counterpart lives in `translations['zh-CN']` near the bottom. Keep both versions consistent. The English page also works without JavaScript.

The September 2026 update describes Zhenghao as a first-year HKUST School of Business and Management student. Quantitative Finance and Mathematics are planned directions. No GPA, awarded degree, internship, research result or team membership is claimed.

The original `#about`, `#projects` and `#contact` anchors are preserved. The academic section is organized by semester and subject, with expandable topics for each course. The existing public email address and `@Keonkeex` GitHub link are retained.

When the academic year changes, update year-of-study labels, the biography, education record, semester, footer date, metadata and both languages. Update `sitemap.xml` after substantive content changes.

## Publish

Commit these files to the `main` branch of `Keonkeex/keonkeex.github.io`. The public URL is `https://keonkeex.github.io/`.

## 本次更新（2026 年 9 月）

- 更新为香港科技大学商学院本科一年级身份；量化金融与数学明确列为规划方向。
- 按学期和学科分类展示课程，并可展开查看每门课的 topics。
- 加入 32 页 AP Microeconomics Notebook 的 PDF 与 TeX 下载入口。
- 增加中英文切换、移动端样式、键盘焦点、可展开的学习重点和搜索引擎元信息。
- 桌面端采用更窄、更靠左的固定个人信息栏和右侧详细介绍；移动端自动改为单栏。
- 背景调整为纯白色，整体更正式、学术化。

已检查 JavaScript 语法、79 个页面翻译键、站内锚点、笔记文件链接与结构化数据。当前环境限制本地浏览器预览，因此尚未完成浏览器视觉和实际交互验证。此改版尚未推送到线上仓库。
