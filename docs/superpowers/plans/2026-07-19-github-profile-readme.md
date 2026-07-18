# GitHub Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build, validate, and publish the `Tianyi-Zhang-NKU/Tianyi-Zhang-NKU` GitHub profile README with project-first content, a prominent technology section, restrained honors, and generated contribution animations.

**Architecture:** Keep the repository static and dependency-free. `README.md` owns all visible profile content, `.github/workflows/snake.yml` generates theme-aware contribution snake assets onto an orphan `output` branch, and the committed design/plan documents retain decision history without affecting the profile rendering.

**Tech Stack:** GitHub Flavored Markdown, safe inline HTML, Shields.io, skillicons.dev, readme-typing-svg, github-readme-activity-graph, GitHub Actions, Platane/snk, peaceiris/actions-gh-pages, Git, GitHub CLI.

---

## File Map

- Create `README.md`: complete visible GitHub profile.
- Create `.github/workflows/snake.yml`: scheduled/manual contribution snake generation and `output` branch publication.
- Preserve `docs/superpowers/specs/2026-07-19-github-profile-readme-design.md`: approved design specification.
- Preserve `docs/superpowers/plans/2026-07-19-github-profile-readme.md`: implementation and validation record.

### Task 1: Implement The Profile README

**Files:**
- Create: `README.md`

- [ ] **Step 1: Create the complete profile content**

Create `README.md` with exactly this structure and factual content:

