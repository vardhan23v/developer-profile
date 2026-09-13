# Sree Vardhan V — Developer Profile (Week 01)

**Generative AI Developer & Full-Stack Developer**
> *I build with AI. I ship with code.*

This is my **Week 01 Web Development Task — Developer Profile Page**, built to be deployed on **GitHub Pages** from `index.html` (with external `style.css`).

🔗 **Full Portfolio (Vercel):** https://vardhan-v-portfilo.vercel.app  
🔗 **GitHub:** https://github.com/vardhan23v  
🔗 **LinkedIn:** https://www.linkedin.com/in/vardhan-v23  
📧 **Email:** 23vvardhan@gmail.com

---

## ✅ Task Checklist (all covered)

- [x] Repository is **Public**
- [x] `index.html` present in root (main page)
- [x] `style.css` external stylesheet
- [x] **About Me** section — `id="about"`
- [x] **Skills** section — `id="skills"` (Languages, Frontend, Backend, Databases, AI/LLM, Cloud & Tools)
- [x] **Projects** section — `id="projects"` (6 featured from my real portfolio)
- [x] **Contact** section — `id="contact"`
- [x] **Bonus Contact Form** — `id="contactForm"` (Name, Email, Subject, Message + JS validation, no backend needed)
- [x] GitHub Pages enabled (`main` → `/ (root)`)
- [x] Live link works
- [x] Single-file fallback still works if you inline `style.css` back

## 📁 Structure

```
.
├── index.html   # Main profile — About / Skills / Projects / Contact + Form
├── style.css    # All styling (extracted from inline <style>)
└── README.md    # This file
```

For the simplest submission you can also upload just `index.html` (with inline CSS) — GitHub Pages will still serve it. This split version is cleaner for evaluation.

## 🚀 How to deploy (exact steps as per task)

1. Create new repo on GitHub: `developer-profile` (Public)
2. `Add file → Upload files` → upload `index.html` + `style.css` (if using split) — ensure `index.html` is in repo root
3. `Settings → Pages → Build and deployment → Deploy from a branch → Branch: main → Folder: / (root) → Save`
4. Wait ~1 min → open `https://YOUR-USERNAME.github.io/REPO-NAME/`
5. Submit that **live Pages URL** (not the repo URL) in the Google Form

## 🧩 Content Source

This Week 01 profile mirrors my production portfolio data (to stay consistent):

- `src/classic/data/site.ts` — identity (Sree Vardhan V, Kurnool, NMAM Institute of Technology)
- `src/classic/data/skills.ts` — 6 skill groups
- `src/classic/data/projects.ts` — featuredProjects (Extension AI, AI Code Reviewer, HPL Auction, DisasterMind AI, Vard AI, Apex Retail ERP)
- `src/classic/data/experience.ts` — OxCode, FlyRank AI, Zetheta, Zaalima

Full portfolio code: https://github.com/vardhan23v/vardhan-v-portfilo

## ✨ Features of this page

- Dark theme matching main portfolio (`#0a0a0f` bg, `#7c6cff` accent gradient)
- Responsive (mobile → desktop), accessible, semantic HTML
- No build step — pure HTML/CSS/JS, deploys instantly on Pages
- Form: frontend-only validation + success/error toast (`handleSubmit()` in `index.html:343`)

## 📝 Customize

Edit `index.html` directly — no framework needed. To re-inline CSS for a single-file upload, copy `style.css` back into a `<style>` block in `<head>`.

---

© 2026 Sree Vardhan V — Built for Week 01 Task. Full site built with Vite + React 19 + TypeScript (deployed on Vercel).
