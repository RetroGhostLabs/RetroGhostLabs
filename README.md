<p align="center">
  <img src="https://content.diamondops.gg/news/9c659aac-e7ef-43c8-bf86-a3b6b4deccad.webp" width="220" alt="Illustration of Shaun in a baseball cap holding a game controller, with the DiamondOps and RetroGhost Labs logos behind him" />
</p>

<h1 align="center">Hey, I'm Shaun 👻</h1>

<p align="center">
  <b>Solo developer &amp; founder at RetroGhost Labs</b> — a.k.a. <i>the Headghoul of RGL</i><br/>
  I build native iOS apps, a production web platform, a backend that feeds them all,<br/>
  and the AI tooling that lets one person ship like a team.
</p>

<p align="center">
  <a href="https://retroghostlabs.com/dev-corner/"><b>🛠️ Dev Corner</b></a> ·
  <a href="https://diamondops.gg">DiamondOps</a> ·
  <a href="https://faketoms.com">FakeToms</a> ·
  <a href="https://retroghostlabs.com">RetroGhost Labs</a> ·
  <a href="https://www.youtube.com/@RetroGhostLabs">YouTube</a> ·
  <a href="#-connect">All links ↓</a>
</p>

---

## 🛠️ Shaun's Dev Corner — start here for dev stuff

