# Spencer X Smith

**I build AI systems for financial services and legal firms.**

A lot of consultants added "AI" to their bio in the last two years. I'd rather show you the work. Everything below is either public code you can run yourself, or client work described as specifically as confidentiality allows.

## Start here

**[AdvisorMap](https://github.com/spencerxsmith/AdvisorMap)** turns 670,000+ public Form 5500 retirement-plan filings into prospecting intelligence: which plans have no advisor, which plans changed advisors this year, and which firms are winning or losing plans. Three years of Department of Labor data, entity resolution across 48,000+ service providers, $10T+ in plan assets mapped. Python, DuckDB, Parquet, Streamlit.

The README walks through the unglamorous parts - truncated names, typo'd EINs, and why "Fidelity National Financial" isn't Fidelity Investments. That's 90% of real data work, so that's what the repo shows.

Why retirement plans? I worked as a 401(k) wholesaler earlier in my career. I know what advisors actually ask for, because I sat across the table from them for years.

**[cite-check](https://github.com/spencerxsmith/cite-check)** is for the legal side: RAG answers with citations a machine can verify. Every citation is anchored to a verbatim quote, and a deterministic verifier confirms the quote actually appears in the cited source - catching fabricated citations before a lawyer relies on one. Extracted from a decision-memory system I built for a law firm's operations team, rebuilt with synthetic data.

**[Delta Choice Benefits Advisor](https://github.com/spencerxsmith/delta-choice-benefits-advisor)** is a smaller one: a decision tool that helps Delta flyers pick benefits based on how they fly and who they fly with. Built because the choice was genuinely confusing, including to me.

## Client work

These repos are private because the work belongs to clients. The patterns are worth describing:

- **Decision memory for a law firm's operations team.** Firms lose institutional knowledge every time someone leaves. This captures operational decisions with their rationale, then answers natural-language questions with cited sources. Next.js, Postgres with pgvector, Claude.
- **Marketing-collateral builder for a global accounting-software company.** Partner-marketing teams generate on-brand collateral from structured inputs instead of waiting on a design queue.
- **Booking portal for a global asset manager's national 401(k) summit.** Scheduling logic, not a form.
- **Participant portal for a financial-advisor study-group community.** Meeting materials, member directory, session logistics.
- **Client-intake automation for a litigation firm.** Forms that used to be PDFs and phone tag.
- **Post-meeting recall tool.** Captures what you learned while it's fresh, before the next meeting overwrites it.

## Background

30 years in professional services and emerging technology. Former 401(k) wholesaler. Co-author of *ROTOMA: The ROI of Social Media Top of Mind*. I speak regularly to financial-services audiences, most recently closing out the PLANSPONSOR 2026 National Conference in Nashville.

I write about practical AI adoption at [spencerXsmith.com](https://spencerXsmith.com) - no hype, just what's working at real firms.

## Get in touch

If you're at a financial-services or legal firm and you're past the "should we use AI" conversation and into the "what do we actually build" one, that's where I'm useful.

Find me at [spencerXsmith.com](https://spencerXsmith.com) or on [LinkedIn](https://www.linkedin.com/in/spencerxsmith).
