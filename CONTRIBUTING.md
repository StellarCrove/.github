# Contributing to StellarCrove

Thank you for your interest in contributing to StellarCrove and the LumenForge ecosystem!

## Ecosystem Overview

StellarCrove maintains three interconnected repositories:
- [`lumenforge-contracts`](https://github.com/StellarCrove/lumenforge-contracts): Rust Soroban smart contracts (`lumen_vault` and `lumen_vault_factory`).
- [`lumenforge-sdk`](https://github.com/StellarCrove/lumenforge-sdk): TypeScript client library and CLI.
- [`lumenforge-docs`](https://github.com/StellarCrove/lumenforge-docs): Architecture specifications, threat models, and integration guides.

## Development Workflow

1. Fork the respective repository and create a branch from `main`.
2. Write clean, focused code adhering to the project's formatting and linting rules:
   - For Rust: `cargo fmt --check` and `cargo clippy -- -D warnings`
   - For TypeScript: `npm run lint` and `npm run typecheck`
3. Ensure 100% of test suites pass:
   - For Rust: `make test` or `cargo test --workspace`
   - For TypeScript: `npm test`
4. Open a pull request targeting `main` with a clear explanation of changes and linked issue numbers.

## Security Disclosures

If you discover a security vulnerability or exploit vector, please **do not** file a public issue. Instead, open a [private security advisory](https://github.com/StellarCrove/lumenforge-contracts/security/advisories/new) or contact the core maintainers.
