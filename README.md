# Hi, I'm Mehmet Şirin Usanmaz.

**DevOps | Cloud | Automation | Observability**

I help teams build faster, more reliable, and observable systems.

<p align="left"> <img src="https://komarev.com/ghpvc/?username=musanmaz&label=Profile%20views&color=0e75b6&style=flat" alt="musanmaz" /> </p>

---

<p align="left">
  <a href="https://mehmet.tech"><img src="https://img.shields.io/badge/mehmet.tech-000000?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://github.com/musanmaz"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/mehmetsirinusanmaz"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@musanmaz"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="https://twitter.com/musanmaz"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>

<p align="left">
  <a href="mailto:hello@mehmet.tech"><img src="https://img.shields.io/badge/hello@mehmet.tech-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="mailto:info@musanmaz.com.tr"><img src="https://img.shields.io/badge/info@musanmaz.com.tr-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email" /></a>
  <a href="mailto:usanmaz@mehmetsir.in"><img src="https://img.shields.io/badge/usanmaz@mehmetsir.in-333333?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
</p>

---

## Featured Projects

### [Runtrixy](https://runtrixy.com)

No-code BDD test automation platform for web, REST API, and SQL testing.

- **Problem:** Teams need to write and execute BDD tests without coding expertise. Existing tools are fragmented across web UI, API, and database testing. Runtrixy unifies all three under a single Gherkin-based platform with 300+ predefined steps.
- **Tech stack:** Java 21, Spring Boot 3.x, React 18, TypeScript, Vite, Tailwind CSS, Next.js 16 (landing), PostgreSQL 16, Redis 7, MinIO, Selenium WebDriver, Cucumber/Gherkin.
- **Use case:** QA teams and developers automating BDD test scenarios. Features include Monaco editor with Gherkin autocomplete, Git integration (GitHub/GitLab/Bitbucket), real-time WebSocket execution, scheduled runs, visual regression, and multi-language support (70+ languages including Turkish).

