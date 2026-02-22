# Hi, I'm Mehmet Şirin Usanmaz.

**DevOps | Cloud | Automation | Observability**

I help teams build faster, more reliable, and observable systems.

<p align="left"> <img src="https://komarev.com/ghpvc/?username=musanmaz&label=Profile%20views&color=0e75b6&style=flat" alt="musanmaz" /> </p>

---

🌐 [mehmet.tech](https://mehmet.tech) · [GitHub](https://github.com/musanmaz) · [LinkedIn](https://linkedin.com/in/mehmetsirinusanmaz) · [Medium](https://medium.com/@usanmazmehmet) · [X](https://twitter.com/musanmaz) · [Instagram](https://instagram.com/musanmaz)

📬 [hello@mehmet.tech](mailto:hello@mehmet.tech) · [info@musanmaz.com.tr](mailto:info@musanmaz.com.tr) · [usanmaz@mehmetsir.in](mailto:usanmaz@mehmetsir.in)

---

## Featured Projects

### [CronWizard](https://github.com/musanmaz/cronwizard)

Cron expression generator, validator, and scheduler toolkit.

- **Problem:** Writing and validating cron expressions manually is error-prone. Teams need a quick way to generate, verify, preview upcoming runs, and export to Kubernetes CronJob / GitHub Actions / systemd formats.
- **Tech stack:** Next.js 14 (App Router) + NestJS 10 monorepo, TypeScript, Tailwind CSS, shadcn/ui, Zod, Vitest. pnpm workspaces.
- **Use case:** DevOps and backend teams scheduling cron-based jobs. API endpoints: `generate`, `validate`, `next`, `export`, `healthz`, `readyz`.

🔗 [cronwizard.com](https://cronwizard.com)

---

### [mehmet.tech](https://github.com/musanmaz/mehmet.tech)

Personal website and digital business card.

- **Problem:** A single page to present professional profile, projects, and contact info.
- **Tech stack:** Next.js, TypeScript.
- **Use case:** Personal branding, portfolio showcase.

🔗 [mehmet.tech](https://mehmet.tech)

---

### [dns-helper](https://github.com/musanmaz/dns-helper)

Cross-platform DNS switching and benchmarking tool.

- **Problem:** Switching DNS profiles across operating systems requires different commands and manual steps. Comparing DNS performance lacks a unified tool.
- **Tech stack:** Go. Supports macOS, Linux, and Windows.
- **Use case:** Network admins, developers diagnosing DNS issues. Built-in profiles for Cloudflare, Google, Quad9, OpenDNS. Benchmarks with avg/p50/p90 latency and success rate.

```
dns-helper switch cloudflare
dns-helper benchmark all
dns-helper status
```

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

📝 [Medium — @usanmazmehmet](https://medium.com/@usanmazmehmet)

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
| 📸 Instagram | [musanmaz](https://instagram.com/musanmaz) | — |
| ✍️ Medium | [usanmazmehmet](https://medium.com/@usanmazmehmet) | — |

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
