# TChaJue.github.io

个人网站，通过 GitHub Pages 发布在 **https://tchajue.github.io/**

## 本地预览

直接用浏览器打开 `index.html` 即可，无需构建工具、无外部依赖（单文件）。

## 修改内容

所有需要替换的地方都在 `index.html` 里用 `<!-- TODO -->` 标注了：

| 位置 | 改什么 |
| --- | --- |
| `<title>` | 浏览器标签页标题 |
| `.tagline` | 一句话自我介绍 |
| `.meta` | 地区、当前状态 |
| `.skills` | 技能标签，随意增删 |
| `.projects` | 项目卡片，改标题、描述和链接 |
| `.links` | GitHub / 邮箱，`mailto:` 后换成真实邮箱 |

## 发布

改动推到 `main` 分支后，GitHub Pages 会在几十秒内自动更新：

```bash
git add .
git commit -m "更新内容"
git push
```

## Pages 配置

Settings → Pages → Build and deployment
- Source: **Deploy from a branch**
- Branch: **main** / **/ (root)**
