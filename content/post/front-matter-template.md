---
title: "Front Matter 完整字段模板说明"
description: "本站文章的 front matter 全字段参考模板：标题、日期、分类、标签、摘要、封面、版权等，写新文章时复制此文件改内容即可。"
date: 2026-11-05T20:15:00+08:00
lastmod: 2026-11-05T20:15:00+08:00
slug: front-matter-template
categories:
    - 站点公告
tags:
    - 模板
    - Hugo
keywords:
    - Hugo 教程
    - front matter
draft: false
math: false
comments: false
license: "本文采用 CC BY-NC-SA 4.0 协议发布"
image: ""
style:
    background: "#2a9d8f"
    color: "#fff"
---

## 这是模板文

本文章本身是「完整字段模板」的实例，写新文章时建议复制本文件，然后逐项替换：

| 字段 | 含义 | 说明 |
| ---- | ---- | ---- |
| `title` | 标题 | 文章主标题 |
| `description` | 摘要 | 用于列表页与 SEO 描述 |
| `date` | 发布日期 | 格式 `YYYY-MM-DDTHH:MM:SS+08:00` |
| `lastmod` | 最后修改 | 可选 |
| `slug` | URL 别名 | 最终地址为 `/p/<slug>/` |
| `categories` | 分类 | 一篇文章建议只放一个主分类 |
| `tags` | 标签 | 可多个 |
| `keywords` | 关键词 | 可选，利于 SEO |
| `draft` | 草稿 | `true` 时本地可见、构建时不发布 |
| `image` | 封面图 | 留空则不显示封面 |
| `style` | 分类卡片配色 | 仅对分类页面生效 |

## 常用命令

```bash
# 新建文章
hugo new content post/my-writeup.md

# 本地预览（含草稿）
hugo server --buildDrafts
```

后续内容按正常 Markdown 编写即可。
