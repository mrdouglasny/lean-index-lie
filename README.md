# lean-index-lie

Topical index for Lie algebra formalization in Lean 4. **[How to use this index in your project](https://github.com/mrdouglasny/lean-index/blob/main/docs/use-topic-index.md)**

**6,581 topic-matched declarations** across **18 repositories** (scanned 569 repos, 298K declarations).

Tracks Lean declarations related to:
- **Lie algebras** (2,747 matches): Lie rings, subalgebras, ideals, Killing form, Engel/Lie theorems
- **Representation theory** (2,624 matches): Lie modules, weight spaces, irreducibility, Schur's lemma
- **Root systems** (1,210 matches): root pairings, Dynkin diagrams, Weyl/Coxeter groups, Cartan matrices

See [SELECTION.md](SELECTION.md) for exact selection criteria. See [REPOS.md](REPOS.md) for all indexed repositories.

## Indexed Repos

| Repository | Topic Matches | Description |
|-----------|:---:|-------------|
| [leanprover-community/mathlib4](https://github.com/leanprover-community/mathlib4) | 5,000 | The math library for Lean 4 |
| [LieLean/LowDimSolvClassification](https://github.com/LieLean/LowDimSolvClassification) | 249 | Low-dimensional solvable Lie algebra classification |
| [kkytola/VirasoroProject](https://github.com/kkytola/VirasoroProject) | 113 | Virasoro algebra formalization |
| [kbuzzard/ClassFieldTheory](https://github.com/kbuzzard/ClassFieldTheory) | 64 | Class field theory (uses Lie infrastructure) |
| [themathqueen/monlib4](https://github.com/themathqueen/monlib4) | 40 | Operator algebras (von Neumann, Lie concepts) |
| [bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep](https://github.com/bicmr-ai4math/Group6-Formalization-on-Lie-algebra-rep) | 35 | Lie algebra representation formalization |
| [ocfnash/LieClassification](https://github.com/ocfnash/LieClassification) | 3 | Classification of finite-dimensional Lie algebras |
| [PlanetMacro/LieRinehart](https://github.com/PlanetMacro/LieRinehart) | 3 | Lie-Rinehart algebras |

Additional repos are discovered automatically via Lean Reservoir and GitHub search.

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
