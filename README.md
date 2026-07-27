# VIP Win-Back Dashboard — Ample Couture

Static, self-contained dashboard for VIP health, win-back, and blast-effectiveness tracking.

- **Overview** — 850 Diamond & Platinum VIPs: status, days silent, priority, lifetime (cash vs gift-card).
- **Blast Report** — Friday WhatsApp blast effectiveness: who came back, what they bought, how they paid.

All data is embedded in `index.html` (single file, no build step, no backend).

## Deploy (Vercel)
This is a static site. On Vercel: **New Project → Import this repo → Deploy** (no framework, no build command, output = root). It serves `index.html` automatically.

## Updating the data
Regenerate `index.html` from the source order/VIP files and commit — Vercel redeploys on every push to the default branch.
