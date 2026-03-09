# Pricing Landscape: AI Coding Assistants
*Generated: March 9, 2026*

## Market Pricing Overview

- **Dominant value metric:** Credit/usage-based systems (adopted by 6+ competitors in 2025-2026), driven by the 5-20x compute cost of agentic AI features vs. simple autocomplete
- **Price range:** $0 (BYOK/open-source) to $200/mo (Cursor Ultra, Augment Max) for individuals; $19-75/user/mo for teams/enterprise
- **Median entry paid price:** $19-20/mo for individual developers
- **Free tier prevalence:** 15 of 15 competitors offer a free tier — universally expected in 2026

## Tier-by-Tier Comparison

### Individual Plans

| Competitor | Free Tier | Entry Paid | Power User | How It Scales |
|-----------|-----------|------------|------------|---------------|
| **Cursor** | Limited completions, limited agent | $20/mo (Pro) — $20 credit pool | $200/mo (Ultra) — 20x usage | Credit-based; premium models draw from pool |
| **GitHub Copilot** | 2,000 completions, 50 chats | $10/mo (Pro) — 300 premium req | $39/mo (Pro+) — 1,500 premium req | Per-seat + premium request metering |
| **Windsurf** | 25 credits (~25 messages) | $15/mo (Pro) — 500 credits | $15/mo + add-on credits ($10/250) | Credit-based; add-ons roll over |
| **Cline** | Unlimited (BYOK) | $0 (pay API provider directly) | API costs only (~$5-50/mo typical) | Pure usage via API provider |
| **Augment** | Limited | $20/mo (Indie) — 40K credits | $200/mo (Max) — 450K credits | Credit-based; auto top-up at $15/24K |
| **Tabnine** | Dev Preview (minimal) | $39/mo (Code Assistant) | $59/mo (Agentic Platform) | Per-seat; annual-only |
| **Sourcegraph Amp** | Limited (ad-supported) | ~$59 (credit-based) | Enterprise only | Credit-based |
| **Amazon Q** | 50 agentic req/mo, 1K LOC transform | $19/mo (Pro) — expanded limits | $19/mo (no power tier) | Per-seat + LOC overage at $0.003 |
| **JetBrains AI** | Basic AI, 3 credits/30 days | $10/mo (AI Pro) — 10 credits | $30/mo (AI Ultimate) — 35 credits | Credit-based ($1/credit) |
| **Claude Code** | Via Claude Pro ($20/mo) | $20/mo (Pro) — usage limits | $100/mo (Max) | Token-based via API or subscription |
| **Supermaven** | Basic completions | $10/mo (Pro) | $10/mo (same) | Flat per-seat, no credits |
| **Continue** | Unlimited (BYOK, open-source) | $10/user/mo (Teams) | Custom (Enterprise) | BYOK + management layer |
| **Replit** | Limited | $20/mo (Core) | $100/mo (Pro, 15 builders) | Platform subscription + credits |
| **Qodo** | 250 credits | $19/user/mo (Teams) — 2,500 credits | Custom (Enterprise) | Credit-based; 5x for premium models |
| **Google Gemini Code Assist** | Free (daily limits) | $25/mo ($299/yr bundle) | $75/user/mo (Enterprise) | Per-seat; ecosystem-bundled |

### Team/Enterprise Plans

| Competitor | Team Price | Enterprise Price | Key Enterprise Features |
|-----------|-----------|-----------------|----------------------|
| **Cursor** | $40/user/mo | Custom | SSO, SAML/OIDC, SCIM, audit logs, privacy mode |
| **GitHub Copilot** | $19/user/mo (Business) | $39/user/mo | IP indemnity, policy controls, data excluded from training |
| **Windsurf** | $30/user/mo | Custom | SSO, RBAC, analytics, hybrid deployment |
| **Cline** | $20/user/mo (first 10 free) | Custom | SSO, SLA, auth logs, fine-grained permissions |
| **Augment** | $60/user/mo (Standard) | Custom | SOC 2, ISO 42001, CMEK, dedicated support |
| **Tabnine** | $39/user/mo | Custom | Air-gapped, VPC, on-prem, zero retention |
| **Sourcegraph** | N/A | $59/user/mo (Cody Enterprise) | Code search, batch changes, custom deployment |
| **Amazon Q** | $19/user/mo (Pro) | Same | IAM, IP indemnity, admin dashboard |
| **JetBrains AI** | AI Pro ($10-20/mo) | Custom | Enterprise governance |
| **Claude Code** | $25-30/user/mo (Standard) | $150/user/mo (Premium) | Full Claude Code, SSO, audit logs |

## Value Metric Analysis

| Competitor | Value Metric | Why It Works/Doesn't | Impact on Scaling |
|-----------|-------------|---------------------|-------------------|
| Cursor | Credits ($1 = 1 credit) | Aligns cost with model usage intensity; creates anxiety and billing complaints | Heavy users hit $40-60/mo; enterprises face unpredictable per-seat costs |
| GitHub Copilot | Per-seat + premium requests | Familiar to enterprise procurement; creates natural upsell | Linear and predictable; premium request model creates upgrade friction |
| Windsurf | Credits ($0.04/credit) | Transparent per-message pricing; but 25 free credits is very limiting | Add-on credits roll over; auto-refill creates ongoing spend |
| Cline | BYOK (API provider billing) | Maximum transparency; eliminates middleman markup | Scales with actual API consumption; user controls cost entirely |
| Augment | Credits (tool-call-based) | Captures compute cost precisely; but 293–4,261 credit variance per task creates unpredictability | Auto top-up at $15/24K creates runaway bills for heavy users |
| Tabnine | Per-seat (flat) | Predictable for procurement; simple to understand | Linear scaling; no usage surprises but no flexibility either |
| JetBrains AI | Credits ($1/credit) | Integrates with existing subscription; but "phantom consumption" erodes trust | Credits consumed even when assistant is idle — major complaint |

