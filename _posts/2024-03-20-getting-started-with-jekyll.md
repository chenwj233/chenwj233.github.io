---
title: Jekyll博客搭建指南
date: 2024-03-20 15:00:00 +0800
categories: [Tutorial, Web Development]
tags: [jekyll, tutorial, web, static-site, github-pages]
---

# Jekyll博客搭建指南

Jekyll是一个简单而强大的静态网站生成器，特别适合用来搭建个人博客。本文将介绍如何使用Jekyll搭建一个漂亮的个人博客。

## 环境准备

1. 安装Ruby
2. 安装Jekyll和Bundler
3. 选择一个主题

## 基本步骤

### 1. 创建新站点

```bash
jekyll new my-blog
cd my-blog
```

### 2. 本地预览

```bash
bundle exec jekyll serve
```

### 3. 自定义配置

编辑 `_config.yml` 文件，设置你的网站信息：

```yaml
title: 我的博客
description: 个人博客网站
```

## 常用功能

### 文章管理

- 在 `_posts` 目录下创建文章
- 使用Markdown格式编写
- 添加front matter配置

### 页面布局

- 使用Liquid模板语言
- 自定义CSS样式
- 添加JavaScript功能

## 部署

1. 推送到GitHub
2. 启用GitHub Pages
3. 等待自动构建

## 总结

Jekyll是一个强大的博客框架，通过简单的配置就能搭建出专业的博客网站。希望这篇文章对你有所帮助！ 