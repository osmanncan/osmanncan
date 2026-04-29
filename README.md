<div align="center">

<!-- TERMINAL INIT -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&repeat=true&width=500&height=45&lines=%24+./osmancan+--init+%F0%9F%9A%80" alt="Init" />

<br/>

<!-- ASCII NAME -->
```
 ╔═══════════════════════════════════════════════════════════════════╗
 ║                                                                   ║
 ║    ▄▀▀▀▄  ▄▀▀▀▀  ▄▀▄▀▄  ▄▀▀▀▄  ▄▀  ▄  ▄▀▀▀▄  ▄▀▀▀▄  ▄▀  ▄    ║
 ║    █   █  ▀▄▄▄   █ ▀ █  █▀▀▀█  █ ▀▄█  █     ▀ █▀▀▀█  █ ▀▄█    ║
 ║    ▀▄▄▄▀  ▄▄▄▀▀  ▀   ▀  ▀   ▀  ▀   ▀  ▀▄▄▄▀  ▀   ▀  ▀   ▀    ║
 ║                                                                   ║
 ║           ⟨  Frontend  ·  Mobile  ·  Architecture  ⟩             ║
 ║                                                                   ║
 ╚═══════════════════════════════════════════════════════════════════╝
```

<br/>

<!-- BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/osmancan-altinkaynak)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:osmancann25@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/osmanncan)

---

<!-- ABOUT -->
### `> cat ./about.json`

```json
{
  "name": "Osmancan Altınkaynak",
  "title": "Frontend & Mobile Engineer",
  "location": "Turkey 🇹🇷",
  "philosophy": "Ship fast, architect smart, never compromise on UX",
  "currently": {
    "building": "Production-grade mobile apps with Expo + Supabase",
    "exploring": "AI integration & serverless edge computing",
    "obsessing_over": "60fps animations & offline-first patterns"
  },
  "goal": "Remote work + Global career 🌍"
}
```

---

<!-- SKILLS -->
### `> ls ./tech-stack --categorized`

```
 ┌─────────────────────────────────────────────────────────────────┐
 │                        TECH STACK                               │
 ├─────────────────────────────────────────────────────────────────┤
 │                                                                 │
 │  ⚛️  FRONTEND & MOBILE                                         │
 │  ├── React ························ ████████████████████░  95%  │
 │  ├── React Native (Expo) ·········· ████████████████████░  95%  │
 │  ├── Next.js ······················ █████████████████░░░░  85%  │
 │  ├── TypeScript ··················· ████████████████████░  90%  │
 │  └── CSS / Animations ············· █████████████████░░░░  85%  │
 │                                                                 │
 │  ⚙️  BACKEND & DATABASE                                        │
 │  ├── Supabase ····················· ████████████████████░  90%  │
 │  ├── PostgreSQL ··················· ████████████████░░░░░  80%  │
 │  ├── Deno Edge Functions ·········· █████████████████░░░░  85%  │
 │  └── REST API Design ·············· ████████████████████░  90%  │
 │                                                                 │
 │  🧠 ARCHITECTURE                                               │
 │  ├── Offline-First Design ········· ████████████████████░  95%  │
 │  ├── State Management ············· ████████████████████░  95%  │
 │  ├── Auth & Security ·············· █████████████████░░░░  85%  │
 │  └── Payment Systems ·············· █████████████████░░░░  85%  │
 │                                                                 │
 │  🔧 TOOLS                                                      │
 │  ├── Git / GitHub ················· ████████████████████░  90%  │
 │  ├── VS Code ····················· ████████████████████░  95%  │
 │  ├── Figma ························ █████████████████░░░░  85%  │
 │  └── CI/CD ························ ██████████████░░░░░░░  70%  │
 │                                                                 │
 └─────────────────────────────────────────────────────────────────┘
```

---

<!-- ARCHITECTURE -->
### `> docker inspect production-app --format='{{.Architecture}}'`

> _Ben sadece arayüz yazmıyorum — production-ready, ölçeklenebilir sistemler tasarlıyorum._

