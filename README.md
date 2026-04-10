# Spencer Lee

Senior engineer at [Waypoint Network](https://waypointnetwork.ai). I build systems that sit between messy real-world data and trustworthy automated action — agent orchestration, verifier-driven reliability loops, structured intelligence pipelines, and the product architectures underneath them.

Most of my current work is private. The pinned repos below are side projects and earlier prototypes. For samples of the production work, see the gists below.

## What I'm building at Waypoint

- **Agent orchestration platform** — hierarchical commander pattern with queue-based delegation, write serialization, delegated authorization, and audit trails
- **MCP verification server** — static analysis, sandboxed execution, property-based fuzzing, and repair loops for coding agents ([court-jester-mcp](https://github.com/slee1996/court-jester-mcp), the pinned Rust repo, is this)
- **Structured intelligence pipelines** — multi-stage extraction over public records and web data, entity matching, confidence scoring, and provenance tracking
- **Multi-tenant travel platform** — bookings, search normalization, scraper orchestration, and graph-synchronized authorization

## Code samples from private work

These gists are extracted from production Waypoint systems:

- [**Sandboxed execution with process-group memory enforcement**](https://gist.github.com/slee1996/52e9d0e33519a297d00b26db99ebc7ac) — Rust, cross-platform OS primitives, async memory monitoring
- [**Queue-based write serialization**](https://gist.github.com/slee1996/74b36f3fc192461e05d774c9979e1a2d) — JS, promise-chain lane ordering, FNV-1a idempotency keys, causal status progression
- [**Zanzibar-inspired authorization engine**](https://gist.github.com/slee1996/d13a2c6a962d33bb66043878e9abc2d2) — TypeScript, recursive relation traversal with cycle detection and computed usersets
- [**Name normalization and fuzzy matching**](https://gist.github.com/slee1996/c0cdfd2a254bcd785410a40f9571220a) — Python, multi-variant key generation, Unicode transliteration, Levenshtein distance
- [**SVG/PDF generation pipeline**](https://gist.github.com/slee1996/1040f86cb7832c66c5bd1359b4e1d499) — TypeScript, binary image parsing, Chart.js in headless Playwright, SVG injection

## Stack

TypeScript, Python, Rust. Cloudflare Workers, Postgres, MCP, Playwright.

End-to-end ownership in small, fast-moving environments.
