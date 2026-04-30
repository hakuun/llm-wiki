---
title: AI Overseas Tool Site 14-Day Execution Plan
type: synthesis
tags: [ai-overseas, seo, tool-site, nextjs, etsy, execution-plan]
sources: [raw/sources/ai-overseas-tool-site-planning-conversation-2026-04-30.md]
created: 2026-04-30
updated: 2026-04-30
status: active
---

# AI Overseas Tool Site 14-Day Execution Plan

This plan is customized for a frontend developer building a small English SEO tool site for overseas users.

## Current Preferences

- Role: frontend developer.
- First site type: tool-based SEO site, not a pure content site.
- Recommended niche: Etsy seller tools.
- First product: Etsy Listing Helper.
- Supporting tools: Etsy Tags Generator, Etsy Title Generator, Etsy Description Generator.
- Tech stack: Next.js + Tailwind CSS.
- Deployment: Vercel.
- Supporting tools: GitHub, Cloudflare, Supabase.
- AI capability: undecided; use a two-phase approach.
  - Phase 1: rule-based generation to validate SEO and user behavior.
  - Phase 2: add Claude API or another LLM API after early validation.
- Available time: 1-2 hours per day.

## Strategic Update

The direct keyword `Free Etsy Tags Generator` appears competitive. The plan should not rely on that head term as the first-stage traffic battlefield.

The updated strategy is:

> Build a broader Etsy Listing Helper, then use long-tail category pages and supporting generator pages to acquire search traffic.

This keeps the Etsy direction but shifts the main product from a single tag generator to a fuller listing optimization workflow.

## Positioning

Recommended positioning:

> A lightweight listing helper for Etsy sellers that generates tags, title ideas, description openings, and keyword ideas for handmade and digital product listings.

Avoid naming the brand directly after Etsy to reduce trademark and platform-dependency risk. Use Etsy in page titles and content where appropriate for search intent, but prefer a broader brand such as Maker SEO Tools, Listing Helper, Craft Listing Tools, Seller Tag Tools, or ListingBoost.

## MVP Scope

### Core Page

- `/etsy-listing-helper`
- Main intent: help Etsy sellers create better listing assets from product information.
- Purpose: generate Etsy-friendly tags, title ideas, description openings, and keyword ideas.

### Supporting Tool Pages

- `/etsy-tags-generator`
- `/etsy-title-generator`
- `/etsy-description-generator`

These pages can target narrower tool keywords, but they should internally link back to the broader listing helper.

### First Long-Tail Pages

Use category-specific pages as the early SEO wedge:

- `/etsy-tags-for-digital-products`
- `/etsy-tags-for-printable-wall-art`
- `/etsy-tags-for-crochet-plushies`
- `/etsy-tags-for-handmade-jewelry`
- `/etsy-tags-for-wedding-invitations`
- `/etsy-tags-for-svg-files`
- `/etsy-tags-for-stickers`
- `/etsy-tags-for-candles`
- `/etsy-tags-for-mugs`
- `/etsy-tags-for-t-shirts`

### MVP Features

- Product name input.
- Category selector.
- Optional fields for material, style, occasion, and target buyer.
- Generate up to 13 Etsy tag ideas.
- Generate 3 listing title ideas.
- Generate 2 description opening drafts.
- Generate keyword ideas.
- Keep tags short and readable.
- Deduplicate tags.
- Copy all tags.
- Copy individual tag.
- Copy title and description drafts.
- Basic event tracking for generation and copy actions.

## Recommended Stack

### Frontend and App

- Next.js App Router.
- TypeScript.
- Tailwind CSS.
- Static or mostly static pages for SEO.
- Server component pages for long-tail content where possible.

### Deployment and Infrastructure

- GitHub for code hosting.
- Vercel for initial deployment.
- Cloudflare for domain DNS and optional caching.
- Supabase only when persistence is needed, such as saved generations, email collection, user accounts, or feedback storage.

### Analytics and SEO

