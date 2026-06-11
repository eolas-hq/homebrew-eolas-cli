# Eolas CLI

Terminal access to the Eolas platform API.

## Install (macOS, Apple Silicon)

```bash
brew tap eolas-hq/eolas-cli
brew install eolas
```

## Use with Claude Code

The CLI bundles a Claude Code skill that teaches AI agents how to drive it
(querying, creating, and bulk-importing Eolas data). Install it with:

```bash
eolas skill install
```

## Upgrade

```bash
brew update && brew upgrade eolas
```

Re-run `eolas skill install` after upgrading so the skill matches the new CLI version.

Binaries are published automatically from the Eolas monorepo build pipeline.
The formula in `Formula/eolas.rb` is machine-generated — do not edit it here.
