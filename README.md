# Decision Stack

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) for building your [Decision Stack](https://thedecisionstack.com) — the strategic alignment framework by Martin Eriksson and Jonny Schneider.

## What is a Decision Stack?

A Decision Stack structures strategic thinking into five layers:

**Vision** → **Strategy** → **Objectives** → **Principles** → **Opportunities**

Each layer builds on the one above, creating a coherent thread from aspiration to action. Teams that share a Decision Stack can make autonomous decisions that stay aligned.

## What this skill does

This skill helps you prepare the strategic context needed to build your Decision Stack. It works as a guided extraction assistant — organising your existing documents, thinking, and data into a structured bundle.

**Four modes:**
- **Context dump** — share your docs, get organised themes back
- **Strategic exploration** — guided Socratic questioning across 10 strategic areas
- **Focused deep-dive** — go deep on one specific area
- **Gap analysis** — see what's covered and what's missing

**Output:** A structured JSON context bundle you can import into [Lunastak](https://app.lunastak.io) to generate your full Decision Stack.

## Installation

```bash
npx claude-code-skill install jonnyschneider/decision-stack
```

Or manually:

```bash
git clone https://github.com/jonnyschneider/decision-stack.git ~/Dev/decision-stack
ln -s ~/Dev/decision-stack ~/.claude/skills/decision-stack
```

## Usage

In Claude Code:

```
/decision-stack
```

Or just start talking about your strategy:

> "I want to build my Decision Stack. I have a pitch deck and some strategy notes."

## Generate your Decision Stack

This skill prepares the context. To generate your full Decision Stack (Vision, Strategy, Objectives, Principles, Opportunities), import the context bundle into [Lunastak](https://app.lunastak.io).

## About

The Decision Stack framework is from [The Decision Stack](https://thedecisionstack.com) by Martin Eriksson. [Lunastak](https://lunastak.io) is an AI strategy coach that helps leaders build and maintain their Decision Stack.

Built by [Jonny Schneider](https://github.com/jonnyschneider).

## License

MIT
