# anthoney.cn 博客源文件

本分支（`hexo`）是博客的源文件。推送到本分支后，GitHub Actions 会自动构建并发布到 `main` 分支（GitHub Pages → Cloudflare）。

## 写作 / 发布（任何设备，无需安装任何东西）

1. 打开 <https://github.com/anthoneycn/anthoneycn.github.io/tree/hexo>
2. 确认左上角分支选择的是 **hexo**
3. 电脑端：按键盘 `.` 进入网页版 VS Code；手机端：直接点文件右侧的铅笔图标编辑
4. 文章在 `source/_posts/` 目录，新建文件命名如 `my-post.md`，开头写上：

```markdown
---
title: 文章标题
date: 2026-10-29 23:00:00
tags: [随笔]
---
正文……
```

5. 点 **Commit changes**（Commit message 随便写）→ 自动开始发布，约 2 分钟后网站更新

## 本地写作（桌面电脑）

桌面 `C:\Users\Administrator\Desktop\blog` 工程仍然可用：`npx hexo server` 本地预览，或直接 `npx hexo deploy` 发布。

发布到此分支与本地 deploy 等价，都会走 Cloudflare 加速。
