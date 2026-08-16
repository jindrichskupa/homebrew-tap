# homebrew-tap

Homebrew tap for [jindrichskupa](https://github.com/jindrichskupa)'s tools.

## Install

```bash
brew install --cask jindrichskupa/tap/franta
brew install jindrichskupa/tap/dictator
```

Or tap first, then install:

```bash
brew tap jindrichskupa/tap
brew install --cask franta
brew install dictator
```

## Available

| Package    | Type    | Description                                      | Source |
|------------|---------|--------------------------------------------------|--------|
| `franta`   | cask    | Terminal UI for Apache Kafka                     | [jindrichskupa/franta](https://github.com/jindrichskupa/franta) |
| `dictator` | formula | One registry of Claude Code sessions across every repository | [jindrichskupa/dictator](https://github.com/jindrichskupa/dictator) |

`franta` is a cask because it ships prebuilt binaries; `dictator` is a formula
because it is shell source.

After installing `dictator`, run `brew info dictator` for the zsh and Claude
Code hook setup it prints in its caveats.

## Notes

Casks in `Casks/` and formulae in `Formula/` are generated automatically on
each upstream release — `franta` by [GoReleaser](https://goreleaser.com),
`dictator` by its release workflow — do not edit by hand.