- Google Search Console.
- Bing Webmaster Tools.
- Vercel Analytics or Plausible.
- Event tracking for:
  - `generate_listing_clicked`
  - `copy_all_tags_clicked`
  - `copy_single_tag_clicked`
  - `copy_title_clicked`
  - `copy_description_clicked`
  - `category_selected`

## 14-Day Plan

## Day 1: Lock the Niche and Site Promise

Time budget: 1-2 hours.

Tasks:

1. Choose the first niche: Etsy seller tools.
2. Define the first user segment: Etsy sellers optimizing product listings.
3. Confirm the first product: Etsy Listing Helper.
4. Choose a working brand name that is not overly tied to Etsy.
5. Write a one-sentence promise:
   - `Generate better tags, titles, and listing ideas for handmade and digital products.`
6. Create a simple project note with:
   - target user
   - main problem
   - first product
   - supporting tools
   - success metric for MVP

Output:

```txt
Niche: Etsy seller tools
First product: Etsy Listing Helper
Supporting tools: Etsy Tags Generator, Etsy Title Generator, Etsy Description Generator
Target user: Etsy sellers improving product listing discovery
MVP success metric: pages indexed + first impressions in Search Console + real generate/copy events
```

## Day 2: Build the Keyword Seed List

Time budget: 1-2 hours.

Tasks:

1. Use Google autocomplete for seed phrases:
   - `etsy listing`
   - `etsy listing generator`
   - `etsy tags`
   - `etsy title`
   - `etsy description`
   - `etsy seo`
   - `etsy profit`
2. Collect 50-100 candidate keywords.
3. Classify each keyword by page type:
   - Core tool
   - Supporting tool
   - Category example page
   - Blog guide
   - Calculator
   - Template
4. Mark obvious high-competition terms and low-competition long-tail terms.

Output columns:

```txt
Keyword | Intent | Page Type | Competition Guess | Notes
```

Priority candidates:

- `etsy listing helper`
- `etsy listing generator`
- `etsy product title generator`
- `etsy product description generator`
- `etsy listing description generator`
- `etsy tags generator`
- `etsy tag generator free`
- `etsy tags for digital products`
- `etsy tags for printable wall art`
- `etsy tags for crochet plushies`
- `etsy tags for handmade jewelry`
- `etsy tags for wedding invitations`
- `etsy tags for svg files`
- `etsy tags for stickers`
- `etsy profit calculator`

## Day 3: Validate SERPs and Select the First Cluster

Time budget: 1-2 hours.

Tasks:

1. Search the broader listing terms and 10 long-tail category terms in Google.
2. Check whether the first page has weak results:
   - old-looking tools
   - thin blog posts
   - Reddit, Quora, Medium, forums
   - low-quality AI content
3. Avoid SERPs dominated only by large authoritative sites.
4. Confirm the first cluster around `/etsy-listing-helper` plus category-specific tag pages.

Output:

```txt
Main page: /etsy-listing-helper
Supporting tool pages: /etsy-tags-generator, /etsy-title-generator, /etsy-description-generator
Supporting SEO pages: 10 category-specific Etsy tag/example pages
Reason: avoid hard reliance on the competitive tags-generator head term while still covering its intent
```

Decision rule:

If `etsy listing generator` is also too competitive, keep the main product but rely on category-specific pages first.

## Day 4: Competitor and UX Breakdown

Time budget: 1-2 hours.

Tasks:

1. Review the top 5-10 pages for:
   - `etsy listing generator`
   - `etsy tags generator`
   - `etsy title generator`
   - `etsy description generator`
2. Record their features, weaknesses, and content structure.
3. Identify one UX advantage to build:
   - one input flow that generates tags, titles, and descriptions together
   - cleaner mobile UI
   - copy buttons
   - category-specific examples
   - less intrusive ads
   - more practical seller guidance
4. Draft the first page structure.

Target page structure:

```txt
H1: Free Etsy Listing Helper
Intro
Tool form
Generated tags
Generated title ideas
Generated description openings
Keyword ideas
Examples by category
Best practices
FAQ
Internal links to supporting tools and long-tail pages
```

## Day 5: Set Up the Project

Time budget: 1-2 hours.

