# date-report

销售数据交互报表（静态页面）。

## 在线访问

部署完成后访问：

- 首页：<https://moyi5603.github.io/date-report/>
- 报表：<https://moyi5603.github.io/date-report/data-report.html>

## 本地预览

在仓库根目录启动静态服务器后打开 `data-report.html`，例如：

```bash
python3 -m http.server 8080
```

浏览器访问 <http://localhost:8080/data-report.html>

## GitHub Pages

使用 GitHub Actions 自动部署（见 `.github/workflows/pages.yml`）。

首次需在仓库 **Settings → Pages → Build and deployment** 中将 **Source** 设为 **GitHub Actions**。之后每次推送到 `main` 分支会自动发布。
