# 周喜宁 · 游戏 UI 设计师

个人作品集站点 —— 游戏 UI / 界面设计、项目经历与练习作品。

## 本地预览

零依赖、零构建，双击 `index.html` 即可打开。

推荐用本地服务器预览（资源加载行为与线上完全一致）：

```bash
python -m http.server 8080
```

然后浏览器访问 <http://localhost:8080>。

## 目录结构

```
.
├── index.html      站点主体：结构 / 样式 / 交互全部内联，单文件
├── assets/         项目封面、界面截图、练习原画、背景素材
├── .nojekyll       告知 GitHub Pages 跳过 Jekyll 处理
└── .gitignore
```

## 部署

纯静态站点，无需任何构建步骤。推送到 GitHub 后，在仓库
**Settings → Pages** 中将 Source 设为 `Deploy from a branch`，
分支选 `main`、目录选 `/ (root)`，保存后即可获得访问地址。

## 说明

站内所有作品与图像版权归作者所有，未经许可请勿转载或商用。
