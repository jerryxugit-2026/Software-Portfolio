# Software Portfolio · Ziyang Xu

Five pieces of software, each made for someone — a study tool for myself and my
buddies, a browser assistant for my mum, models that check each other, safe hands
for an AI agent's daily work, and tools that learned to live where people already
are — even inside WeChat.

**▶ Live site: [jerryxugit-2026.github.io/Software-Portfolio](https://jerryxugit-2026.github.io/Software-Portfolio/)**

## The five chapters

| # | Chapter | What it is | Source |
|---|---|---|---|
| 01 | Made for myself and my buddies | **Ziyang Vocab Master** — your own PDF becomes your own study deck; browser-only, free, registered software copyright | [Build-Vocab-Master](https://github.com/jerryxugit-2026/Build-Vocab-Master) |
| 02 | Made for Mum | **DSH Browser Companion** — the page you are reading, handed to a local AI agent; runs locally and asks before it acts | [dsh-web-companion](https://github.com/jerryxugit-2026/dsh-web-companion) |
| 03 | Made for truth | **PiMoa** — a blind review panel of models in a read-only sandbox; **JEV** — a judge that knows how sure it is (Go MCP server) | [Build-Agent-Tools-PiMoa](https://github.com/jerryxugit-2026/Build-Agent-Tools-PiMoa) |
| 04 | Made for the daily job | **office-gateway · browser-gateway · Sheet Shadow** — five engines and 145 site adapters behind one door; Sheet Shadow is the agent-safe hand for Excel | Sheet Shadow: [Build-Agent-Tools-PiMoa/tree/main/sheet_shadow](https://github.com/jerryxugit-2026/Build-Agent-Tools-PiMoa/tree/main/sheet_shadow) (MIT). The two gateways are not public yet — they bundle third-party engines whose licences are still being checked. |
| 05 | Made for everyone and everywhere | the tools' five homes — shared gateway → rented cloud → torn-out public entrance → Cloudflare Worker → WeChat + Muse ("forward it and it is handled; tap favourites and it is filed") | [Build-MCP-Gateway](https://github.com/jerryxugit-2026/Build-MCP-Gateway) (MIT) — the gateway and its Cloudflare Worker. The WeChat bridge is built on a third-party open-source bridge; the bridge itself is not public yet. |

Every account, key and password in the published sources is a mock. Real
credentials never leave the machine.

---

This repository hosts the site source (`index.html` + `assets/`), served with
GitHub Pages.
