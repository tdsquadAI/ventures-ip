# Revenue Channels — All Companies

Complete map of revenue channels across the sub-company architecture and their payment/billing status.

## Company #1: TechAI Content

| Channel | Platform | Payment Provider | Status |
|---------|----------|-----------------|--------|
| YouTube ad revenue | YouTube | Google AdSense | ⏳ Needs monetization setup |
| Digital downloads | Gumroad | Stripe (via Gumroad) | ✅ Active (squadai.gumroad.com) |
| Sponsorships | Direct | Invoice → Stripe | ⏳ Not started |
| Newsletter premium | Kit (ConvertKit) | Stripe | ⏳ Needs connection |

## Company #2: JellyBolt Games

| Channel | Platform | Payment Provider | Status |
|---------|----------|-----------------|--------|
| Game sales | Google Play | Google Play Billing | ⏳ Needs developer account |
| In-app purchases | Google Play | Google Play Billing | ⏳ Needs developer account |
| Game sales | Apple App Store | Apple In-App Purchase | 📋 Planned |
| Game sales | itch.io | Stripe (via itch.io) | ✅ Active (16 games live) |

## Company #3: Content Empire

| Channel | Platform | Payment Provider | Status |
|---------|----------|-----------------|--------|
| Online courses | Teachable/Udemy | Stripe | ⏳ Needs course platform |
| eBooks | Gumroad | Stripe (via Gumroad) | ✅ Active (squadai.gumroad.com) |
| Workshop tickets | Eventbrite | Stripe | 📋 Planned |
| Membership | Patreon | Stripe (via Patreon) | 📋 Planned |

## Company #4: (TBD)

| Channel | Platform | Payment Provider | Status |
|---------|----------|-----------------|--------|
| — | — | — | Not yet defined |

## Company #5: Ventures & IP

| Channel | Platform | Payment Provider | Status |
|---------|----------|-----------------|--------|
| Consulting invoices | Direct | Stripe Invoicing | ⏳ Needs Stripe setup |
| Payment links | Website | Stripe Payment Links | ⏳ Needs Stripe setup |
| Retainer subscriptions | Direct | Stripe Subscriptions | ⏳ Needs Stripe setup |
| IP licensing fees | Direct | Stripe Invoicing | ⏳ Needs Stripe setup |
| Patent royalties | Direct | Wire / Stripe | 📋 Future |

## Cross-Company Notes

### Stripe as Central Payment Rail
Stripe should be the central payment processor for all direct-to-customer revenue:
- Single Stripe account with multiple products, or
- Stripe Connect for multi-entity setup

### Priority Setup Order
1. **Ventures & IP** (highest margin, immediate revenue potential)
2. **Content Empire** (course sales ready to launch)
3. **TechAI Content** (YouTube + Gumroad)
4. **JellyBolt Games** (platform-specific billing, less urgent)

### Tax Considerations
- [ ] Determine business entity structure for invoicing
- [ ] Set up tax collection for applicable jurisdictions
- [ ] Consult accountant on multi-company revenue reporting
