# News

## v0.2.5 - 2023-11-28

- Improvements to testing and documentation support.

## v0.2.4 - 2023-08-10

- Minor internal improvements to doc builder and interactions with QuantumSavory.jl

## v0.2.3 - 2023-07-24

- Add all conditional Paulis.
- Remove `stab_to_ket` in favor of directly using the `Ket` constructor.

## v0.2.2 - 2023-06-28 

- Bump `QuantumInterface` compat.
- Upstream some `apply!` definitions to QuantumOpticsBase.

## v0.2.1 - 2023-06-11 

- Bump `QuantumInterface` compat.

## v0.2.0 - 2023-05-27

- **(breaking)** Merge with `QSymbolicsBase` and turn `QSymbolicsOptics` and `QSymbolicsClifford` into extensions.
- **(breaking)** Require julia 1.9.
- Drop `QuantumOptics` dependencies (now depends only on `QuantumOpticsBase`)

## `QSymbolicsBase` v0.1.2

- Pretty printing with Latexify.
- Implement bras.

## v0.1.1

- Bosonic states basis and common states and operators.
- Bumping `QSymbolicsBase` to 0.1.1.
- Bumping `QSymbolicsOptics` to 0.1.1.
- Added tests.

## `QSymbolicsBase` v0.1.1

- Bosonic states basis and common states and operators.
- Documentation and more symbol names available for the qubit base states.
- `SApplyOp` implemented for superoperator acting on operator.
- `STensorSuperOperator` implemented for tensor products of superoperators.
