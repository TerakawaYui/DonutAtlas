# GitHub Pages 部署

此目录是静态网站，可直接部署；无需上传原始 FITS，也无需运行 Python。

1. 创建用于此星图的 GitHub 仓库。
2. 用 Git 或 GitHub Desktop 上传本目录内容，让 index.html、.nojekyll、sky/、assets/ 位于仓库根目录。无需上传 work/ 或虚拟环境。
3. 在仓库 Settings → Pages → Build and deployment 中选择 Deploy from a branch。
4. 选择 main 分支与 /(root)，保存。
5. 等待 GitHub Pages 部署成功，访问其返回的网址。通常为 https://你的用户名.github.io/仓库名/。

当前发布内容约479 MiB，最大单文件约5.2 MiB。建议使用 Git 或 GitHub Desktop 整体提交，避免网页逐个上传。

公开分发前，请确认这些结果和 FITS 派生图像可以公开。公开网站的访客可以下载其瓦片、图片和目录数据。

网页已使用相对资源路径，支持仓库名子路径部署。数据按需加载：低倍加载概览，放大加载精细背景，打开目标加载其切片。所有内容均来自本目录，不依赖本机 F: 或 G: 盘。

官方说明：
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

本次仅准备好部署文件，尚未创建仓库或公开发布网站。
