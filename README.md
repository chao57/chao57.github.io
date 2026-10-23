# Eric Chen Portfolio

Astro 静态作品集，迁移自 https://chao53.github.io/ 。

## 本地运行
需要 Node.js 24 LTS。

```sh
npm ci
npm run dev
```

构建：`npm run build`；预览：`npm run preview`。

## 更新内容
- 项目：src/data/projects.json（title / desc / tags / category / cover / content）。content 保留旧站正文 HTML，之后可逐项改写。
- 首页和个人介绍：src/pages/index.astro
- 样式：src/styles/global.css
- 图片：public/assets

## GitHub Pages 发布
注册新 GitHub 账号后，建立名为 新用户名.github.io 的仓库，将此目录的源码推送到 main 分支。在 Settings → Pages → Source 选择 GitHub Actions。网站地址将为 https://新用户名.github.io/。工作流会自动构建发布。当前版本未推送或覆盖旧站。

内容从旧站恢复，经历、邮箱等沿用旧站公开信息，请在正式投递前检查。未制作不存在的简历下载链接；演示视频使用哔哩哔哩外链。


