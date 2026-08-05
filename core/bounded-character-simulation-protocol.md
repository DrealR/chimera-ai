# Bounded Character Simulation Protocol

AI roleplay can help explore a narrative world only when each character remains a bounded operator rather than a disguised mouthpiece for the author, model, or framework.

This protocol implements CHIMERA Story Mode for human-led, agent-led, and mixed ensembles.

> **The model may generate a character's movement. It does not own the character, the world, or the canon.**

## What the simulation is

A character simulation is a structured counterfactual run inside a declared narrative substrate.

It can help expose:

- unexpected alliances;
- contradictions in world rules;
- missing stakeholders or consequences;
- plausible character pressures;
- branches an author did not notice;
- places where the story is forcing an answer;
- questions worth carrying into later research or writing.

It is not proof about reality, a reliable prediction of human behavior, or an autonomous source of canon.

## Required roles

### World-state steward

Maintains the authoritative state of the run:

- bodies and locations;
- time and sequence;
- resources and constraints;
- public events;
- hidden conditions;
- consequences already installed;
- the declared stop condition.

The steward may narrate the environment but should not choose on behalf of character operators.

### Character operators

Choose actions from bounded local viewpoints. A character operator receives only the information their character can perceive, remember, infer, or has been explicitly told.

### Human director and evaluator

Defines the question, approves safety boundaries, resolves genuine governance disputes, debriefs the run, and decides whether any output becomes a Candidate.

The same human may play a character, but the role distinction should remain explicit.

## Context isolation

Keep these layers separate:

```text
author truth
world-state truth
character observation
character belief
character intention
player or model inference
```

An agent must not act on author-level information merely because the prompt, retrieval system, or model context contains it.

Use separate context envelopes when possible. If infrastructure requires shared context, label inaccessible information and explicitly instruct the character operator not to use it. Treat unexplained knowledge leakage as a simulation error, not a clever revelation.

## Character envelope

Each character operator should receive:

```yaml
character_id:
run_id:
current_time:
current_location:
role:
local_goals: []
protected_values: []
known_facts: []
beliefs: []
uncertainties: []
relationships: []
resources: []
membrane_permissions: []
membrane_restrictions: []
current_body_state: []
recent_events: []
private_memory: []
available_actions: []
hard_constraints: []
```

Do not give the character a full plot summary, intended arc, secret ending, or framework lesson they have not earned locally.

## Turn protocol

For each turn:

1. The steward provides the character's local observation.
2. The character operator separates observation from inference.
3. The operator states an intention and selects an action.
4. The steward checks the action against location, resources, membranes, and world rules.
5. The steward installs the consequence.
6. Only bodies capable of perceiving that consequence receive it.
7. The authoritative world state and relevant local memories update.
8. The stop condition is checked.

The record should preserve:

```text
observation
-> inference
-> intention
-> action
-> ruling
-> consequence
-> state delta
```

This makes later debrief possible. It also prevents generated prose from silently rewriting prior facts.

## Simultaneous actions

When multiple characters act before observing one another:

1. collect their actions independently;
2. freeze them before resolution;
3. apply the declared timing and conflict rules;
4. install one shared consequence state;
5. reveal only locally available results.

Do not let the later-sampled agent retroactively optimize against the earlier agent's private choice.

## Counterfactual reruns

Record the baseline run and name the single changed condition:

```yaml
baseline_run:
counterfactual_run:
changed_condition:
preserved_conditions: []
comparison_question:
```

Useful comparisons include:

- disclosure now versus disclosure later;
- centralized authority versus appeal rights;
- access to a resource versus no access;
- one remembered event versus one forgotten event;
- acceptance versus refusal of the same offer.

If many conditions change, classify the result as a new scenario rather than a controlled counterfactual.

## Provenance record

Every consequential run should retain:

```yaml
run_id:
date:
story_version:
prime_canon_version:
world_state_version:
human_participants: []
model_providers: []
model_ids: []
system_prompt_versions: []
character_prompt_versions: []
tools_enabled: []
sampling_settings: {}
retrieval_sources: []
private_context_classes: []
manual_interventions: []
changed_conditions: []
stop_reason:
```

