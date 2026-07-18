# GitHub Profile README Design

## Objective

Create and publish the public GitHub profile repository `Tianyi-Zhang-NKU/Tianyi-Zhang-NKU`. The profile should present Harry Zhang (张天译) as a 2024 undergraduate in Software Engineering at Nankai University whose main direction is AI. It should combine a clean professional structure, restrained technology styling, and lightweight animation.

The page must prioritize real projects and engineering practice. Honors and student leadership provide supporting context but must not compete visually with the project and technology sections.

## Audience And Language

- Primary audience: GitHub visitors, technical collaborators, internship reviewers, and student project teammates.
- Primary language: Chinese.
- English is used for the hero tagline, section subtitles, project status labels, and technology names.
- Tone: concise, concrete, professional, and personal without exaggerated marketing claims.

## Information Architecture

The README uses the following order:

1. Animated hero and contact line.
2. `About · 关于我` with five short personal-positioning lines.
3. `Projects · 项目与实践`, the dominant content section.
4. `Tech Stack · 技术栈`, the dominant visual section.
5. `所获荣誉`, rendered as a restrained text list.
6. `学生工作`, rendered as a single compact line.
7. GitHub activity visualization and animated contribution snake.

The project section should occupy more space than all honors and leadership content combined.

## Hero

- Centered name: `Harry Zhang · 张天译`.
- Identity: `南开大学软件工程本科生 · AI Builder & Explorer`.
- Animated typing line: `Building useful AI systems, from ideas to verified products.`
- Use a small row of animated emoji assets. Keep the row shorter and more restrained than the reference profile.
- Include Nankai University, Software Engineering 2024, AI/Agent/CV, GitHub, and `2412227@mail.nankai.edu.cn` in compact links or badges.
- Do not use a visitor counter or a large badge wall.

## About

Use five readable lines rather than one paragraph:

- Nankai University School of Software, Software Engineering, undergraduate class of 2024.
- Main interests: AI Agent, computer vision, model evaluation, and AI-native software engineering.
- Current work: a real education-company mini program and learning/programming-oriented Coding Agents.
- Engineering preference: turn ideas into runnable, demonstrable, reproducible products with evidence and verification.
- Open to discussions about AI applications, Agent engineering, and useful software projects.

Do not publish GPA, ranking, certificate images, local paths, phone numbers, or unrelated personal records.

## Project Hierarchy

### Level 1: Featured Projects

Each featured project gets a linked title, status label, two or three factual bullets, and a compact technology line.

#### 趣帆学习空间

- Link: `https://github.com/Tianyi-Zhang-NKU/qufan-learning-space-miniapp`.
- Mark as `Current Internship · Private`.
- Explain that it is a multi-role WeChat mini program being developed for an education company.
- Mention student/parent, teacher, administrator, and teaching-research workflows, including learning, assignment feedback, materials, and role-based access.
- Emphasize ongoing real-product delivery and maintainable implementation without disclosing private source, internal URLs, company data, or unverified business metrics.
- Stack: WeChat Mini Program, JavaScript, CloudBase, product delivery.

#### Zerror 知芽

- Link: `https://github.com/worstwoof/Zerror`.
- Mark as `Team Project · AIGC 华北赛区二等奖`.
- Explain that it is an AIGC learning product for middle-school error-question growth, combining OCR, intelligent analysis, multimodal content, and a learning loop.
- State Harry's verified contribution: product concept organization, solution copy, project planning, and showcase README/presentation expression.
- Stack: Flutter, FastAPI, OCR, LLM, multimodal learning.

### Level 2: Selected Engineering Projects

These projects are visually smaller than Level 1 but each receives a substantial two-sentence description and technology line.

#### CppPilot / cpp-learn-agent

- Mark as a private project under active development; do not invent a public repository link.
- Describe the Windows desktop learning Agent for C++ beginners that connects a code workspace, teaching Agent, and desktop companion.
- State the implemented baseline: toolchain discovery, Monaco editing, build/run, diagnostics, CMake, clangd/LSP, and GDB debugging. Clearly state that Agent/MCP and the desktop companion are later milestones.
- Stack: Electron, Vue 3, TypeScript, Monaco, SQLite, C++ toolchain.

#### NKU Rust Coding Agent

- Link: `https://github.com/JadeAndStone/NKU-Rust-Project`.
- Describe the local CLI Coding Agent with multi-turn tool calls, Ask/Code modes, command approval, diff inspection, and file rollback.
- State Harry's verified contribution: project-level Agent rules, test and Clippy closure, `/差异`, `/验证`, Ask/Code capabilities, report materials, demo script and recording, and pre-submission quality instructions.
- Stack: Rust, Cargo workspace, SSE, Agent tools, 44 tests.

#### Space Music / Music Website

