# Playground for Visual Studio Code

This is a playground for Visual Studio Code (VSCode) settings.

# Note

- [How to use workspace](/docs/how-to-use-workspace.md)

## Development

Install [lefthook](https://github.com/evilmartians/lefthook) and register the Git hooks:

```sh
lefthook install
```

The following local checks run automatically on `pre-commit` and `pre-push`:

| Check | Tool | What it does |
|-------|------|--------------|
| typos | [typos](https://github.com/crate-ci/typos) | Spell-checks all files (mirrors the `spellcheck` CI job) |

To run the checks manually:

```sh
typos .
```

# LICENSE

- CC0 1.0 Universal
