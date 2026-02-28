# JOE PRO — Developer Handoff Sheet
## Dream Builder Intelligence Upgrade
### From: David | Garcia Luna / MATTIEGARZ LLC

---

## OVERVIEW

Dream Builder currently has Joe — the AI e-commerce assistant. We are adding **Joe Pro** as a premium upgrade tier inside the existing Dream Builder platform. Joe Pro is not a separate product. It is an intelligence layer that upgrades Joe with real market data.

Think of it this way:
- **Basic Joe** = personal e-commerce coach and assistant
- **Joe Pro** = everything Joe does PLUS full market intelligence powered by live data

---

## WHAT JOE PRO DOES

Joe Pro gives Dream Builder members real-time e-commerce intelligence in plain English through the Joe interface. Specifically:

1. **Trending Product Intelligence** — What products are trending right now across Amazon, TikTok Shop, and Etsy. Updated regularly.

2. **Competitor Analysis** — What competitors are selling, how they're pricing, what's working for them.

3. **Buyer Keyword Intelligence** — What buyers are actually typing when they're ready to purchase. Actionable SEO data for e-commerce sellers.

4. **Content Intelligence** — What posts, videos, and ads are driving the most e-commerce sales right now across social platforms.

5. **Plain English Delivery** — All of this data is interpreted and delivered by Joe Pro in simple, actionable language. Not raw data dumps. Joe Pro tells the member exactly what to do with the information.

---

## HOW IT WORKS TECHNICALLY

Joe Pro pulls data from external APIs and feeds it into the Joe AI system so Joe can interpret it and present it to the user in conversation.

### Required API Integrations

**Product Trend Data**
- Amazon Product Advertising API — trending and best selling products
- TikTok Shop API — trending products and viral items
- Etsy API — trending handmade and niche products
- Google Trends API (free) — search trend data by category and keyword

**Competitor & SEO Intelligence**
- SEMrush API — competitor analysis, keyword data, search volume (primary option)
- Alternative: DataForSEO API — more affordable, same core functionality, recommended for cost efficiency
- Alternative: Ahrefs API — strong backlink and keyword data

**Social Content Intelligence**
- Meta Marketing API — trending ad content and performance data
- TikTok for Business API — trending content and creative intelligence

**Pricing Intelligence**
- Rainforest API — Amazon product and pricing data (affordable and reliable)
- Keepa API — Amazon price history and trend tracking

---

## PLATFORM STRUCTURE

- Joe Pro is an **upgrade tier inside Dream Builder** — not a separate platform
- Members on the basic tier see Joe as normal
- Members who upgrade to Joe Pro unlock the intelligence features inside the same Joe interface
- The upgrade should be seamless — same chat interface, Joe just becomes more powerful
- Build a simple upgrade/paywall trigger inside Dream Builder that unlocks Joe Pro features when the member is on the premium tier

---

## JOE PRO SYSTEM PROMPT ADDITION

On top of Joe's existing system prompt, Joe Pro needs the following added capability instructions:

- Joe Pro has access to live market data through integrated APIs
- When a member asks what's trending, Joe Pro pulls current data and presents the top opportunities in their niche
- When a member asks about a competitor, Joe Pro retrieves and summarizes competitor data
- When a member needs keywords, Joe Pro pulls buyer intent keywords relevant to their products
- When a member needs content ideas, Joe Pro pulls what's currently performing best in their category
- Joe Pro always translates data into plain English action steps — never raw numbers without context

---

## VERSION 1 REQUIREMENTS

Build it complete and solid. Version 1 should include all of the above. Once V1 is live and stable, additional features will be added on top.

**V1 Must Haves:**
- All API integrations connected and pulling live data
- Joe Pro tier unlocked inside Dream Builder as a premium upgrade
- Joe Pro system prompt updated with intelligence capabilities
- Clean, simple UI indicator showing the member they are on Joe Pro
- Data refreshes on a reasonable schedule (daily minimum for trend data)

---

## PRIORITY

This is high priority. Get Dream Builder's basic Joe live first if not already done. Joe Pro follows immediately after.

---

## QUESTIONS

Direct all questions to David via the usual channel.

---

*Garcia Luna / MATTIEGARZ LLC — Confidential*