Do not publish private prompts, personal histories, likenesses, or participant data merely because they contributed to a run. Provenance must preserve lineage without violating the source body's membrane.

## Debrief and canon gate

After the run, separate:

1. what happened in the sandbox;
2. what the run revealed about the story;
3. what the run may suggest about the framework;
4. what would require outside evidence;
5. what should be rejected.

An outcome moves through:

```text
Sandbox
-> Candidate
-> human review
-> Canon or Retired
```

Repeated model output is not a vote. Fluency is not character truth. Surprise is a reason to inspect, not a reason to canonize.

## Failure modes

### Omniscient drift

Characters use secrets, author notes, or other characters' private state.

**Correction:** restore isolated context and replay from the last valid state.

### Character convergence

Different characters acquire the same cadence, moral language, assumptions, and solution.

**Correction:** strengthen distinct histories, protected values, perceptual limits, and incompatible local incentives.

### Plot obedience

The model selects actions because they advance the intended outline rather than because the character could choose them.

**Correction:** remove future plot knowledge and permit refusal, delay, failure, and misinterpretation.

### Framework ventriloquism

Characters explain CHIMERA terminology instead of living through the relation.

**Correction:** translate the concept into a concrete need, conflict, memory, resource, or consequence.

### Sycophantic resolution

Every body quickly accepts the human director's preferred synthesis.

**Correction:** preserve real costs, opposition, distrust, and values that do not dissolve after one speech.

### Retroactive continuity

The model invents prior events to justify the current output.

**Correction:** require cited state lineage for historical claims; otherwise mark the claim as character belief or reject it.

### Infinite event flood

Generation continues adding factions, mysteries, and twists faster than the world can metabolize them.

**Correction:** enforce scope, state budgets, and stop conditions. Let unfinished branches remain unfinished.

### Persona overclaim

A stable voice is treated as proof of a stable human-like interior or enduring identity.

**Correction:** distinguish the base model, deployment, prompt, memory, character state, generated performance, and any human interpretation.

### Canon by volume

Machine-generated material overwhelms human-created work through quantity.

**Correction:** canon has a human selection bottleneck and a reasoned lineage note.

## Pre-run checklist

- Is the exploration question explicit?
- Are Prime canon and revisable composites separated?
- Is there an authoritative world state?
- Does every character have bounded knowledge?
- Are private contexts isolated?
- Can characters refuse the expected plot?
- Are resource and membrane constraints executable?
- Is the stop condition visible?
- Is the provenance record ready?
- Does a human own the canon decision?

## Post-run checklist

- Did any character use inaccessible knowledge?
- Did the world preserve prior consequences?
- Did characters remain meaningfully distinct?
- Which outcome was generated by model habit rather than world structure?
- What new cost, body, or contradiction appeared?
- What is merely an evocative carrier image?
- What requires empirical verification?
- What should become Candidate, Canon, Retired, or remain Sandbox?
- Were private bodies and contributor rights preserved?
- What would falsify the interpretation drawn from the run?

## Compact rule

```text
AI opens branches.
Bounded characters walk locally.
The world settles consequence.
Humans evaluate the residue.
Canon changes only by intentional judgment.
```

> **A useful character simulation preserves enough separation that the world can answer the model back.**

## See also

- [Narrative Substrate and Story Mode](../../../nucleus/framework/docs/narrative-substrate-and-story-mode.md)
- [Reflexive Mirrors and Answerable Models](reflexive-mirrors-and-answerable-models.md)
- [Corrigible Mirrors and Shared Primes](corrigible-mirrors-and-shared-primes.md)
- [Between the Waters — Corrigible Mirror Checklist](between-the-waters-implementation-checklist.md)
- [Model Constellation Research Protocol](model-constellation-research-protocol.md)
- [The Sandbox](../deep/the-sandbox.md)
