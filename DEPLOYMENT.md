# GitHub Pages 部署指南

## 概述

本项目已配置 GitHub Actions 来自动部署到 GitHub Pages。每次推送到 `main` 或 `master` 分支时，网站会自动重新部署。

## 快速开始

### 1. 启用 GitHub Pages

1. 进入你的 GitHub 仓库
2. 点击 "Settings" 标签
3. 在左侧菜单中找到 "Pages"
4. 在 "Source" 部分，选择 "GitHub Actions"

### 2. 推送代码

```bash
# 确保你在 main 或 master 分支
git add .
git commit -m "Initial commit with GitHub Pages setup"
git push origin main
```

### 3. 查看部署状态

1. 进入仓库的 "Actions" 标签
2. 查看 "Deploy to GitHub Pages" 工作流的状态
3. 部署成功后，你的网站将在 `https://[username].github.io/[repository-name]` 可用
