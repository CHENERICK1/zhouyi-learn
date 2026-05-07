# 周易入门

一个简洁优雅的周易学习网站，包含阴阳五行基础、八卦、六十四卦查阅、以及硬币占卜模拟。

## 在线访问

部署后访问：`https://你的用户名.github.io/zhouyi-learn/`

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages（3分钟完成）

### 方法一：手动部署

1. **创建 GitHub 仓库**
   - 打开 https://github.com/new
   - Repository name 填：`zhouyi-learn`
   - 选择 Public
   - 点击 "Create repository"

2. **推送代码**
   ```bash
   cd zhouyi-learn
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/你的用户名/zhouyi-learn.git
   git push -u origin main
   ```

3. **开启 GitHub Pages**
   - 打开仓库 → Settings → Pages
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main`，文件夹选 `/ (root)`
   - 点击 Save
   - 等待 1-2 分钟，网站就会上线！

### 方法二：使用 GitHub 网页上传

1. 创建空仓库 `zhouyi-learn`
2. 点击 "uploading an existing file"
3. 把 `index.html` 拖进去
4. Commit
5. Settings → Pages → 开启（同上步骤3）

## 功能

- 📖 **首页** — 太极图 + 引言
- ☯️ **基础概念** — 阴阳、五行、爻的基本知识
- 🎋 **八卦** — 八个卦象及详细解释，点击可查看
- 🔮 **六十四卦** — 完整64卦网格，点击查看卦辞解读
- 🪙 **占卜** — 硬币占卜模拟器
- 📝 **关于** — 周易背景介绍

## 技术

- 纯 HTML + CSS + JavaScript，无依赖
- 单文件约 26KB，加载极快
- 响应式设计，适配手机
- 中式典雅风格配色

---

祝学习愉快！
