<p align="center">
  <img src="appicon.png" alt="Higher Standard Games" width="128">
</p>

<h1 align="center">Higher Standard Games</h1>

<p align="center">
  Fast arena shooters for the browser, built on our own open engine.<br>
  <a href="https://higherstandardgames.com">higherstandardgames.com</a> •
  <a href="https://washoi.net">Play Washoi</a>
</p>

---

### [Washiki Washoi](https://washoi.net)

An arena FPS that runs in the browser: air control, strafe jumping and
server-authoritative combat. Duel, Amphi, FFA and Search & Destroy, with lobby
matchmaking, ratings, bots and match demos. No install: open
[washoi.net](https://washoi.net) and play.

Source: [**wash-fps**](https://github.com/Higher-Standard-Games/wash-fps)

### [SHAG Engine](https://github.com/Higher-Standard-Games/shag)

*Scary Hacks And Glue.* The TypeScript engine under Washoi, built on
Babylon.js. It loads idTech3 BSP maps, shaders and PK3 packages, and it runs
headless, so tests, bots and AI agents can drive the full game without a GPU.
One codebase targets web, desktop (Electron) and mobile (Capacitor).

### Repositories

| Repository | What it is |
| --- | --- |
| [shag](https://github.com/Higher-Standard-Games/shag) | The engine, and the home of the build: clone this one |
| [wash-fps](https://github.com/Higher-Standard-Games/wash-fps) | Washoi itself: gameplay, server, bots and the game manual (a submodule of `shag`) |
| [shagger](https://github.com/Higher-Standard-Games/shagger) | Experimental: SHAG features ported to Rust |
| [wash-fps-rust](https://github.com/Higher-Standard-Games/wash-fps-rust) | Experimental: a Rust Washoi client |

All open source under the MIT licence.

```bash
git clone --recursive https://github.com/Higher-Standard-Games/shag.git
cd shag && npm install
npm --prefix src/games/fps run dev
```
