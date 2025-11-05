# 个人博客项目架构

## 项目结构

```
blog-push/
├── index.html          # 主页
├── css/
│   └── style.css      # 样式文件
├── js/
│   └── main.js        # JavaScript文件
├── posts/             # 博客文章目录
│   ├── 2024-01-01-first-post.md
│   └── 2024-01-02-second-post.md
├── images/            # 图片资源
├── about.html         # 关于页面
└── README.md          # 项目说明
```

## 快速开始

### 1. 使用静态站点生成器（推荐）

**Jekyll（GitHub Pages 原生支持）**
```bash
# 安装 Jekyll
gem install bundler jekyll

# 创建新站点
jekyll new my-blog
cd my-blog

# 本地预览
bundle exec jekyll serve
```

**Hugo**
```bash
# 安装 Hugo
# 创建新站点
hugo new site my-blog

# 添加主题并运行
```

### 2. 部署到 GitHub Pages

1. 创建仓库：`username.github.io`
2. 推送代码到 `main` 或 `gh-pages` 分支
3. 在仓库设置中启用 GitHub Pages
4. 访问：`https://username.github.io`

## 技术选型建议

- **Jekyll**：GitHub Pages 原生支持，无需构建
- **Hugo**：速度快，功能强大
- **Hexo**：简单易用，主题丰富
- **VuePress/VitePress**：适合技术文档
