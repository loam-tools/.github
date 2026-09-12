# Contributing to Loam Tools

Loam Tools repositories are maintained as focused engineering projects. Keep changes small, testable and tied to an observable product or reliability improvement.

## Before changing code

1. Check existing issues and pull requests for overlapping work.
2. For routing changes, describe the route class affected: short, regional, multi-day or continent-scale.
3. For behavior changes, include the expected before/after result.
4. Do not add hardcoded production data to make a failing path appear to work.

## Pull requests

A good pull request should:

- solve one coherent problem;
- include or update tests where practical;
- avoid unrelated formatting/refactors;
- document new external services, permissions or data dependencies;
- preserve offline behavior unless the change explicitly improves it;
- include benchmark evidence for routing/performance changes;
- keep secrets, signing files and private credentials out of Git history.

## Commits

Prefer concise conventional-style messages such as:

```text
fix(router): preserve route cache across stage changes
feat(data): add rd5 tile discovery
perf(router): reduce long-route section search time
chore(ci): add benchmark artifact retention
```

## Routing-specific expectations

Routing changes should be evaluated for correctness before speed. When performance is affected, record at least:

- route endpoints;
- profile;
- routing-data version;
- total distance;
- calculation time;
- peak memory when available;
- whether the result was cold-cache or warm-cache.

A faster route that silently changes route semantics is not automatically an improvement.
