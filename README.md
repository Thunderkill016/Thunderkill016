<div align="center">

# MoneyFlow

**Personal finance for Vietnamese users — a ledger you actually own.**

[![Repo](https://img.shields.io/badge/GitHub-moneyflow-181717?style=for-the-badge&logo=github)](https://github.com/Thunderkill016/moneyflow)
[![Live](https://img.shields.io/badge/Live-mfvn.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://mfvn.vercel.app)

![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Postgres%20%2B%20RLS-3ECF8E?logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-deployed-000?logo=vercel)

</div>

---

Hi, I'm **Hoang** — a solo vibe-coder from Vietnam. I ship real products by directing coding agents: I design the system, set the invariants, review the diffs — agents write the code. Every repo carries an `AGENTS.md` so the next session picks up cold.

Current build: **MoneyFlow**.

The idea: most finance apps for Vietnamese users are either too complex, too foreign, or lock your data inside their platform. MoneyFlow is the opposite — a boringly trustworthy ledger where every đồng is traceable, exportable, and yours.

### What it does

- **Multiple accounts** — cash, bank, e-wallet, credit, savings
- **Income / expense / internal transfers** with soft-delete & recovery
- **Budgets, recurring commitments & savings goals**
- **Weekly · monthly · yearly reports**
- **CSV import/export** + full versioned backup
- **Demo mode** — try instantly, no sign-up
- **Authenticated mode** — Supabase Auth, tenant-isolated by Postgres RLS
- Light/dark, responsive

### How it's built

| Principle | Concretely |
|---|---|
| Money is exact | VND stored as integer đồng — never floating point |
| Transfers aren't income | Equal/opposite movements, excluded from reports |
| No silent fallbacks | Missing data is shown missing, never guessed |
| Your data is yours | Row-level security, full export & restore, no lock-in |
| Demo ≠ real | Two explicit runtime modes, never silently mixed |

### Stack

`Next.js 16` · `TypeScript` · `Supabase (Auth + Postgres RLS)` · `Tailwind` · `Vercel`

---

<div align="center">
<sub>Solo + agents · one focused product at a time · everything else is intentionally kept private.</sub>
</div>
