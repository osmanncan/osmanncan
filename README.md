<div align="center">

<!-- GLITCH HEADER -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=30&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&multiline=false&repeat=true&width=435&height=50&lines=%24+./osmancan+--init" alt="Terminal Init" />

</div>

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   ██████╗ ███████╗███╗   ███╗ █████╗ ███╗   ██╗ ██████╗ █████╗ ███╗   ██╗   ║
║  ██╔═══██╗██╔════╝████╗ ████║██╔══██╗████╗  ██║██╔════╝██╔══██╗████╗  ██║   ║
║  ██║   ██║███████╗██╔████╔██║███████║██╔██╗ ██║██║     ███████║██╔██╗ ██║   ║
║  ██║   ██║╚════██║██║╚██╔╝██║██╔══██║██║╚██╗██║██║     ██╔══██║██║╚██╗██║   ║
║  ╚██████╔╝███████║██║ ╚═╝ ██║██║  ██║██║ ╚████║╚██████╗██║  ██║██║ ╚████║   ║
║   ╚═════╝ ╚══════╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝  ║
║                                                                              ║
║                  Frontend & Mobile Engineer  ·  Turkey 🇹🇷                   ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

<a href="https://www.linkedin.com/in/osmancan-altinkaynak"><img src="https://img.shields.io/badge/-%2Fosmancan--altinkaynak-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
<a href="mailto:osmancann25@gmail.com"><img src="https://img.shields.io/badge/-osmancann25%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;
<a href="https://github.com/osmanncan"><img src="https://img.shields.io/badge/-osmanncan-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

### `> cat about.json`

```json
{
  "name": "Osmancan Altınkaynak",
  "title": "Frontend & Mobile Engineer",
  "based_in": "Turkey",
  "focus": "Building production-grade mobile apps that people actually use",
  "philosophy": "Ship fast, architect smart, never compromise on UX",
  "currently": {
    "building": "Full-stack mobile apps with Expo + Supabase",
    "exploring": "AI integration, serverless edge computing",
    "obsessing_over": "60fps animations & offline-first patterns"
  }
}
```

---

### `> ls ./skills --tree`

```
skills/
├── frontend/
│   ├── react ··················· ████████████████████░░  95%
│   ├── react-native (expo) ····· ████████████████████░░  95%
│   ├── next.js ················· ██████████████████░░░░  85%
│   ├── typescript ·············· ████████████████████░░  90%
│   └── css/animations ·········· ██████████████████░░░░  85%
│
├── backend/
│   ├── supabase ················ ████████████████████░░  90%
│   ├── postgresql ·············· ████████████████░░░░░░  80%
│   ├── deno edge functions ····· ██████████████████░░░░  85%
│   └── rest api design ········· ████████████████████░░  90%
│
├── architecture/
│   ├── offline-first ··········· ████████████████████░░  95%
│   ├── state management ········ ████████████████████░░  95%
│   ├── auth & security ········· ██████████████████░░░░  85%
│   └── payment systems ········· ██████████████████░░░░  85%
│
└── tools/
    ├── git ····················· ████████████████████░░  90%
    ├── figma ··················· ██████████████████░░░░  85%
    ├── vs code ················· ████████████████████░░  95%
    └── ci/cd ··················· ██████████████░░░░░░░░  70%
```

---

### `> docker inspect production-app --format='{{.Architecture}}'`

Ben sadece arayüz yazmıyorum — **production-ready, ölçeklenebilir sistemler** tasarlıyorum.

```
┌─────────────────────────────────────────────────────────────────────┐
│                        SYSTEM ARCHITECTURE                          │
│                                                                     │
│  ┌──────────┐     ┌──────────────┐     ┌────────────────────────┐  │
│  │  Client   │────▶│  Deno Edge   │────▶│  Supabase / PostgreSQL │  │
│  │  (Expo)   │◀────│  Functions   │◀────│  + Row Level Security  │  │
│  └──────────┘     └──────┬───────┘     └────────────────────────┘  │
│       │                  │                                          │
│       │           ┌──────┴───────┐                                  │
│       │           │   Services   │                                  │
│       │           ├──────────────┤                                  │
│       │           │ • RevenueCat │─── Payment validation            │
│       │           │ • Gemini AI  │─── Proxied, keys hidden          │
│       │           │ • Deep Links │─── Asymmetric auth               │
│       │           └──────────────┘                                  │
│       │                                                             │
│  ┌────┴─────────────────────────────────────────────┐               │
│  │              CLIENT-SIDE CACHE LAYER             │               │
│  │  Zustand + AsyncStorage  ·  Offline-first        │               │
│  │  Minimize API calls  ·  Reduce cloud costs       │               │
│  └──────────────────────────────────────────────────┘               │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

<details>
<summary><b>⚡ Mimari detayları göster</b></summary>
<br/>

| Katman | Teknoloji | Ne Yaptım |
|--------|-----------|-----------|
| 🛡️ **Auth & DB** | Supabase / PostgreSQL | Deep Link ile asymmetric encryption auth, strict RLS ile kullanıcılar arası tam veri izolasyonu |
| ⚡ **Edge Backend** | Deno Edge Functions | V8 üzerinde ultra-hızlı serverless; RevenueCat webhook'ları server-side'da validate, Gemini AI isteklerini proxy ile API key'leri %100 gizli |
| 💳 **Payments** | RevenueCat | Apple/Google IAP lifecycle yönetimi, free trial takibi, secure renewal validation |
| 💾 **Cache** | Zustand + AsyncStorage | Offline-first deneyim; global state lokal cache ile senkronize, sunucu istekleri minimumda, internet olmadan bile uygulama çalışır |

</details>

---

### `> git log --oneline --graph | head -5`

```
* feat: production-grade mobile app with offline-first architecture
* feat: serverless edge functions for payment & AI proxy
* feat: asymmetric auth with deep links + row level security
* refactor: zustand state management with persistent cache
* init: expo + supabase + typescript boilerplate
```

---

### `> neofetch`

```
                    osmancan@developer
   ╭──────────╮     ─────────────────────
   │  ⌨️  📱  │     OS:      macOS / Windows
   │  ☕  🚀  │     Shell:   zsh + oh-my-zsh
   │  🎯  💡  │     Editor:  VS Code (vim keybindings)
   ╰──────────╯     Stack:   React Native · Expo · Supabase
                    Focus:   Mobile-first, offline-first
                    Status:  Open to remote opportunities 🌍
                    Uptime:  Coding since day one
```

---

<div align="center">

### `> echo $CONTACT`

```
 ┌──────────────────────────────────────────────────┐
 │                                                    │
 │   💼  Open to remote & freelance opportunities     │
 │   🌍  Global career, location independent          │
 │   🤝  Interested in challenging mobile projects    │
 │                                                    │
 │   Let's build something great together.            │
 │                                                    │
 └──────────────────────────────────────────────────┘
```

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=4000&pause=2000&color=00FF41&center=true&vCenter=true&repeat=true&width=300&height=25&lines=%24+exit+0+%E2%9C%93;Connection+closed." alt="Exit" />

</div>
