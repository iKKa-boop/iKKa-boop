<!-- Header -->
<div align="center">

```
 ██████╗ ███████╗██╗   ██╗ ██████╗ ██████╗ ███████╗
 ██╔══██╗██╔════╝██║   ██║██╔═══██╗██╔══██╗██╔════╝
 ██║  ██║█████╗  ██║   ██║██║   ██║██████╔╝███████╗
 ██║  ██║██╔══╝  ╚██╗ ██╔╝██║   ██║██╔═══╝ ╚════██║
 ██████╔╝███████╗ ╚████╔╝ ╚██████╔╝██║     ███████║
 ╚═════╝ ╚══════╝  ╚═══╝   ╚═════╝ ╚═╝     ╚══════╝
```

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=15&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=docker+build+.+--tag+adhil%3Alatest;docker+compose+up+--detach;systemctl+status+everything+%E2%9C%94;Kerala%2C+India+%F0%9F%87%AE%F0%9F%87%B3)](https://git.io/typing-svg)

</div>

---

## `$ docker inspect adhil --format '{{.Bio}}'`

DevOps engineer. Containers, pipelines, server infra — building systems that stay up and scale without drama.

Currently running **DeutschMeister** (Dockerized Next.js + NestJS + PostgreSQL) and wiring up CI/CD pipelines for production workloads.

---

## `// containers & infra`

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

## `// ci/cd & automation`

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Workflows](https://img.shields.io/badge/Workflows-Automated-6e40c9?style=flat-square)
![Scripting](https://img.shields.io/badge/Scripting-Bash-4EAA25?style=flat-square)
![Scheduled Jobs](https://img.shields.io/badge/Scheduled-Jobs-555?style=flat-square)

## `// server management`

![Port Management](https://img.shields.io/badge/Port-Management-007ACC?style=flat-square)
![Service Config](https://img.shields.io/badge/Service-Config-007ACC?style=flat-square)
![DB Schema](https://img.shields.io/badge/DB-Schema_Design-316192?style=flat-square)
![Reverse Proxy](https://img.shields.io/badge/Reverse-Proxy-009639?style=flat-square)
![Log Rotation](https://img.shields.io/badge/Log-Rotation-555?style=flat-square)

---

## `// pipeline · deutschmeister v7`

```
[ build ] → [ compose up ] → [ postgres init ] → [ scraper ] → [ :3100 ]
    ✔             ✔                 ✔                ✔          ● LIVE
```

---

## `// shipped`

<table>
<tr>
<td width="50%">

### 🐳 DeutschMeister *(v7 "Bauhaus")*
Fully Dockerized Goethe exam prep platform.

**Infra:**
- Docker Compose orchestration (3 services)
- Bind-mounted news scraper → `./data/news/`
- 9-table PostgreSQL schema
- Production port: **3100**
- Containerized cron-style scraper

`Docker` `Compose` `PostgreSQL` `NestJS` `Next.js`

</td>
<td width="50%">

### 🕷️ News Scraper Service
Containerized data pipeline with persistent storage.

**Infra:**
- Bind mounts chosen over Docker named volumes
- Targets nachrichtenleicht.de + MERLIN corpus
- CC BY-SA 4.0 content lifecycle management
- Scheduled execution inside Docker

`Docker` `Bind Mounts` `Scheduled` `Node.js`

</td>
</tr>
<tr>
<td width="50%">

### 📡 OpenRouter API Pipeline
Rate-limit-aware integration with graceful degradation.

**Infra:**
- `Retry-After` header handling on 429s
- 38-topic content pipeline (A2–C1)
- Correct base URL enforcement (`/api/v1`)

`OpenRouter` `API` `Rate limiting` `Node.js`

</td>
<td width="50%">

### 🗄️ Multi-User Browser App
Zero-dependency client-side deployment.

**Infra:**
- localStorage for cross-session persistence
- No build step, no bundler, no server
- Tab-based multi-user state management

`Browser-native` `localStorage` `Zero deps`

</td>
</tr>
</table>

---

## `// stats`

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=iKKa-boop&theme=github-dark&hide_border=true&background=0d1117&ring=58a6ff&fire=3fb950&currStreakLabel=58a6ff)

</div>

---

## `// currently running`

```yaml
containers:
  - deutschmeister-frontend:  Up   →  :3100
  - deutschmeister-api:       Up   →  NestJS
  - deutschmeister-db:        Up   →  PostgreSQL (9 tables)
  - news-scraper:             Scheduled

focus:
  - DeutschMeister v7 production hardening
  - CI/CD pipeline automation
  - Infra monitoring & log management

location: Kerala, India 🇮🇳
```

---

## `// links`

[![GitHub](https://img.shields.io/badge/GitHub-iKKa--boop-181717?style=flat-square&logo=github)](https://github.com/iKKa-boop)

---

<div align="center">
<sub><code>/* uptime: TBD · last deploy: May 2026 · Kerala, IN */</code></sub>
</div>
