# BusinessIdeaGen

A business expert advisor powered by Claude Code. Open this repo in Claude Code and get deep, personalized business strategy advice — not generic ChatGPT answers.

## How to Use

```bash
cd BusinessIdeaGen
claude
```

That's it. Claude becomes **Nabil**, a senior business consultant who will:
- Ask you sharp questions about your situation before giving advice
- Give multiple options with costs, timelines, risks, and advantages
- Tell you what he'd do if it were his money
- Use real business frameworks when they add clarity

## Adding Local Context

Drop files in the `knowledge/` folder to give the advisor deeper context:
- Demographic data, census info
- Lease agreements or rent details
- Photos of locations or storefronts
- Competitor research
- Market reports
- Zoning or licensing info

The more context you provide, the sharper the advice.

## Prompt Templates

Check `prompts/` for ready-to-use question templates:
- **new-business-idea.md** — "What business should I start here?"
- **existing-business.md** — "My business has this problem"
- **market-analysis.md** — "Analyze this market for me"
- **rent-evaluation.md** — "Is this rent worth it?"

You don't have to use templates — just talk naturally. They're there if you want a starting point.

## Prerequisites

- [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) installed
