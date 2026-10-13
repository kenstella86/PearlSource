# PearlSource — Guangdong Sourcing Agent

A static website for a local sourcing agent serving overseas buyers in Guangzhou, Foshan, Shenzhen, and Dongguan.

## Domain (planned)
- **PearlSource.com** — to be purchased on Cloudflare Registrar once PMF is validated
- For now, deploy to `pearlsource.pages.dev`

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub repo
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect Git repo
3. Build settings:
   - Framework preset: **None** (static site)
   - Build command: *(leave empty)*
   - Output directory: `/` (root)
4. Deploy — done. Every push to main auto-deploys.

## Structure
```
index.html                 Homepage (hero, differentiators, cities, process, comparison, pricing)
why-us.html                Detailed Alibaba vs. PearlSource comparison
how-it-works.html         6-step process, what you get in 48h
services.html              Pricing: free match / $199 audit / 5% agent
sourcing-request.html      6-field inquiry form (the conversion page)
about.html                Team, location, who we work with
cities.html               4-city overview
cities/foshan.html        Foshan detail page (template for other cities)
css/style.css              Shared stylesheet
robots.txt                Allows Google + AI crawlers (GPTBot, ClaudeBot, PerplexityBot)
sitemap.xml               XML sitemap for Search Console
```

## SEO / GEO features built in
- Unique title, meta description, canonical URL on every page
- Organization Schema JSON-LD on homepage
- robots.txt explicitly allows GPTBot, ClaudeBot, PerplexityBot (Generative Engine Optimization)
- Clean, keyword-rich URL structure (no numbered IDs)
- Transparent pricing pages (Google loves pricing transparency for commercial queries)

## Next steps before buying a real domain
1. Deploy to pages.dev and submit to Google Search Console
2. Fill 30–50 real factory profiles (each with your own photos)
3. Add 1 blog article per city (e.g., "Foshan ceramic sourcing guide 2026")
4. Watch inquiry volume for 4–6 weeks. If you get 5+ real inquiries per week, buy PearlSource.com and connect it.

## Domain decision rule
- **Buy the .com only after** you've received at least 10 real sourcing inquiries through pages.dev
- Don't spend $10 before validating that strangers actually want your service
