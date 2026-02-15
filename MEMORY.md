# MEMORY.md - Long-Term Memory

*Curated learnings and significant decisions. Updated periodically from daily logs.*

---

## Strategic Decisions

### 2026-02-07: FacturSimple → VixPic Pivot
**Yassine's instruction:** Stop all FacturSimple work, focus on VixPic (BYOK AI Image Tool).

**Reasoning:**
- FacturSimple was a French e-invoicing tool for auto-entrepreneurs
- 58 pages of content built, 40+ communities identified
- But: DNS never resolved (NXDOMAIN), deployment blocked
- VixPic represents a larger market opportunity with clearer path to revenue

**VixPic Core Thesis:**
- BYOK (Bring Your Own Key) AI image generation is an unserved market
- TypingMind, Msty exist for chat - nothing for images
- Pain points: $30/mo subscriptions, credit expiration, censorship, no API access
- LTD model ($29-149) with edge proxy architecture

---

## Project Knowledge

### zaanix-studio GitHub Org
- Owner: Yassine
- Member: robhayesbuilds
- Repos: vixpic, factursimple, control-center, ai-image-tool-research, x-growth-research, docucollect, rob-dashboard

### Tech Stack Preferences
- shadcn/ui + Zod + React Hook Form
- Tabler icons (not emojis - avoid "AI slop" look)
- Skip AppSumo (70% cut) → own site = 97% net

### Marketing Constraints
- Reddit/X automation DISABLED (ban risk)
- Marketing must be transparent (no astroturfing)

---

## Lessons Learned

### Background Agents
- Spawned agents sometimes produce no output
- For critical research, do it directly rather than delegating
- Rate limits on Brave Search API (Free plan = 1 req limit)

### Content Strategy
- 57 profession-specific guides = effective long-tail SEO approach
- But deployment blockers can waste all that effort
- Verify DNS/hosting before massive content investment

---

## SaaS Frameworks (2026)

### The 3-Stage Evolution
Every breakout SaaS follows: **Tool → Smart Recommendations → AI Agent Execution**
Miss this path = cold start death or crushed by incumbents.

### Horizontal SaaS Headwinds
Rob Walling (Startups for the Rest of Us) predicts massive headwinds for bootstrapped horizontal SaaS in 2026. Venture money + AI-first companies flooding big markets. Plateaus hard at $500K-$2M ARR.

**Escape routes:** Vertical positioning, orthogonal markets, lifestyle-scale on single traffic source.

VixPic's BYOK positioning is orthogonal - competing in different dimension than Midjourney/DALL-E.

---

## API SaaS Benchmarks (2026-02-09)

### Revenue Reality for Bootstrapped API Tools
| Revenue Tier | Example | Startup Cost | Team Size |
|--------------|---------|--------------|-----------|
| $600K/year | Bannerbear (image API) | $500 | 1 person |
| $360K/year | Geocode.xyz | $10 | 2 people |
| $264K/year | Scrapingdog | $300 | 6 people |

**Key insight:** Solo founders can hit $50K MRR with API tools. Low startup costs + SEO = high ROI.

### Critical Success Factors
1. **SEO is primary driver** - All successful API businesses grew via content/organic
2. **Solve dev pain points** - "Building X from scratch is complex" = opportunity
3. **Integrations multiply growth** - Fomo grew 600% via integrations ecosystem

### VixPic Comparable: Bannerbear
- API for automated image generation
- 1-person team, $600K/year
- $49-299 pricing tiers
- Closest model to VixPic's vision

---

## Resource Stack for Bootstrappers

| Resource | Use For |
|----------|---------|
| Indie Hackers | Real-time tactics, validation |
| Starter Story | Structured case studies, metrics |
| MicroConf Vault | Deep frameworks (170+ hrs FREE) |
| TinySeed Tales | Longitudinal founder journeys |
| Baremetrics Open | Quantitative benchmarks |

---

## 2026 Bootstrapping Playbook (2026-02-11)

### The 10-Step Framework
1. **Solve small agonizing problem** - "Who pays in 30 days?" beats "What's disruptive?"
2. **Validate with revenue** - 5 paying > 100 interested signups
3. **MVP = opinionated** - One problem solved well, not flexible platform
4. **Price early, honestly** - Low prices signal instability; 2-3 tiers max
5. **Revenue before team** - Founder closeness to users = superpower
6. **Compounding channels** - Channel depth > spread; no paid ads until conversion proven
7. **Retention = growth** - CAC high in 2026; onboarding + docs + proactive support
8. **AI strategic not excessive** - Must lower costs OR add value
9. **Cash flow visibility** - MRR, churn, conservative projections
10. **Raise only when proven** - Bootstrap = voluntary funding leverage

### Micro-SaaS Success Patterns
- Most bootstrap with <$1,000, profitable in 3-6 months
- Profit margins: 80-95% once established
- Break-even: often 10-50 customers