Tasks:

1. Create a Next.js project with TypeScript and Tailwind CSS.
2. Push to GitHub.
3. Deploy the initial site to Vercel.
4. Configure Cloudflare DNS if using a custom domain.
5. Add basic layout:
   - header
   - footer
   - homepage
   - core tool page shell

Recommended routes:

```txt
/
/etsy-listing-helper
/etsy-tags-generator
/etsy-title-generator
/etsy-description-generator
/guides
/privacy-policy
/terms
```

Output:

A live skeleton site with the main route available.

## Day 6: Build the Rule-Based Listing Helper

Time budget: 1-2 hours.

Tasks:

1. Add inputs:
   - product name
   - category
   - style
   - material
   - occasion
   - target buyer
2. Generate tags from deterministic rules and templates.
3. Generate title ideas from category, product, material, style, and buyer intent.
4. Generate description openings from product type, use case, and gift context.
5. Deduplicate tag results.
6. Limit output to 13 tags.
7. Add copy buttons for tags, titles, and descriptions.
8. Add basic empty and error states.

Example input:

```txt
Product: silver moon necklace
Category: jewelry
Style: minimalist
Occasion: birthday gift
Target buyer: women
```

Example output:

```txt
Tags:
silver necklace
moon necklace
minimalist jewelry
birthday gift
gift for her
celestial necklace
handmade necklace
dainty necklace
moon jewelry
necklace gift
jewelry lover gift

Title ideas:
Minimalist Silver Moon Necklace, Celestial Jewelry Gift for Her
Dainty Moon Necklace for Women, Handmade Birthday Gift
Silver Celestial Necklace, Minimalist Jewelry for Everyday Wear

Description openings:
A minimalist silver moon necklace designed for everyday wear and thoughtful gifting.
This dainty celestial necklace makes a simple birthday gift for women who love moon-inspired jewelry.
```

## Day 7: Write and Polish the Main SEO Page

Time budget: 1-2 hours.

Tasks:

1. Add title and meta description.
2. Write concise page copy.
3. Add FAQ.
4. Add internal links placeholder for supporting tools and long-tail pages.
5. Check mobile layout.

Suggested title:

```txt
Free Etsy Listing Helper for Tags, Titles, and Descriptions
```

Suggested meta description:

```txt
Generate Etsy tags, title ideas, description openings, and keyword ideas for your product listings. Built for handmade, digital, and print-on-demand sellers.
```

## Day 8: Add SEO Infrastructure

Time budget: 1-2 hours.

Tasks:

1. Add sitemap.
2. Add robots.txt.
3. Add canonical URLs.
4. Add Open Graph metadata.
5. Add favicon.
6. Add privacy policy and terms pages.
7. Check that pages are crawlable without client-only rendering issues.

Output:

The site is ready for Search Console submission.

## Day 9: Create the First 5 Long-Tail Pages

Time budget: 1-2 hours.

Pages:

- `/etsy-tags-for-digital-products`
- `/etsy-tags-for-printable-wall-art`
- `/etsy-tags-for-crochet-plushies`
- `/etsy-tags-for-handmade-jewelry`
- `/etsy-tags-for-wedding-invitations`

Each page should include:

- 50-100 tag examples.
- 5 title examples.
- 3-5 short description opening examples.
- Practical tips for the category.
- Link back to `/etsy-listing-helper`.
- Link to `/etsy-tags-generator` where relevant.

Quality bar:

Do not publish pure filler. Each page should help a seller choose tags and listing angles for that category.

## Day 10: Create the Next 5 Long-Tail Pages

Time budget: 1-2 hours.

Pages:

- `/etsy-tags-for-svg-files`
- `/etsy-tags-for-stickers`
- `/etsy-tags-for-candles`
- `/etsy-tags-for-mugs`
- `/etsy-tags-for-t-shirts`

Tasks:

1. Use the same structure as Day 9.
2. Add internal links between related pages.
3. Add links from the main listing helper page to all long-tail pages.
4. Add links from homepage to the main tool page.

## Day 11: Add Analytics and Submit for Indexing

