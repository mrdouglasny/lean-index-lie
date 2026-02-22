# lean-index-lie

Topic index for Lie algebra formalization in Lean 4.

Tracks Lean declarations related to:
- **Lie algebras**: Lie rings, subalgebras, ideals, Killing form, Engel/Lie theorems
- **Root systems**: root pairings, Dynkin diagrams, Weyl/Coxeter groups, Cartan matrices
- **Representation theory**: Lie modules, weight spaces, irreducibility, Schur's lemma

See [SELECTION.md](SELECTION.md) for exact selection criteria.

## Data Sources

### Mathlib (~5,900 declarations selected from ~384K)

Only the topic-relevant subset is indexed. See [SELECTION.md](SELECTION.md) for the full filtering criteria.

### Non-Mathlib Repos

| Repository | Stars | Description |
|-----------|-------|-------------|
| [LieLean/LowDimSolvClassification](https://github.com/LieLean/LowDimSolvClassification) | 9 | Low-dimensional solvable Lie algebra classification |
| [ocfnash/LieClassification](https://github.com/ocfnash/LieClassification) | 4 | Classification of finite-dimensional Lie algebras |
| [bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep](https://github.com/bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep) | 2 | Lie algebra representation formalization |

This is the **complete list** of known non-Mathlib Lean 4 repos with Lie algebra content (as of 2026-02-22). Additional repos are discovered automatically during `lean-index update` via Lean Reservoir and GitHub search.

## Usage

### As a consumer

```bash
pip install git+https://github.com/mrdouglasny/lean-index.git
lean-index fetch-db mrdouglasny/lean-index-lie
lean-index search "Killing form"
lean-index search --kind theorem --topic lie-algebras
lean-index stats
```

### Building locally

```bash
pip install git+https://github.com/mrdouglasny/lean-index.git
cd lean-index-lie
lean-index init                # Downloads Mathlib cache + creates topic-filtered DB
lean-index update              # Discovers repos + indexes + matches topics
lean-index stats
lean-index preview-topics      # Estimate impact of changing topics.yaml
```

## CI

The database is rebuilt weekly and published as a GitHub release. Download the latest with:

```bash
lean-index fetch-db mrdouglasny/lean-index-lie
```
