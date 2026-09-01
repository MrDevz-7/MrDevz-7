<h1 align="center">Mauricio Ramirez</h1>
<p align="center">
  <strong>Full-Stack Developer</strong> &nbsp;·&nbsp; Backend & AI-Integration Focus · React · Python &nbsp;·&nbsp; Medellín, Colombia 🇨🇴 (UTC-5)
</p>
<p align="center">
  <a href="https://mrdevzportfolio.netlify.app/">🌐 Portfolio</a>
  &nbsp;·&nbsp;
  <a href="https://nobordersyoga.com">🚀 Live Project</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/MrDevz-7?tab=repositories">📂 Repos</a>
  &nbsp;·&nbsp;
  <a href="mailto:mrdevelopz7@gmail.com">📬 Contact</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/YOUR-LINKEDIN-HANDLE">💼 LinkedIn</a>
</p>

---

I build full-stack products end-to-end — schema design, REST APIs, frontend rendering, LLM orchestration, and cloud deployment — and I document what I build so a team can pick it up without me in the room. My deepest focus is backend systems and AI integration, and shipping production systems that stay up when things go wrong, not just CRUD that works in a demo. Based in Medellín, Colombia (UTC-5), which means full overlap with US Eastern business hours.

---

## 🚀 In Production

### [CustoFinder](https://custo-finder.vercel.app) — Smart lead prospecting, built end-to-end
Full-stack platform for freelancers and agencies: discovers local businesses without a website (OpenStreetMap/Overpass), scores them as leads with Gemini, scrapes competitor sites with Playwright, and tracks the sales pipeline on a drag-and-drop kanban with conversion analytics.

Built for resilience against two independent classes of failure: a **quota-aware API key rotation layer** that transparently fails over to the next available Gemini key on rate-limit exhaustion, keeping the lead-scoring pipeline uninterrupted; and a **mirror-rotation + cache fallback strategy** that serves the last successful result for a given search instead of a hard 502 when upstream providers (Overpass) go down. Also diagnosed and patched a production-only IPv6 routing failure on Render that a local dev environment couldn't reproduce.

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `Docker` `Playwright` `Gemini API` `Next.js` `TypeScript`

### [No Borders Yoga](https://nobordersyoga.com) — Full-stack build for a real client
Headless CMS (Strapi v5), PostgreSQL on Supabase, image delivery via Cloudinary, deployed on Netlify + Render with automated keep-alive through UptimeRobot + GitHub Actions.

The client manages all content independently — classes, retreats, blog — zero technical dependency.

**→ 6+ months in production. Zero downtime.**

`React` `Tailwind` `Strapi v5` `PostgreSQL` `Supabase` `Cloudinary` `Netlify` `Render` `GitHub Actions`

---

## 🔧 Currently building

**Machine Learning Specialization** (Andrew Ng · Stanford / DeepLearning.AI · Coursera) — ✅ completed 2026, now applying supervised and unsupervised learning to the lead-scoring logic in CustoFinder.

**Data Structures & Algorithms** — practicing on HackerRank toward verified badges.

**Cybersecurity** — deepening beyond the Google Cybersecurity Fundamentals & Risk Management track already completed.

---

## 🛠 Stack

| Area | Technologies |
|---|---|
| **Backend** | Python · FastAPI · Node.js · Java · Strapi v5 |
| **AI & Automation** | Gemini API · Prompt engineering · Playwright |
| **Databases** | PostgreSQL · MySQL · SQLite · Supabase |
| **DevOps / Cloud** | Docker · GitHub Actions · Netlify · Render · Vercel · Cloudinary |
| **Frontend** | React · Next.js · TypeScript · JavaScript · Tailwind CSS · Vite · HTML5/CSS3 |
| **Testing & Tools** | Pytest · Playwright · Streamlit · Git |

---

## 📫 Open to

Full-Stack · Backend · AI/LLM integration roles — remote (Colombia and international, full overlap with US Eastern business hours), or on-site/hybrid in Medellín.
