# Backlog Strategy & Tradeoff Decisions

## How Prioritization Was Done

Backlog items were prioritized using the following lens:
1. Safety and system risk
2. Impact to operators and operations
3. Stability and long‑run behavior
4. Cost of late discovery

## A Key Tradeoff Example

We faced a decision:

Option A  
Proceed with a visible UI enhancement requested by stakeholders.

Option B  
Delay UI work to focus on long‑run stability, alarm clarity,
and recovery behavior.

Although Option A was easier to justify in the short term,
I chose Option B.

Rationale:
- A visually improved system that fails unpredictably
  erodes trust faster than missing features.
- Stability issues discovered late are expensive and disruptive.
- In this domain, reliability is a core product feature.

This decision delayed one feature but prevented
multiple late‑stage issues.

## Product Insight

A Product Owner’s role includes choosing what **not** to build,
especially when risk is high.
