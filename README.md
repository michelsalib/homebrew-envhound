# Homebrew tap for envhound

[envhound](https://github.com/michelsalib/envhound) finds which startup file sets each environment
variable, and audits your PATH.

```sh
brew install michelsalib/envhound/envhound
```

This installs the standalone binary from the GitHub release (macOS and Linux, arm64 and x64), with bash
and fish completion. For zsh completion, add `eval "$(envhound completion zsh)"` to `~/.zshrc`, after
`compinit`. Update with `brew upgrade envhound`.

`Formula/envhound.rb` is generated for each release by `scripts/packages.ts` in the envhound repository,
from the release's `SHA256SUMS`.