```
 ┌─────────────────────────────────────────────────────────────────┐
 │                    PRODUCTION ARCHITECTURE                      │
 │                                                                 │
 │     ┌──────────┐      ┌──────────────┐      ┌──────────────┐  │
 │     │  CLIENT  │ ───▶ │  DENO EDGE   │ ───▶ │  SUPABASE /  │  │
 │     │  (Expo)  │ ◀─── │  FUNCTIONS   │ ◀─── │  POSTGRESQL  │  │
 │     └────┬─────┘      └──────┬───────┘      └──────────────┘  │
 │          │                   │                                  │
 │          │            ┌──────┴───────┐                         │
 │          │            │   SERVICES   │                         │
 │          │            ├──────────────┤                         │
 │          │            │ ▸ RevenueCat │── Payment validation    │
 │          │            │ ▸ Gemini AI  │── Proxied, keys hidden  │
 │          │            │ ▸ Deep Links │── Asymmetric auth       │
 │          │            └──────────────┘                         │
 │          │                                                     │
 │     ┌────┴──────────────────────────────────────────────┐      │
 │     │              LOCAL CACHE LAYER                    │      │
 │     │  Zustand + AsyncStorage  ·  Offline-first         │      │
 │     │  Minimize API calls  ·  Zero-downtime UX          │      │
 │     └───────────────────────────────────────────────────┘      │
 │                                                                 │
 └─────────────────────────────────────────────────────────────────┘
```

<details>
<summary><b>📋 Mimari detayları göster</b></summary>
<br/>

| Katman | Teknoloji | Detay |
|:------:|:---------:|:------|
| 🛡️ | **Supabase / PostgreSQL** | Deep Link ile asymmetric encryption auth, strict RLS ile kullanıcılar arası tam veri izolasyonu |
| ⚡ | **Deno Edge Functions** | V8 üzerinde ultra-hızlı serverless — RevenueCat webhook validasyonu, Gemini AI proxy ile API key gizleme |
| 💳 | **RevenueCat** | Apple/Google IAP lifecycle yönetimi, free trial takibi, secure server-side renewal |
| 💾 | **Zustand + AsyncStorage** | Offline-first deneyim — global state lokal cache ile senkronize, internet olmadan bile tam çalışır |

</details>

---

<!-- GIT LOG -->
### `> git log --oneline --graph`

```
 * ⚡ feat: production-grade mobile app with offline-first architecture
 * 🔒 feat: serverless edge functions for payment & AI proxy
 * 🛡️ feat: asymmetric auth with deep links + row level security
 * ♻️  refactor: zustand state management with persistent cache layer
 * 🎨 feat: 60fps animation system with reanimated
 * 🚀 init: expo + supabase + typescript monorepo
```

---

<!-- NEOFETCH -->
### `> neofetch`

```
                                   osmancan@developer
    ┌──────────────┐               ──────────────────────
    │              │               OS      macOS / Windows
    │    ⌨️  📱    │               Shell   zsh + oh-my-zsh
    │              │               Editor  VS Code (vim keybindings)
    │    ☕  🚀    │               Stack   React Native · Expo · Supabase
    │              │               Focus   Mobile-first, offline-first
    │    🎯  💡    │               Status  Open to remote opportunities 🌍
    │              │               Uptime  Coding since day one
    └──────────────┘               
```

---

<!-- CONTACT -->
### `> echo $OPEN_FOR`

```
 ┌─────────────────────────────────────────────────────────────────┐
 │                                                                 │
 │   💼  Remote & freelance opportunities                          │
 │   🌍  Global career, location independent                      │
 │   🤝  Challenging mobile & full-stack projects                  │
 │   🚀  Open source collaboration                                │
 │                                                                 │
 │   → Let's build something great together.                       │
 │                                                                 │
 └─────────────────────────────────────────────────────────────────┘
```

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=4000&pause=2000&color=00FF41&center=true&vCenter=true&repeat=true&width=280&height=20&lines=%24+exit+0+%E2%9C%93;Connection+closed." alt="Exit" />

</div>
