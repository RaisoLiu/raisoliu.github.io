# Raiso Liu 的个人网站

这是我的个人网站，使用 Hugo 构建并部署在 GitHub Pages 上。

## 本地开发

要本地运行这个网站，你需要：

1. 安装 Hugo（推荐使用扩展版本）
2. 克隆这个仓库
3. 运行以下命令：

```bash
git submodule update --init --recursive
hugo server
```

然后在浏览器中访问 `http://localhost:1313` 查看网站。

## 构建

要构建网站，运行：

```bash
hugo --minify
```

构建后的文件将在 `public` 目录中。

## 部署

这个网站使用 GitHub Actions 自动部署到 GitHub Pages。每次推送到 `main` 分支时，网站都会自动更新。

## 许可证

MIT License 