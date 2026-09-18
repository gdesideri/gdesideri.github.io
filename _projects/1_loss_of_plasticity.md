---
layout: page
title: characterizing loss of plasticity in continual learning
description: mapping benchmark data properties to network behaviours
importance: 1
category: research
---

I am extending the understanding that we have so far of **loss of plasticity** in continual
learning by characterizing the existing benchmarks through their data properties and mapping
them to specific behaviours in the network.

Loss of plasticity — the progressive inability of a neural network to keep learning from new
data — is usually studied benchmark by benchmark, and the mitigations we have are largely
empirical. My aim is to make the link between the two explicit: what is it about the data a
benchmark generates that triggers a particular failure mode inside the network?

The work has two sides:

- **Characterizing the benchmarks.** Describing the standard continual learning benchmarks in
  terms of their underlying data properties, rather than treating them as opaque task
  sequences.
- **Mapping properties to behaviours.** Connecting those properties to the specific behaviours
  they induce in the network during training.

Together, this should help explain _why_ existing methods work where they do, and open new
directions for improving them.
