# Awesome-halmos

A curated list of resources on halmos, featuring blogs, videos, code repositories, and practical examples.

## halmos
- Github: [halmos](https://github.com/a16z/halmos/).
- Telegram chat: [halmos Telegram](https://t.me/+4UhzHduai3MzZmUx).

## halmos Knowledge base

- [halmos Getting Started](https://github.com/a16z/halmos/blob/main/docs/getting-started.md): Beginner guide to understand how halmos works.
- [halmos FAQ](https://github.com/a16z/halmos/wiki/FAQ): answers to the most frequently asked questions.
- [Invariant Testing with halmos by Antonio Viggiano](https://a16zcrypto.com/posts/article/implementing-stateful-invariant-testing-with-halmos/): From invariant testing to Formal verification.
- [Leveraging Existing Tests by a16z](https://a16zcrypto.com/posts/article/symbolic-testing-with-halmos-leveraging-existing-tests-for-formal-verification/): How to level-up your existing tests with symbolic execution.
- [@zachobront X Thread: Solady FixedPointMathLib Testing](https://x.com/zachobront/status/1633906650514898947): Solady and Solmate equivalence check.
- [@daejunpark X Thread: My halmos usage #1](https://x.com/daejunpark/status/1744788041078829432): using halmos for equivalence check.
- [@0xkarmacoma X Thread: Solving CurtaCTF with halmos](https://x.com/0xkarmacoma/status/1632551527729758208?s=12&t=FF8FHzY8myIvLlgyCS0FXQ): How karmacoma used halmos for solving a curtaCTF.

## Videos

- [Beyond Fuzzing Symbolic Testing in Practice by karmacoma](https://www.youtube.com/watch?v=GFCjG5KOetM): Understanding path exploration.
- [From Fuzz to Symbolic Tests by Patrick Collins](https://www.youtube.com/watch?v=pjwYr97Q-Ok): A video tutorial on transitioning from fuzz to symbolic testing.
- [Path Explosion and Timeout by Cyfrin](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos-mulwadup?lesson_format=video): Understanding path explosion and timeouts.
- [Setting First Test with halmos by Cyfrin](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos?lesson_format=video): A video tutorial on setting up your first halmos test.
- [Testing WSL with halmos by Cyfrin](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos-wsl?lesson_format=video): A video guide on testing WSL function.

## Test Examples

- [halmos-sandbox](https://github.com/karmacoma-eth/halmos-sandbox/): A repository with +90 halmos test examples.
- [halmos-solady](https://github.com/zobront/halmos-solady): Examples of halmos tests for the Solady library.
- [ERC20 Symbolic Tests](https://github.com/a16z/halmos/tree/main/examples/tokens/ERC20): Symbolic tests for Solady, Solmate, and OpenZeppelin ERC20 tokens.
- [ERC721 Symbolic Tests](https://github.com/a16z/halmos/tree/main/examples/tokens/ERC721): Symbolic tests for Solady, Solmate, and OpenZeppelin ERC721 tokens.
- [WETH Symbolic Testing by horsefacts](https://github.com/horsefacts/weth-invariant-testing/blob/main/test/WETH9.symbolic.t.sol): Symbolic testing for WETH9 contract.
- [Property-Based Testing Benchmark by Antonio Viggiano](https://github.com/aviggiano/property-based-testing-benchmark): Benchmarks for property-based testing.
- [DEI Stablecoin Symbolic Test](https://github.com/a16z/halmos/blob/main/examples/tokens/ERC20/test/DEIStablecoin.t.sol): Symbolic tests for the DEI Stablecoin.
- [Curve Token V3 Symbolic Test](https://github.com/a16z/halmos/blob/main/examples/tokens/ERC20/test/CurveTokenV3.t.sol): Symbolic tests for Curve Token V3.
- [SignatureChecker Equivalence Check](https://github.com/devtooligan/provesigchecker/blob/main/test/test.sol): Equivalence check between OpenZeppelin and Solady's SignatureChecker.
- [ERC20 Differential Tests by Antonio Viggiano](https://github.com/aviggiano/halmos-differential-erc20): Halmos Differential Tests for OpenZeppelin, Solady, and Solmate ERC-20 Token Implementations.

## Projects Using halmos

- [Morpho](https://github.com/morpho-org/morpho-data-structures/blob/7f40c102e6bb852746d0d3c2f97ac3f39dae3c9c/test/TestLogarithmicBuckets.t.sol#L121-L182): Symbolic tests for Morpho's data structures.
- [Cicada](https://github.com/a16z/cicada): Verifying Cicada's big number arithmetic library with symbolic tests.
  - [LibPrimeTest](https://github.com/a16z/cicada/blob/c4dde7737778df759172ecdf7b4b044c60ce1f09/test/LibPrime.t.sol#L220-L232): Symbolic tests for prime number library.
  - [LibUint1024Test](https://github.com/a16z/cicada/blob/c4dde7737778df759172ecdf7b4b044c60ce1f09/test/LibUint1024.t.sol#L222-L245): Symbolic tests for 1024-bit unsigned integer library.
- [Farcaster](https://github.com/farcasterxyz/contracts): Verifying Farcaster's onchain registry contracts.
  - [IdRegistrySymTest](https://github.com/farcasterxyz/contracts/blob/e56b5765ca28a7df149fb434315df0188a6ab14a/test/IdRegistry/IdRegistry.st.sol): Symbolic tests for IdRegistry.
  - [KeyRegistrySymTest](https://github.com/farcasterxyz/contracts/blob/e56b5765ca28a7df149fb434315df0188a6ab14a/test/KeyRegistry/KeyRegistry.st.sol): Symbolic tests for KeyRegistry.
- [snekmate](https://github.com/pcaversaccio/snekmate): Symbolic tests for Vyper-based [`erc20`](https://github.com/pcaversaccio/snekmate/blob/main/test/tokens/halmos/ERC20TestHalmos.t.sol), [`erc721`](https://github.com/pcaversaccio/snekmate/blob/main/test/tokens/halmos/ERC721TestHalmos.t.sol), [`erc1155`](https://github.com/pcaversaccio/snekmate/blob/main/test/tokens/halmos/ERC1155TestHalmos.t.sol), and [`math`](https://github.com/pcaversaccio/snekmate/blob/main/test/utils/halmos/MathTestHalmos.t.sol) contracts.
- [Pimlico](https://github.com/pimlicolabs/erc20-paymaster/blob/main/test/ERC20PaymasterSymbolic.t.sol): Symbolic tests for ERC20Paymaster
