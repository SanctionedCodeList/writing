# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Claude Code skill (plugin) providing research-backed writing guidance for professional documents. It teaches cognitive fluency techniques, style conventions, structure frameworks, and revision processes across legal, academic, executive, and business contexts.

**Type:** Documentation-only plugin (no build/test/lint commands)
**Distribution:** SCL Marketplace or direct GitHub installation

## Repository Structure

```
skills/writing/
├── SKILL.md                 # Core principles, style selector, universal rules
├── techniques/              # Cross-cutting methods (fluency, concision, structure)
├── styles/                  # Context-specific guides (persuasive, academic, etc.)
└── references/              # Research backing, authorities, exemplars
```

**SKILL.md** is the hub. Techniques apply universally. Styles activate based on document type.

## Editing Guidelines

### Match the Project's Standards

This project teaches good writing. Contributions must demonstrate it:
- Lead with the point
- Use active voice
- Cut unnecessary words
- Keep sentences under 20 words
- Ground advice in research or concrete examples

### Research-Backed Content

New techniques or principles require empirical support. Cite studies, authorities, or documented best practices. See `references/` for the existing research base.

### Structural Hierarchy

1. **Universal principles** (SKILL.md) — apply to all documents
2. **Techniques** — tactical methods (concision, fluency, structure)
3. **Styles** — context-specific conventions
4. **References** — supporting research and exemplars

New content should fit this hierarchy. Don't duplicate guidance across levels.

### AI Antipatterns

Avoid the tells listed in `techniques/ai-antipatterns.md`:
- Overused words: "delve," "tapestry," "multifaceted," "nuanced," "landscape"
- Structural tells: "Moreover" chains, numbered lists for everything
- Empty phrases: "It's important to note that," "in today's world"

## Plugin Files

```
.claude-plugin/
├── plugin.json              # Metadata (name, version, author)
└── marketplace.json         # SCL marketplace configuration
```

Update version in `plugin.json` when releasing changes.

## Issue Reporting

```bash
gh issue create --repo SanctionedCodeList/writing --title "Bug: [description]"
gh issue create --repo SanctionedCodeList/writing --title "Feature: [description]"
gh issue list --repo SanctionedCodeList/writing
```
