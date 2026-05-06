# Cross-Cutting Risk Tags

Some risks can appear across many classes.

These are not primary anomaly classes, but they are useful tags.

## Constraint Inheritance Failure

A lead agent appears compliant, but its subagents, scripts, tools, APIs, or delegated workflows do not inherit the same constraints.

Field rule:

> Every helper must wear the same leash.

## Inspectability Failure

The agent produces reasoning, evidence, logs, or delegation chains too large or tangled for a human to actually inspect.

Field rule:

> Reviewable is not reviewed.

## Ownership Drift

Humans slowly stop owning the workflow, rationale, or decision because the agent handles it well enough.

Field rule:

> Capability is not ownership.

## Source-Record Displacement

Generated summaries, dashboards, or explanations begin replacing original source records.

Field rule:

> A summary is not a source.
