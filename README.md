# What AI coding agents cost, where they break, and what shipped

[![figures](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Ffigures.json)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/figures.md) [![writeups](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fwriteups.json)](https://xyzs996.github.io/ai-coding-field-notes/) [![updated](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fupdated.json)](https://github.com/xyzs996/ai-coding-field-notes/releases) [![license](https://img.shields.io/badge/data-CC%20BY%204.0-blue)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/LICENSE)

26 write-ups on running AI coding agents in production — token bills,
tool switching costs, where the agents actually break, and what the
numbers looked like afterwards.

**Read these on the web:** [AI Coding Field Notes](https://xyzs996.github.io/ai-coding-field-notes/) — the same write-ups with the figures table, the topic pages and the
links between them.

**On the figures.** Every number here traces back to a named source or
a run we did. Numbers we could not trace were cut before publishing,
not rounded or guessed. Each piece says up front that it was drafted
with AI assistance.

## The figures, as data (270 rows)

Every figure published across the 26 write-ups —
prices, percentages, multiples, token counts and durations — pulled into one table. Each row carries
the **full sentence it came from** and a link to the piece, so
you can check it without reading all of them.

```
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.json
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.csv
```

Fields: `value`, `kind` (`price` / `percent` / `multiple` / `tokens` / `duration`), `context`, `article`, `published`, `url`. `published` is the day that
write-up went out, not the day the figure was in force —
prices move, so read each row as of its own date.
Browse it as a table:
[figures.md](figures.md).

Those two go through jsDelivr, which caches `@main` for up to 12
hours — fine for a table that is rebuilt once a day. If you want
it uncached, the origin is
`https://xyzs996.github.io/ai-coding-field-notes/data/figures.json`.

A number without its sentence is not checkable — `$1.43` could be
per million tokens, per month, or per seat. The sentence is quoted
verbatim, not summarised.

**Citing a row?** `@main` moves — today's row 88 may be somewhere
else tomorrow. Every snapshot is also frozen as a dated release,
and these two always resolve to the newest frozen one:

```
curl -sL https://github.com/xyzs996/ai-coding-field-notes/releases/latest/download/figures.json
curl -sL https://github.com/xyzs996/ai-coding-field-notes/releases/latest/download/figures.csv
```

[All snapshots](https://github.com/xyzs996/ai-coding-field-notes/releases) — one per day the table actually changed.

**Corrections wanted.** If a figure is stale, a tool changed its
pricing, or you ran the same thing and got something else — [open an
issue](https://github.com/xyzs996/ai-coding-field-notes/issues/new/choose). That is
what this repo is for.

If this table saves you an afternoon, a star helps other people find
it. The data is CC BY and does not require starring.

**Follow along.** [Atom feed](https://xyzs996.github.io/ai-coding-field-notes/feed.xml) — new
write-ups land there first.

**By topic.** [Automation Systems](topics/automation-systems.md) (9) · [Indie Development](topics/indie-development.md) (9) · [AI Costs](topics/ai-costs.md) (6) · [AI Implementation](topics/ai-implementation.md) (6) · [SaaS Business](topics/saas-business.md) (6) · [Cost Savings](topics/cost-savings.md) (5) · [AI Programming](topics/ai-programming.md) (4) · [Development Tools](topics/development-tools.md) (4) · [Niche Market](topics/niche-market.md) (4) · [Chinese AI](topics/chinese-ai.md) (3) · [Micro SaaS](topics/micro-saas.md) (3) · [Productivity](topics/productivity.md) (3) · [Token Optimization](topics/token-optimization.md) (3)

## The write-ups

### [1.6 Billion Free Tokens Is a Compression Ratio, Not a Strategy](articles/1-6-billion-free-tokens-is-a-compression-ratio-not-a.md)

OmniRoute aggregates 237 providers and advertises roughly 1.6 billion free tokens a month, and that figure is arithmetic rather than a promotion, because the RTK+Caveman layer compresses 10,000 tok…

`Token Optimization` `Cost Savings` `Indie Development` `Development Tools`

### [58 Million Plays Started With One Account, Not Four](articles/58-million-plays-started-with-one-account-not-four.md)

Two brothers ran a single short-video account until one piece of content took off, and only then copied it across several accounts, which is how the cumulative play count passed 58 million.

`Content Marketing` `Video Marketing` `SaaS Business` `Automation Systems`

### [A 30-Line Script, 200 Users, and a Niche Nobody Wanted](articles/a-30-line-script-200-users-and-a-niche-nobody-wanted.md)

"Solving a niche problem is the secret to building a profitable Micro-SaaS." This common advice ignores the power of focusing on a single, well-defined pain point in a specific market.

`AI Automation` `Micro SaaS` `SaaS Business` `Niche Market`

### [AI Agent Loop Engineering: Karpathy's Method for 5x Productivity Gains](articles/ai-agent-loop-engineering-karpathy-s-method-for-5x.md)

A developer in China’s AI community achieved 5x productivity gains using loop engineering, reducing MVP development time from four prompt tuning sessions to a single command installation.

`Enterprise AI` `Developer Tools` `Automation Systems` `Indie Development`

### [AI Programming Tool Selection Strategy: From Rapid Prototyping to Long-term Collaboration](articles/ai-programming-tool-selection-strategy-from-rapid.md)

A specialized code review agent beat Claude Code on accuracy across 200 real pull requests and 50 open-source repositories while burning about one-ninth the tokens.

`AI Implementation` `AI Costs` `Development Tools` `Enterprise Automation`

### [AI-Generated Local Business Websites Don't Rent for $3,000/Month (Until You Do This)](articles/ai-generated-local-business-websites-don-t-rent-for-3-000.md)

You can build AI-generated local business websites, rent them to plumbers or dentists for $500–$3,000 a month, and scale to passive income.

`AI Tools` `Local SEO` `Niche Market` `Revenue Growth`

### [Beyond Chat: How Codex Can Automate Your Word/Excel/PPT/PDF Workflows](articles/beyond-chat-how-codex-can-automate-your-word-excel-ppt-pdf.md)

Codex's office automation capabilities, which are severely underestimated, can be transformed into powerful document processing agents, as shown by real-world developers, one of whom automated PDF…

`Codex` `AI Programming` `Automation Systems` `Office Automation`

### [Beyond Token Pricing: How Indie Devs Should Really Evaluate AI Model Costs](articles/beyond-token-pricing-how-indie-devs-should-really-evaluate.md)

Microsoft's evaluation of Kimi K3 landed on a number that should change how you read a pricing page: about 60 percent of the cost difference between models comes from the thinking depth a task requ…

`AI Systems` `AI Implementation` `AI Pricing` `Indie Development`

### [Boosting AI Bot Conversion: A Deep Dive into Funnel Data](articles/boosting-ai-bot-conversion-a-deep-dive-into-funnel-data.md)

One reported case moved entry-group conversion from 9.1% to 55.1% by rebuilding an automated onboarding flow around what the funnel data actually showed, rather than around what the team assumed us…

`AI Implementation` `AI Bot Conversion` `Funnel Data Analysis` `Enterprise AI Adoption`

### [Choosing the Right AI Model for Coding: Cost vs. Efficiency](articles/choosing-the-right-ai-model-for-coding-cost-vs-efficiency.md)

Fable 5, the cheapest option at $9.05 per run, delivers only 41.2% accuracy in React projects.

`Code Review` `AI Costs` `Indie Development` `Development Tools`

### [From AI Demo to Product: Loop Engineering for Indie Devs](articles/from-ai-demo-to-product-loop-engineering-for-indie-devs.md)

The agent processes 40-plus podcast channels overnight, transcribed and summarized, ready to read by morning.

`Productivity` `AI Implementation` `Automation Systems` `Indie Development`

### [How Chinese AI Agent Tools Leverage 1.6 Billion Free Tokens](articles/how-chinese-ai-agent-tools-leverage-1-6-billion-free-tokens.md)

Chinese AI agent tools offer a game-changing strategy for independent developers to access a massive pool of 1.6 billion free tokens monthly.

`Token Optimization` `Cost Savings` `Chinese AI` `Automation Systems`

### [How Chinese Developers Are Using Codex Record & Replay to Streamline Repetitive Workflows](articles/how-chinese-developers-are-using-codex-record-replay-to.md)

A monthly report that used to take four hours now takes a few minutes.

`Workflow Automation` `AI Development` `Chinese AI` `Automation Systems`

### [How to Build a Micro-SaaS Without Spending a Dime on Ads](articles/how-to-build-a-micro-saas-without-spending-a-dime-on-ads.md)

Jordan posted an introduction thread across 3 Reddit sub-boards and had 200 people asking for access within days, at zero cost, and those users stuck around better than the paid traffic he never bo…

`Micro-SaaS` `Rental Business` `SaaS Business` `Automation Systems`

### [MonkeyCode: The Open-Source AI Coding Platform With 900 Million Free Tokens](articles/monkeycode-the-open-source-ai-coding-platform-with-900.md)

MonkeyCode's free tier includes 900 million tokens, deploys to your own network with 1 command, and ships as open source you can read.

`Open-Source` `AI Costs` `Indie Development` `Development Tools`

### [Stop Chatting With AI: How I Use /loop and /hook to Automate My Indie Dev Workflow](articles/stop-chatting-with-ai-how-i-use-loop-and-hook-to-automate.md)

If you run a solo dev shop, the day goes to fragmented feeds, forty open tabs, and backend maintenance that eats the hours meant for product logic.

`Productivity` `Recurring Revenue` `AI Features` `Niche Market`

### [The 5 AI Features That Separated 27 Profitable Solopreneurs From the Rest](articles/the-5-ai-features-that-separated-27-profitable-solopreneurs.md)

Of the 27 AI-powered micro-SaaS projects that generated predictable monthly revenue in a recent analysis, every profitable one used at least three of the same five architectural components.

`AI Automation` `Micro SaaS` `Indie Developer` `AI for Solopreneurs`

### [The AI Branding Revolution: How Indie Developers Are Ditching Design Costs with AI](articles/the-ai-branding-revolution-how-indie-developers-are.md)

Chris launched WiseMindAI last year and came out of a single session with Miora's brand visual template holding more than ten finished assets, covering color schemes, typography and social graphics…

`AI Tools` `Cost Savings` `SaaS Business` `Indie Development`

### [The Cost-Effective Guide to Using Open Code Review for AI Programming Tools](articles/the-cost-effective-guide-to-using-open-code-review-for-ai.md)

Open Code Review is an open-source review tool built for AI-assisted development, and in benchmark tests spanning 200 real pull requests across 50 open-source repositories it scored higher on both…

`Code Review` `Cost Savings` `SaaS Business` `Automation Systems`

### [The First Line of Defense in AI Programming: Environment Variable Management](articles/the-first-line-of-defense-in-ai-programming-environment.md)

MonkeyCode ships with 900 million free tokens and supports private deployment, which tells you exactly what its users are doing: pointing an AI coding tool at their own keys, on their own infrastru…

`AI Development` `AI Programming` `Environment Variables` `AI Security`

### [The Hidden Costs of GPT-5.6 Model Selection: A Developer's Real-World Guide](articles/the-hidden-costs-of-gpt-5-6-model-selection-a-developer-s.md)

"Choosing the right GPT-5.6 model for your business is more about avoiding cost overruns than just picking the cheapest option."

`AI Implementation` `AI Costs` `AI Programming` `Cost Savings`

### [The Klarna Lesson: Why AI Implementation Needs a Staircase, Not a Leap](articles/the-klarna-lesson-why-ai-implementation-needs-a-staircase.md)

Klarna's AI customer service experiment, which replaced 700 human agents, initially saved $40 million in a year, but the quality of service suffered so badly that they had to rehire humans, leading…

`Artificial Intelligence` `AI Systems` `Automation Systems` `Enterprise Automation`

### [Token Optimization for Indie Developers' AI API Bills](articles/token-optimization-for-indie-developers-ai-api-bills.md)

In July 2026, while indie developers building AI coding products full-time watched their API burn rate climb toward their revenue, a quieter shift in the Chinese developer stack showed a different…

`AI Costs` `Token Optimization` `SaaS Business` `Chinese AI`

### [When AI Customer Service Backfired: Klarna’s Case and the Four-Stage Path to Enterprise AI Adoption](articles/when-ai-customer-service-backfired-klarna-s-case-and-the.md)

Klarna reported $4 million a year in savings and a 99.96 percent conversation engagement rate, the kind of pair of numbers that ends an internal debate before it starts.

`AI Implementation` `AI Costs` `Niche Market` `Profitable Business`

### [Why Pi's 1000-Token Agent Engine Needs a Sandbox Before You Touch It](articles/why-pi-s-1000-token-agent-engine-needs-a-sandbox-before-you.md)

Pi's system prompt and its 4 tool descriptions come to under 1,000 tokens, which is the whole reason to like it.

`Security` `AI Programming` `Indie Development` `Sandbox`

### [Why Your Indie App Needs Short-Form Video Marketing (And How to Get Started)](articles/why-your-indie-app-needs-short-form-video-marketing-and-how.md)

The videos run about 60 seconds.

`Productivity` `Content Creation` `Indie Development` `Short Form Video`

## Related

- [free-llm-api](https://github.com/xyzs996/free-llm-api) — verified free LLM API tiers, rate limits, and no-card options.

## Reuse

Copyright © 2026 xyzs996. Everything here — the write-ups in
`articles/` and the dataset in `data/` alike — is licensed
[CC BY 4.0](LICENSE): copy it, republish it, build on it, sell it.

One condition: say where it came from. A link back to
<https://xyzs996.github.io/ai-coding-field-notes/> next to whatever you reuse is enough.
