<p>
  <img src="https://img.shields.io/badge/Senior%20Frontend%20Engineer-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI--native%20Product%20Builder-7C3AED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Complex%20UI%20Engineering-2563EB?style=for-the-badge" />
</p>

# Hi, I'm Baishi 👋

I'm a senior frontend engineer focused on **complex web applications, interactive UI systems, and AI-native product engineering**.

I have 10+ years of experience building production systems across web, desktop, mini-programs, internal tools, and AI-assisted workflows. My strongest area is turning ambiguous product requirements into maintainable frontend architecture: editors, visual workflows, rich-text extensions, timeline/Gantt interactions, data-heavy dashboards, and AI-assisted user flows.

Recently, I am building **Career Workbench** — an AI résumé workbench that uses a personal fact library and target job descriptions to generate traceable, role-specific résumés without hallucinating experience.

<p align="center">
  <a href="mailto:415453941@qq.com"><img src="https://img.shields.io/badge/Email-contact-EA4335?logo=gmail&logoColor=white"></a>
</p>

---


## What I’m good at

### Complex Frontend Engineering

- Rich editors, custom interaction models, drag/drop, keyboard shortcuts, selection, resize, zoom, undo/redo-style workflows
- Gantt/timeline rendering, Canvas + DOM hybrid rendering, tree/outliner editors
- Quill extensions, custom blots, inline references, image resize/preview, editor plugin behavior
- Large React/Vue applications, state modeling, component architecture, performance-sensitive UI

### AI Product Engineering

- AI-assisted résumé generation, JD parsing, evidence-based matching, and conversational editing
- Designing AI workflows with clear trust boundaries: browser → Edge Function → AI workflow → structured database writes
- Human-in-the-loop AI UX: generated suggestions should be explainable, traceable, and accepted/rejected by the user
- Using AI coding tools for requirement decomposition, architecture review, code generation, refactoring, and code review

### Full-stack Product Delivery

- React / TypeScript / Vite / Zustand / TanStack Query / Ant Design / HeroUI
- Node.js / Electron / Puppeteer / Supabase / Postgres / Edge Functions / Deno
- pnpm workspace monorepos, testable domain packages, feature specs, architecture docs
- Experience leading frontend teams and shipping business-critical internal platforms

---

## Featured Projects

### [Career Workbench](https://github.com/baishiup/career-workbench)

**AI résumé workbench for developers**  
Turn a personal fact library + target JD into a traceable, tailored résumé.

Core loop:

> upload résumé → fact library → browse jobs → AI match → generate tailored résumé → edit with AI patches

Tech stack:

`React 19` · `TypeScript strict` · `Vite` · `Supabase` · `Postgres RLS` · `Edge Functions` · `Deno` · `Dify` · `assistant-ui` · `Quill` · `pnpm workspace`

Engineering highlights:

- The browser never talks to AI providers directly; all secret-bearing operations go through Supabase Edge Functions.
- AI output is anchored to a structured personal fact library to reduce hallucinated résumé content.
- Core business rules are extracted into a pure domain package and shared across web and Edge Functions.
- Includes architecture docs, feature specs, mock mode, tests, and deployment-oriented scripts.

Live demo: https://career-workbench.vercel.app

---

### [Interactive Frontend Labs](https://github.com/baishiup/interactive-frontend-labs)

A frontend portfolio monorepo extracted and generalized from production work.

It focuses on reusable complex frontend capabilities:

- `vanilla-gantt` — dependency-light Gantt/timeline module using TypeScript, native DOM, and Canvas/DOM hybrid rendering
- `vanilla-outliner` — native DOM outliner editor with tree editing, drag ordering, rectangle selection, and keyboard operations
- `quill-extensions` — Quill 2 modules for keyword highlight, image resize preview, and inline reference blots

The repo uses mock data only and removes private business APIs, permissions, and product-specific workflows.

---

## Engineering Style

I care about building software that is not only usable, but also understandable and maintainable.

My usual workflow:

1. Clarify product constraints and failure cases
2. Design domain models and feature specs before coding
3. Separate business rules from UI details
4. Keep AI-generated code under human review
5. Use tests, mock mode, and documentation to make the project easier to continue

I prefer AI as an engineering partner, not as a black box. The goal is not “generate more code”, but to improve requirement decomposition, architectural judgment, iteration speed, and code review quality.

---

## Tech Stack

### Frontend / UI Engineering

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000" />
  <img src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue-42B883?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Ant%20Design-1677FF?style=flat-square&logo=antdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/HeroUI-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square" />
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" />
</p>

### Complex Interaction / Editor

<p>
  <img src="https://img.shields.io/badge/Quill-1D4ED8?style=flat-square" />
  <img src="https://img.shields.io/badge/Canvas-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Rich%20Editor-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/Drag%20%26%20Drop-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/Gantt%20%2F%20Timeline-0F766E?style=flat-square" />
  <img src="https://img.shields.io/badge/Keyboard%20UX-374151?style=flat-square" />
</p>

### Desktop / Automation

<p>
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/WebView-374151?style=flat-square" />
  <img src="https://img.shields.io/badge/Browser%20Automation-111827?style=flat-square" />
</p>

### Backend / AI / Data

<p>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Edge%20Functions-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Deno-000000?style=flat-square&logo=deno&logoColor=white" />
  <img src="https://img.shields.io/badge/Dify-1C64F2?style=flat-square" />
  <img src="https://img.shields.io/badge/AI%20Workflow-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/RLS-0F766E?style=flat-square" />
</p>

### Engineering Workflow

<p>
  <img src="https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white" />
  <img src="https://img.shields.io/badge/Monorepo-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=000" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Feature%20Spec-334155?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture%20Docs-475569?style=flat-square" />
</p>

---

## Career Focus

I’m currently looking for roles around:

- Senior Frontend Engineer
- AI-native Frontend Engineer
- Frontend-heavy Full-stack Engineer
- Product Engineer for AI tools, editors, workflow platforms, internal systems, or data-heavy SaaS products

I’m especially interested in teams that value:

- complex UI engineering
- product sense
- AI-assisted development
- architecture judgment
- ownership from idea to delivery

