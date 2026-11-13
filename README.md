# 双星照诗笺

静态网站，可通过 GitHub Pages 托管。网站、人物肖像和诗卷检索数据均直接从仓库静态文件读取。

## 发布

1. 将本目录内容推送到 GitHub 仓库的 `main` 分支。
2. 在仓库 **Settings → Pages → Build and deployment** 中，将 **Source** 设为 **GitHub Actions**。
3. 每次推送到 `main` 后，`.github/workflows/pages.yml` 会自动部署；首次发布可在 **Actions** 页面查看进度与网站地址。

若仓库名为 `用户名.github.io`，站点地址为 `https://用户名.github.io/`；其他仓库通常为 `https://用户名.github.io/仓库名/`。