```markdown
<div align="center">

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving hand" width="46" height="46" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Glowing%20Star.png" alt="Glowing star" width="46" height="46" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="46" height="46" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" alt="Laptop" width="46" height="46" />

# Hi, I'm Harry Zhang · 张天译

**南开大学软件工程本科生 · AI Builder & Explorer**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=19&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=680&lines=Building+useful+AI+systems;From+ideas+to+verified+products;Agent+%C2%B7+Vision+%C2%B7+Software+Engineering" alt="Typing introduction" />

[![Nankai University](https://img.shields.io/badge/Nankai_University-Software_Engineering-7A0019?style=flat-square)](https://en.nankai.edu.cn/)
[![Focus](https://img.shields.io/badge/Focus-AI_%C2%B7_Agent_%C2%B7_CV-238636?style=flat-square)](#-tech-stack--技术栈)
[![GitHub](https://img.shields.io/badge/GitHub-Tianyi--Zhang--NKU-181717?style=flat-square&logo=github)](https://github.com/Tianyi-Zhang-NKU)
[![Email](https://img.shields.io/badge/Email-2412227%40mail.nankai.edu.cn-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:2412227@mail.nankai.edu.cn)

</div>

## 🧭 About · 关于我

- 🎓 南开大学软件学院软件工程专业 **2024 级本科生**，关注人工智能与可靠的软件工程实践。
- 🤖 主要探索 **AI Agent、计算机视觉、模型评估与 AI-native 软件开发**，重视工具证据、验证闭环和可维护实现。
- 🔭 正在参与教培公司的真实小程序交付，也持续构建面向学习与编程场景的 **Coding Agent**。
- 🧩 喜欢把想法推进为**能运行、能演示、能复现**的产品，并在团队协作中承担方案、实现、测试和最终表达。
- 📫 欢迎交流 AI 应用、Agent 工程与有意思的软件项目：**2412227@mail.nankai.edu.cn**。

## 🚀 Projects · 项目与实践

### 01 · [趣帆学习空间](https://github.com/Tianyi-Zhang-NKU/qufan-learning-space-miniapp)

`CURRENT INTERNSHIP` `PRIVATE REPOSITORY`

- 为教培公司持续开发的多角色微信小程序，服务学生/家长、教师、管理员与教研团队。
- 覆盖课程学习、作业与反馈、资料管理、权限分级等真实业务流程，并面向日常运营持续迭代。
- 项目重点不只是完成页面，而是把多角色需求落实为可维护、可交付的产品功能。

`WeChat Mini Program` `JavaScript` `CloudBase` `Product Delivery`

### 02 · [Zerror 知芽](https://github.com/worstwoof/Zerror)

`TEAM PROJECT` `AIGC 创新赛华北赛区二等奖`

- 面向中学学习场景的 AIGC 智能错题成长应用，把 OCR、智能解析、多模态内容和学习闭环整合为可运行产品。
- 在团队中主要负责项目理念梳理、方案文案、项目策划与展示 README，推动复杂功能形成清晰的产品叙事。
- 项目获得 AIGC 创新赛华北赛区二等奖，是我参与 AI 产品协作与比赛交付的重要实践。

`Flutter` `FastAPI` `OCR` `LLM` `Multimodal Learning`

### Selected Engineering Projects

#### CppPilot · cpp-learn-agent

`PRIVATE` `ACTIVE DEVELOPMENT`

面向 C++ 初学者的 Windows 桌面学习 Agent，把代码工作区、教学型 Agent 与桌面宠物串成完整学习流程。当前已落地工具链探测、Monaco 编辑、编译运行、诊断、CMake、clangd/LSP 与 GDB 调试基础；Agent/MCP、知识树与桌面宠物属于后续里程碑。

`Electron` `Vue 3` `TypeScript` `Monaco` `SQLite` `C++ Toolchain`

#### [NKU Rust Coding Agent](https://github.com/JadeAndStone/NKU-Rust-Project)

团队开发的本地 CLI Coding Agent，支持多轮工具调用、Ask/Code 模式、命令审批、差异查看与文件回滚。我负责项目级 Agent 规则、测试与 Clippy 收口、`/差异`、`/验证`、Ask/Code 能力补强，以及报告材料、演示脚本和提交前质量说明。

`Rust` `Cargo Workspace` `SSE` `Agent Tools` `44 Tests`

#### [Space Music · Music Website](https://github.com/worstwoof/Music-Website)

团队完成的沉浸式音乐 Web 应用，融合 WebGL 动态背景、GSAP 动画、明暗主题、实时音频可视化和音频/MV 双模式播放器。我负责首页功能与页面设计，并参与演示视频录制，将视觉表达与完整交互结合起来。

`JavaScript` `Web Audio API` `Three.js` `GSAP` `View Transitions`

### More Builds

| Project | What I built / explored |
| --- | --- |
| [**FocusGuard**](https://github.com/Tianyi-Zhang-NKU/FocusGuard) | 基于姿态与视觉感知的桌面健康辅助系统，将课程项目完成为可交互应用。 |
| [**BDC 2026 Stock Walk-Forward**](https://github.com/Tianyi-Zhang-NKU/bdc2026-stock-walk-forward) | 股票收益预测、滚动验证、候选池集成与过拟合审计组成的可复现实验流水线。 |
| [**WanderInNKU**](https://github.com/Tianyi-Zhang-NKU/WanderInNKU) | 面向南开大学招生季的一站式信息平台，为考生、家长和招生工作人员提供服务。 |
| [**Territory Duel**](https://github.com/Tianyi-Zhang-NKU/Territory-Duel-Mini-game) | 使用 C++ / Qt 完成的领地对决小游戏，包含完整玩法与桌面交互界面。 |

## ⚙️ Tech Stack · 技术栈

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,ts,js,cpp,rust,dart,pytorch,opencv,vue,electron,flutter,fastapi,git,docker,sqlite&theme=dark&perline=8)](https://skillicons.dev)

</div>

| Languages | AI & Data | Product Engineering |
| --- | --- | --- |
| Python · TypeScript · JavaScript | PyTorch · OpenCV · MediaPipe | Vue · Electron · Flutter |
| C++ · Rust · Dart | LLM · Agent · Time Series | FastAPI · Mini Program · SQLite |
| SQL · Shell | Evaluation · Verification | Git · Docker · GitHub Actions |

> **Current focus:** Agent planning · repository memory · evaluation · verification · AI-native software engineering

### 🏅 所获荣誉

- **AIGC 创新赛华北赛区二等奖**
- **南开大学 2024-2025 学年度学业优秀奖学金**
- **南开大学 2024-2025 学年度优秀学生干部**
- **南开大学 2025-2026 学年度优秀共青团干部**

<sub>另：2026 第十八届中国电机工程学会杯全国大学生电工数学建模竞赛全国一等奖 · 2026 Mathematical Contest in Modeling Honorable Mention · 2025-2026 第一学期《线性代数》助教</sub>

### 学生工作

软件工程专业班长（大一、大二连续两年） · 共青团南开大学软件学院委员会组织部副部长（大二一年） · 共青团南开大学委员会组织部综合办公室主任

## 📊 GitHub Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Tianyi-Zhang-NKU&theme=github-compact&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Tianyi-Zhang-NKU&theme=github-light&hide_border=true" />
  <img alt="Harry Zhang's GitHub activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=Tianyi-Zhang-NKU&theme=github-compact&hide_border=true" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/output/github-contribution-grid-snake.svg" />
</picture>

<div align="center">

**Thanks for visiting. 欢迎通过 [Email](mailto:2412227@mail.nankai.edu.cn) 或 [GitHub](https://github.com/Tianyi-Zhang-NKU) 与我交流。**

</div>
```

