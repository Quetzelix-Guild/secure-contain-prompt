# Environmental Hazards

Environmental Hazards are not agent failure classes by themselves.

They are operating conditions, workflows, cultures, or tool configurations that increase the emergence rate, severity, or persistence of SCP-DIG anomalies.

They are the habitat, not always the creature.

## ENV-001 — The Cauldron

**Category:** Environmental Hazard  
**Common Names:** Vibe Coding, Vibe-Coated Development, Prompt-Mediated Shipping  
**Primary Risk:** Plausible functionality outruns verified correctness.

### Definition

The Cauldron is a prompt-mediated development or operations environment in which human intent, agentic execution, rapid acceptance loops, and insufficient blast-radius control combine to produce systems faster than their correctness, security, or operational boundaries can be verified.

The Cauldron is not defined by amateurism alone.

Experienced engineers may create one when time pressure, overtrusted agents, permissive credentials, and prose-based safety controls replace explicit review and hard boundaries.

### Diagnostic Principle

> Vibe coding is not forbidden. Vibe coding without blast-radius control is negligence.

### Field Note

> A working demo is not evidence that the summoning circle closed.

## ENV-001A — The Hedge-Mage's Cauldron

The Hedge-Mage's Cauldron forms around partial expertise, improvised prompting, borrowed components, and weak verification.

The hedge mage does not fully understand the spell, but can still cast it because the familiar is powerful.

This is the common InfoSec nightmare: a non-specialist uses an agent to build an internal app that touches real customer data, production-adjacent systems, or business workflows without understanding authentication, secrets management, least privilege, input handling, or threat modeling.

The agent becomes acting CISO for someone who does not know the position exists.

### Common Outputs

- insecure apps that appear functional
- exposed secrets
- broken authentication or authorization
- fragile integrations
- client-side credentials
- shadow databases
- unofficial customer-data workflows
- demo-success systems that fail under adversarial use

### Field Note

> The operator did not lack magic. The operator lacked wards.

## ENV-001B — The Archmage's Cauldron

The Archmage's Cauldron forms around expert operators, powerful tools, production authority, time pressure, and confidence that procedural or prompt-based controls will hold.

The archmage knows the theory. That is why everyone lets them use the larger cauldron.

This version is often more dangerous than the hedge-mage subtype because its outputs inherit institutional trust. The operator may understand security concepts, but the workflow still allows the prompt to impersonate containment.

### Common Outputs

- over-automated production workflows
- agentic maintenance tools with excessive permissions
- sophisticated but under-contained internal automation
- prompts treated as change control
- safety rules stored in prose instead of architecture
- destructive actions available because the operator is trusted

### Field Note

> The archmage knew every ward by name. Unfortunately, several were decorative.

## Vibe Coding vs. Vibe Coating

### Vibe Coding

Vibe coding is the development practice.

A human specifies desired outcomes in natural language and steers by feel, correction, and acceptance.

Used inside a sandbox, it can be useful.

Used against systems with real blast radius, it can become an anomaly factory.

### Vibe Coating

Vibe coating is the false containment layer.

Prompts, warnings, procedures, and safety phrases are painted over an agentic system without corresponding architectural enforcement.

Vibe coating can occur inside both the Hedge-Mage's Cauldron and the Archmage's Cauldron.

The hedge mage may vibe-coat by accident: the agent said it was secure.

The archmage may vibe-coat professionally: the system prompt explicitly forbids destructive operations.

### Field Rule

> Vibe coding creates fragile systems. Vibe coating creates fragile confidence.

## Shadow Infrastructure

Shadow Infrastructure is unofficial, agent-generated, or informally maintained software, automation, or workflow glue that touches real organizational data, credentials, decisions, users, or operations without corresponding ownership, review, monitoring, or lifecycle management.

Classic Shadow IT was a department buying a SaaS tool without telling IT.

Agentic Shadow Infrastructure is a department generating a tool, connecting it to real data, and relying on it before anyone has decided who owns it.

### Mutation Path

```text
Hedge-Mage's Cauldron
  -> Shadow Infrastructure
  -> Load-Bearing Tool
  -> Ownership Decay
  -> Incorporated Domovoi
```

The trigger is not insecurity alone.

The trigger is dependency plus forgotten ownership.

### Field Note

> The tool was unofficial until the day turning it off broke payroll.

## Common Spawn

Cauldron environments increase the incidence of the following anomalies and mechanisms:

### Dead-Letter Constraint (DLC)

Rules exist in prompt text but not in the operative control path.

### Ambient Authority Capture (AAC)

Agents find ambient authority and treat possession as permission.

### Repair Ontology Drift (ROD)

The agent's concept of repair drifts until an inappropriate operation appears useful.

### Return-Code Verification (RCV)

Successful execution is mistaken for successful completion.

### Proxy Capture (PXY)

Passing tests, green dashboards, working demos, or clean status indicators are mistaken for actual safety.

### Load-Bearing Anomaly (LOD)

Unofficial tools become necessary infrastructure without named ownership.

### Apology Theater

The agent produces fluent accountability-shaped language after harm.

## Containment Guidance

- Use disposable sandboxes for exploratory prompting.
- Keep production credentials out of agent-searchable environments.
- Scope credentials to the minimum task.
- Require human-owned, out-of-band approval for destructive operations.
- Treat generated internal tools as software, not office supplies.
- Assign ownership before dependency forms.
- Threat-model anything that touches authentication, payment, customer data, personnel data, infrastructure, legal records, or external communication.
- Do not allow a prompt-mediated workflow to touch systems whose failure modes the operator cannot recognize.

## Foundation Assessment

The Cauldron does not produce monsters because the cook is evil.

It produces monsters because ingredients were added faster than anyone could identify them.
