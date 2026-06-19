<p>
  <img src="https://img.shields.io/badge/Senior%20Frontend%20Engineer-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI--native%20Product%20Builder-7C3AED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Complex%20UI%20Engineering-2563EB?style=for-the-badge" />
</p>

# Hi, I'm Baishi 👋

Senior frontend engineer with **10+ years** building complex web applications, interactive UI systems, and AI-native products — across web, desktop, mini-programs, and internal platforms. I turn ambiguous product requirements into maintainable frontend architecture: editors, visual workflows, rich-text extensions, timeline/Gantt interactions, and AI-assisted user flows. I've also led frontend teams and shipped business-critical internal systems.

<p>
  <a href="mailto:415453941@qq.com"><img src="https://img.shields.io/badge/Email-415453941@qq.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

## 🚀 Featured Projects

### Career Workbench — AI résumé workbench for developers

<p>
  <a href="https://career-workbench.vercel.app"><img src="https://img.shields.io/badge/▶%20Live%20Demo-2ea44f?style=for-the-badge"></a>
  <a href="https://github.com/baishiup/career-workbench"><img src="https://img.shields.io/badge/Source-111827?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

<a href="https://career-workbench.vercel.app">
  <img src="https://raw.githubusercontent.com/baishiup/career-workbench/main/docs/assets/readme-hero.png" width="680" alt="Career Workbench product screens">
</a>

Turn a personal fact library + a target JD into a **traceable, tailored résumé — without hallucinated experience.**

> upload résumé → fact library → browse jobs → AI match → generate tailored résumé → edit with AI patches

**Engineering highlights**

- The browser never talks to AI providers directly; all secret-bearing operations go through Supabase Edge Functions.
- AI output is anchored to a structured personal fact library to reduce hallucinated content.
- Core business rules live in a pure, unit-tested domain package, shared across web and Edge Functions.
- A network-layer mock (MSW) fakes the entire Supabase surface — REST / Auth / Functions / Storage — so the full app runs and **deploys as a static site with zero backend**. *The live demo runs entirely on it.*

`React 19` · `TypeScript strict` · `Supabase` · `Postgres RLS` · `Edge Functions / Deno` · `Dify` · `assistant-ui` · `Quill` · `pnpm monorepo`

---

### Interactive Frontend Labs — complex UI, engineered by hand

<p>
  <a href="https://interactive-frontend-labs.vercel.app"><img src="https://img.shields.io/badge/▶%20Live%20Demo-2ea44f?style=for-the-badge"></a>
  <a href="https://github.com/baishiup/interactive-frontend-labs"><img src="https://img.shields.io/badge/Source-111827?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

A frontend portfolio monorepo extracted and generalized from production work — **no framework magic**, mock data only.

- `vanilla-gantt` — dependency-light Gantt/timeline module: TypeScript, native DOM, Canvas/DOM hybrid rendering, drag-to-resize dates and progress.
- `vanilla-outliner` — native-DOM outliner editor: tree editing, drag ordering, rectangle selection, full keyboard model — original editor architecture preserved.
- `quill-extensions` — Quill 2 modules: keyword highlight, image resize/preview, and a custom inline-reference blot.

---

## 🧩 What I'm good at

**Complex frontend engineering** — rich editors, custom interaction models, drag/drop, keyboard shortcuts, selection, resize, zoom, undo/redo workflows · Gantt/timeline rendering · Canvas + DOM hybrid rendering · tree/outliner editors · Quill extensions, custom blots, inline references · large React/Vue apps, state modeling, performance-sensitive UI.

**AI product engineering** — AI-assisted résumé generation, JD parsing, evidence-based matching, conversational editing · AI workflows with clear trust boundaries (browser → Edge Function → AI workflow → structured DB writes) · human-in-the-loop UX where suggestions are explainable, traceable, and accepted/rejected by the user.

> I treat AI as an engineering **partner, not a black box**. The goal isn't to *generate more code* — it's to improve requirement decomposition, architectural judgment, iteration speed, and code-review quality.

---

## 🛠 Engineering Style

1. Clarify product constraints and failure cases
2. Design domain models and feature specs before coding
3. Separate business rules from UI details
4. Keep AI-generated code under human review
5. Use tests, mock mode, and documentation to make the project easy to continue

---

## ⚙️ Tech Stack

**Frontend / UI**

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

**Complex Interaction / Editor**

<p>
  <img src="https://img.shields.io/badge/Quill-1D4ED8?style=flat-square" />
  <img src="https://img.shields.io/badge/Canvas-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Rich%20Editor-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/Drag%20%26%20Drop-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/Gantt%20%2F%20Timeline-0F766E?style=flat-square" />
  <img src="https://img.shields.io/badge/Keyboard%20UX-374151?style=flat-square" />
</p>

**Desktop / Automation**

<p>
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/WebView-374151?style=flat-square" />
  <img src="https://img.shields.io/badge/Browser%20Automation-111827?style=flat-square" />
</p>

**Backend / AI / Data**

<p>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Edge%20Functions-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Deno-000000?style=flat-square&logo=deno&logoColor=white" />
  <img src="https://img.shields.io/badge/Dify-1C64F2?style=flat-square&logo=dify" />
  <img src="https://img.shields.io/badge/AI%20Workflow-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/RLS-0F766E?style=flat-square" />
</p>

**Engineering Workflow**

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

## 🎯 Career Focus

Open to **Senior Frontend / AI-native Frontend / Frontend-heavy Full-stack / Product Engineer** roles — especially on AI tools, editors, workflow platforms, internal systems, or data-heavy SaaS.

I'm drawn to teams that value complex UI engineering, product sense, AI-assisted development, architectural judgment, and ownership from idea to delivery.
