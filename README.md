# github-actions-pip

[![[C]ontinuous [I]ntegration](https://github.com/percebus/github-actions-pip/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/github-actions-pip/actions/workflows/always.yml) [![CodeQL](https://github.com/percebus/github-actions-pip/actions/workflows/codeql.yml/badge.svg)](https://github.com/percebus/github-actions-pip/actions/workflows/codeql.yml) [![Pull Request](https://github.com/percebus/github-actions-pip/actions/workflows/pull_request.yml/badge.svg?event=pull_request)](https://github.com/percebus/github-actions-pip/actions/workflows/pull_request.yml)

[`LICENSE`](./LICENSE)

github re-usable actions &amp; workflows for pip

## GitHub

### Actions

| action                                                 | test      |
| ------------------------------------------------------ | --------- |
| [`install-upgrade`](./.github/actions/install-upgrade) | See Tests |
| [`install`](./.github/actions/install)                 | See Tests |
| [`freeze`](./.github/actions/freeze)                   | See Tests |

### Workflows

#### Tests

| workflow                                           | details                                | test                                                                                                                                                                                                   |
| -------------------------------------------------- | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [example1](./.github/workflows/test__example1.yml) | [example1](./assets/examples/example1) | [![Test example1](https://github.com/percebus/github-actions-pip/actions/workflows/test__example1.yml/badge.svg)](https://github.com/percebus/github-actions-pip/actions/workflows/test__example1.yml) |
| [`pipx`](./.github/workflows/test__pipx.yml)       | [pipx](./assets/examples/pipx)         | [![Test pipx](https://github.com/percebus/github-actions-pip/actions/workflows/test__pipx.yml/badge.svg)](https://github.com/percebus/github-actions-pip/actions/workflows/test__pipx.yml)             |

## References

- [Customizing your advanced setup for code scanning](https://docs.github.com/en/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/customizing-your-advanced-setup-for-code-scanning)
