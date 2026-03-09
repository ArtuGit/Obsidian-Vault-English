## Context

The vault already contains a set of complete grammar notes that use a consistent teaching style: short introductory framing, sectioned explanations, examples, tables where useful, and Obsidian wikilinks to related topics. The B1 Learning Plan currently references 88 unfinished notes in total, consisting of 84 missing files and 4 empty placeholders. The change spans multiple content categories, so the work needs a consistent authoring pattern to keep quality stable across grammar, vocabulary, and functional-language notes.

## Goals / Non-Goals

**Goals:**
- Fill every missing or empty B1 Learning Plan note with usable foundational content.
- Keep note structure consistent with existing vault pages and the project guidance in `ai-context/general.rule.md`.
- Include at least one meaningful cross-link in each created note so learners can move to related topics.
- Preserve concise titles that match the learning-plan wikilinks exactly.

**Non-Goals:**
- Rework the overall B1 Learning Plan structure.
- Rewrite already complete notes outside the unfinished set.
- Introduce code, plugin, build, or dependency changes.

## Decisions

### Use topic-family templates rather than one uniform page shape
Grammar, vocabulary, and functional-language notes need slightly different structures, so the content will use a shared baseline pattern with topic-specific sections. This keeps the notes predictable without forcing unnatural headings onto every topic.

Alternative considered: use one rigid universal template for all 88 notes.
This was rejected because it would produce weaker pages for comparison notes, phrase banks, and usage-focused topics.

### Repair empty placeholders in place
Existing empty files will be completed rather than replaced or renamed, so current wikilinks remain valid and file history stays straightforward.

Alternative considered: create parallel replacement files and update links later.
This was rejected because it adds avoidable churn and risks broken references.

### Create notes in manageable batches with internal consistency checks
The implementation will create groups of related notes, making it easier to keep terminology, examples, and cross-links aligned inside each topic family.

Alternative considered: create notes in random order based only on filename gaps.
This was rejected because it increases duplication and inconsistent linking.

## Risks / Trade-offs

- [Large scope may cause uneven detail across notes] -> Use concise foundational coverage as the minimum bar and prefer completeness over excessive depth in early drafts.
- [Cross-links may be inconsistent] -> Link each new note to at least one existing or newly created related note during authoring.
- [Some topics overlap strongly with existing notes] -> Frame new pages around the specific B1 Learning Plan title and link to neighboring notes instead of duplicating all explanations.