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
- youtube videos

Public accounts are not containment logs, court records, or divine tablets.

They are partial reports produced under deadline pressure, reputational pressure, platform incentives, and human memory.

Accordingly, SCP-DIG may compress timelines, alter names, fictionalize entities, abstract technical details, or combine multiple reports into one taxonomic case study.

Unless directly quoted and cited, dialogue, agent reasoning, internal motives, institutional reactions, and causal chains should be read as interpretive reconstruction not a faithful postmordem.

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

By default, prefer fictionalized or generalized entities. Naming a real company, person, project, or model is rarely necessary. For well-known incidents, the shape of the crater is usually enough to identify the blast without naming the architect.

Furthermore, public reports are incomplete by nature; fictionalizing the surrounding details prevents us from accidentally codifying media speculation as technical fact.

### The Exception for Hyper-Scale Entities:

There are rare cases where an incident is so inextricably linked to a highly public organization or figure (e.g., major AI labs, specific foundational models) that attempting to talk around them with pseudonyms actively detracts from the entry.

If you believe using actual names is necessary to preserve the diagnostic value of the entry, a case-by-case determination must be made. Route the request to quetzhelix-guild or open a community discussion for consensus.

Keep in mind the governing ethic of the project: We are here to log the monster, not dox the summoned. Specific public-report details can be retained when they are diagnostically useful, but they increase the entry's public specificity level. Avoid unnecessary proper nouns when the mechanism does not require them.

For public-incident-inspired entries, use generalized patterns:

- a small B2B reservation platform
- an AI coding agent
- an over-scoped infrastructure token
- a destructive storage-volume operation

### Low

The entry uses only broad patterns and contains no identifying details.

### Medium

The entry uses some public-report-shaped details—such as approximate timing, sector, tool type, or incident structure—but strictly fictionalizes names and avoids direct identification.

### High

Reserved for incidents so widely publicized and inextricably linked to a specific hyper-scale organization or well-known figure that maintaining a pseudonym is an absurd distraction.

The entry uses named entities, exact timing, direct quotes, unique technical sequences, or other details that explicitly point to a specific public incident. Because this level bypasses standard fictionalization protocols, 

High-specificity entries require approval (via quetzhelix-guild or community consensus) and must include direct citations or an internal source note.

## Public Specificity Levels

## Ethical Rule

Do not turn a real person, maintainer, coworker, contributor, or company into a monster-of-the-week when a fictionalized entity would teach the mechanism just as well.

Name the mechanism.

Fictionalize the corpse when possible.

## Front-Matter Principle

> Public incidents are diagnostic material, not settled canon.

The field guide may learn from real failures without pretending to own their full factual truth.
