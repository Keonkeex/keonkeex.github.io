# Zhenghao Yu — Personal website

A lightweight, bilingual website for GitHub Pages. The desktop layout keeps a compact personal profile on the left while the detailed introduction scrolls on the right. On phones, the two columns automatically become one. No build step, external fonts, packages or framework are required.

## Preview

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Files

- `index.html`: page content, styles, decorative SVG artwork and language switching.
- `robots.txt`: crawler guidance.
- `sitemap.xml`: the canonical URL and last substantive update date.

## Update content

English copy lives directly in the HTML, in elements marked `data-i18n`. The Chinese counterpart lives in `translations['zh-CN']` near the bottom. Keep both versions consistent. The English page also works without JavaScript.

The September 2026 update describes Zhenghao as a first-year HKUST School of Business and Management student. Quantitative Finance and Mathematics are planned directions. No GPA, awarded degree, internship, research result or team membership is claimed.

The original `#about`, `#projects` and `#contact` anchors are preserved. The projects anchor currently introduces learning areas; add links to real projects and write-ups as they become available. The existing public email address and `@Keonkeex` GitHub link are retained.

When the academic year changes, update year-of-study labels, the biography, education record, semester, footer date, metadata and both languages. Update `sitemap.xml` after substantive content changes.

## Publish

Commit these files to the `main` branch of `Keonkeex/keonkeex.github.io`. The public URL is `https://keonkeex.github.io/`.

## 本次更新（2026 年 9 月）

- 更新为香港科技大学商学院本科一年级身份；量化金融与数学明确列为规划方向。
- 补充当前学习方向、课程、音乐与网球兴趣，保留原公开邮箱。
- 增加中英文切换、移动端样式、键盘焦点、可展开的学习重点和搜索引擎元信息。
- 桌面端改为左侧固定个人信息、右侧详细介绍；移动端自动改为单栏。
- 所有样式、脚本与图形都包含在 `index.html` 中，下载后直接用浏览器打开即可预览。

已检查 JavaScript 语法、65 个页面翻译键、站内锚点与结构化数据。当前环境限制本地浏览器预览，因此尚未完成浏览器视觉和实际交互验证。此改版尚未推送到线上仓库。