Time budget: 1-2 hours.

Tasks:

1. Add Google Search Console.
2. Add Bing Webmaster Tools.
3. Submit sitemap.
4. Request indexing for the homepage and `/etsy-listing-helper`.
5. Add Vercel Analytics or Plausible.
6. Track key events:
   - generate listing click
   - copy all tags
   - copy single tag
   - copy title
   - copy description
   - category selected

Output:

The site has indexing and product-behavior visibility.

## Day 12: Do Initial Distribution

Time budget: 1-2 hours.

Tasks:

1. Share the tool in places where feedback is acceptable.
2. Avoid spam or hard promotion.
3. Ask for feedback from Etsy sellers.
4. Write one short launch post.

Positioning example:

```txt
I made a free Etsy listing helper that generates tag ideas, title ideas, and description openings for handmade and digital product sellers. I am looking for feedback from Etsy shop owners.
```

Possible channels:

- Indie Hackers.
- Reddit communities where tool feedback is allowed.
- X/Twitter.
- Personal blog or Medium.
- Relevant maker communities.

## Day 13: Review Data and Fix UX Problems

Time budget: 1-2 hours.

Tasks:

1. Check whether pages are indexed or discovered.
2. Check Search Console impressions if any exist.
3. Review analytics events.
4. If users visit but do not generate a listing, improve the first screen.
5. If users generate but do not copy, improve result display and copy CTAs.
6. Fix mobile issues.

Decision hints:

- No impressions yet: normal for a new site; continue building and wait.
- Impressions but low CTR: improve title and meta description.
- Visits but no tool usage: improve above-the-fold clarity.
- Tool usage but no copy events: improve result quality and copy interactions.
- Tool usage but no return visits: add saved examples or downloadable outputs later.

## Day 14: Decide the Next Build Step

Time budget: 1-2 hours.

Choose one path based on evidence:

### Path A: Continue the Etsy Listing Cluster

Use this if pages are indexed or getting impressions.

Next tools:

- Etsy Tags Generator.
- Etsy Title Generator.
- Etsy Description Generator.
- Etsy Profit Calculator.
- Etsy SEO Checker.

### Path B: Improve the Main Listing Helper

Use this if people visit but do not interact.

Improve:

- first screen copy
- category examples
- result quality
- copy interactions
- mobile layout

### Path C: Add AI Generation

Use this if users interact with the rule-based version and better output quality becomes the bottleneck.

Add:

- Claude API or another LLM API.
- prompt caching where available.
- rate limits.
- daily free quota.
- fallback to rule-based examples if API is unavailable.

### Path D: Pivot Keyword Cluster

Use this if the SERP is too competitive and no long-tail pages are gaining impressions after several weeks.

Try adjacent clusters:

- YouTube title tools.
- Resume bullet point tools.
- Shopify product description tools.

## 30-Day Extension

After the first 14 days, continue only if the site is indexed and the workflow feels repeatable.

Recommended next sequence:

1. Add dedicated Etsy Tags Generator page.
2. Add dedicated Etsy Title Generator page.
3. Add dedicated Etsy Description Generator page.
4. Add Etsy Profit Calculator.
5. Add 20-30 more long-tail example pages.
6. Add email capture or feedback form.
7. Add Supabase only when data persistence is clearly needed.
8. Add AI generation after validating demand with the rule-based tool.

## Weekly Review Checklist

Review every 7 days:

- Which pages are indexed?
- Which queries have impressions?
- Which pages have clicks?
- Which pages have tool interactions?
- Which long-tail categories show early promise?
- Does the main opportunity look like listing helper, tags, titles, descriptions, or calculators?
- What is the next smallest useful tool or page cluster?

## Key Principles

- Ship a small complete site before adding advanced features.
- Prefer tool pages over generic blog posts.
- Use long-tail pages to support the main listing helper.
- Do not rely on `Free Etsy Tags Generator` as the only SEO entry point.
- Keep the first version rule-based unless output quality blocks validation.
- Do not add Supabase, login, or payment until there is evidence of usage.
- Let Search Console and event data decide the next build step.
