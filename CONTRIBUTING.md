# Contributing

This repository is the **public showcase page for [Planoda](https://planoda.com/?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=intro)** — the AI-native work platform. It holds the landing page and its screenshots. **It is not the Planoda source code**, which is closed and hosted.

There is no application to build here, so pull requests adding features to Planoda cannot be accepted through this repo.

## Where to take things

| I want to…                           | Go here                                                                                                                                                                                                                                                             |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Report a bug **in Planoda**          | [planoda.com/contact](https://planoda.com/contact?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=bug)                                                                                                                             |
| Request a **feature** in Planoda     | [planoda.com/roadmap](https://planoda.com/roadmap?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=roadmap)                                                                                                                         |
| Report a **security issue**          | [planoda.com/security](https://planoda.com/security?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=security) — please do **not** open a public issue                                                                              |
| Read the **docs** or use the **API** | [planoda.com/docs](https://planoda.com/docs?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=docs) · [API](https://planoda.com/developers/api?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=api) |
| Fix a **typo or broken link here**   | Open a pull request against this repository — those are very welcome.                                                                                                                                                                                               |

## Working on this repository

The only tooling here is Prettier, which keeps the Markdown and JSON formatted.

### Prerequisites

- **Node.js** v24 or higher (`node --version`) — the pinned version lives in `.nvmrc`
- **pnpm** v10 or higher (`pnpm --version`)

### Setup

```bash
git clone https://github.com/idimetrix/idimetrix.git
cd idimetrix
pnpm install
```

### Before opening a pull request

```bash
pnpm run format   # prettier --write .
```

Keep the README's factual claims aligned with what [planoda.com](https://planoda.com/?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=claims) actually states — no invented metrics, customer counts, testimonials, or competitor feature comparisons.

## Code of conduct

By participating you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md).

## Contact

- **Planoda support**: [planoda.com/contact](https://planoda.com/contact?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=contact)
- **Docs**: [planoda.com/docs](https://planoda.com/docs?utm_source=github&utm_medium=contributing&utm_campaign=founder_promo&utm_content=contact_docs)