- Link: `https://github.com/worstwoof/Music-Website`.
- Describe the immersive music web application with WebGL visuals, GSAP animation, light/dark themes, real-time audio visualization, and audio/MV playback modes.
- State Harry's verified contribution: homepage functionality, page design, and demo video recording.
- Stack: JavaScript, Web Audio API, Three.js, GSAP, View Transitions.

### Level 3: More Builds

Use a compact two-column Markdown table or list. Each item gets one useful sentence and a link.

- `FocusGuard`: `https://github.com/Tianyi-Zhang-NKU/FocusGuard`; a computer-vision desktop health assistant using pose and visual perception.
- `BDC 2026 Stock Walk-Forward`: `https://github.com/Tianyi-Zhang-NKU/bdc2026-stock-walk-forward`; a reproducible stock-return prediction pipeline with rolling validation, candidate-pool ensembling, and overfitting audits.
- `WanderInNKU`: `https://github.com/Tianyi-Zhang-NKU/WanderInNKU`; an integrated admissions-season information platform for prospective students, parents, and admissions staff.
- `Territory Duel`: `https://github.com/Tianyi-Zhang-NKU/Territory-Duel-Mini-game`; a C++/Qt territory game with complete gameplay and desktop interaction.

Do not include MindSprout/知返, NutriSight, Salary Cat, the low-value certificate items, or unfinished research themes presented as completed projects.

## Tech Stack

This is the most visually prominent section after Projects.

- Use a centered skill-icon strip for languages and major frameworks.
- Follow it with three compact categories:
  - Languages: Python, TypeScript, JavaScript, C++, Rust, Dart.
  - AI & Data: PyTorch, OpenCV, MediaPipe, LLM, Agent, time series.
  - Engineering: Vue, Electron, Flutter, FastAPI, WeChat Mini Program, Git, Docker, SQLite.
- Use `skillicons.dev` for supported factual icons and small shields only for unsupported concepts.
- Avoid a language-percentage card because public repository language ratios would misrepresent private and collaborative work.
- Keep technology colors varied rather than turning the page into a single blue or purple palette.

## 所获荣誉

Render this as a low-contrast text list, not colored cards:

- AIGC 创新赛华北赛区二等奖.
- 南开大学 2024-2025 学年度学业优秀奖学金.
- 南开大学 2024-2025 学年度优秀学生干部.
- 南开大学 2025-2026 学年度优秀共青团干部.

Add a smaller secondary line:

- 2026 第十八届中国电机工程学会杯全国大学生电工数学建模竞赛全国一等奖.
- 2026 Mathematical Contest in Modeling, Honorable Mention.
- 2025-2026 第一学期《线性代数》助教经历.

Do not embed original certificates. Do not mention the Tianfu Cup or Shuwei Cup.

## 学生工作

Use one compact line with no cards or timeline:

- 软件工程专业班长（大一、大二连续两年）.
- 共青团南开大学软件学院委员会组织部副部长（大二一年）.
- 共青团南开大学委员会组织部综合办公室主任.

## Dynamic Visuals

- Use `readme-typing-svg` only in the hero.
- Use `github-readme-activity-graph` for a theme-aware activity graph.
- Use `Platane/snk` through GitHub Actions to generate light and dark contribution snake SVGs on an `output` branch.
- The snake workflow runs on manual dispatch and a daily schedule and has only `contents: write` permission.
- Use external image services sparingly. The profile must remain understandable if a dynamic image temporarily fails.

## Repository Structure

```text
Tianyi-Zhang-NKU/
|-- README.md
|-- .github/
|   `-- workflows/
|       `-- snake.yml
`-- docs/
    `-- superpowers/
        `-- specs/
            `-- 2026-07-19-github-profile-readme-design.md
```

No certificate scans, private source archives, generated local previews, credentials, or personal documents are committed.

## Publication

- Create the public repository `Tianyi-Zhang-NKU/Tianyi-Zhang-NKU` if it does not exist.
- Use `main` as the default branch.
- Commit the README, workflow, and design documentation with intentional commit messages.
- Push with the authenticated GitHub CLI account `Tianyi-Zhang-NKU`.
- Trigger the snake workflow after the first push and wait for its result before final verification.

## Validation

Before completion:

1. Check Markdown structure, HTML tag balance, image URLs, repository links, and mail link.
2. Confirm every project description is grounded in inspected repositories, local project files, or user-provided facts.
3. Confirm private-project labels do not expose private content or imply public access.
4. Confirm excluded projects and awards do not appear.
5. Confirm the GitHub Actions workflow parses and completes successfully.
6. Inspect the public GitHub profile on desktop and mobile-width browser views for broken images, overflow, excessive visual density, and section hierarchy.
7. Confirm the public profile URL is `https://github.com/Tianyi-Zhang-NKU` and that the new README renders on the account overview.
