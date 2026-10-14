# 旅鉴 · 小红书旅行灵感 Agent

一个纯前端旅行规划与攻略整理 Demo。首页直接生成分区行程；辅助页面包含攻略体检、避坑整理和系列创作。

## GitHub Pages 发布

仓库根目录需要包含 `index.html`、`.nojekyll` 和 `.github/workflows/pages.yml`。推送到 `main` 后，GitHub Actions 会自动发布站点。

首次发布前，在 GitHub 仓库的 **Settings → Pages → Build and deployment** 中将 **Source** 设为 **GitHub Actions**。完成首次 Actions 发布后，网址通常为：

`https://xuexi-xixi.github.io/travel-agent-demo/`

## 项目文件

- `index.html`：网站本体，使用 HTML、CSS 和 JavaScript，无需构建步骤。
- `开发路线与代码讲解.md`：产品规划与代码结构说明。
- `.github/workflows/pages.yml`：GitHub Pages 自动发布流程。

当前示例中的餐饮和住宿名称、价位是规划演示用的区域参考，不是实时商家或报价。接入地图与商户数据源后，才能提供具体店名、实时距离和可预订价格。

