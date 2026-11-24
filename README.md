# 青蓝研习社 · 初中高效学习与强化训练助手

本压缩包已整理好 **GitHub Pages** 电脑端一键部署所需的全部静态文件：

- `index.html`：完整单文件网页应用（含七大学科要点、多邻国风格闯关路径与逐题模式、天津市人教+外研教材与真题、全题型仿真卷/历年真题整卷、语文10–30分钟专项写作训练、拍照上传错题与同类变式强化、训练计时器及积分激励系统）
- `.nojekyll`：关闭 GitHub Pages 默认 Jekyll 解析，加快静态页面发布
- `README.md`：部署说明文档

## 电脑端快速部署步骤（GitHub Pages）

1. 登录 [GitHub](https://github.com) 后点击右上角 **`+`** → **New repository**，填写英文仓库名（如 `junior-study`），可见性选择 **Public**，点击 **Create repository**。
2. 在新建仓库页面点击 **uploading an existing file**（或 **Add file → Upload files**），将解压后的 `index.html`、`.nojekyll` 和 `README.md` 全部拖入上传区，点击底部 **Commit changes**。
3. 进入仓库顶部 **Settings → Pages**，在 **Build and deployment → Branch** 中选择 **`main`** 分支和 **`/ (root)`** 目录，点击 **Save**。
4. 等待 1–3 分钟刷新页面，点击顶部的 **Visit site**（格式为 `https://你的用户名.github.io/仓库名/`）即可在电脑或手机浏览器直接访问。

### 本地预览
直接双击解压后的 `index.html`，即可在电脑任意现代浏览器（Chrome / Edge / Safari）中打开使用。
