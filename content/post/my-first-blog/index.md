---
title: "我的第一篇博客 —— Hugo 从零搭建"
description: "记录我用 Hugo + Stack 主题搭建个人博客的完整过程"
date: 2026-08-02T09:56:27+09:00
image: 
math: 
license: no license
comments: true
draft: false
categories: ["Hugo", "教程"]
tags: ["静态网站", "Markdown", "GitHub Pages"]
build:
    list: always    # Change to "never" to hide the page from the list
---

![博客封面](img/cover.jpg "Hugo 博客搭建教程封面")

## 为什么选择 Hugo？

Hugo 是目前**最快**的静态网站生成器。它的核心优势是：

1. **速度极快**：构建一个包含数百篇文章的网站仅需几毫秒
2. **无依赖**：生成的是纯静态 HTML，无需数据库
3. **灵活**：支持多种内容组织和主题系统

### 安装 Hugo

在 Arch Linux 上安装 Hugo 非常简单：

```bash
sudo pacman -S hugo
```

## YouTube video as shortcode

{{< youtube "dQw4w9WgXcQ" >}}
