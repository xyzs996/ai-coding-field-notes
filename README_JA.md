# AI コーディングエージェントの実際の料金:335 行、どの行にも出典の一文と日付つき

[English](./README.md) · [中文](./README_CN.md) · [Español](./README_ES.md) · **日本語** · [한국어](./README_KO.md) · [Tiếng Việt](./README_VI.md) · [Français](./README_FR.md) · [Deutsch](./README_DE.md) · [Русский](./README_RU.md) · [Bahasa Indonesia](./README_ID.md)

[![figures](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Ffigures.json)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/figures.md) [![writeups](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fwriteups.json)](https://xyzs996.github.io/ai-coding-field-notes/) [![updated](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fupdated.json)](https://github.com/xyzs996/ai-coding-field-notes/releases) [![license](https://img.shields.io/badge/data-CC%20BY%204.0-blue)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/LICENSE)

オープンなデータセットです。32 本の実測ノートに出てきた数字 —— 料金、割合、倍率、トークン数、所要時間 —— をすべて 1 行ずつに抜き出し、**元の一文と公開日を必ず添えて**あります。

## エージェント向けモデルの今日の値段

Design Arena の *agents* 部門で順位のついた 60 モデルの、100 万トークンあたりの**定価**です。請求額ではありません — キャッシュ、バッチ、提供元ごとに価格は違います。OpenRouter の公開カタログより、最終取得日 2026-08-22。安い順に 3 つ:

| $ in / 1M | $ out / 1M | Model | Best agents rank |
| --- | --- | --- | --- |
| $0.1875 | $0.9375 | Gemini 3.7 Flash `batch` | #3 androidnative |
| $0.25 | $1.50 | Gemini 3 Flash Preview `batch` | #9 agenticslides |
| $0.30 | $1.20 | MiniMax M3 | #10 python-pptxslides |

[60 モデル全部](prices.md) · [JSON](https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/prices.json) · [CSV](https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/prices.csv)

## まず数字から

以下の行は**英語の原文そのまま**で、翻訳していません。数字は元の一文から切り離すと検証できないからです —— `$1.43` が 100 万トークンあたりなのか、月額なのか、1 席あたりなのかは、その一文にしか書かれていません。

| Figure | The sentence it came from | Write-up |
| --- | --- | --- |
| `$1.43` | The $1.43 and the $9.05 are both frontier models doing a job they were not specifically built for. | [The Two Best AI Code Reviewers Score the Same. One Costs $1.43 a Run, the Other $9.05.](articles/the-two-best-ai-code-reviewers-score-the-same-one-costs-1.md) |
| `$29` | Before writing a contract-comparison tool, one builder handled three to ten comparisons by hand at $29 a document, and only turned the routine into software once the same people kept coming back and paying for it. | [Debunking the Myth of Overnight Success in Micro-SaaS](articles/debunking-the-myth-of-overnight-success-in-micro-saas.md) |
| `90%` | 90% of developers still rely on manual prompt writing, while top performers use Skill Package to automate 80% of repetitive tasks, saving hours weekly. | [Best Practices for AI Agent Skill Management](articles/best-practices-for-ai-agent-skill-management.md) |
| `80%` | When the Claude Code team decided to slash 80% of their system prompts, most developers expected the model to lose its edge in complex engineering tasks. | [Why Stripping 80% of System Prompts Actually Improved Claude Code's Performance](articles/why-stripping-80-of-system-prompts-actually-improved-claude.md) |
| `$30` | With a budget as low as $30 per day, developers have reached an effective lead cost of $3 to $4. | [Stop Reading SimilarWeb Like a Traffic Dashboard — Read It Like a Feasibility Test](articles/stop-reading-similarweb-like-a-traffic-dashboard-read-it.md) |
| `$1,000` | Instead of chasing a 2.5% consumer conversion rate across unpredictable social channels, you sell a single $1,000 to $5,000 service package directly to one business owner — no massive ad campaigns, no hundreds of low-tier support tickets. | [How Indie Developers Are Building AI-Powered "Digital Landlords" and Renting Them Out for Monthly Cash Flow](articles/how-indie-developers-are-building-ai-powered-digital.md) |
| `40-second` | When an independent developer uses Agency Agents to set up a 40-second response cycle for e-commerce listings, they are building a feedback loop that reads market conditions and adjusts, which is what separates a timed automation from a script on a timer. | [Stop Chatting With AI: How I Use /loop and /hook to Automate My Indie Dev Workflow](articles/stop-chatting-with-ai-how-i-use-loop-and-hook-to-automate.md) |
| `9.1%` | One reported case moved entry-group conversion from 9.1% to 55.1% by rebuilding an automated onboarding flow around what the funnel data actually showed, rather than around what the team assumed users were doing. | [Boosting AI Bot Conversion: A Deep Dive into Funnel Data](articles/boosting-ai-bot-conversion-a-deep-dive-into-funnel-data.md) |
| `$1.25` | Meta priced Muse Spark 1.1 at $1.25 per million input and $4.25 per million output, roughly 75% and 83% below Anthropic's Opus, and the tradeoff is visible in the benchmarks, since it leads on MCP Atlas and JobBench while trailing on SWE-Bench Pro and DeepSWE 1.1. | [1.6 Billion Free Tokens Is a Compression Ratio, Not a Strategy](articles/1-6-billion-free-tokens-is-a-compression-ratio-not-a.md) |
| `9x` | Open Code Review reports roughly 9x lower token consumption than general-purpose agents while holding accuracy, which suggests that a specialized agent aimed at one job often beats a heavy generalist on the only axis an indie developer can afford to optimize. | [Token Optimization for Indie Developers' AI API Bills](articles/token-optimization-for-indie-developers-ai-api-bills.md) |
| `87 percent` | The 87 percent figure and those two cases are measuring the same thing from different angles, which is time spent moving data by hand between a system that knows the answer and a system that needs it. | [The 5 AI Features That Separated 27 Profitable Solopreneurs From the Rest](articles/the-5-ai-features-that-separated-27-profitable-solopreneurs.md) |
| `40 seconds` | By using an AI agent to automate responses, negotiation, and price adjustment, the average response time can be reduced to within 40 seconds. | [From AI Demo to Product: Loop Engineering for Indie Devs](articles/from-ai-demo-to-product-loop-engineering-for-indie-devs.md) |

[全 335 行](figures.md)

```
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.json
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.csv
```

`published` はそのノートを公開した日で、**その料金が有効だった日ではありません**。料金は動きます。各行はその行自身の日付で読んでください。

## 本文

本文は**英語**です:https://xyzs996.github.io/ai-coding-field-notes/ —— 数値表、トピック別ページ、ベンダー別ページがあります。数字だけでよければ、上の `curl` 二本で足ります。

## ひとこと

- **このリポジトリにスターを**付けると更新を追えます。データは CC BY なので、スターの有無でできることは変わりません。
- **数字が違う?** 料金が変わった、自分で測ったら別の数字になった —— issue を立ててください。このリポジトリはそのためにあります。 ([issue](https://github.com/xyzs996/ai-coding-field-notes/issues/new?template=correction.yml))
- **欲しい数字がない?** どの指標を、どのベンダーの、どの単位で —— 一行で結構です。必須項目は一つだけ、届いたものは新しい行になります。 ([form](https://github.com/xyzs996/ai-coding-field-notes/issues/new?template=figure.yml))

---

CC BY 4.0:複製・再公開・加工・販売、自由です。条件は一つだけ、出典を示すこと。https://xyzs996.github.io/ai-coding-field-notes/ へのリンクで十分です。
