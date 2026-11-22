<div align="center">

<img src="https://nyumi.cat/brand/paw.png" width="80" alt="nyumi" />

# nyumi.cat

**soft paws, sharp claws.**

game enhancement platform with cloud configs, real-time updates,<br>
invite-only accounts, and a community that actually helps.

[![website](https://img.shields.io/badge/nyumi.cat-visit-f7d1f5?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJhMTAgMTAgMCAxIDAgMCAyMCAxMCAxMCAwIDAgMCAwLTIwem0wIDE4YTggOCAwIDEgMSAwLTE2IDggOCAwIDAgMSAwIDE2eiIgZmlsbD0iI2Y3ZDFmNSIvPjwvc3ZnPg==)](https://nyumi.cat)
[![discord](https://img.shields.io/badge/discord-join-5865f2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/nyumi)
[![status](https://img.shields.io/badge/status-check-10b981?style=flat-square)](https://nyumi.cat/status)

</div>

---

### architecture

```
nyumi.cat
├── web        next.js 16 · tailwind 4 · react 19 · server components
├── api        rust · axum · sqlite · passkey auth · crypto payments
├── loader     native game client · auto-update · cloud configs
└── docs       internal guides and runbooks
```

### stack

| layer | tech |
|:------|:-----|
| **frontend** | next.js 16, react 19, tailwind css 4 |
| **backend** | rust, axum, sqlx, sqlite |
| **auth** | webauthn/passkeys + password fallback |
| **payments** | nowpayments (ltc, btc, eth, sol, usdt, +) |
| **infra** | coolify, ovh bare metal, cloudflare |
| **chat** | real-time global chat with polling |

### features

- 🎮 cloud-synced game configs with version detection
- 🔐 passkey authentication (webauthn)
- 💸 white-label crypto checkout (8 coins)
- 👤 public profiles with avatars & banners
- 💬 global community chat
- 🎫 invite-only registration system
- 📦 license key distribution

<div align="center">
<sub>built with care · <a href="https://nyumi.cat">nyumi.cat</a></sub>
</div>
