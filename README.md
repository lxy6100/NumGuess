# 猜数字（仅 Bulls）网页版

这是一个纯前端单页应用（无后端、无 npm、无构建工具），可直接部署到 GitHub Pages（Deploy from branch）。

规则更新：秘密数允许重复数字；程序的猜测不会使用“全位相同”的数字串。

## 本地运行

在仓库根目录执行：

```bash
python -m http.server 8000
```

然后在浏览器打开：

- <http://localhost:8000>

## GitHub Pages 部署（Deploy from branch）

1. 打开仓库 **Settings**。
2. 进入 **Pages**。
3. 在 **Build and deployment** 下：
   - **Source** 选择 `Deploy from a branch`
   - **Branch** 选择 `main`
   - **Folder** 选择 `/ (root)`
4. 保存后等待发布完成。

> 本项目入口文件为仓库根目录的 `index.html`，资源均为相对路径，可直接用于 Pages。