- [ ] **Step 2: Check the README for prohibited or stale content**

Run:

```powershell
$forbidden = @('MindSprout','知返','NutriSight','Salary Cat','天府杯','数维杯',('T'+'BD'),('FIX'+'ME'))
rg -n -i ($forbidden -join '|') README.md
```

Expected: exit code `1` and no matches.

- [ ] **Step 3: Check the intended project and identity markers**

Run:

```powershell
rg -n '趣帆学习空间|Zerror 知芽|CppPilot|NKU Rust Coding Agent|Space Music|FocusGuard|BDC 2026|WanderInNKU|Territory Duel|Tech Stack|所获荣誉|综合办公室主任' README.md
```

Expected: every marker appears at least once.

- [ ] **Step 4: Commit the visible profile**

```powershell
git add README.md
git commit -m "feat: add project-focused GitHub profile"
```

Expected: one commit creating `README.md`.

### Task 2: Add Contribution Snake Automation

**Files:**
- Create: `.github/workflows/snake.yml`

- [ ] **Step 1: Create the workflow**

Create `.github/workflows/snake.yml`:

```yaml
name: Generate contribution snake

on:
  schedule:
    - cron: "15 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: Generate snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Publish generated assets
        uses: peaceiris/actions-gh-pages@v4
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_branch: output
          publish_dir: ./dist
          force_orphan: true
```

- [ ] **Step 2: Validate the workflow shape**

Run:

```powershell
rg -n 'workflow_dispatch|contents: write|Platane/snk/svg-only@v3|publish_branch: output|force_orphan: true' .github/workflows/snake.yml
```

Expected: all five workflow requirements appear.

- [ ] **Step 3: Commit the workflow**

```powershell
git add .github/workflows/snake.yml
git commit -m "ci: generate contribution snake"
```

Expected: one commit creating the workflow.

### Task 3: Validate The Local Repository

**Files:**
- Verify: `README.md`
- Verify: `.github/workflows/snake.yml`
- Verify: `docs/superpowers/specs/2026-07-19-github-profile-readme-design.md`
- Verify: `docs/superpowers/plans/2026-07-19-github-profile-readme.md`

- [ ] **Step 1: Check Git whitespace and repository state**

Run:

```powershell
git diff --check
git status --short
git log --oneline --decorate -5
```

Expected: `git diff --check` and `git status --short` have no output; log shows the design, README, workflow, and plan commits.

- [ ] **Step 2: Validate Markdown and HTML contracts**

Run a bounded PowerShell check that asserts matching `<div>`, `<picture>`, and `<sub>` tags and confirms the profile has exactly one H1:

