# 首尔 TWICE 行程网页 GitHub Pages 部署说明

## 发布文件

把本目录下的文件上传到 GitHub 仓库根目录：

- `index.html`
- `seoul-hero.png`
- `.nojekyll`

`index.html` 必须放在发布源的顶层，GitHub Pages 会把它作为网站入口。

## GitHub Pages 设置

1. 在 GitHub 新建一个公开仓库，或使用已有仓库。
2. 上传本目录下的 3 个发布文件到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/(root)`，保存。
6. 等待 GitHub Pages 部署完成，访问地址通常是：

```text
https://你的GitHub用户名.github.io/仓库名/
```

## 注意事项

- GitHub Pages 发布的网站会公开在互联网上，请确认页面里没有隐私信息。
- 你在网页上新增/编辑的行程保存在访问者自己的浏览器本地，不会自动同步到 GitHub。
- 后续要更新默认行程，需要修改并重新上传 `index.html`。

参考：

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
