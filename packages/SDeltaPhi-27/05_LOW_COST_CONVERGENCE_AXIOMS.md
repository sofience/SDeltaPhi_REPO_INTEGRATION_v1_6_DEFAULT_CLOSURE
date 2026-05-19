# Low-Cost Convergence Axioms

## Axiom 27-1 — Operational Cost and Restoration Cost Must Be Separated

The cost of continuing along a path is not the same as the cost of abandoning, revising, or reopening that path.

```text
C_op(P) != C_rest(P)
```

## Axiom 27-2 — Exception Compression Lowers Operational Cost

When exception frequency falls, routine continuation becomes cheaper.

```text
E(P)↓ -> C_op(P)↓
```

## Axiom 27-3 — Cheap Continuation Increases Repetition

A path with lower operational cost is selected more often.

```text
C_op(P)↓ -> repeated selection↑
```

## Axiom 27-4 — Repetition Produces Fixation

Repeated selection increases path fixation.

```text
R(P)↑ -> F(P)↑
```

## Axiom 27-5 — Fixation Raises Restoration Cost

As path fixation increases, the cost of restoration, revision, or reopening rises.

```text
F(P)↑ -> C_rest(P)↑
```

## Axiom 27-6 — Low-Cost Convergence Generates Practical Irreversibility

Repeated low-cost operation can manufacture the restoration cost explosion by which irreversibility is later judged.

```text
E(P)↓ -> C_op(P)↓ -> R(P)↑ -> F(P)↑ -> C_rest(P)↑
```
