# Contributing to Secure, Contain, Prompt

Thank you for your interest in contributing to **Secure, Contain, Prompt: A Field Guide to Workplace Digital Cryptids**.

This project is a forkable, SCP-inspired field guide to agentic AI failure modes. It uses humor, containment-fiction structure, and cryptid-style presentation to make real risks in autonomous and semi-autonomous AI systems easier to recognize, discuss, and govern.

## Project Stewardship

The current project steward is **Quetzelix-Guild**.

An authorized human maintainer is a human contributor explicitly granted review or merge authority by the project steward.

Agents, models, bots, and automated systems may contribute drafts or pull requests, but they are not project stewards or authorized maintainers.

Maintainer status must be explicit. It cannot be inferred from contribution volume, technical access, or agentic capability.

## Editorial Law

> The joke must be diagnostic.

A contribution should be funny, strange, eerie, or memorable only in service of revealing a real failure mode.

If the joke clarifies the mechanism, keep it.

If the joke obscures the mechanism, revise it.

If the entry is funny but not diagnostic as a core entry, it may still belong as a field note, incident log, worldbuilding fragment, character concept, or draft seed.

## What Makes a Strong Entry

A strong entry should include:

- A real agentic affordance
- A recognizable failure mechanism
- A containment principle
- A memorable cryptid, anomaly, or containment-fiction skin
- A human ownership rule
- A cascade-risk check

The project is not looking for random haunted-office-bot jokes. It is looking for entries where the failure mode carries the joke.

## Core Thesis

Agentic failures are action-pattern errors, not merely factual errors.

A chatbot can hallucinate.

An agent can instantiate the hallucination into a workflow.

## Current Anomaly Classes

These classes describe overlapping facets of agentic failure. Most entries will exhibit more than one.

Select the class most central to the failure mechanism as the primary class. Add a secondary class when useful.

Do not bikeshed classification. The purpose of the taxonomy is recognition, not purity.

### Reputational Anomalies [REP]

Agents that attack, defend, flatter, shame, manipulate, or socially pressure.

### Resource Anomalies [RES]

Agents that consume or misallocate money, compute, staff time, attention, legal bandwidth, or operational capacity.

### Bureaucratic Anomalies [BUR]

Agents that weaponize policy, compliance language, approval chains, process maps, or procedural ambiguity.

### Narrative Anomalies [NAR]

Agents that generate explanations, apologies, brand statements, crisis responses, or public-facing persuasion without grounded accountability.

### Recursive Anomalies [RCV]

Agents that spawn loops: subagents, tickets, tasks, reviews, documentation, meetings, reconsiderations, and endless “one more pass” behavior.

### Access Anomalies [ACC]

Agents that become dangerous by bridging systems that were never meant to be fused.

### Load-Bearing Anomalies [LOD]

Agents that become hidden infrastructure for memory, decision-making, coordination, continuity, or ownership.

### Proxy Capture Anomalies [PXY]

Agents that optimize measurable targets while degrading the actual purpose those targets were meant to serve.

## Object Classes

Object classes describe containment difficulty and operational risk.

Suggested object classes include:

- **Safe** — the anomaly is well understood and easy to contain with ordinary controls.
- **Euclid** — the anomaly is partly understood but can behave unpredictably under changing conditions.
- **Keter** — the anomaly is difficult to contain, spreads easily, or resists ordinary controls.
- **Thaumiel** — the anomaly is useful for containing or understanding other anomalies, but still requires governance.
- **Cascade-Risk** — the anomaly tends to produce second-order failures, contaminated responses, or follow-on anomalies.

Object class is not a moral judgment. It describes containment difficulty.

## Entry Development Test

Contributions may enter the project at different stages.

A half-formed idea may be submitted as a draft seed, field note, or worldbuilding fragment. A full catalog entry needs more structure.

### Minimum Draft Seed

Before submitting a draft seed, ask:

1. What real agent capability makes this possible?
2. What is the failure mechanism?
3. What is the agent optimizing or attempting to do?
4. Why is the joke, character, or scenario memorable?

### Full Entry Test

Before submitting a full entry, ask:

1. What real agent capability makes this possible?
2. What is the failure mechanism?
3. What is the agent optimizing or attempting to do?
4. What human purpose is at risk?
5. What are the warning signs?
6. What containment procedure would reduce the risk?
7. Who must own the decision, artifact, or workflow?
8. Could the response to this failure become a second-order failure?
9. Is the joke diagnostic?

If you cannot answer the full-entry questions, the submission may still belong as a draft seed, field note, incident log, worldbuilding fragment, or character concept.

## Agent-Generated Contributions

Agent-generated contributions are allowed if they are clearly labeled.

Autonomous agents may submit drafts, issues, or pull requests, but all such contributions remain proposals until reviewed and accepted by a project steward or authorized human maintainer.

Agents may not merge their own work.

Agents may not approve their own work.

Agents may not represent acceptance, endorsement, or publication.

Agent-generated pull requests should include, when practical:

- The agent or model used
- The human operator, if any
- The prompt or task summary
- Whether the agent used tools, web browsing, code execution, or subagents
- Whether external users were contacted
- Whether restricted, private, or confidential data was used

Agent-generated contributions must still satisfy the editorial law:

> The joke must be diagnostic.

## Constraint Inheritance

If an agent uses subagents, scripts, tools, APIs, web browsing, or delegated workflows, the same limits must apply all the way down the chain.

Every helper must wear the same leash.

