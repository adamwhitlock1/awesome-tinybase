# Verification notes

Initial review date: October 2, 2026.

The README contains 17 curated entries. Each entry's source was inspected for relevance and its URL checked. GitHub repositories and paths were checked through the authenticated GitHub REST API; other pages were fetched with HTTP GET. Repository checks also inspected archive status and the current default branch. Descriptions summarize the linked material in original wording.

These checks establish source availability and documented use. They do not prove installation, runtime behavior, deployment reliability, security, or compatibility with every current dependency version. A repository's latest push can include non-code changes. Dates below are review snapshots, not a maintenance commitment.

## Entries

| Resource | Source inspected | Availability on review date | Upstream latest push, UTC date |
| --- | --- | --- | --- |
| [TinyBase source](https://github.com/tinyplex/tinybase) | Repository readme | GitHub API, 200 | 2026-09-29 |
| [The basics](https://tinybase.org/guides/the-basics/) | Documentation page | HTTP GET, 200 | Not applicable |
| [create-tinybase](https://github.com/tinyplex/create-tinybase) | Repository readme | GitHub API, 200 | 2026-09-24 |
| [Expo TinyBase example](https://github.com/expo/examples/tree/master/with-tinybase) | Directory readme | GitHub API, 200 | 2026-09-03 |
| [TinyHub](https://github.com/tinyplex/tinyhub) | Repository readme | GitHub API, 200 | 2025-06-10 |
| [TinyRooms](https://github.com/tinyplex/tinyrooms) | Repository readme | GitHub API, 200 | 2024-09-13 |
| [Groceries shopping list](https://github.com/betomoedano/groceries-shopping-list-app) | Repository readme | GitHub API, 200 | 2025-09-15 |
| [React](https://tinybase.org/guides/building-uis-with-react/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Solid](https://tinybase.org/guides/building-uis-with-solid/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Svelte](https://tinybase.org/guides/building-uis-with-svelte/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Persistence](https://tinybase.org/guides/persistence/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Database persistence](https://tinybase.org/guides/persistence/database-persistence/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Synchronization](https://tinybase.org/guides/synchronization/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Cloudflare Durable Objects](https://tinybase.org/guides/integrations/cloudflare-durable-objects/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Queries](https://tinybase.org/guides/using-queries/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Checkpoints](https://tinybase.org/guides/using-checkpoints/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Synchronizing apps with TinyBase](https://expo.dev/blog/how-to-synchronize-reactive-local-first-apps-with-tinybase) | Documentation page | HTTP GET, 200 | Not applicable |

## Excluded or superseded candidates

- Archived tinyplex/vite-tinybase and tinybase-ts-react templates: replaced by create-tinybase.
- betomoedano/todo-app-with-tinybase: no repository README at review time; the documented shopping-list app was selected instead.
- nickmessing/vue-tinybase: minimal README and older update history; omitted pending better maintenance evidence.
- JSH32/tinybase: a different database project, unrelated to tinyplex/TinyBase.

## Updating this record

For a later addition or correction, record the check date, source evidence, and result with the affected entry. Retain the original date for unchanged rows. Link-check failures need investigation: rate limits and access restrictions can occur even when a page exists. Prefer a verified canonical replacement to an unexamined redirect.
