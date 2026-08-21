# Cuánto cuestan de verdad los agentes de código con IA: 335 cifras, cada una con su frase y su fecha

[English](./README.md) · [中文](./README_CN.md) · **Español** · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Tiếng Việt](./README_VI.md) · [Français](./README_FR.md) · [Deutsch](./README_DE.md) · [Русский](./README_RU.md) · [Bahasa Indonesia](./README_ID.md)

[![figures](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Ffigures.json)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/figures.md) [![writeups](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fwriteups.json)](https://xyzs996.github.io/ai-coding-field-notes/) [![updated](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fxyzs996%2Fai-coding-field-notes%40main%2Fdata%2Fbadges%2Fupdated.json)](https://github.com/xyzs996/ai-coding-field-notes/releases) [![license](https://img.shields.io/badge/data-CC%20BY%204.0-blue)](https://github.com/xyzs996/ai-coding-field-notes/blob/main/LICENSE)

Un conjunto de datos abierto. Cada cifra publicada en 32 notas de campo — precios, porcentajes, múltiplos, recuentos de tokens y duraciones — extraída a una fila, **con la frase completa de la que salió y la fecha de publicación**.

## Las cifras primero

Las líneas siguientes están **en inglés, copiadas tal cual**, sin traducir: una cifra sin su frase no se puede verificar — `$1.43` podría ser por millón de tokens, por mes o por puesto.

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

[Las 335 filas](figures.md)

```
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.json
curl -s https://cdn.jsdelivr.net/gh/xyzs996/ai-coding-field-notes@main/data/figures.csv
```

El campo `published` es el día en que salió esa nota, **no el día en que ese precio estaba vigente**. Los precios cambian: lea cada fila según su propia fecha.

## Los textos

Los textos están **en inglés**, aquí: https://xyzs996.github.io/ai-coding-field-notes/ — con la tabla de cifras, las páginas por tema y las páginas por proveedor. Si solo quiere los datos, los dos `curl` de arriba bastan.

## Diga algo

- **Marque el repositorio con una estrella** para seguir las actualizaciones. Los datos son CC BY: la estrella no cambia nada de lo que puede hacer con ellos.
- **¿Una cifra está mal?** Si un precio cambió o usted midió otra cosa, abra un issue. Para eso existe este repositorio. ([issue](https://github.com/xyzs996/ai-coding-field-notes/issues/new?template=correction.yml))
- **¿Falta una cifra?** Diga qué métrica, qué proveedor y en qué unidad, en una línea — el formulario tiene un solo campo obligatorio y las peticiones se convierten en filas. ([form](https://github.com/xyzs996/ai-coding-field-notes/issues/new?template=figure.yml))

---

CC BY 4.0: copie, republique, derive o venda. Una sola condición: diga de dónde salió, con un enlace a https://xyzs996.github.io/ai-coding-field-notes/.
