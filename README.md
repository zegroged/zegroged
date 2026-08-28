## Hi, I'm Yılmaz Mert

Self-taught software engineer from Turkey. I build and ship full products end to end — backend,
frontend, mobile, infrastructure — and I run them in production on my own server.

Most of what you'll find here are **shut-down ventures published as reference implementations**.
None of them found a market; that part I got wrong. The engineering is real: production systems
with paying pilot customers, field-debugged mobile apps, and infrastructure I operated myself.

### Open source

| Contribution | What it is |
|---|---|
| [tauri-apps/tauri#15923](https://github.com/tauri-apps/tauri/pull/15923) | A UTF-8 BOM made `tauri.conf.json` fail with an opaque `expected value at line 1 column 1` on a file that looks valid in an editor. Unreported. I traced it to the exact line in `tauri-utils`, fixed it at the shared read boundary so JSON, JSON5 and TOML are all covered, and checked the tests fail without the fix rather than passing vacuously. Approved by a maintainer. |
| [vacuous-tests-mcp](https://github.com/zegroged/vacuous-tests-mcp) | An MCP server that finds tests which pass no matter what the code does — assertions true by construction, tests with no assertion, empty bodies. I wrote it after finding that exact failure class in my own test suite. Python, Rust and TypeScript. |

### What I work on

**Systems & security** — Rust, cryptography, anonymity networks. I'm building a serverless,
metadata-resistant P2P messenger over Tor (X3DH + Double Ratchet, v3 onion hosting).

**AI engineering** — LLM agent harnesses (tool loops, approval gates, loop detection) and
retrieval systems that go past naive cosine similarity: hybrid BM25 + embeddings with
cross-encoder reranking and graceful fallback.

**Full-stack products** — Next.js, TypeScript, Prisma, PostgreSQL, Docker. Multi-tenant SaaS,
marketplaces, payment integrations, mobile clients.

### Selected work

| Project | What it is |
|---|---|
| [hali-platform](https://github.com/zegroged/hali-platform) | Carpet-cleaning marketplace. Ran in production with a pilot customer; two mobile apps. Includes a written post-mortem of a silent two-hour location-tracking outage caused by OEM battery management. |
| [jarvis](https://github.com/zegroged/jarvis) | Local LLM agent — 18 tools, loop detection, approval gates — plus a hybrid reranking RAG pipeline and a hand-written Turkish security corpus (~254k words). |
| [dijital-kafe](https://github.com/zegroged/dijital-kafe) | Multi-tenant QR menu + POS SaaS. Wildcard subdomains, 7 roles, payments, commission and withholding accounting. |
| [webrtc-matchmaking](https://github.com/zegroged/webrtc-matchmaking) | Real-time matchmaking engine and WebRTC signaling. Weighted scoring with progressive threshold relaxation. |

### Currently

Contributing to open source and looking for remote engineering work — security, AI
infrastructure, or backend. Improving my English alongside it.

📍 Turkey (UTC+3, overlaps European hours) · 🌐 [trgenci.com](https://trgenci.com)
