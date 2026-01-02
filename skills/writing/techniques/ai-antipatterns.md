# AI Writing Antipatterns

AI-generated text displays identifiable patterns that undermine credibility. This guide catalogs tells to avoid and edit out.

## High-Alert Vocabulary

These words have seen dramatic usage increases since 2022. One may be coincidental; clusters are red flags.

### Tier 1: Immediate Red Flags

| Word | Alternative |
|------|-------------|
| **delve** | examine, explore, look at, investigate |
| **tapestry** | combination, mix, array, collection |
| **multifaceted** | complex, varied, diverse |
| **pivotal** | important, key, significant |
| **realm** | area, field, domain, space |
| **landscape** | environment, situation, context |

### Tier 2: Strong Indicators

| Word | Alternative |
|------|-------------|
| **nuanced** | subtle, detailed, careful |
| **intricate** | detailed, complex, elaborate |
| **meticulous** | careful, thorough, precise |
| **crucial/vital** | important, necessary, essential |
| **embark** | start, begin, launch |
| **showcasing** | showing, demonstrating |
| **underscores** | highlights, emphasizes, shows |
| **comprehensive** | complete, thorough, full |
| **cutting-edge** | new, modern, advanced |
| **revolutionary** | new, significant, major |
| **testament** | proof, evidence, example |

### Tier 3: Moderate Indicators (In Clusters)

| Category | Words |
|----------|-------|
| Verbs | foster, leverage, utilize, navigate, unpack |
| Adjectives | robust, seamless, holistic, dynamic, innovative |
| Nouns | synergy, paradigm, framework, ecosystem |

---

## Structural Patterns

### The Negation Structure ("It's Not X, It's Y")

**Avoid:**
- "X isn't just about Y"
- "X is more than just Y"
- "It's not merely X, it's Y"

**Bad:** "Teams who thrive aren't just using AI for speed. They're combining it with judgment."

**Good:** "Thriving teams combine AI speed with human judgment."

### The Rule of Three (Triplets)

AI defaults to tricolon as a rhetorical device:

**Obvious AI:**
- "I honed my skills in research, collaboration, and problem-solving"
- "This approach is efficient, effective, and economical"

**Fixes:**
- Remove one item
- Combine two items
- Add significantly more items
- Restructure as prose

### Formulaic Openings

| Avoid | Fix |
|-------|-----|
| "In today's ever-evolving world..." | Delete; start with your point |
| "In the realm of..." | "In [topic]..." or start with topic |
| "When it comes to..." | Delete; state topic directly |
| "It's important to note that..." | Delete; just state it |
| "As we navigate the complexities of..." | Delete entirely |

### Formulaic Closings

| Avoid | Fix |
|-------|-----|
| "In conclusion..." | Often unnecessary; delete |
| "In summary..." | Often unnecessary; delete |
| "In essence..." | Delete; restate key point if needed |
| "Overall..." | Delete or be specific |

### Section-Ending Summaries

AI adds redundant summaries at section ends. Professional documents don't restate what was just said—move directly to next section.

---

## Transition Word Overuse

AI overuses formal academic transitions that create choppy, predictable flow.

| Transition | Alternative |
|------------|-------------|
| **Moreover** | Also, And, [new sentence] |
| **Furthermore** | Also, And, [restructure] |
| **Additionally** | Also, And, [new sentence] |
| **Consequently** | So, Therefore, As a result |
| **Subsequently** | Then, Next, After that |
| **Interestingly** | Delete; let content speak |
| **Notably** | Delete or integrate naturally |

**AI pattern:**
> "The market grew 15%. Moreover, spending increased. Furthermore, inventory stabilized. Additionally, margins improved."

**Human pattern:**
> "The market grew 15%, driven by increased spending. Inventory stabilized, and margins improved."

**Fix strategy:**
1. Delete unnecessary transitions
2. Combine short sentences
3. Use "and," "but," "so" instead of formal alternatives
4. Let paragraph breaks do transition work

---

## Empty Significance Markers

Phrases that inflate importance without adding substance.

