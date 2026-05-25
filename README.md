# datareport

销售数据交互报表（静态页面）。

## 在线访问

- 数据概况（默认）：<https://moyi5603.github.io/datareport/dashboard.html>
- 销售明细：<https://moyi5603.github.io/datareport/data-report.html>

## 本地预览

在仓库根目录启动静态服务器，例如：

```bash
python3 -m http.server 8080
```

- 数据概况：<http://localhost:8080/dashboard.html>
- 销售明细：<http://localhost:8080/data-report.html>

## GitHub Pages

使用 GitHub Actions 自动部署（见 `.github/workflows/pages.yml`）。

首次需在仓库 **Settings → Pages → Build and deployment** 中将 **Source** 设为 **GitHub Actions**。之后每次推送到 `main` 分支会自动发布。
