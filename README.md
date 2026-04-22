# paper-storyteller

Turn your ML/CV/NLP paper from a dry tech report into a narrative that reads like Wu, Efros, and Isola wrote it.

A [Claude Code](https://claude.ai/claude-code) skill that guides you through a 3-phase workflow — Brainstorm, Write, Polish — to produce papers with story arcs, cross-disciplinary metaphors, and the question-driven structure that top venues reward.

## When to Use

- Drafting or revising any paper section (abstract, intro, related work, method, experiments, conclusion)
- Your intro starts with "Recent advances in X..." and you know it needs a hook
- The paper reads like a tech report — correct structure, but no story
- You have strong results but struggle to articulate *why* they matter
- You want a Socratic brainstorm partner to extract the narrative before you start writing

## Usage

```
/paper-storyteller
```

Works on the current paper in your project. The skill reads existing sections and walks you through improving narrative quality, one phase at a time.

## How it works

1. **Brainstorm** — A Socratic dialogue (Q&A in Chinese or English) extracts the paper's core story: what gap exists, what insight you found, and a cross-disciplinary metaphor that ties it together. Outputs a confirmed Story Outline.
2. **Write** — Section-by-section drafting using dedicated section guides (intro, method, related work, etc.) and the style principles of narrative-driven academic writing. Each paragraph maps back to the Story Outline.
3. **Polish** — An automatic style checklist flags weak openings, inconsistent metaphors, missing story-arc elements, and common anti-patterns. Provides concrete revision suggestions.

## Install

### Via skills.sh (recommended)

```bash
npx skills add freemty/paper-storyteller
```

Works with Claude Code, Cursor, Codex, Windsurf, and [15+ other agents](https://skills.sh).

### Manual

```bash
git clone https://github.com/freemty/paper-storyteller.git ~/.claude/skills/paper-storyteller
```

## License

MIT
