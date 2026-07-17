# Hey, I am Rhythm

Full-stack developer (MERN + Fastify) at Tglobal, New Delhi. I build and debug production systems for real businesses: inventory, billing, healthcare claims, finance analytics. Looking for full-time Node/React roles where I can own backend problems.

**Latest shipped: [Sifinn](https://sifinn.vercel.app) — a live FP&A platform for Indian SaaS startups.**

> **understanding > memorizing**

[Email](mailto:rhythmmittal19@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rhythmmittal19/) · [Portfolio](https://rhythmmittal19.github.io)

## What I ship at work

- Vendor stock counts were silently corrupting to zero on size-only sales. Traced it to a projection-blind recompute and fixed it for good. ~140 commits on that production MERN dashboard, backed by ~198 server tests.
- Every dashboard KPI showed ₹0 despite 27 real bills in the system. Root cause: IST timezone math rolled "today" over at 5:30 AM, plus a missing import that 500ed the stats route. Fixed with timezone-aware aggregation.
- Built the GST returns/credit-note flow: server-authoritative refund math, proportional discount scaling, atomic transactions. The server never trusts client money math.
- WhatsApp shopkeeper assistant: Fastify + Prisma + PostgreSQL + Redis + BullMQ behind a webhook-to-queue pipeline. Hinglish rule-based NLU with 62 tests, GST invoice PDFs, 4-role RBAC.
- Cut marketing-site assets from 1.1 MB to 468 KB with an SVGO pipeline. Reversed a naive code-splitting strategy that caused 50-200ms hydration hiccups mid-scroll.
- Healthcare claims SaaS frontend (~61k LOC): notifications service wired into 49 mutation hooks, ~120-column bulk-claim template validation (CPT, NPI, ICD-10).

Employer code is private. Sifinn is the part you can click. Happy to whiteboard the rest.

AI tools are part of my daily workflow; the architecture, the code review, and every fix above are mine. My commits carry Co-Authored-By trailers because I disclose it.

## Things you can actually run

- 🟢 [Sifinn](https://sifinn.vercel.app) — live FP&A platform. Next.js 16 + Python/DuckDB core, import engine validated to-the-rupee against real partner workbooks.
- ⌨️ [Task-Tracker](https://github.com/RhythmMittal19/Task-Tracker) — task manager CLI in pure Node.js. Zero dependencies on purpose.
- 📊 [Github-User-Activity](https://github.com/RhythmMittal19/Github-User-Activity) — GitHub activity from the terminal. Plain fetch, no libraries.
- 🧱 [git-gud](https://github.com/RhythmMittal19/git-gud) — 26 vanilla-JS projects, zero frameworks, all logic hand-written. Built to understand, not to ship fast.

## Now

- Rebuilding [my portfolio](https://github.com/RhythmMittal19/rhythmmittal19.github.io) in React. Watch the commits.
- Going deeper on React internals. Notes land in project READMEs as I go.

## Stack

Daily: JavaScript/TypeScript, Node.js, Fastify, Express, React, Next.js, Prisma, PostgreSQL, MongoDB, Redis. Also at home with: Python, Docker, Git, Linux.

## Stats

Both cards below are generated daily by my own GitHub Actions pipeline in this repo. No third-party stats services.

<table>
  <tr>
    <td><img src="stats.svg" alt="GitHub stats, self-generated daily" /></td>
    <td><img src="languages.svg" alt="Language breakdown, self-generated daily" /></td>
  </tr>
</table>

---

*Every line understood. Delhi, India.*
