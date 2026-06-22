# Changelog (since 2026-06-15)

## New Declarations (6488)

### Group6-Formalization-on-Lie-algebra-rep (+42)

- `card_eq_card_quotient_mul_card_subgroup'` (theorem) in Exercise.abstract_algebra
- `center_eq_top'` (lemma) in Exercise.abstract_algebra
- `Representation` (abbrev) in LieAlgRep.CasimirElement
- `IsAssociativeBilForm` (def) in LieAlgRep.CasimirElement
- `CasimirElement` (def) in LieAlgRep.CasimirElement
- `bracket_in_glV` (lemma) in LieAlgRep.CasimirElement
- `comm_zero_bracket` (lemma) in LieAlgRep.CasimirElement
- `Representation.asLieModule` (def) in LieAlgRep.lie_algebra
- `Representation.asLieModuleEquiv` (def) in LieAlgRep.lie_algebra
- `Representation.smul_map` (lemma) in LieAlgRep.lie_algebra
- `Representation.kernel` (def) in LieAlgRep.lie_algebra
- `Representation.mem_kernel` (theorem) in LieAlgRep.lie_algebra
- `Representation.lie_ring_module_of_lie_hom` (instance) in LieAlgRep.lie_algebra
- `Representation.lie_module_of_lie_hom` (instance) in LieAlgRep.lie_algebra
- `Representation.lie_module_of_lie_hom_apply` (lemma) in LieAlgRep.lie_algebra
- `Representation.coe_add` (lemma) in LieAlgRep.lie_algebra
- `Representation.coe_zero` (lemma) in LieAlgRep.lie_algebra
- `Representation.coe_smul` (lemma) in LieAlgRep.lie_algebra
- `Representation.LieSubmodule'.liesubtype` (def) in LieAlgRep.lie_algebra
- `Representation.domRestrict'` (def) in LieAlgRep.lie_algebra
- `Representation.dom_restrict'_add` (theorem) in LieAlgRep.lie_algebra
- `Representation.dom_restrict'_zero` (theorem) in LieAlgRep.lie_algebra
- `Representation.dom_restrict'_smul` (theorem) in LieAlgRep.lie_algebra
- `Representation.dom_restrict'_map_lie` (theorem) in LieAlgRep.lie_algebra
- `Representation.LieModuleHomResScalar` (def) in LieAlgRep.lie_algebra
- `Representation.mem_LieModuleHomResScalar` (lemma) in LieAlgRep.lie_algebra
- `Representation.ResScalar` (lemma) in LieAlgRep.lie_algebra
- `Representation.obtain_scalar` (def) in LieAlgRep.lie_algebra
- `Representation.lie_apply_of_lie_hom_res_scalar` (lemma) in LieAlgRep.lie_algebra
- `Representation.LieModuleHomResZero` (def) in LieAlgRep.lie_algebra
- `Representation.LieModuleHomResZero'` (def) in LieAlgRep.lie_algebra
- `Representation.mem_LieModuleHomResZero'` (lemma) in LieAlgRep.lie_algebra
- `Representation.ResZero` (lemma) in LieAlgRep.lie_algebra
- `Representation.IsIrreducible` (class) in LieAlgRep.lie_algebra
- `Representation.IsCompletelyReducible` (class) in LieAlgRep.lie_algebra
- `Schur` (lemma) in LieAlgRep.lie_algebra
- `HasBracket` (instance) in LieAlgRep.lie_algebra
- `Codimension` (def) in LieAlgRep.lie_algebra
- `hello` (def) in LieAlgRep.Basic
- `Ideal.IsPrime_not_mem_mul` (theorem) in LieAlgRep.prime_ideal_aviod_Thm
- `Multiset.erase_refl` (theorem) in LieAlgRep.prime_ideal_aviod_Thm
- `prime_ideal_finset_version` (theorem) in LieAlgRep.prime_ideal_aviod_Thm

### LieClassification (+1)

