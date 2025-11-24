# yimadAI
# 一麻袋 AI 摄影棚 · 静态网站

本仓库用于存放 **「一麻袋 AI 摄影棚」官网 / H5 展示页** 的静态代码，主要用于展示和引导用户进入：
- 模特库
- 姿势库
- 服装库
- AI 工作台
- 我的（账号与设置）

页面设计风格参考 **Midjourney 官网布局**，整体为 **浅色简约 + 橘色点缀**，突出 AI 摄影棚的科技感与时尚感。

---

## 在线预览（可选）

> 如果你启用了 GitHub Pages，可以在这里填上地址：

- GitHub Pages：`https://你的 GitHub 名字.github.io/yimadAI/`

---

## 功能模块

当前版本包含以下页面：

- `index.html`：首页（模块入口总览）
- `models.html`：模特库列表与模特详情入口
- `poses.html`：姿势库入口与分类展示
- `studio.html`：AI 工作台入口（快速开始制作服装大片）
- `my.html`：我的页面（账号信息、历史记录等的入口）
- `assets/`：静态资源文件
  - `assets/css/style.css`：全站样式
  - `assets/js/main.js`：基础交互逻辑（导航、高亮等）
  - `assets/images/`：LOGO、示意图等图片资源

---

## 目录结构

```text
yimadAI/
├─ index.html          # 首页
├─ models.html         # 模特库
├─ poses.html          # 姿势库
├─ studio.html         # AI 工作台
├─ my.html             # 我的页面
└─ assets/
   ├─ css/
   │   └─ style.css    # 全局样式
   ├─ js/
   │   └─ main.js      # 简单交互脚本
   └─ images/