🔗 [runtrixy.com](https://runtrixy.com)

---

### [HesapBotu](https://hesapbotu.com)

Turkey's smart calculator and AI analysis platform — 10+ categories, live data, and a Gemini-powered assistant.

- **Problem:** Turkish users have no single, accurate tool for finance, career, and education calculations. Switching between scattered calculators is slow, and none offer natural-language queries.
- **Tech stack:** Next.js 16 (App Router), Tailwind CSS v4, Prisma, Neon PostgreSQL, Vercel. Cookie-based JWT auth with Edge-compatible `jose`; Gemini AI via `@google/genai`.
- **Calculators (10+ categories):** Loan amortisation (İhtiyaç/Konut/Taşıt) with BSMV & KKDF, net/gross salary with 12-month progressive tax brackets, LGS percentile and TYT/AYT/Y-SAY/Y-EA score panels (OBP included), BMR/ideal weight, gold, currency, crypto, and more.
- **AI Assistant:** The `HesapBotu` widget accepts free-form Turkish queries (`"100.000 TL kredi 3.5 faizle 12 ayda ne kadar?"`) and routes them to the correct calculator engine via Gemini intent parsing.
- **Live data:** Exchange rates (`exchangerate-api.com`), BTC/ETH/BNB and gold prices (`CoinGecko`, XAU-indexed), all proxied server-side with 5–60 min revalidation to keep API keys off the client.
- **Blog & FAQ:** Full blog system (Markdown + custom TOC, JSON-LD `Article`/`FAQPage` schemas, related posts/calculators). 20+ FAQ entries across 5 categories at `/sss`.
- **Admin panel:** Dark-mode dashboard with Markdown preview editor, soft/hard delete, image upload (5 MB cap, images only), and brute-force delay. DOMPurify sanitisation against stored XSS. *(Private repository.)*

🔗 [hesapbotu.com](https://hesapbotu.com)

---

### [CronWizard](https://github.com/musanmaz/cronwizard)

Cron expression generator, validator, and scheduler toolkit.

- **Problem:** Writing and validating cron expressions manually is error-prone. Teams need a quick way to generate, verify, preview upcoming runs, and export to Kubernetes CronJob / GitHub Actions / systemd formats.
- **Tech stack:** Next.js 14 (App Router) + NestJS 10 monorepo, TypeScript, Tailwind CSS, shadcn/ui, Zod, Vitest. pnpm workspaces.
- **Use case:** DevOps and backend teams scheduling cron-based jobs. API endpoints: `generate`, `validate`, `next`, `export`, `healthz`, `readyz`.

🔗 [cronwizard.com](https://cronwizard.com)

---

### [NEXTERM](https://github.com/musanmaz/nexterm)

AI-powered terminal emulator and DevOps desktop workspace with a sci-fi interface.

- **Problem:** Developers juggle between terminal, Docker Desktop, Kubernetes dashboards, Git GUIs, and SSH clients. NEXTERM unifies terminal emulation, container management, Kubernetes operations, Git visualization, SSH connections, and AI chat into a single fullscreen workspace — a modern spiritual successor to [eDEX-UI](https://github.com/GitSquared/edex-ui).
- **Tech stack:** Tauri v2 (Rust), Svelte 5, TypeScript, Vite 6, xterm.js, Three.js, Tailwind CSS. Rust crates: `sysinfo`, `portable-pty`, `bollard` (Docker), `git2`. Distributed via [Homebrew](https://github.com/musanmaz/homebrew-nexterm): `brew tap musanmaz/nexterm && brew install nexterm`.
- **Use case:** DevOps engineers and developers who want a single-pane-of-glass workspace. Features include multi-tab terminal, multi-provider AI chat (LiteLLM/OpenAI/Anthropic/Ollama) with 4 modes (Chat/Plan/Agent/Ask), Docker container & image management with exec, Kubernetes context/namespace/pod/deployment control, Git branch graph & status synced with terminal CWD, SSH profile manager, real-time system monitoring, and 5 built-in themes.

---

### [Spyglass](https://github.com/musanmaz/spyglass)

Modern, open-source network looking glass for ISPs and network operators.

- **Problem:** ISPs and network operators need a clean, modern web interface to let users run BGP route lookups, ping, and traceroute queries across multiple routers. Legacy looking glass tools lack real-time streaming and multi-platform support.
- **Tech stack:** Python 3.11+, FastAPI, SQLAlchemy 2, Netmiko, React 18, TypeScript 5, Tailwind CSS, Zustand, PostgreSQL 15, Redis 7, Docker, Nginx.
- **Use case:** Network operators providing public or internal looking glass services. Supports 13 router platforms (Cisco IOS/IOS-XR/NX-OS, Juniper, Arista, Huawei, Nokia, MikroTik, FRRouting, BIRD, VyOS, and more) with real-time WebSocket streaming.

🔗 [spyglass.mehmet.tech](https://spyglass.mehmet.tech)

---

### [NetShift](https://github.com/musanmaz/netshift)

Native macOS menu bar app for managing DNS servers and `/etc/hosts` files.

- **Problem:** Switching DNS profiles and managing hosts files on macOS requires terminal commands and manual editing. NetShift provides a single-click solution with a native menu bar interface.
- **Tech stack:** Swift, SwiftUI, macOS 14+ (Sonoma). Distributed via [Homebrew](https://github.com/musanmaz/homebrew-netshift): `brew tap musanmaz/netshift && brew install --cask netshift`.
- **Use case:** Developers and network admins managing multiple hosts files and DNS configurations. Features include hosts file editor (local, remote, combined), DNS profiles (Cloudflare, Google, Quad9, OpenDNS), DNS benchmark with avg/P50/P90 latency, and automatic DNS cache flushing.

---

### [local-llm](https://github.com/musanmaz/local-llm)

Multi-model chat app that queries 4 LLMs in parallel and generates a judge summary.

- **Problem:** Comparing responses across multiple LLM providers requires switching between tools. local-llm sends every message to 4 models simultaneously via a LiteLLM proxy and uses a judge model to synthesize a summary — all in one interface.
- **Tech stack:** Next.js 15 (App Router), PostgreSQL, LiteLLM proxy, Docker Compose. Cookie-based JWT session management; supports OpenAI, Anthropic, xAI (Grok), and Google Gemini.
- **Use case:** Developers and researchers evaluating LLM quality side-by-side. Supports cheap/best model mode switching, persistent thread history, and self-hosted deployment via Docker.

---

### [BoxGuard](https://github.com/musanmaz/BoxGuard)

Vagrant box and SSH vulnerability scanner with real CVE integration.

- **Problem:** Detecting security vulnerabilities in Vagrant boxes and remote systems requires manual checks or complex toolchains. BoxGuard automates OS detection, package inventory, and CVE matching in a single CLI tool.
- **Tech stack:** Go, OSV.dev API, Ubuntu USN feeds. Hybrid matching engine combining real CVE data with stub rules.
- **Use case:** Security-conscious teams scanning Vagrant environments and SSH-reachable hosts. Supports Ubuntu, Debian, RHEL, CentOS, Rocky Linux, AlmaLinux with table and JSON output formats.

---

### [mehmet.tech](https://github.com/musanmaz/mehmet.tech)

Personal website and digital business card.

- **Problem:** A single page to present professional profile, projects, and contact info.
- **Tech stack:** Next.js, TypeScript.
- **Use case:** Personal branding, portfolio showcase.

🔗 [mehmet.tech](https://mehmet.tech)

---

### [TurkNet/consul-io](https://github.com/TurkNet/consul-io)

CLI tool to import and export configuration files to/from Consul KV store.

- **Problem:** Managing configuration files across microservices in Consul KV requires manual uploads or custom scripts. consul-io automates bulk import/export with directory structure preservation, ACL token support, `--ignore` filtering, and colorful console output.
- **Tech stack:** Go, Cobra CLI, HashiCorp Consul API, fatih/color.
- **Use case:** Microservice infrastructures using Consul for config management. Finds `.production` files in a directory tree and syncs them with Consul KV.

```
consul-io import test --ignore="test/team1/apps/project2"
consul-io export test
consul-io version
```

---

### [TurkNet/TnHermione](https://github.com/TurkNet/TnHermione)

AI-powered chatbot with image generation, multilingual support, and Prometheus metrics.

- **Problem:** Internal teams need a conversational AI assistant that answers questions, generates images from prompts, filters sensitive information (passwords, tokens, keys), and integrates with Microsoft Teams — all with built-in observability.
- **Tech stack:** Python, Microsoft Bot Framework, Prometheus `/metrics` endpoint, Docker.
- **Use case:** Enterprise teams needing an AI chatbot with sensitive data filtering, command support (`/clean`, `/language`, `/image`, `/help`, `/nolog`, `/log`), and monitoring via Prometheus.

---

### [bb-dev-report](https://github.com/musanmaz/bb-dev-report)

Developer activity reporting app for Bitbucket Cloud via Atlassian Connect.

- **Problem:** Engineering managers need visibility into developer contributions across Bitbucket workspaces without manually aggregating data.
- **Tech stack:** JavaScript, Node.js, Express, Atlassian Connect.
- **Use case:** Team leads and engineering managers tracking developer productivity.

---

## Other Projects

### DevOps / Platform Tooling

| Project | Description | Language |
|---------|-------------|----------|
| [docker-slave](https://github.com/musanmaz/docker-slave) | Docker slave image for Jenkins | Dockerfile |
| [docker-jenkins-slave-atlassian-sdk](https://github.com/musanmaz/docker-jenkins-slave-atlassian-sdk) | Jenkins slave image with Atlassian SDK | Dockerfile |
| [chrome-stable](https://github.com/musanmaz/chrome-stable) | Chrome Stable installation script | Shell |
| [jira](https://github.com/musanmaz/jira) | Jira helper tools | Shell |
| [docker-dashing](https://github.com/musanmaz/docker-dashing) | Dashing dashboard Docker container | Shell |

### CI/CD & Pipelines

| Project | Description | Language |
|---------|-------------|----------|
| [hello-github-actions](https://github.com/musanmaz/hello-github-actions) | GitHub Actions starter template | Dockerfile |
| [nodejs-docker-jenkins-slave](https://github.com/musanmaz/nodejs-docker-jenkins-slave) | Node.js Jenkins slave image | Dockerfile |
| [dotnet-core-slave](https://github.com/musanmaz/dotnet-core-slave) | .NET Core Jenkins slave image | Dockerfile |

### Learning / Demo

| Project | Description | Language |
|---------|-------------|----------|
| [DreamTest](https://github.com/musanmaz/DreamTest) | Test automation experiment | Java |
| [allure-report-gradle](https://github.com/musanmaz/allure-report-gradle) | Allure Report + Gradle integration | Java |
| [example-node-rest](https://github.com/musanmaz/example-node-rest) | Node.js REST API example | JavaScript |
| [senfoni](https://github.com/musanmaz/senfoni) | JavaScript project | JavaScript |

---

## Technology Focus

| Platform & Cloud | Observability & Automation |
|---|---|
| Kubernetes, OpenShift | Grafana, Prometheus |
| Docker, Container Security | Elasticsearch, Kibana (ELK) |
| AWS, Azure | Consul, Vault |
| Jenkins, GitHub Actions | Selenium, Test Automation |
| Nginx, OpenResty | Kafka |
| Node.js, Go, TypeScript | Redis, PostgreSQL, MongoDB |

---

## Open Source & Contributions

### Forks

| Repo | Description |
|------|-------------|
| [wiremock](https://github.com/musanmaz/wiremock) | HTTP service mocking tool *(fork)* |
| [mocha](https://github.com/musanmaz/mocha) | JavaScript test framework *(fork)* |
| [wolfichef](https://github.com/musanmaz/wolfichef) | Secure image creator with Wolfi packages *(fork)* |
| [container-up](https://github.com/musanmaz/container-up) | Container demos in various languages *(fork)* |
| [sonarqube-openshift-docker](https://github.com/musanmaz/sonarqube-openshift-docker) | OpenShift SonarQube Docker build *(fork)* |
| [jira-openshift](https://github.com/musanmaz/jira-openshift) | Jira templates for OpenShift *(fork)* |
| [crowd](https://github.com/musanmaz/crowd) | Dockerized Atlassian Crowd *(fork)* |
| [bitbucket](https://github.com/musanmaz/bitbucket) | Dockerized Atlassian Bitbucket *(fork)* |
| [confluence](https://github.com/musanmaz/confluence) | Dockerized Atlassian Confluence *(fork)* |
| [letsencrypt](https://github.com/musanmaz/letsencrypt) | Dockerized Let's Encrypt Client *(fork)* |
| [docker-atlassian-sdk](https://github.com/musanmaz/docker-atlassian-sdk) | Atlassian SDK Docker image *(fork)* |
| [setup-java](https://github.com/musanmaz/setup-java) | GitHub Actions Java setup *(fork)* |

### Organization Contributions

- **[TurkNet/consul-io](https://github.com/TurkNet/consul-io)** — Consul KV import/export CLI tool (Go)
- **[TurkNet/TnHermione](https://github.com/TurkNet/TnHermione)** — AI-powered chatbot with sensitive data filtering (Python)

---

## Writing

📝 [Medium — @musanmaz](https://medium.com/@musanmaz)

- [My One-Year Leadership Journey: Expectations, Realities, and Lessons Learned](https://medium.com/turknettech/bir-y%C4%B1ll%C4%B1k-liderlik-yolculu%C4%9Fum-beklentiler-ger%C3%A7ekler-ve-%C3%B6%C4%9Frendiklerim-e5db422b4bc6)
- [Consul IO: A Simple and Effective CLI Tool](https://medium.com/turknettech/consul-io-basit-ve-etkili-bir-cli-arac%C4%B1-b5c77739194a)
<!-- Add new articles here -->

---

## Contact

| Channel | Address | Purpose |
|---------|---------|---------|
| ✉️ Email | [hello@mehmet.tech](mailto:hello@mehmet.tech) | General inquiries |
| 💼 Email | [info@musanmaz.com.tr](mailto:info@musanmaz.com.tr) | Business / proposals |
| 📧 Email | [usanmaz@mehmetsir.in](mailto:usanmaz@mehmetsir.in) | Alternative |
| 🌐 Website | [mehmet.tech](https://mehmet.tech) | — |
| 🐙 GitHub | [musanmaz](https://github.com/musanmaz) | — |
| 💼 LinkedIn | [mehmetsirinusanmaz](https://linkedin.com/in/mehmetsirinusanmaz) | — |
| 🐦 X | [musanmaz](https://twitter.com/musanmaz) | — |
| ✍️ Medium | [musanmaz](https://medium.com/@musanmaz) | — |

---

## GitHub Stats

<p align="center">
  <a href="https://github.com/musanmaz">
    <img height="180" src="https://github-readme-stats-fast.vercel.app/api?username=musanmaz&show_icons=true&theme=transparent&include_all_commits=true&show=reviews,prs_merged,prs_merged_percentage" alt="Mehmet's GitHub stats" />
  </a>
  <a href="https://github.com/musanmaz">
    <img height="180" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=musanmaz&layout=compact&theme=transparent&langs_count=8" alt="Top Languages" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/musanmaz">
    <img src="https://github-readme-stats-fast.vercel.app/api/streak?username=musanmaz&theme=transparent" alt="GitHub Streak" />
  </a>
</p>

---

<sub>Domains: [mehmet.tech](https://mehmet.tech) · [musanmaz.com.tr](https://musanmaz.com.tr) · [mehmetsir.in](https://mehmetsir.in)</sub>
