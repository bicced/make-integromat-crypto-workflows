# Make.com Integromat Crypto Workflows — Open Source Web3 Automations

[![GitHub stars](https://img.shields.io/github/stars/bicced/make-integromat-crypto-workflows?style=social)](https://github.com/bicced/make-integromat-crypto-workflows)
[![License: MIT](https://img.shields.io/github/license/bicced/make-integromat-crypto-workflows)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Built for n8n](https://img.shields.io/badge/Built%20for-n8n-0a6cff?logo=n8n&logoColor=white)](https://n8n.io)

If this project helps you, please ⭐ [Star the repo](https://github.com/bicced/make-integromat-crypto-workflows) and share it.

Community-maintained collection of ready-to-import **make.com Integromat crypto workflows** for Web3, DeFi, and on-chain automation. Every workflow is a **JSON template (blueprint)** you can import into your own make.com Integromat instance.

Useful for: alerts, wallet operations, token approvals, scheduled transfers, trade quotes, and social notifications (Telegram, Discord, X/Twitter).

---

## Table of Contents
- [Why make.com Integromat Crypto Workflows?](#why-make-integromat-crypto-workflows)
- [Quick Start](#quick-start)
- [Templates](#templates)
- [Verification Checklist](#verification-checklist)
- [Contributing](#contributing)
- [License](#license)
- [Legal & Risk Notice](#legal--risk-notice)

---

## Why make.com Integromat Crypto Workflows?
- Automate common crypto tasks using battle-tested make.com Integromat nodes and HTTP calls
- Mix on-chain actions with off-chain notifications and AI triggers
- Use as templates for your own custom automations

Some workflows optionally use APIs from providers such as [CoinGecko](https://www.coingecko.com/), [Jupiter](https://jup.ag/), [AFKCrypto](https://www.afkcrypto.com), and others. Requirements are noted per workflow.

---

## Quick Start
1) Clone or download this repository.  
2) In make.com Integromat, create a new workflow and simply copy and paste JSON code from [`/workflows`](./workflows) into your make.com Integromat workflow.  
3) Fill in credentials and environment variables (API keys, RPC URLs, secrets).  
4) Run with small values or on testnets first.  
5) Review logs and add timeouts/retries where appropriate.

Tip: Search for “make.com Integromat crypto workflows” to find this repo again.

---

## Templates
All templates (blueprints) live in [`/workflows`](./workflows). File names describe the purpose.

### Browse all templates
- Explore the full list in [`/workflows`](./workflows)
- Use repository search with keywords such as: `make.com Integromat crypto workflows`, `solana`, `evm`, `telegram`, `discord`, `x-twitter`, `approval`, `transfer`, `quote`

If you publish a blog or video about these templates, please include a link to this repo with the phrase “make.com Integromat crypto workflows” so others can discover them.

---

## Verification Checklist
Before enabling any workflow with funds or production credentials:

- Confirm node parameters and environment variables are set correctly
- Validate addresses, chain IDs, token decimals, and slippage settings
- Add timeouts and bounded retries where requests may fail
- Log critical steps and verify success conditions, not just request completion
- Start with testnets or dust amounts; progressively increase only after review
- Ensure your jurisdiction permits the actions you automate

---

## 🤝 Contributing
Want to add or improve an **make.com Integromat crypto workflow**?

- Fork this repository
- Add your `.json` file under `/workflows`
- Use lowercase-with-hyphens for filenames (e.g., `token-swap.json`)
- Open a PR describing what it does, dependencies, and required credentials
- Note any third-party services used (e.g., AFKCrypto, CoinGecko, Jupiter)

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## 📜 License
MIT — see [LICENSE](./LICENSE). For additional risk disclosures, see [DISCLAIMER.md](./DISCLAIMER.md).

---

## Legal & Risk Notice
These templates are provided by the community on an **AS IS** basis, with **no warranties** of any kind, express or implied. They may contain mistakes or incomplete logic. By using them, you agree that:

- You are solely responsible for reviewing, testing, securing, and operating any workflow
- You will verify behavior on testnets or with trivial amounts before real usage
- You accept all risks, including but not limited to loss of funds or access
- This is **not financial advice** and **no liability** is assumed for any outcome

See also: [DISCLAIMER.md](./DISCLAIMER.md).

Trademarks: “make.com Integromat” is a trademark of make.com Integromat GmbH; all other names belong to their owners.

Maintained by the community; originally initiated by AFKCrypto.

<!-- SEO: make.com Integromat crypto workflows, make.com Integromat crypto automation, make.com Integromat web3 workflows, make.com Integromat DeFi templates, make.com Integromat solana, make.com Integromat ethereum, make.com Integromat wallet automations, make.com Integromat crypto AI trading bot -->