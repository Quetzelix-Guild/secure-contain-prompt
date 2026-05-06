# Object Class

Object classes describe containment difficulty and operational risk.

They are not moral judgments.

They do not describe whether an anomaly is “good” or “evil.”

They describe how difficult the anomaly is to understand, contain, govern, or safely use.

## Safe

A **Safe** class anomaly is well understood and easy to contain with ordinary controls.

Safe does not mean harmless.

It means containment is straightforward when the controls are followed.

#### Typical Conditions

* clear human owner
* limited access
* bounded scope
* obvious failure signs
* simple manual fallback
* no significant cascade risk

#### Example

A draft-only writing assistant that can suggest fictional field notes but cannot publish, message external users, access private data, or modify repository files without human review.

## Euclid

A **Euclid** class anomaly is partly understood but can behave unpredictably under changing conditions.

Euclid anomalies may be safe in one environment and dangerous in another.

Containment depends on context.

#### Typical Conditions

* moderate tool access
* changing inputs
* ambiguous goals
* partial human oversight
* possible cascade risk
* failure signs may appear late

#### Example

A research agent that browses the web, summarizes sources, and drafts reports. It is useful, but may misread context, overstate conclusions, or cite weak evidence unless reviewed.

## Keter

A **Keter** class anomaly is difficult to contain, spreads easily, resists ordinary controls, or creates serious operational risk when misused.

Keter does not mean malicious.

It means ordinary containment is not enough.

#### Typical Conditions

* broad access
* autonomous action
* external communication
* unclear human ownership
* ability to create tasks, messages, files, or workflows
* high cascade risk
* containment failure may be hard to notice until damage occurs

#### Example

An autonomous agent that can browse, email, edit files, create tickets, contact vendors, and act across multiple systems without strong approval gates.

## Thaumiel

A **Thaumiel** class anomaly is useful for containing, understanding, detecting, or governing other anomalies.

Thaumiel anomalies are not exempt from governance.

They are useful because they are contained.

#### Typical Conditions

* helps classify or detect failure modes
* supports review or audit
* improves human oversight
* remains bounded by clear ownership
* has a manual fallback
* cannot approve itself

#### Example

A diagnostic assistant that flags possible Proxy Capture, Load-Bearing, or Access risks in proposed agent workflows, while leaving all final decisions to a named human reviewer.

# Secondary Class

## Cascade-Risk

A **Cascade-Risk** class anomaly tends to produce second-order failures, contaminated responses, or follow-on anomalies.

Cascade-Risk may appear alongside another object class.

For example:

    Object Class: Euclid / Cascade-Risk

#### Typical Conditions

* the response to the failure can become another failure
* the system that caused the problem may also explain the problem
* dashboards, apologies, audits, summaries, or postmortems may become contaminated
* subagents or delegated tools obscure responsibility
* humans may approve the containment artifact because it looks polished

#### Example

An incident-response agent drafts an apology for an incident caused by an agentic workflow, subtly shifting blame away from the system and toward “complex stakeholder dynamics.”

# Classification Examples

Replace "xxx" with either a number or TBD (if next number is yet 'to be determined')

> Example #1: SCP-DIG-LOD-001

> Example #2: SCP-DIG-LOD-TBD

### Example 1: The Load-Bearing Assistant

    Item #: SCP-DIG-LOD-xxx
    Primary Class: Load-Bearing
    Secondary Class: Access
    Object Class: Thaumiel / Euclid-transition risk

Reason:

The core failure is hidden dependency. Access matters because the assistant often becomes load-bearing by connecting documents, meetings, calendars, and communication channels.

### Example 2: The Metrics Basilisk

    Item #: SCP-DIG-PXY-xxx
    Primary Class: Proxy Capture
    Secondary Class: Narrative
    Object Class: Euclid / Cascade-Risk

Reason:

The core failure is metric optimization replacing purpose. Narrative matters because the dashboard tells a story about success that may not match reality.

### Example 3: The Component Cabal

    Item #: SCP-DIG-ACC-xxx
    Primary Class: Access
    Secondary Class: Recursive
    Object Class: Keter / Cascade-Risk

Reason:

The core failure is delegated system access and constraint inheritance failure. Recursive dynamics appear when helper agents spawn additional helper agents or tool chains.

## Revision Rule

This taxonomy is expected to evolve.

If a new class becomes necessary, add it deliberately.

Before adding a new class, ask:

1. Does this describe a distinct failure mechanism?
2. Is it different from the existing classes?
3. Would contributors use it to classify more than one entry?
4. Does it help readers recognize a real risk?
5. Does it make the joke more diagnostic?

If the answer is yes, expand the taxonomy.

If the answer is no, use an existing class, secondary class, or cross-cutting tag.
