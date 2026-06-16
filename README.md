# voluntold-ai/homebrew-tap

Homebrew tap for the [voluntold](https://voluntold.ai) CLI — the agent runtime
that routes issue-board work to AI coding agents.

## Install

```sh
brew install voluntold-ai/tap/voluntold
```

…or, equivalently:

```sh
brew tap voluntold-ai/tap
brew install voluntold
```

Bash/zsh/fish shell completions are installed automatically.

## Upgrading

```sh
brew update && brew upgrade voluntold
```

## How this works

`Formula/voluntold.rb` is **auto-generated** — the [voluntold](https://github.com/DomBlack/voluntold)
release CI rebuilds it (new version + checksums) on every release and
force-pushes it here. It points at the pre-built, garble-obfuscated binaries
served from <https://dl.voluntold.ai>. Don't edit the formula by hand; changes
are overwritten.
