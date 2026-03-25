# Contributing to Dabroiotexs DAO Decentralization

Thank you for your interest in contributing! This project welcomes contributions of all kinds.

## Ways to Contribute

- **Bug reports** — Open an issue using the Bug Report template.
- **Feature requests** — Open an issue using the Feature Request template.
- **Code contributions** — Fork, branch, code, test, PR.
- **Documentation** — Improve docs in the `docs/` folder.
- **Governance proposals** — Draft proposals following `docs/dao-constitution.md`.

## Development Setup

```bash
git clone https://github.com/AuditorSEC-Initiative/dabroiotexs-dao-decentralization
cd dabroiotexs-dao-decentralization
npm install          # or: yarn install
npx hardhat compile  # compile IoTeX smart contracts
npx hardhat test     # run test suite
```

## Pull Request Process

1. Fork the repository and create a branch: `git checkout -b feat/your-feature`.
2. Make your changes with clear, atomic commits.
3. Add or update tests as appropriate.
4. Run `npx hardhat test` and ensure all tests pass.
5. Submit a Pull Request against `main` with a clear description.
6. Wait for review from a maintainer (usually within 72 hours).

## Code Style

- Solidity: follow [Solidity Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html).
- JavaScript/TypeScript: ESLint + Prettier (configs in repo root).
- Markdown: 80-character line limit preferred.

## Governance Contributions

- Governance proposals must follow the lifecycle defined in `docs/dao-constitution.md`.
- Draft proposals as Markdown in `proposals/` folder and open a PR for community review.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](docs/dao-constitution.md#article-viii--code-of-conduct).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
