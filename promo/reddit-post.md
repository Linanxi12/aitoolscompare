Title: I built a site that compares AI tools with a transparent scoring framework — no sponsored reviews, no AI-generated filler

Hey r/programming,

Over the past week I built [aitools-hub.xyz](https://aitools-hub.xyz) — a static site that does side-by-side AI tool comparisons with a public scoring methodology.

**Why I built it:**
Every AI tool comparison I found was either a sponsored listicle or surface-level "Claude is good, GPT is also good" fluff. I wanted something with actual weighted scores, test methodology, and clear "pick X if you..." recommendations.

**What's different:**
- Every article follows the exact same 6-section format
- Scores use weighted dimensions (coding: 35/35/30, image: 40/35/25) — all adjustable per comparison with documented rationale
- All data sources cited, no fake benchmarks
- Built with Hugo + GitHub Pages, $0 hosting, no tracking except analytics
- 5 articles live: Cursor vs Copilot, Claude vs GPT-4o, Copilot vs Codeium, Midjourney vs DALL-E 3, SD3 vs Midjourney

**I'd love feedback on:**
1. Is the weighted scoring useful or over-engineered?
2. What other tool pairs should I compare?
3. Would you trust comparison scores that use public benchmarks + community consensus vs lab testing?

Site: https://aitools-hub.xyz
GitHub: https://github.com/Linanxi12/aitoolscompare