- `LieAlgebra.equivGeckConstruction` (def) in LieClassification.Main

### LowDimSolvClassification (+300)

- `LieAlgebra.Dim3.aux_dim_comm` (lemma) in Lie.Classification3
- `LieAlgebra.Dim3.heisenberg_iff` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.affinePlusAbelian_iff` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.hyperbolic_iff` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.family_iff` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.classification` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.Family.iso_iff` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.Family.not_iso_hyperbolic` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.Family.iso_1` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.Family.not_iso_0_1` (theorem) in Lie.Classification3
- `LieAlgebra.Dim3.Family.iso_0` (theorem) in Lie.Classification3
- `LieAlgebra.mkAbelian` (def) in Lie.InstancesConstructions
- `LieAlgebra.Abelian.DerivationOfLinearMap'` (def) in Lie.InstancesConstructions
- `LieAlgebra.Abelian.DerivationOfLinearMap` (def) in Lie.InstancesConstructions
- `LieAlgebra.Abelian.DerivationCoeLinearMap` (theorem) in Lie.InstancesConstructions
- `LieAlgebra.Abelian.DerivationCoeFun` (theorem) in Lie.InstancesConstructions
- `LieAlgebra.Abelian.DerivationCoeFun'` (theorem) in Lie.InstancesConstructions
- `LieAlgebra.ofAffineEquivAux` (def) in Lie.InstancesConstructions
- `LieAlgebra.OfAffineEquiv` (abbrev) in Lie.InstancesConstructions
- `LieAlgebra.RealHyperbolicAux'` (def) in Lie.InstancesConstructions
- `LieAlgebra.RealHyperbolicAux` (def) in Lie.InstancesConstructions
- `LieAlgebra.RealHyperbolic` (abbrev) in Lie.InstancesConstructions
- `LieAlgebra.RealHyperbolic'` (abbrev) in Lie.InstancesConstructions
- `LieSemidirectProduct` (def) in Lie.Semidirect
- `LieSemidirectProduct.ext` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.add_left` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.add_right` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.zero_left` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.zero_right` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.neg_left` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.neg_right` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.smul_left` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.smul_right` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.bracket_def` (lemma) in Lie.Semidirect
- `LieSemidirectProduct.inl` (def) in Lie.Semidirect
- `LieSemidirectProduct.inr` (def) in Lie.Semidirect
- `LieSemidirectProduct.fst` (def) in Lie.Semidirect
- `LieSemidirectProduct.fst_inl` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.fst_inr` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.fst_inl'` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.fst_inr'` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.snd_inl'` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.snd_inr'` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.inl_left_add_inr_right` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.leftSubalgebra` (def) in Lie.Semidirect
- `LieSemidirectProduct.rightIdeal` (def) in Lie.Semidirect
- `LieSemidirectProduct.rightIdeal_equiv_right` (def) in Lie.Semidirect
- `LieSemidirectProduct.range_inr_eq_ker_fst` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.finrank_eq` (theorem) in Lie.Semidirect
- `LieSemidirectProduct.isAlmostAbelian` (theorem) in Lie.Semidirect
- ... and 250 more

### finite-groups (+48)

- `FG.matrix_representation` (structure) in src.matrix_representation
- `FG.matrix_representation.is_equivalent_symm` (lemma) in src.matrix_representation
- `FG.matrix_representation.is_equivalent_iff` (lemma) in src.matrix_representation
- `FG.matrix_representation.irreducible_representation` (def) in src.matrix_representation
- `FG.schur_lemma.schur_lemma₂` (lemma) in src.schur_lemma
- `FG.finite_group` (class) in src.basic.finite_group
- `FG.linear_operator` (def) in src.basic.representation
- `FG.representation` (class) in src.basic.representation
- `FG.vec3` (structure) in src.linear_space3.data
- `FG.vec3.vector3` (def) in src.linear_space3.data
- `FG.vec3.from_vector_eq` (lemma) in src.linear_space3.data
- `FG.vec3.equiv_vector` (def) in src.linear_space3.data
- `FG.mat3` (structure) in src.linear_space3.data
- `FG.mat3.matrix3` (def) in src.linear_space3.data
- `FG.mat3.from_matrix_eq` (lemma) in src.linear_space3.data
- `FG.mat3.equiv_matrix` (def) in src.linear_space3.data
- `FG.mat3.mat_dot_vec_assoc` (lemma) in src.linear_space3.data
- `FG.mat3_representation` (class) in src.linear_space3.mat3_representation
- `FG.mat3.is_invertible` (def) in src.linear_space3.invertible_mat3
- `FG.mat3.unitary_is_inverible` (lemma) in src.linear_space3.invertible_mat3
- `FG.mat3.inverse` (def) in src.linear_space3.invertible_mat3
- `FG.mat3.det_iff` (theorem) in src.linear_space3.invertible_mat3
- `FG.mat3.inverse_invertible` (lemma) in src.linear_space3.invertible_mat3
- `FG.vec` (def) in src.linear_space.vector
- `FG.vec.smul` (def) in src.linear_space.vector
- `FG.block_diagonal` (inductive) in src.linear_space.block_diagonal
- `FG.block_diagonal.to_func` (def) in src.linear_space.block_diagonal
- `FG.miscs.vector_annihilates_right` (def) in src.linear_space.miscs
- `FG.miscs.vector_annihilates_left` (def) in src.linear_space.miscs
- `FG.miscs.vector_annihilates` (def) in src.linear_space.miscs
- `FG.miscs.vector_annihilates_or_ivertible` (lemma) in src.linear_space.miscs
- `FG.matrix_func` (def) in src.linear_space.square_matrix
- `FG.square_matrix` (def) in src.linear_space.square_matrix
- `FG.square_matrix.is_invertible` (def) in src.linear_space.square_matrix
- `FG.square_matrix.det1_eq` (lemma) in src.linear_space.square_matrix
- `FG.square_matrix.det2_eq` (lemma) in src.linear_space.square_matrix
- `FG.invertible_matrix` (def) in src.linear_space.invertible_matrix
- `FG.example_parity.ℤ₂` (inductive) in src.examples.Z2
- `FG.example_parity.ℤ₂.rep` (def) in src.examples.Z2
- `FG.example_S₃.S₃` (inductive) in src.examples.S3
- `FG.example_S₃.S₃.is_non_abelian` (lemma) in src.examples.S3
- `FG.example_int.group_int` (structure) in src.examples.int_addition
- `FG.example_int.group_int.rep` (def) in src.examples.int_addition
- `FG.example_int.group_int.rep.is_reducible_by_P` (lemma) in src.examples.int_addition
- `FG.example_Z₃.Z₃` (inductive) in src.linear_space3.examples.Z3
- `FG.example_Z₃.Z₃.rep1` (def) in src.linear_space3.examples.Z3
- `FG.example_Z₃.Z₃.rep2` (def) in src.linear_space3.examples.Z3
- `FG.example_Z₃.Z₃.rep2.is_reducible` (lemma) in src.linear_space3.examples.Z3

### joyalRepresentationTheorem (+9)

- `toBoundedLatticeHom` (def) in JoyalRepresentationTheorem
- `BoundedLatticeSpectrum` (def) in JoyalRepresentationTheorem
- `BoundedLatticeSpectrum.exists_of_filter` (lemma) in JoyalRepresentationTheorem
- `joyalRepresentation` (def) in JoyalRepresentationTheorem
- `joyalRepresentation.latticeHom` (def) in JoyalRepresentationTheorem
- `joyalRepresentation.embedding` (lemma) in JoyalRepresentationTheorem
- `joyalRepresentation.injective` (theorem) in JoyalRepresentationTheorem
- `joyalRepresentation.orderEmbedding` (def) in JoyalRepresentationTheorem
- `joyalRepresentation.heytingHom` (def) in JoyalRepresentationTheorem

### mathlib4 (+5782)

- `Action.tensor_ρ_apply` (theorem) in Mathlib.RepresentationTheory.Action
- `AddGroupLieAlgebra` (def) in Mathlib.Geometry.Manifold.GroupLieAlgebra
- `AddGroupLieAlgebra.bracket_def` (theorem) in Mathlib.Geometry.Manifold.GroupLieAlgebra
- `AlgEquiv.toLieEquiv` (def) in Mathlib.Algebra.Lie.OfAssociative
- `AlgEquiv.toLieEquiv_apply` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgEquiv.toLieEquiv_symm_apply` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.coe_toLieHom` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.instCoeLieHom` (instance) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.toLieHom` (def) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.toLieHom_apply` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.toLieHom_comp` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.toLieHom_id` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `AlgHom.toLieHom_injective` (theorem) in Mathlib.Algebra.Lie.OfAssociative
- `Algebra.instLieAdmissibleAlgebra` (def) in Mathlib.Algebra.NonAssoc.LieAdmissible.Defs
- `AlgebraicGeometry.instGeometricallyIrreducibleMorphismRestrict` (instance) in Mathlib.AlgebraicGeometry.Geometrically.Irreducible
- `Array.toSubarray_eq_min` (theorem) in Init.Data.Slice.Array.Lemmas
- `CartanMatrix.A` (def) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_apply_le_zero_of_ne` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_diag` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_isSymm` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_one` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_three` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_transpose` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.A_two` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B` (def) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B_diag` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B_off_diag_nonpos` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B_one` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B_transpose` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.B_two` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C` (def) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C_diag` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C_off_diag_nonpos` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C_one` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C_transpose` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.C_two` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D` (def) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_diag` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_four` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_isSymm` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_off_diag_nonpos` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_one` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_three` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_three'` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_transpose` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.D_two` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.E₆` (def) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.E₆_diag` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.E₆_isSymm` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- `CartanMatrix.E₆_off_diag_nonpos` (theorem) in Mathlib.LinearAlgebra.Matrix.Cartan
- ... and 5732 more

