# Contributing Guidelines

Thank you for your interest in contributing to the Lotus Protobuf Registry! We welcome contributions from the community to help improve and expand the protobuf definitions.

## How to Contribute

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure that the protobuf files are properly formatted and linted using Buf.
4. Write tests for your changes, if applicable.
5. Commit your changes and push them to your forked repository.
6. Open a pull request against the `main` branch of the original repository.
7. Provide a clear and descriptive title for your pull request and explain the changes you have made.
8. Wait for the maintainers to review your pull request. They may provide feedback or request changes.
9. Once your pull request is approved, it will be merged into the `main` branch.

## Protobuf Style Guide

When contributing to this protobuf registry, please adhere to the following style guide:

- Use clear and descriptive names for messages, fields, and enums.
- Follow the naming conventions:
  - Message names should be in PascalCase.
  - Field names should be in snake_case.
  - Enum names should be in PascalCase.
  - Enum values should be in UPPER_SNAKE_CASE.
- Provide comments for messages, fields, and enums to clearly explain their purpose and usage.
- Use appropriate field numbers and reserve ranges for future extensions.
- Avoid making breaking changes to existing protobuf definitions unless absolutely necessary.
- If introducing breaking changes, follow the versioning guidelines and provide clear migration instructions.

## Versioning

This protobuf registry follows semantic versioning. When making changes to the protobuf definitions, adhere to the following guidelines:

- Increment the major version when making incompatible changes that break backward compatibility.
- Increment the minor version when adding new features or modifications that are backward-compatible.
- Increment the patch version when making bug fixes or minor improvements that do not affect compatibility.

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.

## License

By contributing to this protobuf registry, you agree that your contributions will be licensed under the ???.