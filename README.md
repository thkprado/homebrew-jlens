# homebrew-jlens

The [Homebrew](https://brew.sh) tap of [jlens](https://github.com/thkprado/jlens), a JSONata
engine with evaluation audits and editor support.

```sh
brew install thkprado/jlens/jlens
jlens --version
```

The formula installs the release binaries for macOS (Intel and Apple silicon) and Linux
(x86-64 and ARM64, static), checked against the `SHA256SUMS` of each
[release](https://github.com/thkprado/jlens/releases). `brew upgrade` follows the releases.
The first release in this tap is 0.14.0.

`Formula/jlens.rb` is generated: the Homebrew workflow of thkprado/jlens replaces it when a
release is published. Do not edit it here; report issues and send changes to
[thkprado/jlens](https://github.com/thkprado/jlens/issues).

See the [installation page](https://thkprado.github.io/jlens/getting-started/installation.html)
for the other ways to install jlens.
