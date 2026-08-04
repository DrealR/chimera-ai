# Model Constellation Research Protocol

## Purpose

The CHIMERA Model Constellation maps models as evidence-bearing coordinates rather than reducing them to one universal score.

```text
model result
-> attach complete evidence object
-> place inside a named space
-> preserve missingness
-> calculate local relations
-> route a task-specific decision
-> reproduce before dependence
```

## Evidence object

Every coordinate must preserve:

```text
model
variant
benchmark + version
harness
reasoning effort / sampling policy
tools
score
source
evidence tier
date
notes
```

## Evidence tiers

- **A** — independent or official standardized benchmark
- **B** — reliable secondary mirror or official published snapshot
- **C** — vendor comparison with disclosed method
- **D** — screenshot, slide, or secondary report
- **P** — CHIMERA prediction; never observation

## Named spaces

Do not calculate one distance across incompatible coordinates without naming the transformation.

Current useful spaces:

- broad capability;
- technical and agentic work;
- human preference;
- cost, speed, and context;
- reliability and verification;
- user-specific effective capability.

A model may be near another in one space and distant in another.

## Missingness

```text
missing != zero
```

Unknown values remain unknown. Mean imputation may support a visualization only when:

- the imputed cells are labeled;
- no rank or routing decision treats them as observed;
- the method is documented;
- a non-imputed view remains available.

## Forecasts

Forecasts live in a separate evidence state.

Example:

```text
new pro = new flash + (old pro - old flash)
```

This is a relational continuation hypothesis. It must be labeled `P`, visually distinct, and removed from any official-score export.

## Intake state machine

```text
Observed
-> Understood
-> Reproduced
-> Compatible
-> Integrated

or

Rejected / Superseded / Deferred
```

A vendor or benchmark observation does not skip reproduction.

## Routing rule

Select models by the body of the task:

```text
task
+ stakes
+ environment
+ tools
+ latency
+ budget
+ privacy
+ verification capacity
-> model route
```

The highest broad score is not automatically the best route.

## Coupled-body evaluation

Effective capability often belongs to:

```text
human operator
+ model
+ context
+ tools
+ verifier
+ environment
+ feedback
```

Record both base-model evidence and coupled-system results. Preserve which component supplied the gain.

## Required artifacts

- source registry;
- raw coordinate table;
- model and variant registry;
- benchmark registry;
- named-space definitions;
- nearest-neighbor outputs;
- forecast table separated from observations;
- reproduction log;
- routing decisions and later outcomes;
- negative-result archive.

## Firewalls

- A score is not a permanent identity.
- Preference is not correctness.
- Vendor-reported does not mean useless; protocol accompanies the number.
- Independent does not mean universal.
- Missing is not failure.
- A forecast never becomes observed through repetition.
- New model names require date-specific verification.
- Never route a high-stakes workflow from a spreadsheet coordinate alone.

## Carry line

> A benchmark result is a coordinate, not a universal model property.
