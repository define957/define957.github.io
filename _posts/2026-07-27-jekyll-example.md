---
layout: post
title: "Jekyll + GitHub Pages 笔记示例"
date: 2026-07-27 12:00:00 +0800
categories: [jekyll, github-pages]
---

这是一篇示例学习笔记。你可以用 Markdown 格式写内容，Jekyll 会自动把它渲染成网页。

## 为什么要用 Jekyll？

- 支持 Markdown，不用手写 HTML
- 可以按日期、分类、标签组织笔记
- GitHub Pages 原生支持，推送后自动部署

## 怎么新建笔记？

在 `_posts/` 目录下新建文件，文件名格式为：

```
YYYY-MM-DD-title.md
```

文件开头加上 front matter：

```yaml
---
layout: post
title: "你的笔记标题"
date: 2026-07-27 12:00:00 +0800
categories: [machine-learning, svm]
---
```

然后下面直接写 Markdown 正文即可。
