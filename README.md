# Lotus Proto Files

This repository contains the protobuf definitions for the Lotus project. It provides a standardized set of data structures and interfaces for data stored in blockchains.

## Directory Structure

The repository is organized into the following directories:

- `lotus/`:
  - `evm/`: Protobuf definitions related to the Ethereum Virtual Machine (EVM).
  - `exchange/`: Protobuf definitions for exchange-related functionality.
  - `defi/`: Protobuf definitions for decentralized finance (DeFi) use cases.
  - `staking/`: Protobuf definitions for staking and validator-related functionality.
  - `governance/`: Protobuf definitions for governance and voting.
- `options/`: Contains custom protobuf FieldOptions definitions.

## Getting Started

To use the protobuf definitions in this repository, follow these steps:

1. Install the protobuf compiler and Buf by following the instructions in the [Installation](#installation) section.
2. Clone this repository: `git clone https://github.com/trylotus/protos.git`
3. Navigate to the repository directory: `cd protos`
4. Run Buf commands to lint, build, and generate code from the protobuf definitions:
   - Lint: `buf lint`
   - Build: `buf build`
   - Generate Go code: `buf generate --output ./gen/go`

## Installation

### Protobuf Compiler

Install the protobuf compiler by following the instructions for your operating system:
- [Linux](https://grpc.io/docs/protoc-installation/#install-using-apt-get-on-linux)
- [macOS](https://grpc.io/docs/protoc-installation/#install-using-homebrew-on-macos)
- [Windows](https://grpc.io/docs/protoc-installation/#install-on-windows)

### Buf

Install Buf by following the installation instructions for your operating system from the [official Buf documentation](https://docs.buf.build/installation).

## Contributing

Contributions to this protobuf registry are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This repository is licensed under the ???.