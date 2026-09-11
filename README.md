# alecf/homebrew-tap

Homebrew formulae for my tools.

```bash
brew tap alecf/tap
```

Tap once, and everything below is installable by name.

## Formulae

| formula | what it is |
| --- | --- |
| [`thicket`](https://github.com/alecf/thicket) | Deterministic complexity reports for TypeScript codebases |

```bash
brew install alecf/tap/thicket
```

## How these are updated

Formulae here are **generated**, not hand-edited. Each tool's release workflow
builds its artifacts, computes their checksums, renders its own
`Formula/<name>.rb`, and pushes it here on tag. A formula file carries a
generated-by banner naming the script that wrote it.

So: don't edit a formula in this repo. Fix the generator in the tool's
repository and cut a release.
