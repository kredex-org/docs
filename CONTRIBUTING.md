# Contributing to Kredex Docs

Thank you for helping make Kredex easier to understand! This is the **friendliest repo to start in**. For the general flow (fork → branch → PR), see the [org-wide Contributing Guide](https://github.com/kredex-org/.github/blob/main/CONTRIBUTING.md).

## Quick edit (no setup)

Spot a typo? You can fix it right in your browser:

1. Open the file in `pages/` on GitHub.
2. Click the ✏️ pencil icon. GitHub will fork the repo for you.
3. Make your edit, then choose **Propose changes** and open the pull request.

## Local setup (for bigger changes)

```bash
git clone https://github.com/<you>/docs.git
cd docs
git remote add upstream https://github.com/kredex-org/docs.git
npm install
npm run dev     # http://localhost:3000
```

Before opening a PR, make sure `npm run build` succeeds.

## Writing guide

- **Write for beginners.** Define jargon on first use (e.g. "Soroban, Stellar's smart-contract platform").
- **Be concise.** Short sentences, active voice, one idea per paragraph.
- **Show, don't just tell.** Prefer a working example, command or screenshot.
- **Use headings** (`##`, `###`) so the right-hand table of contents works.
- **Code blocks** must declare a language: ` ```bash `, ` ```ts `, ` ```rust `.
- **Commands** should be copy-pasteable, with placeholders in `<angle-brackets>`.
- **Links:** use relative links for internal pages (`/setup`), descriptive link text (not "click here").
- **Images:** put them in `public/` and add alt text.
- **Never include** secret keys, real personal data or real wallet seeds. Use Testnet addresses only.
- **Keep it accurate.** If you're documenting behavior, verify it in the [product](https://github.com/kredex-org/product) or [contracts](https://github.com/kredex-org/contracts) source.

## Adding a page

1. Create `pages/<slug>.mdx`.
2. Add it to `pages/_meta.ts` to control sidebar order and title.
3. Run `npm run dev` and check it renders properly, including on a narrow (mobile) window.

## Commit & PR

- Use [Conventional Commits](https://www.conventionalcommits.org/): `docs: add troubleshooting for Freighter`.
- One focused change per PR.
- Fill in the PR template. For visual changes, attach a screenshot.

## Ideas for first contributions

- 🐛 Fix typos, broken links or outdated commands
- 📖 Add a glossary page
- 🧭 Write a "Troubleshooting" page
- 🖼️ Add screenshots to the usage guide
- 🌍 Translate a page
- 🔍 Improve contract documentation (compare with the [contracts reference](https://github.com/kredex-org/contracts/blob/main/docs/CONTRACTS.md))

## Questions?

Ask in [Discussions](https://github.com/orgs/kredex-org/discussions) or on [@kredexweb3](https://x.com/kredexweb3). We're happy to help.