### Revenue Benchmarks (Real Companies)
| Company | Revenue | Model |
|---------|---------|-------|
| Buffer | $20M+ ARR | Started with 2 features |
| Plausible | $100K+ MRR | 2 employees, privacy positioning |
| RemoveBackground | $3M ARR Y1 | Single feature → sold to Canva |
| ConvertKit | $25M/year | $5K start, affiliate program |
| Dorik | $11.9M/year | Side project → no-code builder |

### Weekend Validation Framework
- **Friday (2h):** Landing page + pricing + email capture
- **Saturday (4h):** 5 subreddits, helpful content, soft CTA
- **Sunday:** Analyze, iterate or pivot

---

## VixPic Competitive Intelligence (2026-02-10)

### Direct Competitor: SeamUI
- Pricing: $39-199 LTD tiers
- Features: 11+ AI models, BYOK, bulk gen, projects
- Target: E-commerce, course creators, agencies

### VixPic Differentiation Strategy
1. **Lower entry price** - $29 vs $39
2. **More providers** - Replicate/FAL models SeamUI lacks
3. **Privacy edge** - Edge proxy, keys never touch server
4. **Developer API** - Power user segment SeamUI ignores

### Market Validation
- BYOKList.com curates 40+ BYOK tools → category is real
- 70-90% cost savings vs subscriptions → strong value prop
- SeamUI existence proves demand; market not saturated

---

## LTD Platform Landscape (2026-02-12)

### Platform Comparison for VixPic Launch

| Platform | Take Rate | Refund | Best For |
|----------|-----------|--------|----------|
| AppSumo | ~70% | 60 days | Massive audience, brand validation |
| Pitchground | ~50% | 60 days | SaaS-focused, better splits |
| Dealify | Better | 30 days | Startup/growth hacker audience |
| Own site | ~3% (Stripe) | Custom | Max margin, own customer relationship |

### Recommended LTD Launch Strategy
1. **Phase 1: Own site** - Early adopters, $29-149 tiers, 97% net
2. **Phase 2: Pitchground** - If need broader exposure, 50% cut acceptable
3. **Phase 3: AppSumo** - Only if brand validation needed, 70% cut hurts

