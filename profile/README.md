<div align="center">

<img src="https://raw.githubusercontent.com/Alayra-Systems-Pvt-Limited/.github/main/profile/assets/hero.gif" alt="Alayra Systems: See clearly. Build sovereignly. Stand reliably." width="100%"/>

<br>

**Sovereign AI infrastructure, built in Pakistan for the world.**

[![Website](https://img.shields.io/badge/alayrasystems.com-C9A84C?style=for-the-badge&logo=googlechrome&logoColor=black)](https://alayrasystems.com)
[![Nexus Cloud](https://img.shields.io/badge/Nexus_Cloud-22d3ee?style=for-the-badge&logo=vercel&logoColor=black)](https://alayra-nexus-cloud-frontend.vercel.app)
[![Kinetic IDE](https://img.shields.io/badge/kinetic--ide.com-0e7490?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://kinetic-ide.com)
[![npm](https://img.shields.io/badge/npm-@alayrasystems/nexus-cb0000?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@alayrasystems/nexus)
[![X](https://img.shields.io/badge/X-@alayranexus-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/alayranexus)

</div>

---

## Who we are

**Alayra Systems** is an engineering company with teams in **Pakistan** and the **United States**. We build developer tools and AI infrastructure for people and organizations that want modern AI **without handing their code, keys, or telemetry to someone else's cloud**.

Two products, one belief: **you should own your AI stack.**

---

<div align="center">

# Alayra Nexus

**One gateway in front of every AI provider you use.**

<a href="https://alayra-nexus-cloud-frontend.vercel.app"><img src="https://raw.githubusercontent.com/Alayra-Systems-Pvt-Limited/.github/main/profile/assets/nexus.gif" alt="Alayra Nexus routing requests across providers with automatic failover" width="100%"/></a>

[![Open Nexus Cloud](https://img.shields.io/badge/Create_your_workspace-Nexus_Cloud-22d3ee?style=for-the-badge)](https://alayra-nexus-cloud-frontend.vercel.app)
[![Source](https://img.shields.io/badge/Open_source-Apache_2.0-6d28d9?style=for-the-badge&logo=github)](https://github.com/Alayra-Systems-Pvt-Limited/Alayra-Nexus)
[![Live demo](https://img.shields.io/badge/Live_demo-dashboard-0e7490?style=for-the-badge)](https://alayra-systems-pvt-limited.github.io/Alayra-Nexus/demo/)

</div>

Bring your own provider keys. Nexus sends each request through the tiers you choose, fails over when a key fails, and answers in the OpenAI format your code already speaks. Only the base URL changes.

**Where it stands today**

| | |
| :--- | :--- |
| **Open-source gateway** | Live. Self-host in three commands, Apache 2.0, on GitHub, npm and Docker Hub. |
| **Nexus Cloud sign-up** | **Open.** Create an account and workspace, verify your email, secure it with two-factor sign-in, and work with your own API keys. |
| **Hosted endpoint** | Coming soon. Nexus Cloud will run the same gateway for you. |

**What you get**

- Tiered failover (Premium, Standard, Fast) with circuit-breaking key pools
- OpenAI `/v1/chat/completions` and Anthropic `/v1/messages`, so OpenAI SDKs, Anthropic SDKs and Claude Code all route through one pool
- Cache-aware sticky routing, real-time per-key rate limits
- USD cost on every request, team attribution, analytics, CSV export
- Team keys, bring-your-own-key, optional guardrails
- Provider keys encrypted at rest with AES-256-GCM

**Providers verified with real completions:** Groq, OpenRouter, Google Gemini, Mistral, Hugging Face, Cloudflare Workers AI. OpenAI and Anthropic are available as presets, and any OpenAI-compatible endpoint can be added.

```bash
curl -O https://raw.githubusercontent.com/Alayra-Systems-Pvt-Limited/Alayra-Nexus/main/docker-compose.yml
printf 'MASTER_ENCRYPTION_KEY=%s\nADMIN_PASSWORD=change-me\n' "$(openssl rand -hex 32)" > .env
docker compose up -d
```

Dashboard on `localhost:3000`, OpenAI-compatible API on `localhost:3000/v1`.

---

<div align="center">

# Kinetic IDE

**Intelligence without surveillance. Full control. Zero cloud. Your code, your rules.**

[![Download](https://img.shields.io/badge/Start_free-90_days-C9A84C?style=for-the-badge)](https://kinetic-ide.com)
[![Engineering record](https://img.shields.io/badge/Engineering_record-GitHub-0e7490?style=for-the-badge&logo=github)](https://github.com/Alayra-Systems-Pvt-Limited/Kinetic-IDE)

</div>

A security-hardened, agentic development environment where AI reasoning, tool execution, and codebase indexing stay under your control.

| | |
| :--- | :--- |
| **RAG Engine** | Understands your whole codebase, locally. |
| **Squad Mode** | Specialist agents working together, with validated output. |
| **Pulse Archive** | Permanent session memory, so the AI stops forgetting. |
| **Sentry Gate** | Every write is approved by you. Nothing changes without consent. |
| **Bring Your Own Key** | Run your own model instances and defaults. |
| **Privacy first** | AES-256 vault, local RAG, code stays on your machine. |

---

## Public repositories

| Repository | What it is |
| :--- | :--- |
| [**Alayra-Nexus**](https://github.com/Alayra-Systems-Pvt-Limited/Alayra-Nexus) | Open-source AI gateway and operations platform. Apache 2.0. |
| [**Kinetic-IDE**](https://github.com/Alayra-Systems-Pvt-Limited/Kinetic-IDE) | The public engineering record and milestones of Kinetic IDE. |
| [**KineticFrontend**](https://github.com/Alayra-Systems-Pvt-Limited/KineticFrontend) | Public showcase of the Kinetic IDE website and its 3D interface. |

The rest of our work (the IDE core, engine, cloud services, and admin tooling) lives in private repositories.

---

## What we care about

- **Sovereignty.** Your keys, your code, your data boundary.
- **Production-grade from day one.** Routing, failover, backups, audit and security are features, not roadmap items.
- **Honest engineering.** We publish what is shipped and label what is not.
- **Open where it counts.** Nexus is open source so you can read it, run it, and trust it.

## Tech we work in

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-dea584?style=flat-square&logo=rust&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)

## Get involved

- **Create a Nexus Cloud workspace:** [alayra-nexus-cloud-frontend.vercel.app](https://alayra-nexus-cloud-frontend.vercel.app)
- **Self-host Nexus:** see the [quick start](https://github.com/Alayra-Systems-Pvt-Limited/Alayra-Nexus#quick-start)
- **Star the repos** you like, and open an issue or discussion on any public repo
- **Work or partner with us:** [info@alayrasystems.com](mailto:info@alayrasystems.com)

<br>

<div align="center">

<sub>Alayra Systems LLC (United States) &nbsp;·&nbsp; Alayra Systems Pvt. Limited (Pakistan)</sub>

</div>
