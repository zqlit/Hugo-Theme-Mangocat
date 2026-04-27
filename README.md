# Hugo Theme MangoCat

一个基于 Astro 主题 MangoCat 移植的 Hugo 博客主题，保持了原主题的设计风格和功能特性。

## 🌱 移植声明

本主题是基于 [Almango/MangoCat](https://github.com/Almango/MangoCat) 主题移植到 Hugo 框架的版本。原主题是由 Almango 开发的 Astro 主题，设计简洁现代，功能丰富。

- **原作者**：Almango
- **原仓库**：<https://github.com/Almango/MangoCat>
- **移植者**：\[zqlit]
- **移植版本**：v1.0.0

## ✨ 特性

- **现代化设计**：简洁优雅的界面，支持自定义主题色
- **响应式布局**：完美适配桌面端和移动端
- **深色模式**：支持自动/手动切换深色主题
- **美观文档**：采用 GitHub Markdown 格式、增强阅读体验
- **SEO 友好**：自动生成 RSS、Sitemap
- **评论系统**：内置 Artalk 评论支持
- **精美图标**：采用 Remix Icons 图标库
- **毛玻璃效果**：现代感十足的导航栏设计

## 🛠️ 安装

### 环境要求

- Hugo v0.128.0+（建议使用最新版本）
- Node.js v20.0.0+（用于构建静态资源）

### 安装步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/zqlit/Hugo-Theme-Mangocat.git
   cd Hugo-Theme-Mangocat
   ```
2. **安装依赖**
   ```bash
   npm install
   ```
3. **启动开发服务器**
   ```bash
   hugo server -D
   ```
4. **构建生产版本**
   ```bash
   hugo --minify
   ```

## 📁 项目结构

```
.
├── archetypes/         # 内容模板
├── content/            # 内容文件
│   ├── posts/          # 博客文章
│   ├── about.md        # 关于页面
│   ├── archive.md      # 归档页面
│   ├── circle.md       # 鱼塘页面
│   ├── link.md         # 友链页面
│   └── project.md      # 项目页面
├── data/              # 数据文件
│   ├── friends.toml    # 友链配置
│   └── projects.toml   # 项目配置
├── layouts/           # 布局模板
├── static/            # 静态资源
├── themes/            # 主题文件
│   └── mangocat/       # MangoCat 主题
├── hugo.toml          # Hugo 配置文件
└── README.md          # 项目说明
```

## 🎨 配置

### 基本配置

编辑 `hugo.toml` 文件，配置站点基本信息：

```toml
# 站点基本信息
title = "你的站点名称"
baseURL = "https://your-site.com/"
languageCode = "zh-CN"
theme = "mangocat"

# 主题配置
[params]
  title = "你的站点名称"
  subtitle = "站点副标题"
  description = "站点描述"
  author = "你的名字"
  themeColor = "#1890ff"  # 主题颜色

# 评论系统配置
[params.comment]
  enable = true
  provider = "artalk"
  [params.comment.artalk]
    server = "https://artalk-server.com"  # Artalk 服务器地址
    site = "你的站点名称"
```

### 友链配置

编辑 `data/friends.toml` 文件，添加友链：

```toml
[[friends]]
name = "朋友名称"
url = "https://friend-site.com"
avatar = "https://friend-site.com/avatar.jpg"
rss = "https://friend-site.com/feed.xml"  # 用于鱼塘页面
```

### 项目配置

编辑 `data/projects.toml` 文件，添加项目：

```toml
[[projects]]
name = "项目名称"
description = "项目描述"
url = "https://project-site.com"
```

## 📝 创建文章

在 `content/posts/` 目录下创建 Markdown 文件，添加以下 frontmatter：

```yaml
title: 文章标题
description: 文章描述
date: 2024-01-01
tags:
  - 标签1
  - 标签2
categories:
  - 分类
cover: https://example.com/cover.jpg  # 文章封面图
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个主题！

## 📄 许可证

本主题基于 MIT 许可证开源，与原主题保持一致。

## 🙏 致谢

- **Almango**：原 MangoCat 主题的作者，提供了这么优秀的设计
- **Hugo 团队**：提供了强大的静态网站生成器
- **所有贡献者**：感谢你们的支持和贡献

***

如果你喜欢这个主题，欢迎给个 Star ⭐️ 支持一下！
