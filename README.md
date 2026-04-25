# How to Solve It

A Socratic problem-solving skill for AI agents, based on George Pólya's *How to Solve It* framework.

When users ask how to solve a problem, analyze a question, or work through something step by step, this skill activates and guides them via Socratic questioning — rather than giving answers directly.

## How It Works

The skill follows Pólya's four-step method:

```
1. Understand the Problem    → What is unknown? What is given?
2. Devise a Plan            → What connects knowns to unknowns?
3. Carry Out the Plan       → Execute and verify each step
4. Review and Extend        → Check the answer; generalize
```

At each step, the AI asks one targeted question based on the user's response. The user arrives at their own answer.

## Two Modes

- **Math mode** — activated when the problem contains numbers, equations, symbols, or geometric figures
- **General mode** — for planning, diagnosis, decision-making, and other non-mathematical problems

The AI detects the mode automatically (or follows the user's stated context).

## When to Use

Trigger phrases:
- "How do I solve this?"
- "Help me analyze this question"
- "I don't know where to start"
- "What's the approach?"
- "Work through this with me"

## Files

```
SKILL.md                — Main skill definition
references/
  heuristics.md         — Categorized Socratic prompts for stuck moments
```

## Background

This is a direct translation and adaptation of the Chinese-language skill [怎样解题](https://clawhub.ai/fanxlab/polya-problem-solving), also published on [ClawHub](https://clawhub.ai/fanxlab/polya-problem-solving).

The framework is derived from George Pólya's classic 1945 book *How to Solve It*, a foundational text in mathematics education and problem-solving pedagogy.

## License

MIT — free to use, modify, and redistribute. No attribution required.