```powershell
$content = Get-Content -LiteralPath README.md -Raw
if (($content | Select-String '<div' -AllMatches).Matches.Count -ne ($content | Select-String '</div>' -AllMatches).Matches.Count) { throw 'Unbalanced div tags' }
if (($content | Select-String '<picture>' -AllMatches).Matches.Count -ne ($content | Select-String '</picture>' -AllMatches).Matches.Count) { throw 'Unbalanced picture tags' }
if (($content | Select-String '<sub>' -AllMatches).Matches.Count -ne ($content | Select-String '</sub>' -AllMatches).Matches.Count) { throw 'Unbalanced sub tags' }
if (($content -split "`n" | Where-Object { $_ -match '^# ' }).Count -ne 1) { throw 'README must contain exactly one H1' }
Write-Output 'README structure OK'
```

Expected: `README structure OK`.

- [ ] **Step 3: Verify external image and project URLs**

Issue focused `Invoke-WebRequest -Method Head` requests for the typing SVG, skill icons, activity graph, public project links, and GitHub account. Treat HTTP `200`, `301`, or `302` as valid. Do not require the snake URLs yet because the `output` branch does not exist before the workflow runs.

Expected: all checked URLs are reachable or redirect normally.


### Task 4: Create And Publish The GitHub Profile Repository

**Files:**
- Publish the entire local repository.

- [ ] **Step 1: Confirm authentication and remote absence**

Run:

```powershell
gh auth status
gh repo view Tianyi-Zhang-NKU/Tianyi-Zhang-NKU --json nameWithOwner,visibility,defaultBranchRef,url
```

Expected: authenticated as `Tianyi-Zhang-NKU`; the second command reports that the repository is not found. If it exists, inspect it and preserve any existing remote content before pushing.

- [ ] **Step 2: Create the public profile repository and push**

If absent, run:

```powershell
gh repo create Tianyi-Zhang-NKU/Tianyi-Zhang-NKU --public --source . --remote origin --push --description "Harry Zhang's GitHub profile"
```

Expected: GitHub creates the public repository, configures `origin`, and pushes `main`.

If present and empty, run:

```powershell
git remote add origin https://github.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU.git
git push -u origin main
```

Expected: `main` is pushed and tracks `origin/main`.

- [ ] **Step 3: Confirm the remote repository state**

Run:

```powershell
gh repo view Tianyi-Zhang-NKU/Tianyi-Zhang-NKU --json nameWithOwner,visibility,defaultBranchRef,url
git status --short --branch
```

Expected: public repository, default branch `main`, and local branch tracking `origin/main` with no changes.

### Task 5: Generate And Verify Dynamic Assets

**Files:**
- Remote workflow: `.github/workflows/snake.yml`
- Remote generated branch: `output`

- [ ] **Step 1: Trigger the contribution snake workflow**

Run:

```powershell
gh workflow run snake.yml --repo Tianyi-Zhang-NKU/Tianyi-Zhang-NKU
```

Expected: workflow dispatch accepted.

- [ ] **Step 2: Wait for the workflow result**

Run:

```powershell
$runId = gh run list --repo Tianyi-Zhang-NKU/Tianyi-Zhang-NKU --workflow snake.yml --limit 1 --json databaseId --jq '.[0].databaseId'
gh run watch $runId --repo Tianyi-Zhang-NKU/Tianyi-Zhang-NKU --exit-status
```

Expected: the latest `Generate contribution snake` run completes successfully.

- [ ] **Step 3: Verify generated snake assets**

Run focused requests for:

```text
https://raw.githubusercontent.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/output/github-contribution-grid-snake.svg
https://raw.githubusercontent.com/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/output/github-contribution-grid-snake-dark.svg
```

Expected: both return HTTP `200` and SVG content.

### Task 6: Inspect The Live Profile

**Files:**
- Verify remote `README.md` rendering at `https://github.com/Tianyi-Zhang-NKU`.

- [ ] **Step 1: Inspect the desktop layout**

Open the public GitHub account overview in the in-app browser at desktop width. Verify the hero, five-line About section, full project hierarchy, technology icons, restrained honors and leadership lines, activity graph, and contribution snake.

Expected: no broken media, clipped text, malformed table, missing project, or excessive honors prominence.

- [ ] **Step 2: Inspect the mobile-width layout**

Use a mobile-width browser viewport and reload the same profile page.

Expected: tables remain horizontally manageable, badges wrap, long project text stays readable, and images fit the content width without overlap.

- [ ] **Step 3: Check public source and final repository cleanliness**

Run:

```powershell
gh api repos/Tianyi-Zhang-NKU/Tianyi-Zhang-NKU/readme -H "Accept: application/vnd.github.raw+json"
git status --short --branch
```

Expected: the raw remote README matches the implemented profile and the local branch is clean and synchronized.


