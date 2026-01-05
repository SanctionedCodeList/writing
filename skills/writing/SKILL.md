---
name: writing
description: |
  Comprehensive writing guidance for professional documents across legal, academic, executive, and business contexts. Use when drafting, editing, or revising any document where quality prose matters: briefs, memos, law review articles, reports, client letters, contracts, executive summaries, presentations. Provides style selection, cognitive fluency techniques, structure frameworks, concision patterns, and revision checklists. Invoke when users ask to write, edit, revise, or improve documents.
---

# Writing

This skill provides guidance on what makes writing effective across professional contexts. It covers principles, techniques, and forum-specific conventions.

## Universal Principles

These apply regardless of document type:

### Lead with the Point

State conclusions before support. Readers shouldn't hunt for your argument.

| Buried | Direct |
|--------|--------|
| "After reviewing the evidence and considering the factors..." | "The contract is enforceable. Three factors support this conclusion..." |

### Active Voice, Concrete Subjects

Identify actors. Assign responsibility. Avoid abstraction.

| Passive/Abstract | Active/Concrete |
|------------------|-----------------|
| "The order was vacated" | "The FTC vacated the order" |
| "A determination was made" | "The court determined" |
| "The regulatory framework imposes obligations" | "The Colorado AI Act requires deployers to conduct impact assessments" |

### One Idea Per Sentence

Don't cram. If you need a comma followed by "and," consider splitting.

### Cut Ruthlessly

Every word must earn its place. See [techniques/concise-writing.md](techniques/concise-writing.md) for patterns.

### Match Formality to Audience

Academic writing is formal but accessible. Client letters are direct but professional. Briefs are precise but readable. Know your reader.

### Consistent Terminology

Use the same term for the same concept throughout. Variation for its own sake confuses readers and undermines the illusory truth effect.

## Style Selection

Load the appropriate style based on what you're writing:

| Document Type | Style Guide |
|---------------|-------------|
| Law review article, scholarly publication | [styles/academic.md](styles/academic.md) |
| Brief, motion, advocacy document | [styles/persuasive.md](styles/persuasive.md) |
| Legal memo, analysis, neutral assessment | [styles/objective.md](styles/objective.md) |
| Client letter, advice, communication | [styles/client-facing.md](styles/client-facing.md) |
| Contract, deal document, agreement | [styles/transactional.md](styles/transactional.md) |
| Executive report, deck, business document | [styles/executive.md](styles/executive.md) |
| Expert witness report, damages analysis, technical opinion | [styles/expert-report.md](styles/expert-report.md) |

## Quick Reference

### Sentence Length

| Length | Comprehension |
|--------|---------------|
| 8 words | ~100% |
| 14 words | ~90% |
| 20 words | Target average |
| 43+ words | Below 10% |

Vary length for rhythm. Don't let multiple consecutive sentences exceed 30 words.

### Paragraph Structure

- **Topic sentence first**: Every paragraph answers "what is this about?" in sentence one
- **One theme per paragraph**: New topic = new paragraph
- **Length**: 3-5 sentences (general), 5-8 sentences (academic/complex)

### Voice Ratio

Target 80-85% active voice. Reserve passive for:
- Unknown actors
- Deliberate emphasis on the object
- Strategic obscuring of agency (use sparingly)

### Information Flow (Given-New Contract)

Start sentences with known information; end with new information. This matches how the brain builds understanding.

| Violates | Follows |
|----------|---------|
| "Novel approaches are needed. The EU AI Act represents one." | "The EU AI Act represents a novel approach. This approach differs from U.S. regulation in three ways." |

### The Speakability Test

Read aloud. If you stumble, readers will too.

## Cross-Cutting Techniques

These techniques apply across all styles:

| Technique | File | Purpose |
|-----------|------|---------|
| Cognitive Fluency | [techniques/cognitive-fluency.md](techniques/cognitive-fluency.md) | Make prose easier to process (and more persuasive) |
| Concise Writing | [techniques/concise-writing.md](techniques/concise-writing.md) | Cut words without losing meaning |
| Compelling Writing | [techniques/compelling-writing.md](techniques/compelling-writing.md) | Engage readers through narrative and structure |
| Structure Frameworks | [techniques/structure-frameworks.md](techniques/structure-frameworks.md) | Organize documents persuasively (Pyramid, IRAC, SCQA) |
| AI Antipatterns | [techniques/ai-antipatterns.md](techniques/ai-antipatterns.md) | Avoid tells that signal AI-generated text |
| Revision Checklist | [techniques/revision-checklist.md](techniques/revision-checklist.md) | Multi-pass editing process |

## Revision Process

Before finalizing any document:

1. **Structure pass**: Does organization serve the argument?
2. **Credibility pass**: Any overstatements, omissions, or attacks?
3. **Prose pass**: Active voice, plain language, no throat-clearing?
4. **Fluency pass**: Given-new contract, concrete language, sentence variety?
5. **Final read**: Read aloud; fix stumbles

See [techniques/revision-checklist.md](techniques/revision-checklist.md) for detailed checklist.

## Common Errors

### Words to Cut

| Cut | Reason |
|-----|--------|
| "it is important to note that" | If important, readers will notice |
| "clearly" / "obviously" | If clear, don't announce it |
| "in order to" | "to" works |
| "the fact that" | Usually deletable |
| "basically" / "actually" / "very" | Filler |

### Nominalizations to Fix

| Weak (Noun) | Strong (Verb) |
|-------------|---------------|
| make a determination | determine |
| conduct an investigation | investigate |
| give consideration to | consider |
| reach a conclusion | conclude |

Search for "-tion," "-ment," "-ity" endings and convert to verbs.

### AI Tells to Avoid

- "delve," "tapestry," "multifaceted," "pivotal," "realm," "landscape"
- "Moreover," "Furthermore," "Additionally" chains
- Formulaic openings ("In today's world...")
- Triplet structures without purpose
- Em dash overuse

See [techniques/ai-antipatterns.md](techniques/ai-antipatterns.md) for full list.

## Deep References

For research backing and detailed guidance:

- **references/authorities/**: Summaries of Garner, Volokh, and other writing authorities
- **references/research/**: Empirical studies on persuasion, fluency, judicial psychology
- **references/exemplars/**: Model document analyses

## Reporting Issues

If you encounter bugs, unexpected behavior, or want to request new features, use the GitHub CLI:

```bash
# Report a bug
gh issue create --repo SanctionedCodeList/writing --title "Bug: [description]" --body "## Problem\n[Describe the issue]\n\n## Expected behavior\n[What should happen]\n\n## Steps to reproduce\n[How to trigger it]"

# Request a feature
gh issue create --repo SanctionedCodeList/writing --title "Feature: [description]" --body "## Use case\n[Why this is needed]\n\n## Proposed solution\n[How it might work]"

# Check existing issues first
gh issue list --repo SanctionedCodeList/writing
```

This helps improve the skill for all users.
