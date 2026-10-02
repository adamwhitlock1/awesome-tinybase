# Awesome TinyBase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of TinyBase apps, starters, framework bindings, and resources for reactive local-first data.

[![License: CC0 1.0](https://img.shields.io/badge/license-CC0_1.0-blue.svg)](LICENSE)

[TinyBase](https://tinybase.org/) provides reactive stores, derived data, persistence, and synchronization. This list groups resources by the work they help you do, from an Expo app to a collaborative browser UI.

An independent community list. **Official** identifies resources maintained by the project team; **Integration** identifies documentation or examples maintained by an integrating project; **Community** identifies third-party work.

## Contents

- [Start here](#start-here)
- [Starters](#starters)
- [Apps to study](#apps-to-study)
- [Framework bindings](#framework-bindings)
- [Persistence and synchronization](#persistence-and-synchronization)
- [Derived data and history](#derived-data-and-history)
- [Mobile learning](#mobile-learning)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [License](#license)

## Start here

- [TinyBase source](https://github.com/tinyplex/tinybase) - Library source, documentation, and release history. **Official.**
- [The basics](https://tinybase.org/guides/the-basics/) - Learn stores, listeners, transactions, and TypeScript usage. **Official.**

## Starters

- [create-tinybase](https://github.com/tinyplex/create-tinybase) - Scaffold React, Solid, Svelte, or vanilla apps with optional persistence and sync. **Official.**
- [Expo TinyBase example](https://github.com/expo/examples/tree/master/with-tinybase) - Mobile starter with Expo SQLite persistence and a web storage fallback. **Integration.**

## Apps to study

- [TinyHub](https://github.com/tinyplex/tinyhub) - Local-first GitHub client with React and GitHub OAuth. **Official.**
- [TinyRooms](https://github.com/tinyplex/tinyrooms) - Explores collaboration, PartyKit synchronization, and optional GitHub OAuth. **Official.**
- [Groceries shopping list](https://github.com/betomoedano/groceries-shopping-list-app) - Cross-platform shopping list using Expo, TinyBase, and Cloudflare synchronization. **Community.**

## Framework bindings

- [React](https://tinybase.org/guides/building-uis-with-react/) - Hooks, context, and components that react to store changes. **Official.**
- [Solid](https://tinybase.org/guides/building-uis-with-solid/) - Reactive primitives and components for Solid applications. **Official.**
- [Svelte](https://tinybase.org/guides/building-uis-with-svelte/) - Reactive functions and components for Svelte applications. **Official.**

## Persistence and synchronization

- [Persistence](https://tinybase.org/guides/persistence/) - Load and save stores with built-in or custom persisters. **Official.**
- [Database persistence](https://tinybase.org/guides/persistence/database-persistence/) - Connect stores to SQL databases, including SQLite and PGlite. **Official.**
- [Synchronization](https://tinybase.org/guides/synchronization/) - Use MergeableStore and synchronizers to exchange changes. **Official.**
- [Cloudflare Durable Objects](https://tinybase.org/guides/integrations/cloudflare-durable-objects/) - Coordinate synchronization across clients with Durable Objects. **Official.**

## Derived data and history

- [Queries](https://tinybase.org/guides/using-queries/) - Derive reactive results with queries and TinyQL. **Official.**
- [Checkpoints](https://tinybase.org/guides/using-checkpoints/) - Add undo and redo through store checkpoints. **Official.**

## Mobile learning

- [Synchronizing apps with TinyBase](https://expo.dev/blog/how-to-synchronize-reactive-local-first-apps-with-tinybase) - Expo walkthrough of local persistence and cross-device synchronization. **Integration.**

## Compatibility

Use create-tinybase for new web projects. Many older tinyplex/vite-tinybase templates are archived. TinyHub, TinyRooms, and community apps are useful source examples; their dependencies may lag the current library.

Links and source descriptions were reviewed on October 2, 2026. [Verification notes](VERIFICATION.md) record the checks and exclusions. Linked applications were not installed or run as part of this review.

## Contributing

We include apps with inspectable TinyBase usage and guides with concrete storage, UI, or sync behavior. Unrelated databases that share the TinyBase name do not belong here.

Read the [contribution guide](CONTRIBUTING.md), then open a pull request with one resource and a short explanation of what it adds. Corrections, broken-link reports, and removal requests are welcome. Participation follows the [code of conduct](CODE_OF_CONDUCT.md).

## License

This list and its original descriptions are dedicated to the public domain under [CC0 1.0](LICENSE). Linked projects, documentation, and trademarks retain their own licenses and ownership.
