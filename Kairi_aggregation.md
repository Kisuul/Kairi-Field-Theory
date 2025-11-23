Kairi Aggregation Rules

Version: Draft 1 Date: 22 November 2025

This document formalizes the aggregation behavior of Kairi units in KFT, including their allowed configurations, stability conditions, transitions, and physical interpretation.


---

1. Definitions

1.1 Kairi (K)

A fundamental excitonic unit with:

A handedness or mirror-state (K⁺, K⁻)

A boundary-layer count ℓ ≥ 1

A phase orientation θ ∈ [0, 2π)


1.2 Layer Parity

Odd-layer Kairi (ℓ = 1, 3, 5, ...): interact with our visible-sector rings.

Even-layer Kairi (ℓ = 2, 4, 6, ...): orthogonal sector; non-interacting unless parity transitions occur.


Parity transitions:

Gain layer: K(ℓ) → K(ℓ + 1)

Lose layer: K(ℓ) → K(ℓ − 1)


These require boundary instabilities or external excitation.


---

2. Aggregation Rules

2.1 Lone Kairi

Allowed but dynamically sterile.

No persistent structures form unless a partner appears.

Equivalent to a free excitation drifting in field-space.


Stability: Marginal (neither stable nor unstable).


---

3. Pairs (Dyads)

3.1 K⁺ + K⁻ Mirrors

Pairs of opposite mirror-state can bind.

However, they have direct annihilation channels.

Annihilation is

unlikely if θ-mismatch > threshold,

more likely when phase-locked or forced into alignment.



Stability: Metastable.

3.2 Same-state Dyads (K⁺ + K⁺ or K⁻ + K⁻)

Repulsive unless mediated by a third unit.

No direct annihilation.


Stability: Non-binding.


---

4. Triads (Minimal Stable Ring)

4.1 n = 3 Rings

Minimal stable configuration.

Phase constraint: 120° offsets.

Requires odd-layer parity.

Triads suppress annihilation channels by distributing phase and stress.


Stability: Stable.

Triads are the first structure that can genuinely store and transmit information or energetic form.


---

5. Higher-Order Rings

5.1 Odd-n Rings (n = 5, 7, 9, ...)

All odd-n structures are allowed.

Increasing n increases:

internal degrees of freedom,

excitation capacity,

renormalization contribution.


Odd-n rings dominate the observable-sector interactions.


Stability: Stable for all n ≥ 3.

5.2 Even-n Rings (n = 4, 6, 8, ...)

Allowed only for even-layer Kairi.

Do not couple to our visible-sectors.

Interaction requires parity change.


Stability: Stable, but hidden.

Transition example:

Even-ring (n = 4) loses a layer → becomes an odd-layer ring → becomes visible.



---

6. Aggregation Dynamics

6.1 Growth

K + Ring(n) → Ring(n + 1) if:

phase slot is available,

parity matches,

energy budget allows.


6.2 Fragmentation

Ring(n) → Ring(k) + Ring(n − k) if:

overstressed,

externally perturbed,

mismatched excitations.


6.3 Annihilation Channels

Only available for:

mirror dyads,

certain stressed triads,

boundary-layer shedding events.



---

7. Summary Table

Structure	Allowed?	Parity Requirement	Stability	Notes

Lone K	Yes	Any	Marginal	Does nothing alone
Pair (mirror)	Yes	Same ℓ	Metastable	Can annihilate
Pair (same-state)	No	–	–	Repulsive
Triad (n=3)	Yes	Odd ℓ	Stable	Minimal stable ring
Odd-n rings	Yes	Odd ℓ	Stable	Primary sector
Even-n rings	Yes	Even ℓ	Stable	Hidden sector



---

8. Open Questions

Does aggregation favor Fibonacci scaling or golden-angle packing across all sectors?

What are the exact thresholds for dyad annihilation vs phase slip survival?

Does large-n behavior approximate continuum field configurations?
