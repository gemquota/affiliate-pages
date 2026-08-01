# Affiliate Pages

Crypto referral & affiliate landing pages, deployed on GitHub Pages:
https://gemquota.github.io/affiliate-pages/

- `index.html` — referral desk hub (links to both pages)
- `coinspot-affiliate.html` — CoinSpot affiliate (30% → 15% → 5% over 3 years)
- `coinspot-referral.html` — CoinSpot referral share page

## Short links (short.io) — BLOCKED on DNS, do not publish yet

Created but NOT live:

| Short link | Destination |
|---|---|
| https://slap.red/4ral | https://www.coinspot.com.au?affiliate=KV925 |
| https://slap.red/w3a8 | https://www.coinspot.com.au/join/REFQMKVRD |
| https://slap.red/7lao | https://gemquota.github.io/affiliate-pages/coinspot-affiliate.html |
| https://slap.red/lt9v | https://gemquota.github.io/affiliate-pages/coinspot-referral.html |

Problem: `slap.red` returns NXDOMAIN at the .red TLD (checked via dns.google:
A/AAAA/NS/SOA all NXDOMAIN, 2026-08-01). The domain registration appears to
have lapsed; short.io's SSL cert for it also expired 2026-07-06. Links will
work only after the domain is renewed and pointed at short.io's DNS records.

Fix checklist (user):
1. Renew/restore `slap.red` at the .red registrar (or wherever it was bought).
2. In short.io dashboard → Domains → slap.red → copy required DNS records.
3. Add them at the DNS provider (A/ALIAS/CNAME to short.io).
4. Confirm short.io shows SSL renewed + "active".
Then I swap the pages back to the short links (5-min job).

Pages currently use direct CoinSpot links so CTAs work immediately.
