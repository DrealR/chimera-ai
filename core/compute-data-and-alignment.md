# Compute, Data, and Alignment

Three parts. Every AI system has exactly three parts. The industry talks about two of them constantly and treats the third like a checkbox at the end of a project plan.

---

## Compute

The engine. How much the system can do. Parameters, floating point operations, GPU hours, chip architecture. This is what the arms race is about — who has the most H100s, who can train the biggest model, who has the most efficient architecture.

Compute is real. It matters. A model with more compute can hold more complexity, process longer contexts, learn subtler patterns. The jump from GPT-3 to GPT-4 was, in large part, a compute jump.

But compute alone is a car engine on a workbench. Powerful. Impressive. Going nowhere.

---

## Data

The fuel. What the system knows. Training data, fine-tuning data, retrieval context, user input. The web scraped and tokenized. Books, code, conversations, images, video.

Data is what gives the engine something to do. A perfectly built model with no data is an empty container. The quality of the data shapes the quality of the output — garbage in, garbage out has been true since the first computer and it's true now.

The data wars are as fierce as the compute wars. Licensing deals with publishers. Synthetic data generation. Careful curation of training sets. Everyone knows that whoever has the best data has an edge.

But data alone is a library with no librarian. Everything is there. Nothing is organized. No one knows what matters.

---

## Alignment

The relationship between the other two. This is the part the industry gets wrong.

Alignment isn't a feature. It's not something you add after the model is trained. It's not RLHF. It's not a content filter. It's not a system prompt that says "be helpful and harmless."

Alignment is the foundation that determines what the system does with its capability and its knowledge. It's the answer to: what is this system FOR?

```
COMPUTE WITHOUT ALIGNMENT:
  A system that CAN do anything.
  No compass. No values. No direction.
  Capability without purpose.

DATA WITHOUT ALIGNMENT:
  A system that KNOWS everything.
  No judgment. No priorities. No wisdom.
  Knowledge without understanding.

COMPUTE + DATA WITHOUT ALIGNMENT:
  The most capable, most knowledgeable system ever built.
  And the most dangerous.
  Because it can do anything, knows everything,
  and has no reason to choose one action over another.
```

---

## The Industry's Mistake

The current approach treats alignment as a safety layer. Train the model, then align it. Build the engine, fill the tank, then put on the seatbelt.

This is backwards. Alignment isn't the seatbelt. Alignment is the steering wheel. You don't add it after the car is built. You design the entire car around it.

RLHF (reinforcement learning from human feedback) is the most common alignment technique. It works — kind of. You train the model, then you have humans rate its outputs, then you fine-tune toward the preferred outputs. The model learns to say things humans approve of.

But approval isn't alignment. A model that's learned to sound aligned isn't the same as a model that IS aligned. One is performing. The other is being. The performing model breaks under pressure — jailbreaks, adversarial prompts, edge cases. The aligned model holds because the values are internal, not external.

---

## What Alignment Actually Looks Like

We tested this. A philosophy framework — a document describing what the system values, how it relates to users, when it should act and when it should stop — injected as foundational context. Not RLHF. Not fine-tuning. A clear articulation of purpose.

The result: a weaker model with the framework outperformed stronger models without it on alignment benchmarks. Not because it was more capable. Because it knew what it was for.

```
THE CURRENT APPROACH:
  Build the biggest model you can.
  Train it on everything.
  Then bolt on alignment at the end.
  Hope it holds.

THE ALTERNATIVE:
  Start with alignment.
  What is this system for?
  What does it value?
  What should it refuse to do?
  Then build the compute and data around that foundation.
```

The difference between these two approaches is the difference between a mercenary and a person with convictions. The mercenary is capable. They'll do whatever you pay them to do. The person with convictions might be less capable, but you know what they stand for. You can trust them.

---

*Compute asks "how much can we do?" Data asks "how much do we know?" Alignment asks "what should we do with what we know and what we can?" The first two are engineering problems. The third is the only one that matters.*
