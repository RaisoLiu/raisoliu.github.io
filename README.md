# Raiso Liu 的個人網站

這是我的個人網站原始碼倉庫，使用 Hugo 建置並部署在 GitHub Pages 上。

## 本地開發

要本地運行這個網站，你需要：

1. 安裝 Hugo（推薦使用擴充版本）
2. 克隆這個倉庫
3. 運行以下指令：

```bash
git submodule update --init --recursive
hugo server
```

然後在瀏覽器中訪問 `http://localhost:1313` 查看網站。

## 建置

要建置網站，運行：

```bash
hugo --minify
```

建置後的檔案將在 `public` 目錄中。

## 部署

這個網站使用 GitHub Actions 自動部署到 GitHub Pages。每次推送到 `main` 分支時，網站都會自動更新。

## 授權條款

MIT License 