# AgroMind

> 基于 AI 的农作物生长预测与智能农业决策系统

![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0-lightgrey)

## 🔗 项目页面 & Demo

- **静态网站（GitHub Pages）**: https://AgroMind555.github.io/AgroMind/  
- **论文 PDF**: [static/pdfs/agromind_paper.pdf](static/pdfs/agromind_paper.pdf)  
- **数据集**: https://huggingface.co/datasets/agromind  
- **源码**: https://github.com/AgroMind555/AgroMind  

## 🚀 快速开始

1. 点击仓库右上角 **Use this template**，fork 到你自己的组织或用户下。  
2. 修改 `index.html` 中所有 `<!-- ⚠️… -->` 注释标记的地方：  
   - 页面标题、描述、OG 元信息（`<meta property="og:…">`）  
   - 引用的图片、视频、PDF 等资源路径  
   - 核心文字（摘要、功能亮点等）  
3. 将 `static/images/favicon.ico` 替换为你自己的 Favicon。  
4. Commit & Push 到 `main` 分支。

## 📂 仓库结构
AgroMind/
├── index.html # 主页
├── static/
│ ├── css/ # 样式文件
│ ├── js/ # 脚本文件
│ ├── images/ # 展示用图片和 favicon
│ ├── videos/ # 演示视频
│ └── pdfs/ # 论文 / 海报等 PDF
└── README.md # 项目说明（本文件）

## ✨ 特性

- **Teaser Video**：项目演示视频一键播放  
- **图片轮播**：4 张关键结果图并自动滑动  
- **PDF 海报**：直接在页面内嵌入海报  
- **多模态数据**：卫星影像、气象和土壤传感器数据融合  

## 🎨 自定义 & 部署

- **编辑内容**：修改 `index.html`，HTML 片段已用注释标明各模块位置。  
- **修改样式**：如需个性化外观，可在 `static/css/index.css` 中调整或引入其他 CSS。  
- **部署 GH Pages**：  
  1. 打开仓库 Settings → Pages。  
  2. 选择分支 `main`、目录 `/ (root)`，点击 Save。  
  3. 访问 `https://<你的用户名>.github.io/<仓库名>/`。

## 📜 引用

如果在论文或项目中引用本系统，请使用：

```bibtex
@article{AgroMind2025,
  title   = {AgroMind: 基于 AI 的农作物生长预测系统},
  author  = {匿名},
  journal = {--},
  year    = {2025},
  url     = {https://AgroMind555.github.io/AgroMind/},
}
