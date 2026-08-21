# Apartment Agent

Shared workspace for finding and negotiating buy-to-rent apartments in Cluj-Napoca.

## Workflow

1. Codex searches active listings.
2. Listings are evaluated against `SEARCH_CRITERIA.md`.
3. Raw candidates are written to `listings/listings.json`.
4. Strong candidates go to `deals/active.md`.
5. Rejected listings go to `deals/rejected.md`.
6. Seller conversations are stored under `negotiations/`.
7. Negotiated opportunities go to `deals/negotiated.md`.
8. The current best opportunity is summarized in `reports/latest.md`.

## Important

The agent may negotiate non-binding prices but must never commit to a purchase, pay money, sign documents, or arrange a viewing without explicit user approval.
