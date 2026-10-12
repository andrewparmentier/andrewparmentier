# Andrew Parmentier

Strategy and business development executive in Boulder, Colorado. Two-time founder: Height Capital Markets (sold 2017) and Ducks Rising (sold 2026).

I build my own tools with AI. Since April 2026 I've built an investment research and risk system and a full-stack web app with Claude Code. I write the spec, an agent writes most of the code, and I review, test and ship.

## What I've built

- **Investment research and risk system** (private). Two Python services built solo: about 18,000 lines and 500+ automated tests.
    - Pulls in RSS feeds, X, YouTube, web articles, PDFs and book pages, and uses Claude to file them into a knowledge base with a running event log for each company.
    - Syncs positions and trades from my brokerage account, read-only, and tracks every position lot by lot.
    - Runs risk monitors: a drawdown brake, a market-volatility brake, post-earnings reaction scoring, liquidity checks and trend-reversal alerts.
    - Sends every decision to me in Slack for approval. The system flags; I decide.
- **[Second-Brain](https://github.com/andrewparmentier/Second-Brain)**: an early, public version of the research ingestion layer. Drop a file or clip a page, get a linked research note.
- **CapCommit**: side project. A college-recruiting tracker for youth water polo families, built solo on Supabase and Vercel. Beta November 2026.

## Stack

Python, TypeScript, SQLite, Supabase, Vercel, Claude API, Claude Code, Slack API, Interactive Brokers API, Obsidian, macOS launchd.

## Contact

[LinkedIn](https://www.linkedin.com/in/a-parm/)
