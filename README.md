<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:131C3A,100:1E1B4B&height=170&section=header&text=KERNTAU&fontSize=60&fontColor=22D3EE&fontAlignY=42&animation=fadeIn" width="100%" alt="KERNTAU" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1400&color=22D3EE&background=0B1020&center=true&vCenter=true&width=620&height=56&lines=%E4%BF%A1%E6%81%AF%E5%AE%89%E5%85%A8%20%C2%B7%20Web%20%E5%BC%80%E5%8F%91%20%C2%B7%20%E4%B8%AA%E4%BA%BA%E5%B7%A5%E5%85%B7;Security-minded%20web%20engineering." alt="信息安全 · Web 开发 · 个人工具" />

<br />

<a href="https://github.com/kerntau"><img src="https://img.shields.io/badge/-%40kerntau-0B1020?style=flat-square&logo=github&logoColor=22D3EE" alt="GitHub" /></a>
<img src="https://img.shields.io/github/followers/kerntau?style=flat-square&label=FOLLOWERS&labelColor=0B1020&color=1E293B&logo=github&logoColor=22D3EE" alt="followers" />
<img src="https://komarev.com/ghpvc/?username=kerntau&style=flat-square&label=VIEWS&color=0B1020" alt="views" />

</div>

---

## 01. THE PURPOSE // 项目本源

散落的知识、实验和工具各自成仓。这里只做一件事——**把它们收拢成一个入口**。

---

## 02. CORE ARCHITECTURE // 内容架构

~~~text
index    kerntau/kerntau · README.md · static
  │
repos    diary · moments · blog-v3 · Trace · openai-agents-starter-node · notes
  │
deploy   per-repository · independent boundaries
~~~

---

## 03. TECHNICAL MATRIX // 技术矩阵

| 方向 | 常用技术 | 典型用途 |
| :--- | :--- | :--- |
| **前端** | `TypeScript` `React` `Vue` `Next.js` `Vite` | Web 应用与静态站点 |
| **服务** | `Go` `Node.js` | API、脚本和工具 |
| **数据** | `PostgreSQL` `Redis` `SQLite` | 应用持久化与缓存 |
| **安全** | Web 安全 · 工程审计 | 学习、实验和防护 |

---

## 04. REPOSITORY TOPOLOGY // 仓库拓扑

| 仓库 | 说明 | 栈 |
| :--- | :--- | :--- |
| **[`diary`](https://github.com/kerntau/diary)** | Markdown 日记 | `Markdown` |
| **[`moments`](https://github.com/kerntau/moments)** | 自托管朋友圈 | `Self-hosted` |
| **[`blog-v3`](https://github.com/kerntau/blog-v3)** | 博客引擎 | `React` `Rsbuild` |
| **[`Trace`](https://github.com/kerntau/Trace)** | 博客与主页 monorepo | `Monorepo` |
| **[`openai-agents-starter-node`](https://github.com/kerntau/openai-agents-starter-node)** | Agent 聊天模板 | `Node.js` `Agents` |
| **[`notes`](https://github.com/kerntau/notes)** | 学习知识库 | `Docusaurus` |

---

## 05. CLONE & QUICK START // 极速开始

以 `diary` 为例：

```bash
# 1 · 挑一个仓库
git clone https://github.com/kerntau/diary.git
cd diary

# 2 · 安装并启动
npm install
npm run dev
```

> 各仓库包管理器不同，先看 `package.json` 的 `packageManager` 字段。

---

## 06. DEPLOYMENT & VERIFICATION // 使用与验证

| # | 改动前检查 |
| :-: | :--- |
| 1 | 读 `README.md` —— 安装方式、脚本、目录约定 |
| 2 | 读 `LICENSE` —— 授权范围 |
| 3 | 复制 `.env.example` → `.env.local`，补齐缺失变量 |

```bash
npm run lint && npm run typecheck && npm run build
```

---

## 07. TELEMETRY // 实时指标

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kerntau&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true&bg_color=0B1020&title_color=22D3EE&icon_color=A78BFA&text_color=C9D1D9" width="48%" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kerntau&layout=compact&hide_border=true&langs_count=8&bg_color=0B1020&title_color=22D3EE&text_color=C9D1D9" width="38%" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kerntau&hide_border=true&background=0B1020&border=0B1020&stroke=22D3EE&ring=22D3EE&fire=A78BFA&currStreakNum=FFFFFF&currStreakLabel=22D3EE&sideNums=FFFFFF&sideLabels=C9D1D9&dates=64748B" width="72%" alt="GitHub streak" />
</p>

<!-- 贪吃蛇依赖 output 分支：先提交 .github/workflows/snake.yml 并手动跑一次 Action，否则此处是裂图 -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake.svg" width="100%" alt="contribution snake" />
  </picture>
</p>

<!-- 卡片由第三方公共实例生成，限流时会渲染为空白；需长期稳定可自建实例后替换域名。 -->

---

## 08. LICENSE // 许可证

各项目许可证以对应仓库为准。

---

<div align="center">
  <sub>保持好奇，保持怀疑。</sub>
  <br /><br />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:131C3A,100:1E1B4B&height=110&section=footer" width="100%" alt="" />
</div>
