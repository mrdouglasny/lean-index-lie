# lean-index-lie

Topical index for Lie algebra formalization in Lean 4. **[How to use this index in your project](https://github.com/mrdouglasny/lean-index/blob/main/docs/use-topic-index.md)**

**6,181 topic-matched declarations** across **6 repositories** (scanned 12 repos, 6,488 declarations).

Tracks Lean declarations related to:
- **Representation theory**: Lie modules, weight spaces, irreducibility, Schur's lemma
- **Lie algebras**: Lie rings, subalgebras, ideals, Killing form, Engel/Lie theorems
- **Root systems**: root pairings, Dynkin diagrams, Weyl/Coxeter groups, Cartan matrices

See [SELECTION.md](SELECTION.md) for exact selection criteria. See [REPOS.md](REPOS.md) for all indexed repositories.

## Indexed Repos

| Repository | Topic Matches | Description |
|-----------|:---:|-------------|
| [leanprover-community/mathlib4](https://github.com/leanprover-community/mathlib4) | 5,782 | Mathlib: the math library for Lean 4 |
| [LieLean/LowDimSolvClassification](https://github.com/LieLean/LowDimSolvClassification) | 249 | Low-dimensional solvable Lie algebra classification (Lean 4) |
| [rootkiller6788/mini-representation-lie-theory](https://github.com/rootkiller6788/mini-representation-lie-theory) | 111 | Representation theory and Lie theory built from scratch, learn algebraic... |
| [bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep](https://github.com/bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep) | 32 | Formalization of finite-dimensional Lie algebra representations (Lean 4) |
| [awodey/joyal](https://github.com/awodey/joyal) | 6 |  |
| [ocfnash/LieClassification](https://github.com/ocfnash/LieClassification) | 1 | Classification of finite-dimensional Lie algebras (Lean 4) |

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

## License

Copyright 2026 Michael R. Douglas. MIT License.
