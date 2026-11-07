# 律 (Lyu) 系列静态站点

一个用于展示「律」系列应用的静态网页，支持明暗双主题与中 / 日 / 英三语切换。

## 预览
- 打开 `index.html` 即可在浏览器查看。

## 目录结构
- `index.html`：GitHub Pages 部署入口，单文件自包含主页（内联样式与脚本，含三语字典与发布配置）。
- `lyu-series-home.html`：Open Design 编辑器的工作文件，内容与 `index.html` 完全一致。
- `images/`：应用图标。
- `privacy.html`：隐私政策。

## 维护说明
- 应用上下线状态在 `index.html` 的 `LYU_RELEASES` 中配置：填入平台 URL 即变为可下载按钮，留空则显示「待上线」。
- 主题与语言选择持久化于 `localStorage`。
- `index.html` 与 `lyu-series-home.html` 是同一份主页的两个副本：前者供 GitHub Pages 访问，后者供编辑器打开。**修改主页后必须同步覆盖另一份再提交**，否则线上会停留在旧版本。

## 部署
- 静态站点，可直接放置于 GitHub Pages（例如 `lyu-series.github.io`）。

## 许可说明
- 代码：MIT License（见 `LICENSE`）。
- 资源：`images/` 目录及其中图标/素材保留所有权利，未经书面授权禁止使用、复制、分发或用于商业目的。
