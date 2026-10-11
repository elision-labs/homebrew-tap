# elision-labs/homebrew-tap

Homebrew formulae for [QueueFlow](https://queueflow.dev), the PostgreSQL-native job queue and workflow engine.

```sh
brew install elision-labs/tap/queueflow
queueflow --version
```

The formula installs the prebuilt `queueflow` server/CLI binary from the
[GitHub release](https://github.com/elision-labs/queueflow-core/releases) for
your platform (macOS on Apple silicon and Intel, Linux x86-64 and arm64).

The formula is generated from
[`deploy/homebrew`](https://github.com/elision-labs/queueflow-core/tree/main/deploy/homebrew)
in the core repository; per release, run `update-formula.sh vX.Y.Z` there and
copy the result to `Formula/queueflow.rb` here.

MIT licensed, like QueueFlow itself.
