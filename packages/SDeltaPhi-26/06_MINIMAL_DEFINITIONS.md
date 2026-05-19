# Minimal Definitions

## Reversibility

A state transition is reversible when restoration to a prior state remains available at sufficiently low cost.

```text
Reversible iff C_restore(t) < theta
```

## Irreversibility

A state transition is irreversible when restoration cost exceeds the threshold of practical return.

```text
Irreversible iff C_restore(t) >= theta
```

## Event Fixation

An event becomes fixed when its reversal is no longer selected within the available cost structure.

```text
Fixation(e) iff C_restore(e) >= theta
```

## Restoration Cost

The total burden required to return from a present state to a prior state.

```text
C_restore(t) = f(E, T, I, N, M)
```

## theta — Practical Return Threshold

The system-dependent threshold below which return remains practically selectable.

## Formal Reversibility

Prior state restoration remains logically describable or computationally representable.

## Practical Irreversibility

Restoration remains formally conceivable but is no longer practically selectable.