**[retroghostlabs.com/dev-corner](https://retroghostlabs.com/dev-corner/)** is my developer blog: how I build software with AI agents, the tools I make for myself, and what I'm learning along the way.

- **Latest:** [How I Stopped Babysitting My AI Agents](https://retroghostlabs.com/dev-corner/flight-deck/). It covers less time watching agents, more time on real work, and Flight Deck, the tool that came out of it.

> Looking for Diamond Dynasty strategy instead? That lives on the [DiamondOps blog](https://diamondops.gg/blog).

---

## ⚾ DiamondOps — market intelligence for MLB The Show Diamond Dynasty

One shared platform, three App Store apps, a web app, a blog and an automated video pipeline — all built and run solo.

| Product | What it does | Platform | Status |
|---|---|---|---|
| **[DiamondOps Web](https://diamondops.gg)** | Live market, flips, trending, OpScore rankings, Diamond Radar, portfolio tracking | Next.js · Vercel | 🟢 Live — v1.31 |
| **[DiamondOps](https://apps.apple.com/us/app/diamondops/id6759801146)** | Diamond Radar, card browser, Flip Finder, collection value — in your pocket | iOS (SwiftUI) | 🟢 App Store — v1.2 |
| **[PitchGuessr](https://apps.apple.com/us/app/pitchguessr/id6758683308)** | Tracks an opponent's pitching patterns and predicts where the next one goes | iOS (SwiftUI) | 🟢 App Store — v1.4 |
| **[PitchTunnels](https://apps.apple.com/us/app/pitchtunnels/id6759800610)** | Pitch-tunneling recommendations by count, situation and handedness | iOS (SwiftUI) | 🟢 App Store — v1.4 |
| **DiamondOps Core** | API, auth (Apple / Google), entitlements, nightly card sync, OpScore engine, analytics | TypeScript · MongoDB · Redis · Docker | 🟢 Production — v1.39 |
| **DiamondOps Content** | Generates Shorts and YouTube videos straight from live API data | Remotion · ElevenLabs | 🛠️ Active |
| **DiamondOps System** | One design-token source that stamps brand updates into every app via auto-PRs | tokens → generator → `repository_dispatch` | 🛠️ Active |

📝 **[The DiamondOps blog](https://diamondops.gg/blog)** — 30+ posts on market timing, OpScore, Diamond Radar report cards and post-mortems where I grade my own predictions in public.

---

## 🧪 Other things coming out of the lab

| Project | What it is | Status |
|---|---|---|
| **[FakeToms](https://faketoms.com)** | Parody "spot the imposter" site with automated daily drops | 🟢 Live |
| **Fake Tom's Fight Club** | 3-on-3 card-binder fighting game (SpriteKit) | 🧪 TestFlight |
| **[The ONs Are On It](https://theons.tv)** | Fan site for a lost 1986 workplace sitcom that never existed | 🟢 Live |
| **[RetroGhost Arcade](https://retroghostarcade.com)** | Web arcade and game incubator — the games people keep playing graduate to iOS | 🛠️ In development |
| **[RetroGhost Labs](https://retroghostlabs.com)** | The company site — apps, guides and blog | 🟢 Live |

---

## 🤖 How one person ships all of this

- **Claude Code + Codex** do the heavy lifting; I direct, review and ship. A second model reviews the code before it merges.
- **Beads** (on a central Dolt server) is the task tracker — every piece of work is a bead with real dependency edges, not a TODO list.
- **Flight Deck** — a Go TUI I built that turns each ready task into its own git worktree with its own Claude Code session, so several run in parallel. ([Read the write-up →](https://retroghostlabs.com/dev-corner/flight-deck/))
- **Design tokens as a stamp** — change the brand once, every consuming repo gets a PR.
- **Enforcement tests over written lessons** — if a mistake happens twice, it becomes a test.

## 📊 GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://retroghostlabs.com/api/github-stats?theme=dark" />
    <img src="https://retroghostlabs.com/api/github-stats?theme=light" alt="Shaun's GitHub stats: contributions, pull requests, repos and top languages, including private repos" />
  </picture>
</p>

<sub>Almost all of my code lives in private repos, so these numbers are totals only.</sub>

## 🏠 Self-hosted homelab

A Docker stack I run myself for databases, automation and monitoring: Postgres, MongoDB, Redis, n8n workflows, Grafana / InfluxDB dashboards, Open WebUI and ComfyUI for local AI, all behind Cloudflare.

---

## 💻 Tech stack

**iOS** — Swift · SwiftUI · SpriteKit · StoreKit 2 · iOS 17+

**Web** — Next.js · React · TypeScript · Tailwind · shadcn/ui · TanStack Query/Table · Astro

**Backend** — Node.js · TypeScript · MongoDB · Redis · Docker · Caddy

**Ops** — Vercel · Cloudflare · Sentry · GitHub Actions · Doppler · n8n · Grafana

**Content** — Remotion · ElevenLabs · Final Cut Pro · Ecamm

**AI workflow** — Claude Code · Codex · Beads/Dolt · Obsidian

---

## 🔗 Connect

**✍️ Blogs**
- 🛠️ **Dev Corner** (dev and AI workflow): [retroghostlabs.com/dev-corner](https://retroghostlabs.com/dev-corner/)
- ⚾ **DiamondOps blog** (Diamond Dynasty market and strategy): [diamondops.gg/blog](https://diamondops.gg/blog)

**🌐 Websites**
- ⚾ **DiamondOps**: [diamondops.gg](https://diamondops.gg)
- 🕵️ **FakeToms**: [faketoms.com](https://faketoms.com)
- 👻 **RetroGhost Labs**: [retroghostlabs.com](https://retroghostlabs.com)
- 🕹️ **RetroGhost Arcade**: [retroghostarcade.com](https://retroghostarcade.com)
- 📺 **The ONs Are On It**: [theons.tv](https://theons.tv)

**📱 iOS apps (App Store)**
- 💎 **DiamondOps**: [apps.apple.com/us/app/diamondops/id6759801146](https://apps.apple.com/us/app/diamondops/id6759801146)
- 🎯 **PitchGuessr**: [apps.apple.com/us/app/pitchguessr/id6758683308](https://apps.apple.com/us/app/pitchguessr/id6758683308)
- 🌀 **PitchTunnels**: [apps.apple.com/us/app/pitchtunnels/id6759800610](https://apps.apple.com/us/app/pitchtunnels/id6759800610)

**🎥 Video and social**
- ▶️ **RetroGhost Labs on YouTube** (dev logs, AI workflow, shipping solo): [@RetroGhostLabs](https://www.youtube.com/@RetroGhostLabs)
- ▶️ **DiamondOps on YouTube** (market analysis and app demos): [@diamondops-rgl](https://www.youtube.com/@diamondops-rgl)
- 📸 **Instagram**: [@diamondopsrgl](https://www.instagram.com/diamondopsrgl/)
- 🎵 **TikTok**: [@diamondops_rgl](https://www.tiktok.com/@diamondops_rgl)

**📧 Email**: [shaun@retroghostlabs.com](mailto:shaun@retroghostlabs.com)

---

## 🧩 How I work

<p align="center">
  <img src="https://content.diamondops.gg/avatars/owner/stylized-01-graphic.png" width="180" alt="Illustrated portrait of Shaun on a blue and orange striped background" />
</p>

**Ship it** — working code over perfect code. Prototype, launch, then polish.

**Own the stack** — self-host what matters. Control the data, the infra and the workflow.

**Grade yourself in public** — predictions get report cards, misses get post-mortems.

**Write it down** — Markdown-first and version-controlled, so the AI tools get better context too.

## 🎸 Off the clock

Writing music and sculpting tone chains on guitar and bass, tinkering with smart-home setups, and a lifelong soft spot for retro tech — Atari 2600 to Macintosh Classic.

---

<p align="center">
  Got a project idea, a collab, or want to talk iOS, Diamond Dynasty or AI workflows?<br/>
  📧 <a href="mailto:shaun@retroghostlabs.com">shaun@retroghostlabs.com</a>
</p>
