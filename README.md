# Daniel Nichiata

Full-stack developer in São Paulo, Brazil. I build and run [CiteMe](https://citeme.app), an academic citation generator and reference checker, on my own: product, code, infrastructure and billing.

Most of my commits go to CiteMe's private repository. The parts I could extract are open source and listed below.

## CiteMe

A live product used by students and researchers to find a source, format it and check that the references in a paper exist.

- **Search** across eight scholarly databases (OpenAlex, Semantic Scholar, PubMed, Europe PMC, arXiv, HAL, BASE, BDTD), with circuit breakers and schema validation at every external boundary
- **Formatting** in 60 curated CSL styles, plus the 10,000+ styles of the CSL repository
- **Surfaces**: web app, browser extension, Obsidian plugin, public REST API and MCP endpoint
- **Five locales**: English, Portuguese, Spanish, French, German

Stack: TypeScript, Next.js (App Router), React, Tailwind, Supabase (Postgres with row-level security), Cloudflare Workers and Durable Objects, Rust compiled to WebAssembly, Paddle for billing, Vitest and Playwright for tests.

## Open source

| Project | What it does | Stack |
|---|---|---|
| [abnt-citation](https://github.com/danielnichiata96/abnt-citation) | Formats citations to the Brazilian ABNT standards (NBR 10520:2023, NBR 6023:2025). Published on [npm](https://www.npmjs.com/package/abnt-citation) and listed in GitHub's *Made in Brazil* collection. | TypeScript |
| [citeme-engine](https://github.com/danielnichiata96/citeme-engine) | Reads BibTeX, RIS, MEDLINE and CSL-JSON, writes BibTeX, BibLaTeX and RIS, and renders any CSL style. Runs in the browser as a Wasm module. Built on Hayagriva. | Rust, WebAssembly |
| [obsidian-citeme](https://github.com/danielnichiata96/obsidian-citeme) | Obsidian plugin to search papers, insert formatted citations and check a note's references. Listed in the official community plugin directory. | TypeScript |

## Contact

I'm open to full-stack roles.

- Email: [danielnichiata@citeme.app](mailto:danielnichiata@citeme.app)
- Site: [citeme.app](https://citeme.app)
