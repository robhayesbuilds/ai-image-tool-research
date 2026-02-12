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

*Last updated: 2026-02-12*
