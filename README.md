# 杜咏键 · 个人主页 (Personal Homepage)

仿学术风单页个人站点（About / News / Projects / Experience / Skills / Contact），纯静态 HTML/CSS/JS，无构建依赖，可直接托管到 GitHub Pages。

- 目标仓库：`duyongjian.github.io`（Public）
- 目标地址：https://duyongjian.github.io
- GitHub：https://github.com/duyongjian

## 本地预览
直接用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages
> 说明：GitHub 连接器（GitHub App 集成）无「创建仓库」权限，仓库需在网页端手动创建一次；文件推送可由助手完成。

1. 打开 https://github.com/new ，仓库名精确填写 `duyongjian.github.io`，选 **Public**，**不要**勾选「Add a README file」（保持空仓库）。
2. 创建好后，由助手通过 GitHub 连接器把 `index.html` 与 `README.md` 推送到 `main` 分支；或本地手动执行：
   ```bash
   git init
   git add index.html README.md
   git commit -m "personal homepage"
   git branch -M main
   git remote add origin https://github.com/duyongjian/duyongjian.github.io.git
   git push -u origin main
   ```
3. 仓库 → Settings → Pages → Source 选择 `main` 分支 `/ (root)`，保存。
4. 等待约 1 分钟，访问 https://duyongjian.github.io 即可。

## 后续可替换的占位内容
- 头像：目前是占位文字「道」，把 `.avatar` 换成 `<img src="avatar.jpg" ...>` 即可。
- 项目卡片里的 `Demo / Code / Docs / Detail` 链接（目前多为 `#`）→ 补上真实链接。
- `CV (PDF)` 链接 → 指向你的简历 PDF。
- 邮箱已填 `2594589804@qq.com`，如需更换请改两处（About 区 socials 与 Contact 区）。
- 小说 / Inkitt 链接如有，可补进对应项目卡片。

> 隐私说明：内容均取自公开简历信息，未包含任何机密项目（如 DLOS 等）。如需公开更多项目细节，自行补充即可。
