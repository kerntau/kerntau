<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:131C3A,100:1E1B4B&height=190&section=header&text=KERNTAU&fontSize=62&fontColor=22D3EE&fontAlignY=36&desc=SECURITY%20%C2%B7%20WEB%20%C2%B7%20TOOLING&descAlignY=58&descSize=15&animation=fadeIn" width="100%" alt="KERNTAU" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=22D3EE&background=0B1020&center=true&vCenter=true&width=620&height=56&lines=%E4%BF%A1%E6%81%AF%E5%AE%89%E5%85%A8%20%C2%B7%20Web%20%E5%BC%80%E5%8F%91%20%C2%B7%20%E4%B8%AA%E4%BA%BA%E5%B7%A5%E5%85%B7;Security-minded%20web%20engineering.;%E4%BF%9D%E6%8C%81%E5%A5%BD%E5%A5%87%EF%BC%8C%E4%BF%9D%E6%8C%81%E6%80%80%E7%96%91%E3%80%82" alt="信息安全 · Web 开发 · 个人工具" />

<br />

<a href="https://github.com/kerntau"><img src="https://img.shields.io/badge/-%40kerntau-0B1020?style=flat-square&logo=github&logoColor=22D3EE" alt="GitHub" /></a>
<img src="https://img.shields.io/github/followers/kerntau?style=flat-square&label=FOLLOWERS&labelColor=0B1020&color=1E293B&logo=github&logoColor=22D3EE" alt="followers" />
<img src="https://komarev.com/ghpvc/?username=kerntau&style=flat-square&label=VIEWS&color=0B1020" alt="views" />

</div>

> 记录信息安全的学习路径、全栈工程实践，以及为个人工作流写下的那些小工具。

---

## 01. THE PURPOSE // 项目本源

这是 **kerntau** 的项目索引与个人资料仓库。

散落的知识、实验和工具各自成仓，这里只做一件事——**把它们收拢成一个可以走进去的入口**。

---

## 02. CORE ARCHITECTURE // 内容架构

本仓库是静态 Profile README，不包含应用运行时。项目按独立仓库维护，GitHub 作为入口连接各个实现。

~~~text
index    kerntau/kerntau · README.md · static
  │
repos    diary · moments · blog-v3 · Trace · openai-agents-starter-node · notes
  │
deploy   per-repository · independent boundaries
~~~

---

## 03. TECHNICAL MATRIX // 技术矩阵

<p align="center">
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/-Vue-41B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/-Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

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

选择具体项目后，进入其仓库 README 执行安装和开发命令：

```bash
# 1 · 挑一个仓库
git clone https://github.com/kerntau/diary.git
cd diary

# 2 · 安装依赖
npm install

# 3 · 启动开发服务器
npm run dev
```

> 各仓库的包管理器可能不同。动手前先看 `package.json` 里的 `packageManager` 字段，`npm` / `pnpm` / `yarn` 不要混用。

---

## 06. DEPLOYMENT & VERIFICATION // 使用与验证

每个项目拥有独立的构建和部署边界。改动之前，按顺序过一遍：

| # | 检查项 |
| :-: | :--- |
| 1 | 读 `README.md` —— 安装方式、脚本、目录约定 |
| 2 | 读 `LICENSE` —— 授权范围 |
| 3 | 复制 `.env.example` → `.env.local`，补齐缺失变量 |
| 4 | 跑通 `lint` / `typecheck` / `build` |

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

<!-- 贪吃蛇依赖 output 分支：先提交 .github/workflows/snake.yml 并手动跑一次 Action，否则此处会是裂图 -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/kerntau/kerntau/output/github-snake.svg" width="100%" alt="contribution snake" />
  </picture>
</p>

<!-- 以上卡片由第三方公共实例生成，偶发限流会渲染为空白；需要长期稳定可自建实例后替换域名。 -->

---

## 08. LICENSE // 许可证

本仓库为个人 Profile。各项目的许可证以对应仓库为准。

---

<div align="center">
  <sub>KERNTAU · 信息安全 · Web 开发 · 个人工具</sub>
  <br /><br />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:131C3A,100:1E1B4B&height=120&section=footer" width="100%" alt="" />
</div>
