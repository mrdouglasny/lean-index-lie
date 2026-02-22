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

### Curated Repos

| Repository | Description |
|-----------|-------------|
| [ocfnash/LieClassification](https://github.com/ocfnash/LieClassification) | Classification of finite-dimensional Lie algebras |
| [LieLean/LowDimSolvClassification](https://github.com/LieLean/LowDimSolvClassification) | Low-dimensional solvable Lie algebra classification |
| [smmercuri/lie-theory-lean4](https://github.com/smmercuri/lie-theory-lean4) | Lie theory in Lean 4 |
| [erdOne/lie_algebras](https://github.com/erdOne/lie_algebras) | Lie algebras in Lean |

Additional repos are discovered automatically from Lean Reservoir and GitHub search.

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