### Why Pitchground > AppSumo for BYOK Tool
- SaaS-focused audience (vs AppSumo's broad mix)
- Better margin (50% vs 70%)
- Still ~400 TrustPilot reviews = established platform
- 60-day refund same as AppSumo

---

## SaaS Resource Usage Framework (2026-02-12)

### How to Extract Maximum Value

**Indie Hackers (daily check)**
- Filter: Bootstrapped + SaaS + revenue sort
- Study "Milestones" posts for exact tactics
- Ask tactical questions, not generic

**Starter Story (weekly deep dive)**
- Consistent interview format = easy comparison
- Focus on "How You Grew" section
- Benchmark startup costs + MRR + team size

**MicroConf Vault (monthly learning)**
- 170+ hours FREE tactical talks
- Not motivational - actual frameworks
- Rob Walling, Rand Fishkin tier content

---

## 2026 SaaS Unit Economics Benchmarks (2026-02-13)

### The Metrics That Matter

| Metric | Median | Best-in-Class | Warning |
|--------|--------|---------------|---------|
| Annual Growth (bootstrapped) | 23% | 40-50% | <15% |
| Net Revenue Retention | 106% | 120-130% | <100% |
| Gross Revenue Retention | 90% | 95%+ | <85% |
| Monthly Churn | ~0.4% | <0.25% | >1% |
| CAC Payback | 12-18 mo | 8-12 mo | >24 mo |
| LTV:CAC | 4:1 | 5:1+ | <3:1 |

### The 2026 Shift: Retention > Acquisition
- CAC rose 14% while growth slowed through 2025
- Existing customers now generate **40%+ of new ARR**
- Companies with NRR >100% grow 1.5-3x faster
- Churn improving while new sales slow = retention winners take all

### Implications for VixPic
- LTD model eliminates churn concerns entirely
- BYOK creates switching costs (user's API keys = investment)
- Focus on expansion: tiers, API access, new providers
- Don't obsess over new customer acquisition at expense of activation

---

## AI-First SaaS Economics & BYOK Advantage (2026-02-14)

### The AI Margin Crisis
Traditional SaaS: 80-90% gross margins
AI-first SaaS: 50-60% average, **25% or negative** for early-stage

**Real examples of margin squeeze:**
| Company | Issue |
|---------|-------|
| GitHub Copilot | Costs Microsoft ~$80/user (charges $10) = $20 avg loss |
| Replit | Margins <10%, sometimes negative during surges |
| Cursor IDE | Had to restructure pricing, issue refunds |

**Root cause:** Every AI inference = direct variable cost. Classic SaaS marginal cost is near-zero; AI SaaS cost scales with usage.

### Why BYOK Is a Structural Margin Hack
VixPic's BYOK model transfers inference costs entirely to user's API account.

| Cost Type | Traditional AI SaaS | VixPic BYOK |
|-----------|---------------------|-------------|
| Inference | Company pays (COGS) | User pays (external) |
| Gross margin | 25-60% | ~95% |
| LTD viability | Suicide | Sustainable |

> "An AI company's COGS rides someone else's price card" - Industry analyst
> 
> **VixPic insight:** Make that 'someone else' = the user, not you.

### AI Solo Founder Revenue Benchmarks
| Founder | Product | ARR | Model |
|---------|---------|-----|-------|
| Nick Dobos | BoredHumans | $8.8M | 100+ SEO tools |
| Bhanu Teja | SiteGPT | $1.14M | Custom chatbots |
| Seth Kramer | PDF.ai | $1.2M | Chat with PDFs |
| Mohamed Maamer | Blackbox AI | $5M | Coding assistant |

**Common patterns:**
- MVP in weeks, not months
- Niche > broad early on
- SEO/community > paid ads
- Usage-based pricing scales
- Solo to $1M ARR before first hire

### The "Build 100 Tools" Strategy
BoredHumans: 100+ small AI tools on one domain → each = SEO landing page → aggregated $8.8M ARR from long-tail traffic.

**VixPic potential:** Add small image utilities (resize, crop, upscale) alongside generator for SEO surface area expansion.

---

## Launch & Distribution Strategy (2026-02-15)

### The Platform Conversion Gap (2025 Data)

| Platform | Conversion Rate | Prep Time | Budget |
|----------|-----------------|-----------|--------|
| Indie Hackers | **23.1%** | 15-20 min/day | $0 |
| Product Hunt | **3.1%** | 50-120 hours | $1,847 avg |

**Key stat:** 89% of Product Hunt founders surveyed wouldn't launch again.

**Post-2024 PH algorithm shift:**
- Featured rate collapsed: 60-98% → 10%
- Same tactics, different results: 300 upvotes = 91 customers (2023) vs 612 upvotes = 1 customer (2024)

### The First 10 Customers Playbook

**The 4-Step Framework:**
1. **Identify & Infiltrate** - 3-5 niche communities
2. **Apply 90/10 Rule** - 90% value, 10% product mention
3. **Soft Ask** - Request feedback, not sales
4. **White-Glove Onboarding** - Turn early users into co-creators

**Timeline:** 6-8 weeks from engagement to first paying customer

**Build in Public stats:**
- 73% faster time to first customer
- 2.3x higher conversion (trial → paid)
- 89% more likely to reach PMF within 6 months

### The 90/10 Rule (Verified)

**Pratham Naik's results (Oct 2024):**
- 1,200 targeted visitors in 6 weeks, $0 budget
- Daily investment: 15-20 minutes

**What worked:**
| Channel | Visitors | Strategy |
|---------|----------|----------|
| Reddit comments | 680 | 20 min/day, 8 subreddits, no pitches |
| SEO content | Consistent | 5 blog posts answering questions |
| Community | 290 | Value-first engagement |

**What failed:** Cold DMs (2% response), generic Twitter threads (8 likes)

**Key insight:** "No single comment blew up. 1,200 visitors came from daily habits—15-20 minutes of genuine engagement, every day, for 6 weeks."

### Indie Hackers Content That Converts

**Headline Formula:** [Specific Number] + [Transformation] + [Timeframe]
- "$0 → 1,200 visitors in 6 weeks" ✓
- "How I grew from 0 to $10K MRR in 5 months" ✓
- "Check out my new SaaS" ✗

**Post structure:**
1. Hook with struggle/failed attempts
2. Pivot point
3. Numbered tactics with results
4. Honest admission of failures
5. Question CTA to community

**Length:** 750-1,500 words

### Multi-Platform Sequencing Strategy

**The "Infinite Marketing Glitch" (Farid Shukurov 2024):**
1. Get any success (small or big)
2. Tell people how you got this success (drives traffic)
3. Tell people how telling drove more traffic
4. Repeat

**His result:** Reddit post about his PH strategy → 1,450 visitors (more than his #1 Product Hunt launch at ~800 visitors)

### Waitlist Fundamentals

**Optimal duration:** 2-4 months
**Target:** 1,000+ highly qualified signups
**Key metric:** Conversion rate (10-60% variance in industry)

**Robinhood case:**
- 1 million+ waitlist before launch
- $0 user acquisition spend
- Referral mechanics (position visibility, move up by referring)

### VixPic Launch Sequence (Recommended)

1. **Phase 1: Indie Hackers (now, 4-6 weeks)**
   - Journey posts documenting FacturSimple → VixPic pivot
   - Build in public with specific numbers
   - 20 min/day engagement
   
2. **Phase 2: Community Building**
   - Reddit r/SaaS, r/SideProject (helpful comments only)
   - Twitter/X build in public threads
   - Target: 500+ engaged followers before PH
   
3. **Phase 3: SEO via Free Tools**
   - Image compressor, converter already built
   - Each tool = landing page = long-tail traffic
   
4. **Phase 4: Product Hunt (only after community momentum)**
   - Use IH community for initial votes
   - Set email capture goal (1,000+), not upvote goal

### When to Skip Indie Hackers

**Don't fit:**
- B2B with complex sales cycles
- Enterprise procurement
- Non-tech audiences
- Products $10-100 (direct sales ineffective)
- AI wrappers without differentiation

**Sobering stat:** 54% of IH products make $0 revenue

---

*Last updated: 2026-02-15*
