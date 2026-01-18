# Spec Delta: Articles content plan

## ADDED Requirements

### Requirement: Articles hub SHALL provide structured navigation
The system SHALL provide an Articles hub page that links to a comprehensive set of Articles subpages and recommends a learning order.

#### Scenario: Learner opens the Articles hub
- **GIVEN** the learner is on the Articles hub
- **WHEN** the learner scans the page
- **THEN** they can see a recommended learning order and links to all Articles subpages

### Requirement: Articles subpages SHALL be substantial (not short)
Each Articles subpage SHALL be a full lesson note including explanation, examples, common error contrasts, and exercises with answer keys.

#### Scenario: Learner uses a subpage to study
- **GIVEN** the learner opens any Articles subpage
- **WHEN** they read and practice
- **THEN** they can find rules/patterns, multiple examples, and an exercise section with an answer key

### Requirement: Articles subpages SHALL cover all levels
Each Articles subpage SHALL include a B1/B2 core explanation AND clearly marked C1 expansions.

#### Scenario: Learner studies at different levels
- **GIVEN** a learner at B1/B2 level opens an Articles subpage
- **WHEN** they follow the main content
- **THEN** they can complete the core rules and exercises without needing advanced notes
- **AND GIVEN** a learner at C1 level opens the same subpage
- **WHEN** they want deeper nuance
- **THEN** they can find clearly labeled C1 expansions

### Requirement: British English SHALL be default with American variants
Articles pages SHALL use British English as the default variety and SHALL provide an “American version” note where natural usage differs.

#### Scenario: Learner encounters a BrE/AmE difference
- **GIVEN** a page includes a usage pattern that differs by variety (e.g., hospital)
- **WHEN** the learner reads the rule
- **THEN** the page presents the British default
- **AND THEN** it provides an American version note showing the American phrasing

### Requirement: Existing countability page SHALL be integrated
The system SHALL integrate the existing page `When Are Countable Nouns Used Without “A” or “An” in English?` into the Articles structure via hub linking and cross-links from relevant pages.

#### Scenario: Learner studies countability and articles
- **GIVEN** the learner is reading about countability and articles
- **WHEN** they need the deeper explanation for article omission with count nouns
- **THEN** they can navigate to the existing deep-dive page from the hub and from the countability subpage

### Requirement: Cross-linking SHALL support problem-based navigation
Articles pages SHALL cross-link to related pages based on common learner problems (e.g., place names, institutions, generic reference).

#### Scenario: Learner gets stuck on place names
- **GIVEN** the learner is reading a page about `the`
- **WHEN** they encounter a rule about countries/rivers
- **THEN** they can follow a link to the dedicated “proper nouns and place names” page
