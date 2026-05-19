# Restoration Cost Model

SΔϕ-26 defines restoration cost as:

```text
C_restore(t) = f(E, T, I, N, M)
```

## Components

```text
E = energetic / material cost
T = temporal cost
I = informational reconstruction cost
N = network propagation cost
M = memory / interpretive residue cost
```

## Reversibility condition

```text
Reversible iff C_restore(t) < theta
```

## Irreversibility condition

```text
Irreversible iff C_restore(t) >= theta
```

## Event fixation

```text
Fixation(e) iff C_restore(e) >= theta
```

## Diagnostic question

Is the return path still selectable under the operative cost structure?