### mini-representation-lie-theory (+305)

- `main` (def) in mini-lie-groups.Main
- `benchCT` (def) in mini-lie-groups.Benchmark.Princeton
- `exCType` (def) in mini-lie-groups.Test.Smoke
- `exA` (def) in mini-lie-groups.Test.Examples
- `exB` (def) in mini-lie-groups.Test.Examples
- `prodAB` (def) in mini-lie-groups.Test.Examples
- `homAB` (def) in mini-lie-groups.Test.Examples
- `regType` (def) in mini-lie-groups.Test.Regression
- `h` (def) in mini-lie-groups.Test.Regression
- `MiniCharacterTheory.Hom` (structure) in mini-character-theory.MiniCharacterTheory.Morphisms.Hom
- `MiniCharacterTheory.homComp` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Hom
- `MiniCharacterTheory.idHom` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Hom
- `MiniCharacterTheory.Iso` (structure) in mini-character-theory.MiniCharacterTheory.Morphisms.Iso
- `MiniCharacterTheory.idIso` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Iso
- `MiniCharacterTheory.isoComp` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Iso
- `MiniCharacterTheory.isEquivalent` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Equiv
- `MiniCharacterTheory.equivRefl` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Equiv
- `MiniCharacterTheory.equivSymm` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Equiv
- `MiniCharacterTheory.equivTrans` (def) in mini-character-theory.MiniCharacterTheory.Morphisms.Equiv
- `MiniCharacterTheory.mainResults` (def) in mini-character-theory.MiniCharacterTheory.Theorems.Main
- `MiniCharacterTheory.enumerateClasses` (def) in mini-character-theory.MiniCharacterTheory.Theorems.Classification
- `MiniCharacterTheory.Classification` (structure) in mini-character-theory.MiniCharacterTheory.Properties.ClassificationData
- `MiniCharacterTheory.sampleClassification` (def) in mini-character-theory.MiniCharacterTheory.Properties.ClassificationData
- `MiniCharacterTheory.invariant` (def) in mini-character-theory.MiniCharacterTheory.Properties.Invariants
- `MiniCharacterTheory.fundamentalInvariant` (def) in mini-character-theory.MiniCharacterTheory.Properties.Invariants
- `MiniCharacterTheory.MiniCharacterTheory.preservedByHom` (def) in mini-character-theory.MiniCharacterTheory.Properties.Invariants
- `MiniCharacterTheory.MiniCharacterTheory.preservedByIso` (def) in mini-character-theory.MiniCharacterTheory.Properties.Invariants
- `MiniCharacterTheory.MiniCharacterTheory.preservationTable` (def) in mini-character-theory.MiniCharacterTheory.Properties.Invariants
- `MiniCharacterTheory.computationalAspect` (def) in mini-character-theory.MiniCharacterTheory.Bridges.ToComputation
- `MiniCharacterTheory.topologicalAspect` (def) in mini-character-theory.MiniCharacterTheory.Bridges.ToTopology
- `MiniCharacterTheory.algebraicStructure` (def) in mini-character-theory.MiniCharacterTheory.Bridges.ToAlgebra
- `MiniCharacterTheory.geometricInterpretation` (def) in mini-character-theory.MiniCharacterTheory.Bridges.ToGeometry
- `MiniCharacterTheory.registerTheory` (def) in mini-character-theory.MiniCharacterTheory.Core.Objects
- `MiniCharacterTheory.theoryRegistry` (def) in mini-character-theory.MiniCharacterTheory.Core.Objects
- `MiniCharacterTheory.CoreType` (structure) in mini-character-theory.MiniCharacterTheory.Core.Basic
- `MiniCharacterTheory.basicOperation` (def) in mini-character-theory.MiniCharacterTheory.Core.Basic
- `MiniCharacterTheory.identityOp` (def) in mini-character-theory.MiniCharacterTheory.Core.Basic
- `MiniCharacterTheory.Product` (structure) in mini-character-theory.MiniCharacterTheory.Constructions.Products
- `MiniCharacterTheory.projLeft` (def) in mini-character-theory.MiniCharacterTheory.Constructions.Products
- `MiniCharacterTheory.projRight` (def) in mini-character-theory.MiniCharacterTheory.Constructions.Products
- `MiniCharacterTheory.Subobject` (structure) in mini-character-theory.MiniCharacterTheory.Constructions.Subobjects
- `MiniCharacterTheory.inclusion` (def) in mini-character-theory.MiniCharacterTheory.Constructions.Subobjects
- `MiniCharacterTheory.Retract` (structure) in mini-character-theory.MiniCharacterTheory.Constructions.Subobjects
- `MiniCharacterTheory.UniversalConstruction` (structure) in mini-character-theory.MiniCharacterTheory.Constructions.Universal
- `MiniCharacterTheory.Quotient` (def) in mini-character-theory.MiniCharacterTheory.Constructions.Quotients
- `MiniCharacterTheory.naturalProj` (def) in mini-character-theory.MiniCharacterTheory.Constructions.Quotients
- `MiniVertexAlgebras.Hom` (structure) in mini-vertex-algebras.MiniVertexAlgebras.Morphisms.Hom
- `MiniVertexAlgebras.homComp` (def) in mini-vertex-algebras.MiniVertexAlgebras.Morphisms.Hom
- `MiniVertexAlgebras.idHom` (def) in mini-vertex-algebras.MiniVertexAlgebras.Morphisms.Hom
- `MiniVertexAlgebras.Iso` (structure) in mini-vertex-algebras.MiniVertexAlgebras.Morphisms.Iso
- ... and 255 more

### modularreptheory (+1)

- `fixedSubalgebra` (def) in Modularreptheory.Basic

## Update History (1 runs)

- **2026-06-22T08:21:24.629952+00:00**: Checked 11 repos, updated 12, +706 -0 declarations
