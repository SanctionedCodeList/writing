# Writing Skill

A Claude Code plugin providing comprehensive writing guidance for professional documents.

## Installation

Add to your Claude Code plugins:

```bash
claude plugins add SanctionedCodeList/writing
```

Or via the SCL marketplace (includes law-tools, office-bridge, and more):

```bash
claude plugins add SanctionedCodeList/SCL_marketplace
```

**Local installation:**

```bash
git clone https://github.com/SanctionedCodeList/writing.git
claude plugins add ./writing
```

## What It Does

This skill provides style guides, cognitive fluency techniques, structure frameworks, and revision checklists for:

- **Legal writing** — briefs, memos, contracts, client letters
- **Academic writing** — law review articles, scholarly publications
- **Executive writing** — reports, decks, business documents

## Structure

```
skills/writing/
├── SKILL.md                 # Core principles and style selector
├── techniques/              # How to write effectively
│   ├── cognitive-fluency.md    # Processing ease = perceived truth
│   ├── concise-writing.md      # Cut words ruthlessly
│   ├── compelling-writing.md   # Narrative and engagement
│   ├── structure-frameworks.md # Pyramid, SCQA, IRAC
│   ├── ai-antipatterns.md      # Avoid AI writing tells
│   └── revision-checklist.md   # Multi-pass editing
├── styles/                  # Context-specific conventions
│   ├── academic.md             # Law review, scholarly
│   ├── persuasive.md           # Briefs, motions
│   ├── objective.md            # Memos, neutral analysis
│   ├── client-facing.md        # Client letters, advice
│   ├── transactional.md        # Contracts, deal documents
│   └── executive.md            # Reports, decks
└── references/              # Supporting material
    ├── authorities/            # Book and authority summaries
    ├── research/               # Empirical studies
    └── exemplars/              # Model document techniques
```

## Key Principles

1. **Cognitive fluency** — Easy-to-read text is judged more true, credible, and persuasive
2. **Lead with the answer** — State conclusions first, then support
3. **Cut ruthlessly** — Every word must earn its place
4. **Match style to context** — Academic differs from advocacy differs from transactional

## Research Foundation

Techniques are grounded in empirical research:

- **Oppenheimer (2006)** — Complex vocabulary reduces perceived intelligence
- **Schwarz et al.** — Processing fluency as truth heuristic
- **Martinez et al. (2023)** — Even lawyers prefer plain English
- **Supreme Court study** — Minimal emotional language increases win rates