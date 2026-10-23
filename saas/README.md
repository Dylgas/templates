<!--
  ╔══════════════════════════════════════════════════════════╗
  ║  WEB APP / SAAS README TEMPLATE                           ║
  ║  How to use: Replace {{PLACEHOLDERS}}, drop a real        ║
  ║  screenshot into assets/, delete this comment block.     ║
  ╚══════════════════════════════════════════════════════════╝
-->

<p align="center">
  <img src="assets/hero.svg" width="100%" alt="{{APP_NAME}}">
</p>

<p align="center">
  <a href="{{LIVE_URL}}"><img src="https://img.shields.io/badge/●_Live-Visit_app-8b5cf6?style=for-the-badge&labelColor=13101f" alt="Live"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-operational-34d399?style=for-the-badge&labelColor=13101f" alt="Status"></a>
  <a href="{{DOCS_URL}}"><img src="https://img.shields.io/badge/docs-read-a78bfa?style=for-the-badge&labelColor=13101f" alt="Docs"></a>
</p>

<p align="center">
  <b>{{ONE_LINE_PITCH}}</b><br>
  <sub>{{TAGLINE}}</sub>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-tech-stack">Stack</a> •
  <a href="#-getting-started">Get started</a> •
  <a href="#-pricing">Pricing</a>
</p>

<br>

<img src="assets/h-features.svg" width="100%" alt="Features">

| | Feature | What it does |
|:-:|---|---|
| ⚡ | **{{FEATURE_1}}** | {{FEATURE_1_DESC}} |
| 🔒 | **{{FEATURE_2}}** | {{FEATURE_2_DESC}} |
| 📊 | **{{FEATURE_3}}** | {{FEATURE_3_DESC}} |
| 🔗 | **{{FEATURE_4}}** | {{FEATURE_4_DESC}} |
| 🌙 | **{{FEATURE_5}}** | {{FEATURE_5_DESC}} |
| 🚀 | **{{FEATURE_6}}** | {{FEATURE_6_DESC}} |

<br>

## 📸 Screenshots

<!-- TODO: Replace these placeholders with real screenshots in assets/ -->
<p align="center">
  <img src="https://placehold.co/900x500/13101f/a78bfa?text=Dashboard" width="48%" alt="Dashboard">
  <img src="https://placehold.co/900x500/13101f/f0abfc?text=Settings" width="48%" alt="Settings">
</p>

<br>

<img src="assets/h-stack.svg" width="100%" alt="Tech stack">

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,tailwind,nodejs,postgres,redis,docker,aws&perline=8" alt="Tech stack">
</p>

```mermaid
flowchart LR
    U([User]) --> CDN[CDN] --> APP[{{APP_NAME}}]
    APP --> API[API] --> DB[(Database)]
    API --> CACHE[(Cache)]
    API --> Q[[Jobs]]
```

<br>

## 🚀 Getting Started

```bash
git clone https://github.com/{{USER}}/{{REPO}}.git
cd {{REPO}}
cp .env.example .env    # add your keys
npm install
npm run dev             # → http://localhost:3000
```

> [!NOTE]
> See [`.env.example`](.env.example) for every setting you'll need.

### Deploy

<p>
  <a href="#"><img src="https://img.shields.io/badge/Deploy_to-Vercel-000?style=for-the-badge&logo=vercel" alt="Deploy to Vercel"></a>
  <a href="#"><img src="https://img.shields.io/badge/Deploy_to-Railway-0B0D0E?style=for-the-badge&logo=railway" alt="Deploy to Railway"></a>
  <a href="#"><img src="https://img.shields.io/badge/Deploy_with-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"></a>
</p>

<br>

<img src="assets/h-pricing.svg" width="100%" alt="Pricing">

| | **Free** | **Pro** | **Team** |
|---|:-:|:-:|:-:|
| Price | $0 | ${{PRO_PRICE}}/mo | ${{TEAM_PRICE}}/mo |
| {{LIMIT_NAME}} | {{FREE_LIMIT}} | {{PRO_LIMIT}} | Unlimited |
| Support | Community | Email | Priority |
| | | **Most popular** | |

<br>

## 🗺️ Roadmap

- [x] {{DONE_1}}
- [x] {{DONE_2}}
- [ ] {{PLANNED_1}}
- [ ] {{PLANNED_2}}

## 📄 License

{{LICENSE}} © [{{AUTHOR}}](https://github.com/{{USER}})

<p align="center">
  <img src="assets/footer.svg" width="100%" alt="Ready to get started?">
</p>