| Phrase | Problem |
|--------|---------|
| "stands as a testament to..." | Empty significance |
| "plays a vital/crucial/pivotal role" | Inflated importance |
| "underscores its importance" | Tell, don't underscore |
| "significant impact on..." | Usually meaningless |
| "demonstrates the importance of..." | Show it instead |

### The "-ing" Clause Pattern

AI attaches present participle phrases for superficial analysis:

**Bad:** "The company expanded into three markets, underscoring its commitment to growth."

**Good:** "The company expanded into three markets." Or: "The company expanded into three markets as part of a five-year growth initiative."

### Editorial Commentary to Delete

- "It's important to note that..."
- "It is worth mentioning..."
- "No discussion would be complete without..."
- "One cannot overstate..."
- "It goes without saying..."

---

## Tone and Style Issues

### Excessive Formality

| Overly Formal | Natural |
|---------------|---------|
| utilize | use |
| facilitate | help |
| implement | do, start |
| endeavor | try |
| commence | begin, start |
| terminate | end |
| prior to | before |
| subsequent to | after |

### Uniform Sentence Length

AI produces paragraphs with similar sentence lengths. Human writing varies:
- Short punchy sentences for emphasis
- Longer sentences for complex ideas
- Fragments for effect

### Excessive Positivity

AI avoids criticism and hedges everything:

**AI-like:** "While there are considerations, the approach demonstrates considerable promise."

**Direct:** "This approach has two significant problems: cost overruns and timeline delays."

### Perfect Grammar

Counterintuitively, perfect grammar can signal AI. Human text contains:
- Occasional fragments for style
- Colloquialisms appropriate to context
- Minor imperfections that feel natural

---

## Punctuation Tells

### Em Dash Overuse

GPT-4 and later use em dashes at 10x the rate of GPT-3.5. AI uses em dashes where humans use commas, parentheses, or colons.

**AI pattern:** "The project—which started in March—delivered results—significant results—by June."

**Human:** "The project, which started in March, delivered significant results by June."

Look for em dashes used:
- Multiple times per paragraph
- Where commas would work
- In formulaic, "punched up" ways

---

## Model-Specific Patterns

### ChatGPT Tells

| Pattern | Examples |
|---------|----------|
| First words | "As," "Yes," "Sure," "Here," "Certainly" |
| Phrases | "such as," "certainly," "overall," "utilize" |
| Formatting | Heavy bold, structured headings, extensive markdown |

### Claude Tells

| Pattern | Examples |
|---------|----------|
| First words | "In," "From," "This," "How," "Based" |
| Phrases | "according to," "based on," "the text," "appears to" |
| Style | Measured tone, minimal markdown |

### Conversational Artifacts

Obvious tells when AI forgets it's writing a document:
- "I hope this helps"
- "Certainly!"
- "Let me know if you have questions"
- "As an AI language model..."

---

## Detection and Editing

### Manual Detection Strategy

1. **Scan for vocabulary clusters** — Three or more Tier 1/2 words per page
2. **Check opening sentences** — Formulaic openers are immediate tells
3. **Look for triplets** — Rule of three patterns throughout
4. **Count em dashes** — More than 2-3 per page is suspicious
5. **Check transitions** — "Moreover/Furthermore/Additionally" chains
6. **Evaluate tone** — Excessive formality without criticism

### The 30-Second Scan Test

Read the first paragraph of each section. If you encounter:
- Any Tier 1 word: Edit immediately
- Formulaic opening: Delete and rewrite
- More than one formal transition: Simplify
- Puffery phrases: Delete

### Humanization Checklist

- [ ] No Tier 1 vocabulary
- [ ] Tier 2 vocabulary used sparingly (max 1-2 instances)
- [ ] No formulaic openings or closings
- [ ] No "Moreover/Furthermore/Additionally" chains
- [ ] Em dashes used sparingly and purposefully
- [ ] Varied sentence length
- [ ] Direct statements instead of puffery
- [ ] No triplet patterns without purpose
- [ ] No negation structures ("not just X, it's Y")
- [ ] No conversational artifacts
- [ ] Critical perspective where appropriate
