# Battle Card: Cursor (Anysphere)
*Last updated: March 9, 2026*

## At a Glance
- **What they do:** AI-first code editor (VS Code fork) with agentic coding, multi-file editing, and workflow automation
- **Founded:** 2022 | **Funding:** $3.2B | **Team:** ~300+
- **Price:** $0-200/mo (credit-based) | **Model:** Credits ($1 = 1 credit)
- **Best for:** Individual developers and small teams who want an AI-native IDE experience with cutting-edge features

## Their Strengths (be honest)
- **Fastest product velocity in the market.** Ships major features monthly (Automations, Cloud Agents, BugBot, Memories). Always first to integrate new AI capabilities. [Data]
- **$2B ARR — fastest-growing SaaS ever.** Grew from $100M to $2B in 12 months with near-zero marketing spend. Product-led growth machine. [Data]
- **Best multi-file editing (Composer).** Handles ~90% of refactoring tasks in one pass. Plan mode provides structured output vs. Copilot's paragraph responses. [Data: G2 reviews, community feedback]
- **Strong enterprise conversion.** 60% of revenue from enterprise contracts. OpenAI, Midjourney, Shopify, Instacart as customers. [Data]

## Their Weaknesses (your openings)
- **Pricing backlash is severe.** June 2025 credit switch was the most discussed negative event in the market. Users report $40-50/mo effective cost vs. advertised $20. "Cursor just nuked the Pro plan" is a recurring sentiment. [Data: Reddit, TechCrunch]
- **Security vulnerabilities.** CVE-2025-54135 and CVE-2025-54136 (RCE). Telemetry transmits commit info with no enterprise opt-out. No audit trails, RBAC, or tenant isolation. [Data: CVE database]
- **IDE lock-in.** VS Code fork means users must adopt Cursor's IDE. Custom rules, workflows, and configs are not portable. High switching cost = high adoption friction. [Data]
- **Buggy updates.** Release-breaking updates that corrupt chat histories (Cursor 2.1), file saving failures, broken Tab key. [Data: Cursor Community Forum]
- **Context limitations.** Despite claiming 200K context, effective code context is ~60-80K tokens. Hallucinates imports, misses type relationships in larger codebases. [Data: user reports]

## How to Win Against Them
- **When they say "Cursor is the fastest AI editor,"** respond: "Fast features mean nothing if your bill is unpredictable. We offer [flat-rate pricing / transparent usage] — no credit anxiety, no billing surprises."
- **When they say "Composer handles multi-file edits,"** respond: "Composer generates massive, hard-to-review PRs. Our agent [verifies its own work / runs tests before presenting results] — you get code that actually works, not code you have to debug."
- **When they say "We have enterprise customers,"** respond: "Cursor has documented RCE vulnerabilities and no audit trails. We provide [SOC 2 / zero retention / air-gapped deployment] out of the box."
- **Lead with:** Predictable pricing + security + accuracy. The three things Cursor users complain about most.

## When They Win Over You
- **Developers who want the absolute latest AI features first.** Cursor ships fastest; if being on the bleeding edge matters more than stability, they win.
- **Teams already deeply invested in Cursor workflows.** High switching costs from .cursorrules, project configs, and team habits make migration painful.
- **"Vibe coders" who prioritize speed over precision.** Cursor's brand is "move fast with AI" — some developers prefer that over careful verification.

## Their Customers' Top Complaint
"Cursor just nuked the Pro plan. '500 requests became ~225,' and they're acting like the old system never existed." — Reddit r/cursor_ai user, 2025

This matters because: Pricing trust, once broken, is extremely hard to rebuild. Developers who've been burned by billing surprises are actively looking for alternatives.

## Key Vulnerability
**The gap between marketed price ($20/mo) and actual price ($40-60/mo for heavy users).** This is Cursor's biggest Achilles' heel. Combined with security vulnerabilities and enterprise governance gaps, there's a clear opening for a "more trustworthy" alternative.

## Churn Signals
- Hitting rate limits multiple times per day on Pro plan — frequency: very common
- Billing shock ($500 in 3 days reported) — frequency: occasional but highly viral
- Feature parity erosion vs. VS Code + Copilot — frequency: growing
- Enterprise security review failures — frequency: common in regulated industries

## Watch For
- **Automations (event-triggered agents):** Cursor is expanding beyond IDE into workflow orchestration (Slack, Linear, GitHub, PagerDuty triggers). This could make them harder to displace.
- **Cloud Agents:** Running in isolated VMs producing merge-ready PRs. If reliability improves, this becomes a major moat.
- **Enterprise pricing formalization:** Expect Cursor to address the pricing backlash with clearer tiers and enterprise packaging in 2026.
