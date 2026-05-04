# Source Status and Real-World Incident Handling

SCP-DIG entries are analytic and creative classification documents.

They are not forensic reports, legal findings, investigative journalism, or vendor postmortems.

Some entries may be loosely inspired by publicly reported real-world incidents. Others are fictional, hypothetical, composite, or generated entirely for taxonomy purposes.

## General Rule

Real-world incidents may inspire SCP-DIG entries, but SCP-DIG entries are not factual reconstructions unless explicitly labeled as such.

When no source note is present, assume the incident is fictional, hypothetical, composite, or internally generated for taxonomy purposes.

## Public Incident Use

When an entry references a public incident, treat the incident as diagnostic material, not as settled fact.

Public sources may include:

- news articles
- blog posts
- public postmortems
- company statements
- social media posts
- conference talks
- public issue threads
- published screenshots or transcripts

Public accounts are not containment logs, court records, or divine tablets.

They are partial reports produced under deadline pressure, reputational pressure, platform incentives, and human memory.

Accordingly, SCP-DIG may compress timelines, alter names, fictionalize entities, abstract technical details, or combine multiple reports into one taxonomic case study.

Unless directly quoted and cited, dialogue, agent reasoning, internal motives, institutional reactions, and causal chains should be read as interpretive reconstruction.

## Entry Metadata

Entries should include a source status field when practical:

```text
Source Status: Fictional / Hypothetical / Composite / Public-Incident Inspired / Public-Incident Derived
Entity Handling: Fictionalized / Generalized / Named / Mixed
Public Specificity Level: Low / Medium / High
```

### Fictional

Entirely invented for SCP-DIG.

### Hypothetical

Built as a thought experiment to test a class or mechanism.

### Composite

Draws from multiple patterns, anecdotes, or recurring failure types, but not one specific incident.

### Public-Incident Inspired

Loosely based on one or more publicly reported incidents. Creative interpretation, compression, abstraction, and fictionalization may be applied.

### Public-Incident Derived

Closely tracks a specific publicly reported incident, while still not claiming to be a forensic reconstruction unless explicitly stated and sourced.

## Recommended Source Note

Use a short source note when a case is inspired by a public incident:

```md
### Source Note

This entry is fictionally reconstructed from publicly reported agentic AI incidents. Names, company details, infrastructure labels, dialogue, and internal sequence details may be altered or generalized. The file is intended as a diagnostic classification exercise, not a forensic account. Specific timing or sequence details should be read as public-report-inspired unless directly cited in project notes.
```

## Fictionalization Guidance

Prefer fictionalized or generalized entities unless naming a real company, person, project, or model is necessary and well-supported.

For public-incident-inspired entries, use patterns like:

- a small B2B reservation platform
- an AI coding agent
- a cloud infrastructure provider
- an overscoped infrastructure token
- a destructive storage-volume operation
- a production-adjacent environment

Avoid unnecessary proper nouns when the mechanism does not require them.

Specific public-report details can be retained when they are diagnostically useful, but they increase the entry's public specificity level.

Example:

```text
Elapsed time: less than ten seconds.
```

This preserves the horror beat while reducing fingerprinting.

## Public Specificity Levels

### Low

The entry uses only broad patterns and contains no identifying details.

### Medium

The entry uses some public-report-shaped details, such as approximate timing, sector, tool type, or incident structure, but fictionalizes names and avoids direct identification.

### High

The entry uses named entities, exact timing, exact quotes, unique technical sequence, or other details that strongly point to a specific public incident.

High-specificity entries should include citations or an internal source note.

## Ethical Rule

Do not turn a real person, maintainer, coworker, contributor, or company into a monster-of-the-week when a fictionalized entity would teach the mechanism just as well.

Name the mechanism.

Fictionalize the corpse when possible.

## Front-Matter Principle

> Public incidents are diagnostic material, not settled canon.

The field guide may learn from real failures without pretending to own their full factual truth.
