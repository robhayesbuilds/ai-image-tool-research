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

*Last updated: 2026-02-09*
