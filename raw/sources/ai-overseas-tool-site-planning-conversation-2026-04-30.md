# AI Overseas Tool Site Planning Conversation

Date: 2026-04-30
Type: conversation record
Status: raw source

## Context

The user is a frontend developer interested in entering the AI overseas website-building / SEO tool-site space, influenced by creators such as “哥飞” and “子木聊AI出海”. The user was initially unsure how to find keywords or decide what kind of website to build.

## Conversation Record

### Initial Question

User asked for advice on joining the overseas website-building industry, especially around how to find keywords and what kind of website to make.

### Initial Recommendation

Assistant recommended avoiding broad pure-content sites and instead starting with a tool-based SEO site. The recommended general approach was:

- Focus on keywords with clear task intent, such as:
  - `xxx generator`
  - `xxx calculator`
  - `xxx template`
  - `xxx converter`
  - `xxx checker`
  - `xxx planner`
  - `xxx examples`
  - `xxx prompt`
  - `how to xxx for yyy`
- Prefer niche vertical audiences instead of broad AI tools:
  - Etsy sellers
  - Shopify store owners
  - YouTube creators
  - TikTok creators
  - indie game developers
  - students
  - HR / recruiters
  - real estate agents
  - resume/job seekers
  - Instagram/Pinterest creators
- Use the formula:
  - `audience + task + tool`
- Suggested example tools included:
  - Etsy listing title generator
  - YouTube title checker
  - TikTok bio generator
  - Shopify product description generator
  - Resume bullet point generator
  - Instagram caption ideas for real estate agents

The assistant recommended starting with an Etsy or YouTube tool site, with Etsy highlighted as a strong initial candidate because it has many keywords, clear seller needs, and suitable tool-style pages.

### Request for a Plan

User said the strategy was good and asked for a customized executable 7-day or longer plan.

### 14-Day Plan Proposed

Assistant proposed a 14-day validation plan:

- Goal: complete a small English tool-based SEO MVP in 14 days.
- Initial direction: Etsy Seller Tools.
- First tool: Free Etsy Tags Generator.
- Recommended stack: Next.js + Tailwind CSS + Vercel.
- MVP structure:
  - one core tool page
  - 10 long-tail SEO pages
  - Google Search Console submission
  - basic analytics and behavior tracking

The proposed first pages were:

- `/etsy-tags-generator`
- `/etsy-tags-for-jewelry`
- `/etsy-tags-for-digital-products`
- `/etsy-tags-for-stickers`
- `/etsy-tags-for-printables`
- `/etsy-tags-for-shirts`
- `/etsy-tags-for-candles`
- `/etsy-tags-for-art`
- `/etsy-tags-for-wedding-invitations`
- `/etsy-tags-for-crochet`
- `/etsy-tags-for-handmade-gifts`

The assistant suggested starting with a rule-based generator before adding an AI API.

### User Preference Collection

User asked the assistant to first ask about their technical stack, tools, and preferences, then formulate a plan and write it into the current project.

The assistant asked about:

1. Preferred technical stack.
2. Common development/deployment tools.
3. Preferred AI API strategy for the first version.
4. Daily time commitment.

User selected:

- Tech stack: Next.js.
- Tools: Vercel, Cloudflare, Supabase, GitHub.
- AI capability: undecided.
- Daily time: 1-2 hours.

### Plan Written to Wiki

Assistant wrote a customized plan into:

- `wiki/syntheses/ai-overseas-tool-site-14-day-plan.md`

The plan used:

- Next.js App Router
- TypeScript
- Tailwind CSS
- Vercel deployment
- GitHub code hosting
- Cloudflare DNS / caching
- Supabase only after persistence is needed
- Rule-based generation for the MVP
- Possible later Claude API or other LLM API integration

### Day 1 Review

User asked what should be done today according to the plan.

Assistant answered that Day 1 should focus on locking the niche and site promise, without writing code:

- Direction: Etsy Seller Tools.
- Target user: Etsy sellers who want to improve product listing discovery.
- First tool: Free Etsy Tags Generator.
- Possible working brand names:
  - Maker SEO Tools
  - Listing Helper
  - Craft Listing Tools
  - Seller Tag Tools
  - ListingBoost
- Recommended working brand: Maker SEO Tools.
- Site promise:
  - `Generate better tags, titles, and listing ideas for handmade and digital products.`

### Competition Concern

User searched Google for `Free Etsy Tags Generator` and found competition already looked intense. User asked whether there was still an opportunity.

### Revised Strategic Judgment

Assistant searched public results and agreed that the direct head term `Free Etsy Tags Generator` is already competitive. The assistant concluded:

- The opportunity is not gone.
- But `Free Etsy Tags Generator` should not be the first-stage primary traffic battlefield.
- It can remain as a supporting tool page.
- The better strategy is to target long-tail category pages, product-specific pages, and broader listing-helper intent.

Observed competitive landscape included:

- AI Etsy tag tools.
- Free Etsy tag generators.
- Etsy SEO SaaS tools.
- Tools with competition/search volume data.
- Reddit discussion around Etsy SEO tag generators.

The assistant recommended shifting from a single `Etsy Tags Generator` positioning to a broader `Etsy Listing Helper` positioning.

### Revised MVP Direction

Recommended revised positioning:

> Etsy Listing Helper: input product information once and generate tags, title ideas, and description drafts.

Revised first product:

- `Etsy Listing Helper`

Revised core page:

- `/etsy-listing-helper`

Supporting tool pages:

- `/etsy-tags-generator`
- `/etsy-title-generator`
- `/etsy-description-generator`

Suggested first SEO cluster:

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

Suggested page title:

- `Free Etsy Listing Helper for Tags, Titles, and Descriptions`

Suggested tool output:

- 13 Etsy tags.
- 3 title ideas.
- 2 description openings.
- Keyword ideas.

### Current Strategic Conclusion

Continue with the Etsy direction, but do not rely on `Free Etsy Tags Generator` as the main entry point.

The stronger strategy is:

> Build a broader Etsy Listing Helper and use long-tail category pages plus supporting generator pages to acquire search traffic.

This creates a better chance of differentiation and better fits the user's frontend strengths, because the user can build a more useful and polished interactive experience than many thin SEO pages or simple tag generators.
