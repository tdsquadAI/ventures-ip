# Stripe Setup Guide — Ventures & IP

## Account Setup
1. Go to https://stripe.com → Sign up with tdsquadai@gmail.com
2. Business type: Individual / Sole trader
3. Business name: Ventures IP (no personal names)
4. Country: Choose appropriate jurisdiction

## Products to Create
- **Starter License** — $199/mo (recurring subscription)
- **Professional License** — $499/mo (recurring subscription)  
- **Enterprise License** — $1,499/mo (recurring subscription)
- **Consulting Hour** — $150 (one-time payment)
- **IP Transfer** — custom pricing

## After Account Creation
Add these as GitHub repo secrets in ventures-ip/ventures-ip:
- `STRIPE_SECRET_KEY` — from Stripe Dashboard → Developers → API Keys
- `STRIPE_WEBHOOK_SECRET` — from Stripe Dashboard → Webhooks

## Payment Links (quick no-code solution)
Use Stripe Payment Links for initial sales before building full checkout:
1. Dashboard → Payment Links → Create Link
2. Select product → Copy URL
3. Add to docs/revenue-engine/README.md as CTA buttons

## Integration with Revenue Engine
Update docs/revenue-engine/README.md to add Stripe payment link buttons
once account is set up.
