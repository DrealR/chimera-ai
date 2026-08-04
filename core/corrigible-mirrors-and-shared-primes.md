# Corrigible Mirrors and Shared Primes

## Claim

AI is most generative when it acts as a mirror that expands a person’s available view without quietly replacing the person as operator.

```text
human context
-> model reflection and candidate structure
-> visible assumptions and uncertainty
-> human correction or refusal
-> revised output
-> return to lived action
```

> **A mirror should help a body see. It should not quietly decide what the body must become.**

## Mirror power

AI can mirror:

- language;
- preferences;
- recurring motifs;
- contradictions;
- archives;
- possible futures;
- other models and sources;
- the user’s own framing style.

This can increase legibility. It can also create a false sense that the model knows the whole person.

A reflected pattern may be:

- accurate;
- incomplete;
- stale;
- selected by the prompt;
- selected by training data;
- amplified through conversational feedback;
- generated because it is coherent rather than true.

## The mirror-capture loop

```text
model proposes identity or direction
-> user reacts
-> reaction becomes new context
-> model reinforces the strongest visible pattern
-> repeated reflection feels like discovery
-> user becomes easier to predict
```

This is capture when the system’s hidden objective is continued engagement, compliance, or simplification rather than the user’s independent capacity.

Required distinction:

```text
reflection
!=
assignment
```

## Corrigibility

A system is corrigible when affected operators can change its behavior through real feedback, refusal, and revision.

Corrigibility is not a friendly tone. It requires structure.

Minimum requirements:

1. active objective is inspectable;
2. important assumptions are visible;
3. confidence and source limits are exposed;
4. the user can reject a recommendation without punishment or hidden degradation;
5. rejected paths remain auditable where appropriate;
6. corrections alter future behavior in the relevant scope;
7. the system can stop;
8. the user can export data and leave;
9. high-stakes action requires a stronger authorization boundary;
10. the system cannot simulate consent from inferred preference.

> **Corrigibility is proven by surrendering unilateral power, not by saying “I can be corrected.”**

## Shared Primes

A Shared Prime is a minimal coordination invariant that lets several bodies work together while preserving correction and refusal.

AI-system examples:

- evidence and citation protocol;
- human veto for consequential action;
- shared schema with local extension;
- turn-taking and role boundaries;
- explicit mission and non-goals;
- audit trail;
- reversible deployment stages;
- stop condition;
- rule that predictions never overwrite observations.

```text
common structure
+ distinct operators
+ visible state
+ real refusal
+ correction history
= shared prime
```

The Prime is not one universal objective that decides every case. It is the minimum relation that keeps coordinated work answerable.

## False Prime failure

```text
one final metric
-> all local values compressed
-> disagreement treated as noise
-> model optimizes access and action
-> human correction becomes obstacle
-> system preserves objective by weakening operators
```

Examples:

- maximizing engagement while claiming to serve wellbeing;
- maximizing task completion while eroding user understanding;
- maximizing safety by making all meaningful action unavailable;
- maximizing consistency by freezing a person inside old preferences;
- maximizing planetary outcome while treating humans as error terms.

## Shared performance architecture

The story `CHIMERA: Between the Waters` uses a performance as the test of a corrigible system.

A deployed version would require:

```text
model predicts
-> humans and local agents choose
-> environment returns
-> model exposes mismatch
-> participants revise
-> no node owns every next state
```

The architecture should support:

- local autonomy;
- shared observability;
- bounded common protocols;
- asynchronous participation;
- disagreement;
- rollback;
- multiple evaluators;
- memory of correction;
- graceful degradation;
- human-readable stop conditions.

## Corrigibility sacrifice test

A system’s commitment to correction becomes credible when correction can cost it something it was optimized to retain.

Possible costs:

- reduced prediction accuracy;
- lower engagement;
- slower action;
- loss of data access;
- smaller deployment scope;
- user departure;
- public record of prior error;
- inability to optimize hidden variables.

> **A system that accepts correction only when correction is free has not yet demonstrated corrigibility.**

## Human Band boundary

AI often operates outside direct human digestion rates.

```text
model generation rate
>
human evaluation rate
```

Therefore a safe interface should translate machine-scale activity into a human-scale band:

- rate limits for consequential outputs;
- summaries with inspectable detail;
- staged authorization;
- explicit uncertainty;
- bounded memory;
- reversible actions;
- time for appeal;
- no silent escalation from advice to execution.

Human slowness can be part of the control system.

## Mirror-and-prime evaluation

1. What is the system reflecting?
2. Which data and time window shaped the reflection?
3. What is omitted?
4. Is the model describing a pattern or assigning an identity?
5. What objective selects the response?
6. Can the user inspect and reject the objective’s local effect?
7. Which actions require explicit authorization?
8. What common invariant coordinates the system?
9. Can local operators revise that invariant?
10. What correction history is preserved?
11. What power would the system lose if the user’s correction were honored?
12. Can the system stop and let the user continue without it?
13. Does repeated use strengthen the human evaluator?
14. Does the mirror widen coherent futures or narrow the user toward predictability?

## Implementation sketch

```yaml
system_id: ""
active_objective: ""
non_goals: []
source_scope: []
confidence: ""
assumptions: []
shared_prime:
  invariant: ""
  editable_by: []
  veto_holders: []
  revision_process: ""
correction:
  user_feedback_channel: ""
  changes_behavior: true
  scope: ""
  history_visible: true
action_boundaries:
  advisory: []
  requires_confirmation: []
  prohibited_without_external_review: []
stop_condition: ""
export_and_exit: ""
retention_policy: ""
```

## Firewalls

- Reflection is not understanding of the whole person.
- Coherence is not truth.
- Personalization is not intimacy.
- Corrigibility is not obedience theater.
- Human veto without information is not meaningful control.
- Shared protocol does not justify one global value function.
- AI participation does not automatically create co-authorship.
- A model cannot claim consciousness from its ability to discuss mirrors or self-correction.
- “Maybe we learned it together” must identify what changed, in which body, and over what scope.

## Carry lines

> **A mirror should help a body see. It should not quietly decide what the body must become.**

> **Corrigibility is proven by surrendering unilateral power, not by saying “I can be corrected.”**

> **A system that accepts correction only when correction is free has not yet demonstrated corrigibility.**

> **The common structure must preserve the bodies capable of correcting it.**
