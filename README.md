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

