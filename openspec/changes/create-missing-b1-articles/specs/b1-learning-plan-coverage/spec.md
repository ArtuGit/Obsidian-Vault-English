## ADDED Requirements

### Requirement: B1 learning plan notes exist
The content system SHALL provide a non-empty note file for every article linked from the B1 Learning Plan.

#### Scenario: Missing linked note is created
- **WHEN** a B1 Learning Plan entry has no corresponding file in `content/`
- **THEN** a new markdown note with the exact linked title MUST be created in `content/`

#### Scenario: Empty linked note is completed
- **WHEN** a B1 Learning Plan entry points to a file that exists but has no usable lesson content
- **THEN** that file MUST be replaced with complete lesson content instead of remaining empty

### Requirement: B1 learning plan notes are usable study pages
Each B1 Learning Plan note SHALL include foundational explanation, learner-facing examples or guidance, and at least one relevant Obsidian cross-link.

#### Scenario: Learner opens a created note
- **WHEN** a learner opens any newly created or completed B1 note
- **THEN** the page MUST contain topic explanation beyond a title alone
- **AND** the page MUST include examples, comparisons, or practice-oriented guidance appropriate to the topic
- **AND** the page MUST include at least one wikilink to a related note

#### Scenario: Note follows vault conventions
- **WHEN** a new B1 note is authored
- **THEN** the title and filename MUST match the learning-plan link target
- **AND** the note MUST keep the title concise
- **AND** the note MUST use vault-compatible markdown conventions such as headings, lists, tables, or callouts where helpful