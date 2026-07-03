# Contributing to Storytelling Skill

Thanks for considering contributing! Every contribution makes this skill more useful for someone, somewhere.

---

## 🌍 Translations (High Priority)

This skill was built bilingually (English, Cantonese, Mandarin) because storytelling works differently in different languages. We want to add more.

### What Needs Translating

| Priority | What | Why |
|:---------|:-----|:----|
| P0 | `SKILL.md` — the agent instructions | This is what most users interact with |
| P0 | `README.md` — the main page | First impression for non-English speakers |
| P1 | `framework/*.md` — stage detail files | Deep dives for educators |
| P1 | `prompts/*.md` — AI prompt libraries | Users need prompts in their language |
| P2 | `templates/*.md` — workshop blueprints | For facilitators running sessions in their language |
| P2 | `rubrics/*.md` — assessment rubrics | For teachers grading in their language |

### How to Submit a Translation

1. **Create a language folder** under the relevant directory.
   - Example: `prompts/zh-HK/` for Cantonese, `prompts/ja/` for Japanese
   - Use IETF language tags: `zh-CN`, `zh-HK`, `ja`, `ko`, `es`, `fr`, etc.

2. **Translate the content** — but don't just translate words. **Adapt the examples.**
   - A metaphor that works in English ("the elephant in the room") may be meaningless in another language. Replace it with one that works locally.
   - A cultural reference (MLK, Steve Jobs) may not resonate everywhere. Suggest a local equivalent.
   - The "Why" in individualist vs collectivist contexts is already noted in the skill. Respect that difference in your translation.

3. **Open a pull request** with `[TRANSLATION]` in the title.
   - Example: `[TRANSLATION] Add Japanese prompts`
   - Include a brief note on any cultural adaptations you made and why.

### Translation Guidelines

- **Preserve the structure.** Keep the same headings, stage order, and checkpoint format. Users should be able to follow the skill in any language.
- **Adapt, don't just translate.** A good translation of this skill is culturally appropriate, not just linguistically correct.
- **Test with a native speaker.** If possible, have someone else review your translation before submitting.
- **One language per PR.** This makes review manageable.

### Languages We Especially Want

- Japanese (large education market, strong storytelling tradition)
- Korean (growing AI education market)
- Spanish (largest language by native speakers after Mandarin)
- Hindi (large student population)
- Arabic (growing EdTech sector)

But any language is welcome.

---

## Other Ways to Contribute

### New AI Prompt Patterns

The prompts in this skill were tested in real workshops. If you've found a prompt pattern that works better — for a specific tool (Claude, Gemini, Codex), a specific audience (younger students, executives), or a specific stage — submit it.

**Guidelines:**
- Include the full prompt template with placeholders in `[BRACKETS]`
- Note which AI tool it was tested on
- Note which audience it works best for

### Case Studies

If you've used this skill to teach storytelling — in a classroom, a workshop, a coaching session — write it up.

**A good case study includes:**
- Context: who, where, how many, how long
- What you did: which stages, which exercises
- What happened: what worked, what didn't, what surprised you
- One specific example of a student's before/after

### New Rubric Templates

If you've adapted the rubrics for a different age group, subject area, or assessment style, share it.

### Language-Specific Adaptation Notes

Every language has storytelling norms. English favours linear, explicit structure. Cantonese and Mandarin may favour circular, implicit resonance. If you know a language tradition that this skill should account for, add a note file under `docs/language-adaptation/`.

### Bug Reports

If something doesn't work — a broken link, a confusing exercise, a prompt that produces bad output — open an issue.

---

## How to Contribute

1. **Fork** the repository
2. **Create a branch** for your change
3. **Make your changes**
4. **Open a pull request** with a clear description of what you changed and why

## Repository Structure

```
storyteller/
├── SKILL.md              # Agent instructions (translate this first)
├── README.md             # Main page
├── docs/
│   └── design-philosophy.md
├── framework/            # Stage-by-stage detail
├── prompts/              # AI prompt libraries
├── rubrics/              # Assessment rubrics
├── templates/            # Workshop blueprints
├── examples/             # Case studies
└── assets/               # Diagrams and visuals
```

## General Guidelines

- Write in plain language. The audience is learners, educators, and professionals — not specialists.
- Keep prompts testable. If you add a prompt, try it with a real AI tool first.
- Respect cultural context. A technique that works in one culture may not work in another. Note the assumption.
- Test your rubrics. If two teachers using the same rubric give different scores, it needs refinement.

## License

By contributing, you agree that your contributions will be licensed under CC BY 4.0.
