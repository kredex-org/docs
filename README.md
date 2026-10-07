<h1 align="center">Kredex Docs</h1>

<p align="center"><em>The official documentation for Kredex: P2P lending with on-chain reputation on Stellar.</em></p>

<p align="center">
  <a href="https://kredex-docs.vercel.app"><img src="https://img.shields.io/badge/Read-the%20Docs-blue" alt="Docs" /></a>
  <img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT" />
  <img src="https://img.shields.io/badge/Nextra-3-black" alt="Nextra" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome" />
  <img src="https://img.shields.io/badge/good%20first%20issues-yes-7057ff" alt="Good first issues" />
</p>

<p align="center">
  <a href="https://kredex-docs.vercel.app">Docs site</a> ·
  <a href="https://kredex.vercel.app">Live App</a> ·
  <a href="https://github.com/kredex-org/product">Product</a> ·
  <a href="https://github.com/kredex-org/contracts">Contracts</a> ·
  <a href="https://github.com/orgs/kredex-org/discussions">Discussions</a> ·
  <a href="https://x.com/kredexweb3">X</a>
</p>

---

## 🌱 The best place to make your first contribution

You don't need to know blockchain, Rust or React to improve documentation. If you can read and write, you can help. Fixing a typo or clarifying one confusing paragraph is a **real, valued contribution**, and we'll help you through your first pull request.

## About

This repository is the source of the [Kredex documentation site](https://kredex-docs.vercel.app), built with [Nextra](https://nextra.site) (Next.js + MDX). It covers setup, architecture, smart contracts, usage guides, and the community feedback that shaped the product.

## Ecosystem

| Repo | Description |
| :-- | :-- |
| [product](https://github.com/kredex-org/product) | Web app (Next.js) |
| [contracts](https://github.com/kredex-org/contracts) | Soroban smart contracts |
| **docs** (you are here) | Documentation site |
| [.github](https://github.com/kredex-org/.github) | Org policies and templates |

## Quick start

**Prerequisites:** [Node.js](https://nodejs.org) 18+ and npm.

```bash
git clone https://github.com/kredex-org/docs.git
cd docs
npm install
npm run dev
```

Open <http://localhost:3000>. Pages hot-reload as you edit.

| Command | What it does |
| :-- | :-- |
| `npm run dev` | Start the dev server |
| `npm run build` | Production build (run before opening a PR) |
| `npm run start` | Serve the production build |

## Project structure

```text
docs/
├─ pages/
│  ├─ index.mdx               # Home
│  ├─ setup.mdx               # Setup guide
│  ├─ usage.mdx               # Using the platform
│  ├─ implementation.mdx      # Architecture and contracts
│  ├─ feedback-evolution.mdx  # Community feedback → product changes
│  ├─ _meta.ts                # Sidebar order and titles
│  └─ _app.jsx
├─ components/                # Reusable React components used in MDX
├─ theme.config.tsx           # Nextra theme (logo, footer, links)
└─ next.config.js
```

To add a page: create `pages/my-page.mdx`, then register it in `pages/_meta.ts`.

## How to contribute

1. Read **[CONTRIBUTING.md](CONTRIBUTING.md)** for the writing guide and PR steps.
2. Pick a [`good first issue`](https://github.com/kredex-org/docs/labels/good%20first%20issue), or fix anything you noticed while reading.
3. Open a PR. We usually reply within a few days.

Ideas for first PRs: fix typos and grammar, add screenshots, write a "Troubleshooting" section, improve explanations for beginners, add a glossary (SEP-12, Soroban, escrow, soulbound NFT), translate pages.

## Community & support

- 💬 [Discussions](https://github.com/orgs/kredex-org/discussions)
- 🐦 [@kredexweb3](https://x.com/kredexweb3)
- 🔐 Security: see the [Security Policy](https://github.com/kredex-org/.github/blob/main/SECURITY.md)
- 📜 [Code of Conduct](https://github.com/kredex-org/.github/blob/main/CODE_OF_CONDUCT.md)

## License

[MIT](LICENSE)
