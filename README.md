# zy27488-blog-source

这是一个可配置、可继续写文章的 Hexo + Butterfly 博客源码仓库。

## 常用文件

- `_config.yml`: Hexo 主配置，改站点标题、网址、语言、生成规则。
- `_config.butterfly.yml`: Butterfly 主题配置，改菜单、头像、背景、侧边栏、页脚。
- `source/_posts/*.md`: 博客文章。
- `source/about/index.md`: 关于页面。
- `source/link/index.md`: 友链页面。
- `.github/workflows/pages.yml`: GitHub Pages 自动部署。

## 本地使用

```bash
npm install
npm run server
```

新建文章：

```bash
npm run new "文章标题"
```

生成静态文件：

```bash
npm run build
```
