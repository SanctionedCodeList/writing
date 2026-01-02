# Writing Skill

**Research-backed writing guidance for professional documents.**

A Claude Code plugin that provides style guides, cognitive fluency techniques, structure frameworks, and revision checklists for legal, academic, and executive writing.

---

## 🚀 Installation

### Option 1: Via SCL Marketplace (Recommended)

Install all SCL plugins at once:

```bash
claude plugins add SanctionedCodeList/SCL_marketplace
```

### Option 2: Standalone Installation

```bash
claude plugins add SanctionedCodeList/writing
```

### Verify Installation

```bash
claude plugins list
# Should show: writing
```

### Try It Out

Start Claude Code and ask:

```
> Help me write a persuasive brief introduction for a patent case
```

Claude will automatically apply persuasive writing techniques from the skill.

---

## What It Does

This skill activates automatically when you're writing professional documents. It provides:

| Category | What You Get |
|----------|--------------|
| **Style Guides** | Six context-specific guides (academic, persuasive, objective, client-facing, transactional, executive) |
| **Techniques** | Cognitive fluency, concise writing, compelling narratives, structure frameworks |
| **Anti-patterns** | AI writing tells to avoid |
| **Revision** | Multi-pass editing checklist |

---

## Style Guides

| Style | Use Case | Key Traits |
|-------|----------|------------|
| **Academic** | Law review articles, scholarly publications | Thesis-driven, heavily cited, nuanced |
| **Persuasive** | Briefs, motions, advocacy | Lead with strength, control narrative, anticipate objections |
| **Objective** | Memos, neutral analysis | Balanced, thorough, clear recommendations |
| **Client-facing** | Client letters, advice | Accessible, actionable, appropriate detail |
| **Transactional** | Contracts, deal documents | Precise, unambiguous, commercially reasonable |
| **Executive** | Reports, presentations, decks | Pyramid structure, lead with answer, visual hierarchy |

---

## Key Principles

### 1. Cognitive Fluency
Easy-to-read text is judged more true, credible, and persuasive. The brain uses processing ease as a truth heuristic.

### 2. Lead with the Answer
State conclusions first, then support. Readers shouldn't have to hunt for your point.

### 3. Cut Ruthlessly
Every word must earn its place. Eliminate throat-clearing, hedging, and redundancy.

### 4. Match Style to Context
Academic differs from advocacy differs from transactional. Use the right register.

---

## Research Foundation

Techniques are grounded in empirical studies:

| Research | Finding |
|----------|---------|
| **Oppenheimer (2006)** | Complex vocabulary reduces perceived intelligence |
| **Schwarz et al.** | Processing fluency serves as truth heuristic |
| **Martinez et al. (2023)** | Even lawyers prefer plain English; recall improved 12%+ |
| **Supreme Court study** | Minimal emotional language increases win rates (29-100%) |
| **Chestek study** | 78.6% of practitioners prefer "story briefs" over pure logos |

---

## Skill Structure

```
skills/writing/
├── SKILL.md                 # Core principles and style selector
├── techniques/              # How to write effectively
│   ├── cognitive-fluency.md
│   ├── concise-writing.md
│   ├── compelling-writing.md
│   ├── structure-frameworks.md
│   ├── ai-antipatterns.md
│   └── revision-checklist.md
├── styles/                  # Context-specific conventions
│   ├── academic.md
│   ├── persuasive.md
│   ├── objective.md
│   ├── client-facing.md
│   ├── transactional.md
│   └── executive.md
└── references/              # Supporting material
    ├── authorities/
    ├── research/
    └── exemplars/
```

---

## Troubleshooting

| Problem | Solution |
|---------|----------|
| Skill not activating | Restart Claude Code after installation |
| Wrong style applied | Explicitly mention the document type in your prompt |
| Too verbose output | Ask Claude to "be concise" or "cut ruthlessly" |

---

## Links

- [GitHub](https://github.com/SanctionedCodeList/writing)
- [SCL Marketplace](https://github.com/SanctionedCodeList/SCL_marketplace)
