# Selection Criteria

This document describes exactly which declarations are included in this index. Only declarations matching at least one criterion below are indexed — everything else (number theory, combinatorics, etc.) is excluded.

## Topic: lie-algebras

### Module prefixes (confidence: 1.0)
Everything under these Mathlib module paths is included:
- `Mathlib.Algebra.Lie.*` — core Lie algebra theory
- `Mathlib.Geometry.Manifold.Algebra.LieGroup` — Lie groups on manifolds
- `Mathlib.Geometry.Manifold.GroupLieAlgebra` — group Lie algebra construction

### Type signature mentions (confidence: 0.8)
Any declaration whose type signature mentions one of these identifiers:
- `LieAlgebra`, `LieRing`, `LieGroup`
- `LieSubalgebra`, `LieIdeal`, `LieModule`
- `LieHom`, `LieEquiv`, `LieSubmodule`
- `killingForm`, `IsSl2Triple`

### Name patterns (confidence: 0.6)
Declarations whose fully qualified name matches:
- `.*Lie[A-Z].*` — names containing "Lie" followed by uppercase
- `.*Cartan[A-Z].*` — Cartan-related names
- `.*Killing[A-Z].*` — Killing form related
- `.*Engel[A-Z].*` — Engel's theorem related

### Search keywords (for GitHub/Reservoir discovery)
- "Lie algebra", "Cartan subalgebra", "semisimple Lie"
- "nilpotent Lie", "solvable Lie", "Killing form", "adjoint representation"

## Topic: root-systems

### Module prefixes (confidence: 1.0)
- `Mathlib.LinearAlgebra.RootSystem.*` — root system theory
- `Mathlib.GroupTheory.Coxeter.*` — Coxeter groups
- `Mathlib.Data.Matrix.Cartan` — Cartan matrices

### Type signature mentions (confidence: 0.8)
- `RootSystem`, `RootPairing`
- `CoxeterMatrix`, `CoxeterGroup`
- `WeylGroup`, `CartanMatrix`

### Name patterns (confidence: 0.6)
- `.*RootSystem.*`, `.*RootPairing.*`, `.*RootSpace.*`
- `.*Dynkin.*`, `.*WeylGroup.*`, `.*Coxeter.*`

### Search keywords
- "root system", "Dynkin diagram", "Weyl group"
- "Coxeter group", "Cartan matrix", "root pairing"

## Topic: representation-theory

### Module prefixes (confidence: 1.0)
- `Mathlib.RepresentationTheory.*`
- `Mathlib.Algebra.Lie.Weights.*`

### Type signature mentions (confidence: 0.8)
- `Representation`, `LieModule`
- `IsWeight`, `genWeightSpace`
- `rootSpace`, `WeightSpace`

### Name patterns (confidence: 0.6)
- `.*WeightSpace.*`, `.*HighestWeight.*`
- `.*Irreducible[MR].*`, `.*Schur[A-Z].*`
- `.*Representation[A-Z].*`

### Search keywords
- "representation theory", "Lie module", "weight space"
- "highest weight", "irreducible representation", "Schur lemma"

---

## How selection works

1. **Mathlib declarations** are downloaded from the official docs cache (~384K total).
2. **Non-Mathlib repos** are discovered from Lean Reservoir (565+ packages) and GitHub search.
3. Repos are **pre-filtered** by name/description matching topic keywords before cloning.
4. Each declaration is tested against the criteria above.
5. Only declarations matching **at least one criterion** from **any topic** are stored in REPOS.md.
6. Confidence scores indicate match quality:
   - **1.0** (module prefix): definite match, the declaration is in a relevant module
   - **0.8** (type mention): high confidence, the declaration uses relevant types
   - **0.6** (name pattern): moderate confidence, regex match on name

## Previewing changes

Before modifying `topics.yaml`, preview the impact:

```bash
# Show how many declarations would be selected with current topics
lean-index preview-topics

# Show how many declarations would be selected with a modified topics.yaml
lean-index preview-topics --config /path/to/modified/topics.yaml
```
