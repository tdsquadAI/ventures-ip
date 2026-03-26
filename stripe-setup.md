# Stripe Setup Checklist — Ventures & IP

## Account Setup

- [ ] Create Stripe account at https://dashboard.stripe.com/register
- [ ] Verify business identity (individual / sole proprietor)
- [ ] Add bank account for payouts
- [ ] Set payout schedule (daily / weekly / monthly)
- [ ] Enable two-factor authentication

## Branding

- [ ] Upload company logo
- [ ] Set statement descriptor: "VENTURES-IP"
- [ ] Configure receipt emails with company branding
- [ ] Set support email and phone

## Products & Prices

Create Stripe Products for each service:

- [ ] **Squad Setup & Configuration** — $5,000 (one-time)
- [ ] **AI Architecture Review** — $3,000 (one-time)
- [ ] **Aspire + Squad Workshop** — $2,000 (one-time)
- [ ] **Custom Agent Development** — $10,000 (one-time, adjustable)
- [ ] **Ongoing Squad Management** — $2,000/month (recurring)

## Payment Links

Generate Stripe Payment Links for self-service:

- [ ] Squad Setup payment link
- [ ] Workshop booking payment link
- [ ] Retainer subscription link

## Invoicing

- [ ] Configure invoice template
- [ ] Set payment terms (Net-30 for retainer clients)
- [ ] Enable automatic reminders (7 days, 14 days overdue)
- [ ] Set up tax collection (if applicable)

## Integration

- [ ] Generate API keys (test + live)
- [ ] Store keys in secure vault (not in repo!)
- [ ] Set up webhook endpoint for payment events
- [ ] Test end-to-end payment flow in test mode

## Go-Live

- [ ] Switch from test mode to live mode
- [ ] Process a real test transaction
- [ ] Verify payout to bank account
- [ ] Enable fraud prevention (Radar)
