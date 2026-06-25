# ListingForge

**ListingForge** is a 100% client-side SEO listing generator for Etsy, Amazon, and eBay sellers: paste your product name, features, materials, and ideal buyer, pick a marketplace + tone, and it forges a copy-ready listing — an SEO title sized to each platform's character limit, benefit-led bullets, a vivid description, and a *ranked keyword tag constellation* trimmed to each marketplace's exact tag rules. No signup, no backend, no tracking — everything runs in your browser.

**Live → (set on deploy)**

## How it works

- **Free tier (keyless, in-browser):** A lightweight NLP engine extracts single- and multi-word phrases from your input, scores them by frequency, position, specificity, and buyer-intent signals (gift, handmade, custom, etc.), dedupes them, and ranks/trims to each marketplace's rules — Etsy (140-char title, 13 tags ≤20 chars), Amazon (200-char title, 5 bullets, backend terms), eBay (80-char title, item-specific keywords). It then builds a structured title, bullets, description, and a ranked tag cloud. Instant, no key required.
- **Pro tier (bring your own key):** Paste your own **GLM (z.ai)** API key — stored only in your browser's localStorage and sent only to the official z.ai endpoint over HTTPS — and the "AI rewrite" button has GLM-4.5 write polished, tone-matched copy and discover long-tail keyword phrases, run through a built-in quality gate that rejects bland, generic filler. We never see your key or your data.

## Privacy

Single self-contained `index.html`. No server, no analytics, no cookies beyond the locally-stored key you choose to save. The free generator never makes a network request with your product data.

## Affiliate disclosure

The "Get a GLM key" link ([z.ai](https://z.ai/subscribe?ic=BWTG6TRYYQ), 5% off) is a **referral link** — we may earn a small commission at no extra cost to you. The free tier works fully without any key; a key is only needed for the optional AI rewrite.
