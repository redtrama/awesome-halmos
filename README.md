## Awesome-Halmos

Repo: [Halmos](https://github.com/a16z/halmos/)
Telegram chat: [Halmos Telegram]([Halmos Telegram Group](https://t.me/+4UhzHduai3MzZmUx))

### Tutorials
- [Getting Started with Halmos](https://github.com/a16z/halmos/blob/main/docs/getting-started.md): Begginer guide from halmos repo.
- [Stateful Invariant Testing](https://a16zcrypto.com/posts/article/implementing-stateful-invariant-testing-with-halmos/): From invariant testing to Formal verification
- [Leveraging Existing Tests](https://a16zcrypto.com/posts/article/symbolic-testing-with-halmos-leveraging-existing-tests-for-formal-verification/): How to level-up your existing tests with symbolic execution.
- [From Fuzz to Symbolic Tests](https://www.youtube.com/watch?v=pjwYr97Q-Ok) (Video by Patrick Collins): A video tutorial on transitioning from fuzz testing to symbolic testing.
- [Testing WSL with Halmos](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos-wsl?lesson_format=video) (Video by Cyfrin): A video guide on testing with WSL and Halmos.

### Test Examples
- [Halmos Sandbox](https://github.com/karmacoma-eth/halmos-sandbox/): A repository with over 90 Halmos test examples.
- [Halmos Solady](https://github.com/zobront/halmos-solady): Examples of Halmos tests for the Solady library.
- [ERC20 Symbolic Tests](https://github.com/a16z/halmos/tree/main/examples/tokens/ERC20): Symbolic tests for ERC20 tokens using Solady, Solmate, and OpenZeppelin.
- [ERC721 Symbolic Tests](https://github.com/a16z/halmos/tree/main/examples/tokens/ERC721): Symbolic tests for ERC721 tokens using Solady, Solmate, and OpenZeppelin.
- [WETH Symbolic Testing](https://github.com/horsefacts/weth-invariant-testing/blob/main/test/WETH9.symbolic.t.sol): Invariant testing for WETH9.
- [Property-Based Testing Benchmark](https://github.com/aviggiano/property-based-testing-benchmark): Benchmarks for property-based testing.
- [DEI Stablecoin Symbolic Test](https://github.com/a16z/halmos/blob/main/examples/tokens/ERC20/test/DEIStablecoin.t.sol): Symbolic tests for the DEI Stablecoin.
- [Curve Token V3 Symbolic Test](https://github.com/a16z/halmos/blob/main/examples/tokens/ERC20/test/CurveTokenV3.t.sol): Symbolic tests for Curve Token V3.
- [SignatureChecker Equivalence Check](https://github.com/devtooligan/provesigchecker/blob/main/test/test.sol): Equivalence check between OpenZeppelin and Solady's SignatureChecker.
- [Snekmate Halmos Tests](https://github.com/pcaversaccio/snekmate/tree/main/test): Various Halmos tests by Snekmate.

### Projects Using Halmos
- [Farcaster Key Registry](https://github.com/farcasterxyz/contracts/blob/e56b5765ca28a7df149fb434315df0188a6ab14a/test/KeyRegistry/KeyRegistry.st.sol): Symbolic tests for the Farcaster Key Registry.
- [Morpho Data Structure](https://github.com/morpho-org/morpho-data-structures/blob/7f40c102e6bb852746d0d3c2f97ac3f39dae3c9c/test/TestLogarithmicBuckets.t.sol#L121-L182): Symbolic tests for Morpho's data structures.
- [Cicada](https://github.com/a16z/cicada): Verifying Cicada's big number arithmetic library with symbolic tests.
  - [LibPrimeTest](https://github.com/a16z/cicada/blob/c4dde7737778df759172ecdf7b4b044c60ce1f09/test/LibPrime.t.sol#L220-L232): Symbolic tests for prime number library.
  - [LibUint1024Test](https://github.com/a16z/cicada/blob/c4dde7737778df759172ecdf7b4b044c60ce1f09/test/LibUint1024.t.sol#L222-L245): Symbolic tests for 1024-bit unsigned integer library.
- [Farcaster](https://github.com/farcasterxyz/contracts): Verifying Farcaster's onchain registry contracts.
  - [IdRegistrySymTest](https://github.com/farcasterxyz/contracts/blob/e56b5765ca28a7df149fb434315df0188a6ab14a/test/IdRegistry/IdRegistry.st.sol): Symbolic tests for IdRegistry.
  - [KeyRegistrySymTest](https://github.com/farcasterxyz/contracts/blob/e56b5765ca28a7df149fb434315df0188a6ab14a/test/KeyRegistry/KeyRegistry.st.sol): Symbolic tests for KeyRegistry.
- [Solady Verification](https://github.com/zobront/halmos-solady): Verifying Solady's fixed-point math library with symbolic tests.

### Twitter Threads
- [Zachbront on Halmos](https://x.com/zachobront/status/1633906650514898947): Insights and updates on Halmos.
- [Equivalence Checking](https://x.com/daejunpark/status/1744788041078829432): Discussion on equivalence checking in Halmos.
- [Solving Real CTF with Halmos](https://x.com/0xkarmacoma/status/1632551527729758208?s=12&t=FF8FHzY8myIvLlgyCS0FXQ): How Halmos was used to solve a @curtaCTF .

### Videos
- [Graphic Explanation about Halmos Path Explosion](https://www.youtube.com/watch?v=GFCjG5KOetM): Understanding path explosion in Halmos.
- [Setting First Test with Halmos](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos?lesson_format=video): A video tutorial on setting up your first Halmos test.
- [Path Explosion and Timeout](https://updraft.cyfrin.io/courses/formal-verification/math-masters/halmos-mulwadup?lesson_format=video): Dealing with path explosion and timeouts in Halmos.
