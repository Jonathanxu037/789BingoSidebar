# 789bingo · 游戏快捷侧边栏

需求 PRD 与交互原型（静态站点，无需构建）。

## 页面
- `index.html`：入口页，通过左侧栏切换以下页面（支持直链 `#prototype` / `#admin` / `#prd`）
- `prototype.html`：前台 H5 游戏页快捷侧边栏原型
- `admin.html`：后台「活动配置 → 游戏快捷侧边栏管理」原型
- `prd.html`：PRD 需求文档（含可点击目录）

## 发布到 GitHub Pages
1. 将本文件夹内全部文件（含 `.nojekyll`）放入仓库根目录并推送。
2. 仓库 Settings → Pages → Source 选择 `Deploy from a branch`，分支选 `main`，目录选 `/ (root)`。
3. 访问 `https://<用户名>.github.io/<仓库名>/`。

> 页面需通过 http(s) 访问；直接双击本地打开 html 可能因浏览器安全限制无法加载。本地预览可在该目录执行 `npx serve` 或 `python3 -m http.server`。
