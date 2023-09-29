# ERC-6551 Reference Implementation

**This repository contains an npm package that provides the reference implementation of [ERC-6551](https://eips.ethereum.org/EIPS/eip-6551). It is forked from https://github.com/erc6551/reference.**

**Notice that the current official version is 0.2.0. Here it is 0.2.1 because of little changes in this version after the first publishing to the scripts. That change did not affect the contracts.**

**This project is under active development and may undergo changes until ERC-6551 is finalized.** For the most recently deployed version of these contracts, see the [v0.2.0](https://github.com/erc6551/reference/releases/tag/v0.2.0) release. We recommend this version for any production usage.

## Using as a Dependency

If you want to use `erc6551/reference` as a dependency in another project, you can add it using `forge install`:

```sh
npm install erc6551
```

and use as
```
import "erc6551/interfaces/IERC6551Account.sol";
```

## Development Setup - original implementation

You will need to have Foundry installed on your system. Please refer to the [Foundry installation guide](https://github.com/foundry-rs/book/blob/master/src/getting-started/installation.md) for detailed instructions.

To use this repository, first clone it:

```sh
git clone https://github.com/erc6551/reference.git
cd contracts
```

Then, install the dependencies:

```sh
forge install
```

## Running Tests

To run the tests, use the `forge test` command:

```sh
forge test
```

For more information on writing and running tests, refer to the [Foundry testing guide](https://github.com/foundry-rs/book/blob/master/src/forge/writing-tests.md).


## History

**0.2.2**

- Making examples' functions `virtual` so that the examples can be used as a base for more advanced contracts