## Pricing Psychology in Use

| Tactic | Used By | How |
|--------|---------|-----|
| **Anchoring** | Cursor ($200 Ultra makes $20 Pro feel cheap), Augment ($200 Max → $60 Standard), GitHub ($39 Pro+ → $10 Pro) | High-price tiers make mid-tiers feel reasonable |
| **Decoy tier** | Cursor (Pro+ "Recommended"), Tabnine (Agentic at $59 pushes to Code Assistant at $39) | Middle tier designed to push to a specific plan |
| **Charm pricing** | GitHub ($10, $39), Amazon Q ($19) | Psychological price points below round numbers |
| **Round pricing** | Cursor ($20, $60, $200), Augment ($20, $60, $200) | Signals premium positioning |
| **Free tier strategy** | All 15 competitors | Universal; varies from generous (Cline unlimited, Copilot 2K completions) to minimal (Windsurf 25 credits) |
| **Annual lock-in** | Cursor (20% off), Copilot (17% off), JetBrains (17% + loyalty discounts), Tabnine (annual-only) | 12-month commitment via discount or requirement |
| **Bundle play** | JetBrains (AI Pro free with All Products Pack), Amazon Q (rounding error on AWS bill), Replit (AI + IDE + hosting) | AI included in broader subscription to drive retention |
| **Transparency play** | Cline ("no middleman, no markup"), Continue (open-source, BYOK) | Anti-lock-in positioning attacks subscription competitors |
| **Credit anxiety** | Augment (auto top-up), Cursor (credit drain), JetBrains (phantom consumption) | Unintended psychology: creates frustration, not loyalty |

## Switching Cost Matrix

| Competitor | Technical Cost | Contractual Cost | Emotional Cost | Overall |
|-----------|---------------|-----------------|----------------|---------|
| **Cursor** | High (IDE fork) | Medium (annual billing) | High (community, identity) | **High** |
| **GitHub Copilot** | Low (plugin) | Low (monthly available) | Medium (GitHub loyalty) | **Low-Medium** |
| **Windsurf** | High (IDE fork) | Low (monthly) | Low (uncertainty from acquisition) | **Medium** |
| **Cline** | Low (VS Code extension) | None | Low-Medium (OSS loyalty) | **Low** |
| **Augment** | Medium (Context Engine data) | Low (monthly) | Low (backlash erodes loyalty) | **Low-Medium** |
| **Tabnine** | Low (plugin) | Medium (annual-only) | Medium (privacy trust) | **Medium** |
| **Sourcegraph** | Medium (code search indexes) | Medium (enterprise contracts) | Low (brand confusion) | **Medium** |
| **Amazon Q** | Medium (AWS-specific features) | Low (monthly) | Low-Medium (AWS loyalty) | **Medium** |
| **JetBrains AI** | High (IDE ecosystem) | Medium (annual + loyalty discounts) | High (IDE devotion) | **High** |
| **Replit** | High (full platform) | Medium (subscription + hosting) | Medium (community) | **High** |

## Pricing Whitespace

### 1. The $5-10/mo Hobbyist Gap
Between free tiers and the $15-20/mo entry point, there's no paid option for hobbyists, students, and part-time developers who want reliable AI but don't code 8 hours/day. **Opportunity:** A $7-9/mo "Hobby" plan with generous but not unlimited usage.

### 2. Predictable Unlimited Plans ($30-50/mo)
The market is moving toward credit anxiety. A truly unlimited plan — no credits, no metering, no surprise bills — at $30-50/mo would be a radical differentiator. **Trade-off:** Must manage compute costs via model routing and caching.

### 3. Outcome-Based Pricing
No competitor prices on measurable outcomes (bugs caught, PRs merged, time saved). All price on inputs (seats, credits, requests). **Opportunity:** "Pay for results" pricing where customers pay based on value delivered, not compute consumed.

### 4. Team Plans Under $20/user
Only Continue ($10/user) and Copilot Business ($19/user) are below $20/user/mo for teams. Most team plans are $30-60/user. **Opportunity:** A $15/user team plan with core features could capture price-sensitive teams.

### 5. Vertical-Specific Tiers
No competitor offers industry-specific tiers (fintech compliance, healthcare HIPAA, gaming optimization) despite different needs and willingness-to-pay. **Opportunity:** Specialized plans with industry-specific context, compliance, and features.

### 6. Annual Team Discounts
Most team plans lack annual billing options. **Opportunity:** Offer 20-25% annual discounts for teams — captures budget and reduces churn.

## Recommendations

- **If competing on price:** Enter at $10/mo individual, $15/user team, with genuinely unlimited usage. Use open-source models + smart routing to manage compute costs. Target the "I just want it to work without billing surprises" segment.

- **If competing on value:** Enter at $25-40/mo with demonstrably superior accuracy and codebase understanding. Justify the premium with measurable productivity gains (time saved, bugs prevented). Target professional developers who will pay more for "gets it right first try."

- **If competing on model:** Adopt the Cline/Continue BYOK approach with a management/enterprise layer on top. Charge $0 for individuals (they pay API providers directly), $15-20/user for team management features. Differentiate on transparency and no vendor lock-in.