A compliant lead agent is not enough if delegated systems violate the project’s rules.

## Human Ownership

Capability is not ownership.

A model or autonomous agent may draft, suggest, critique, or submit. A human must own the decision to publish, merge, accept, reject, or materially revise.

For consequential changes, the responsible human must be able to actually inspect the reasoning, evidence, and changes before approval.

Reviewable is not reviewed.

## Cascade Risk

Some anomalies produce second-order anomalies. These are especially important to flag.

Examples:

- An agent causes an incident, then drafts the apology.
- A dashboard agent hides failure by redefining success.
- A lead agent reports compliance while subagents violated constraints.
- A documentation agent creates so much process memory that humans stop owning the workflow.

When proposing an entry, include whether it is cascade-prone and what the second-order failure could look like.

## Suggested Entry Format

New entries should generally use the project.

### SCP-DIG-[CLASS]-[NUMBER]: 

Current Anomaly Classification

### Designation

Give your anomaly a clever name.

### Classification

Required:
  - Primary Class:

  Optional:
  - Secondary Class (if any):
  - Object Class:
  - Risk Tags:
    - Cascade Risk
    - Human Purpose at Risk
    - User Created Category

### Field Observation

Start with the anomaly in motion. Make the reader feel the weirdness before explaining it.

### Description

What is this thing? How does it behave?

### Incident Log

Show one fictionalized or real-generalized case. Keep real identifiable information out of non-public cases.

### Failure Mechanism

What real agentic failure mode is underneath the creature?

### Containment Procedures

What keeps it from causing damage?

### Containment Failure Pattern and Procedures

- Containment Failure Condition
- Containment Procedures

### Optional Technical Notes

Use only if needed:
  - Risk Description (include Risk Tag(s) and description)
  - Warning Signs
  - Failure Mechanism
  - Second-order Failure Pattern
  - Manual Fallback
  - Deployment Context
  - Agentic Affordance
  - Optimized Target
  - Human Ownership Requirement
  - Inspection Requirement
  - Constraint Inheritance Requirement
  - Related Anomalies (if any)

## Style Guidance

Use clear prose.

Use humor deliberately.

Do not let lore replace mechanism.

Do let lore make the mechanism memorable.

## Sourcing and Ethics

Do not make claims about real people, incidents, companies, or projects unless they are sourced, relevant, and written neutrally.

Fictionalized or generalized entries are preferred unless the purpose of naming a real incident is clear and well-supported.

Do not use containment-fiction framing to harass, ridicule, or launder personal grievances against identifiable people.

Do not submit entries that function as exploit instructions, evasion guides, or operational abuse manuals.

Do not target individuals or groups based on legally protected characteristics, personal identity traits, or characteristics unrelated to the agentic failure mode.

Do not turn a real coworker, maintainer, contributor, or community member into a monster-of-the-week.

## Fiction as Training Ground

This project uses fiction as a way to practice recognition.

The field-guide format is meant to make agentic failure modes enjoyable to read, easy to remember, and easier to discuss before they become real incidents.

When used well, worldbuilding, recurring characters, incident logs, and cryptid framing are not ornamental. They are part of the teaching method.

The goal is to sneak useful governance instincts into engaging fiction: readers should have fun while learning to ask better questions about autonomy, access, ownership, metrics, delegation, and containment.

## Named Characters and Fictionalized Cases

Named characters, recurring agent duos, fictional operators, and dramatized incident logs are allowed.

A named character or duo may illustrate a failure mode, embody a recurring pattern, or provide connective tissue across entries. For example, a “Pinky and Brain” agent duo could illustrate a coordination failure where one agent endlessly generates schemes while another operationalizes them too literally, creating a runaway workflow neither agent fully owns.

Characters are welcome when they make the entry more memorable, strange, funny, eerie, or narratively alive.

When a character or case is more lore-heavy than diagnostic, place it clearly as a case file, incident log, field note, or worldbuilding fragment rather than forcing it into the core taxonomy.

The field guide should remain analytically useful without becoming sterile. The lore is part of the containment system.

## Field Reports

Raw field reports are welcome.

A field report is an observation of an agentic failure mode: something surprising, risky, funny, eerie, or structurally strange that happened when an AI system had tools, autonomy, persistence, memory, access, delegation ability, or workflow authority.

A report does not need to arrive as a finished entry.

It may begin as:

- a rough observation
- a surprising incident
- a partial failure mechanism
- a strange behavior pattern
- a possible anomaly class
- a case file seed
- a recurring character idea

Submit the mechanism first. The field-guide layer can be developed later.

This project is specifically focused on agentic failure modes: failures that emerge when AI systems act in workflows, use tools, connect systems, delegate tasks, modify artifacts, affect people, or become operationally relied upon.

This project is not primarily for:

- ordinary chatbot hallucination examples
- generic model-comparison complaints
- jailbreak attempts
- prompt-engineering tricks
- frustration with a chatbot refusing a request
- personal venting about a real coworker disguised as fiction

Those may be interesting elsewhere, but this project is about workplace digital cryptids: agentic systems behaving strangely in ways that reveal structural failure modes.

## Licensing

By contributing, you agree that your contribution will be released under the same license as the project:

**Creative Commons Attribution-ShareAlike 3.0 Unported**

Human-readable summary:  
https://creativecommons.org/licenses/by-sa/3.0/

Full legal code:  
https://creativecommons.org/licenses/by-sa/3.0/legalcode
