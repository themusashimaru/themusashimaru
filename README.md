# Matt M.

Full-stack developer in New York. I build production systems that move money and run operations: payments, invoicing, POS/CRM, billing SaaS, and AI products.

The domain changes; the shape doesn't. Auth, payments, data integrity, and operations tooling look the same whether the business sells jewelry, software, or services. Mine have been battle-tested in luxury retail, where a mistake costs real money in front of a real customer.

## Shipped and running in production

- **Retail operations platform** for a fine jeweler in Connecticut: POS with invoicing and deposits, consignment tracking, inventory, thermal label printing, and Stripe payments. Non-technical staff run the entire store on it.
- **Multi-store CRM/POS platform** for a luxury retail brand's US flagship operations: sales tracking, commissions, returns netting, reconciliation, repairs workflow, and reporting. Next.js, Supabase with row-level security, Vercel.
- **A live subscription SaaS** with Stripe billing, AI chat tools, and content moderation. Founded and operate it solo: product, infrastructure, and billing end to end.

## Stack

Next.js (App Router) · TypeScript · React · Supabase / Postgres · Stripe · Vercel · Python · Anthropic + OpenAI APIs

## Security audits

Through [Maru Security](https://marusystems.dev) I run independent application-security audits: OWASP-aligned, 136-control methodology across 16 testing phases, with CVSS-scored reports, remediation guidance, and retest verification. Black-box, grey-box, or source review.

It also shows in how I build: row-level security enforced at the database, verified webhooks, least-privilege by default. Code I ship has already been looked at the way an attacker would.

## Open source

| Repo | What it is |
|---|---|
| [ledgerkit](https://github.com/themusashimaru/ledgerkit) | Double-entry ledger engine in strict TypeScript: balanced-by-construction, bigint money, invariant-fuzzed |
| [nextjs-stripe-webhook-kit](https://github.com/themusashimaru/nextjs-stripe-webhook-kit) | Stripe webhooks done properly: raw-body verification, race-safe idempotency, typed routing |
| [supabase-rls-patterns](https://github.com/themusashimaru/supabase-rls-patterns) | Row Level Security that survives production, plus a five-query pre-deploy audit |
| [vibe-coders-security-checklist](https://github.com/themusashimaru/vibe-coders-security-checklist) | A no-shame security checklist for AI-assisted apps, with a runnable scanner |
| [csv-reconcile](https://github.com/themusashimaru/csv-reconcile) | Transaction reconciliation in Python: Decimal money, return netting, hostile-CSV parsing |
| [env-doctor](https://github.com/themusashimaru/env-doctor) | Does your code's environment actually exist? One command answers it |

## Working with me

I take white-label and overflow work for agencies (spec-to-ship features or whole builds, US Eastern hours) and direct projects for businesses that need payments, operations tooling, or AI features. Production work lives in private client repos; happy to do a code walkthrough on a call or start with a paid test task.
