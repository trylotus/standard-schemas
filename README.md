# Lotus Standard Schemas 

This repository contains the protobuf definitions for the Lotus project. It provides a standardized set of data structures and interfaces for data stored in blockchains.

## Why Protobuf?
[Protocol Buffers](https://protobuf.dev/) are free and open-source, language-neutral, platform-neutral extensible mechanisms for serializing structured data. Invented by Google, they're now commonly used in various applications, particularly in microservices architectures and for data storage. Protobuf offers several advantages: it's more efficient than text-based formats like JSON, providing smaller message sizes and faster parsing; it's strongly typed, catching errors at compile-time; it supports backwards compatibility and versioning; and it's language-agnostic, enabling interoperability between different systems. While there are potentially more storage/performance optimized serialization formats, Protobuf strikes a balance between efficiency, ease of use, and widespread adoption, making it a solid choice for many projects where structured data needs to be serialized and transmitted efficiently. 

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
