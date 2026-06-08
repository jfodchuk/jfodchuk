# Hi, I'm John Fodchuk 👋

I build **privacy-first, self-hosted software** — and run the infrastructure it lives on.
By day I'm a maintenance & reliability foreman keeping gas plants and power generation online;
by night I ship products and operate a homelab that treats **reliability and data-integrity as features, not afterthoughts.**

---

## 🚀 What I'm building

### 🌱 [RootsX](https://github.com/jfodchuk/rootsx-showcase) — Employment Case Management Platform
Case management for a Canadian non-profit: caseworkers track client employment journeys —
participant records, case notes, action plans, AI-assisted workflows, and outcome reporting —
built **security-first** (encrypted at rest, JWT auth) and shipped to AWS via GitHub Actions OIDC.

`TypeScript` · `Next.js` · `PostgreSQL` · `AWS ECS Fargate` · `CDK` — live at [rootsx.org](https://rootsx.org)

### 🔍 [MatchForge](https://github.com/jfodchuk/matchforge-showcase) — AI Dating Safety & Due-Diligence
A privacy-conscious safety tool for dating: drag in publicly-visible profile screenshots and AI scores
authenticity, catfish/bot risk, and compatibility into a private shortlist — every signal explained,
public-source input only. Decision-support, not a background check.

`Python` · `FastAPI` · `PostgreSQL + pgvector` · `Redis` · `Stripe` · `DigitalOcean` — live at [match-forge.com](https://match-forge.com)

---

## 🧰 Homelab & systems

Beyond the products, I run a multi-node homelab (Proxmox / LXC) operating **autonomous, instrumented
systems** — multi-agent orchestration, scheduled data pipelines, and a hard discipline around
**measurement integrity**: reconcile independent sources of truth, and refuse to act when they disagree.
One piece of that is open-sourced 👇

- **[xcheck](https://github.com/jfodchuk/xcheck)** — a three-source reconciliation tool. Compare independent measurements
  (API vs ledger vs source-of-truth), flag drift past a threshold, and **fail loud** instead of
  trusting one number. Born from a real incident where internal counters silently diverged from reality.

---

## 🧭 Principles

- **Privacy-conscious** — collect the minimum, guard it, be explicit about what the data is and isn't
- **Measurement integrity** — trust verified numbers over comfortable assumptions; reconcile, don't assume
- **Fail loud, roll back clean** — instrument before you change; every change ships with a revert
- **Responsible use** — decision-support for authorized data only

---

## 📊 GitHub

![John's GitHub stats](https://github-readme-stats.vercel.app/api?username=jfodchuk&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jfodchuk&layout=compact&langs_count=8&theme=tokyonight)

---

## 📫 Connect

- 🌐 [rootsx.org](https://rootsx.org) · [match-forge.com](https://match-forge.com)
- 🐦 X: [@fawdchucker](https://x.com/fawdchucker)
- 💬 Open to collaboration on self-hosted AI, homelab automation, and reliability tooling.

---
*Build tools that respect privacy. Ship on the homelab first.*
