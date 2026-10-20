# Global Executables data

This repository stores the generated datasets and crawl state for
[`asopitech-labs/global-executables`](https://github.com/asopitech-labs/global-executables).
Keeping generated data here allows a normal clone of the source repository to stay small.

The data is published on three independent branches:

- [`dictionary`](../../tree/dictionary): canonical executable records, indexes, metadata,
  history, and production refresh reports.
- [`artifact-data`](../../tree/artifact-data): durable crawl observations and checkpoints.
- [`freshness-data`](../../tree/freshness-data): freshness scheduler state.

These branches start from snapshot root commits. Their previous history remains available
only in the source repository until its generated-data history cleanup completes.

The stable raw dataset base URL is:

```text
https://raw.githubusercontent.com/asopitech-labs/global-executables-data/dictionary
```

Source code, issues, documentation, and release history belong in the
[`global-executables`](https://github.com/asopitech-labs/global-executables) repository.
