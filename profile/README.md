<div align="center">

# LOAM TOOLS

**Routing, maps and offline-first travel software.**

Built for long-distance journeys where connectivity cannot be assumed.

</div>

---

## Current focus

**WAYLOAM** is the main product: a long-distance cycling and bikepacking companion for route planning, multi-day stages, ride progress, gear and safety.

Loam Tools also maintains the supporting routing and release infrastructure behind WAYLOAM.

## Engineering principles

- **Offline first** — prepared trips and core routing should keep working without mobile data.
- **Open geography** — prefer OpenStreetMap, MapLibre and inspectable routing technology.
- **Long-distance by design** — continent-scale bicycle journeys are a primary use case, not an edge case.
- **Measured performance** — routing changes should be benchmarked, cancellable and reproducible.
- **Small interfaces** — keep product UI, routing engine, data and release infrastructure independently maintainable.
- **No fake state** — production paths should not depend on demo routes, hardcoded service responses or silent fallbacks.

## Repositories

| Repository | Purpose |
|---|---|
| `wayloam` | Android application |
| `wayloam-router` | Embedded/offline long-distance bicycle routing engine |
| [`wayloam-releases`](https://github.com/loam-tools/wayloam-releases) | Public alpha APKs and update manifests |

<div align="center">

**LOAM TOOLS** · built for the distance between here and there.

</div>
