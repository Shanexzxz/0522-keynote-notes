# 0522 上午 Keynote 会议纪要

> 第一天会议日程 · AI Coding 主题 4 场 Keynote 完整纪要

## 在线访问

启用 GitHub Pages 后，访问地址为：

```
https://<你的-github-用户名>.github.io/<仓库名>/
```

例如：`https://Shanexzxz.github.io/0522-keynote-notes/`

## 内容

| # | 时间 | 议题 | 演讲者 |
|---|------|------|--------|
| 1 | 09:00–09:40 | 别让 AI Coding "看起来很美"——从评测到落地 | 茹炳晟（复旦大学 CodeWisdom 首席技术专家 / 腾讯研究院特约研究员）|
| 2 | 09:45–10:25 | Agentic Design Patterns | Antonio Gulli（Google CTO 办公室工程总监）|
| 3 | 10:40–11:20 | AI Coding 的产品演进和研发范式变革 | 夏振华（阿里云 Qoder 高级技术专家）|
| 4 | 11:25–12:05 | 快手 AI 研发数字员工平台：从局部 AI 提效到全局 AI 提效 | 王硕（快手 AI 研发平台负责人）⏳ 待补 |

## 页面功能

- **议程时间轴**：按时间顺序展示 4 场 Keynote
- **Key Takeaways 输入框**：可填写整场会议的总结，自动保存到浏览器本地
- **Speech 卡片**：折叠展开，每张卡片含两个 Tab —「整理纪要」与「录音转写」
- **响应式设计**：手机 / 平板 / 桌面均可访问

## 项目结构

```
.
├── index.html                      # GitHub Pages 入口（与 output 内容一致）
├── output/
│   ├── 0522上午会议纪要.html        # HTML 网页版
│   └── 0522上午会议纪要.md          # Markdown 版（同步给腾讯文档 / iWiki）
└── README.md
```

## 部署到 GitHub Pages

1. 在 GitHub 创建一个新仓库（建议命名为 `0522-keynote-notes`）。
2. 在本地推送到该仓库（参考最下面的命令）。
3. 进入仓库 **Settings → Pages**：
   - **Source**：`Deploy from a branch`
   - **Branch**：`main` / 根目录 `/(root)`
   - 保存后等 1–2 分钟，Pages 会构建完成并给出访问 URL。

## 推送命令（首次）

```bash
cd /Users/shaynzhang/WorkBuddy/2026-05-22-11-20-18
git remote add origin git@github.com:<你的用户名>/<仓库名>.git
git branch -M main
git push -u origin main
```

后续更新：

```bash
git add .
git commit -m "update: speech 4 notes"
git push
```
