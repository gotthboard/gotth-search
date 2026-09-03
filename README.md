# gotth-search

> **Distribution:** GitHub is the public clone and, only if implementation is
> admitted later, the future release endpoint.
> Forgejo remains canonical development and the issue/contribution location.
> See [the distribution contract](docs/distribution.md).


Reserved for reusable search mechanics shared by GOTTH applications.

## Intended boundary

This project may eventually own bounded query parsing, index-document
contracts, backend adapters, pagination cursors, result normalization, and
search conformance tests. Consumers remain responsible for deciding which
records a caller may index, discover, count, or read. An adapter must never
turn authorization into post-query filtering.

GOTTH Board's version 1 PostgreSQL full-text search remains inside the board.
Extraction starts only if a second consumer or the planned advanced-search
work proves a stable backend-neutral contract.

## Non-goals

- Forum visibility policy, SQL read models, ranking policy, or UI.
- A search service selected before scale and failure requirements exist.
- Hiding access-control leaks behind a generic result filter.

## Status

Placeholder only. There is no implementation, API, release, tag, compatibility
promise, or dependency to pin.

## Installation, compatibility, and support

Planned placeholder only. There is no implementation, API, support promise, or
release.

There is nothing to install or import. Do not add this repository as a
dependency.

The repository has no selected license and no long-term support promise.
Versioning, release admission, security reporting, and contribution details are
in [the release policy](docs/RELEASING.md), [security policy](SECURITY.md), and
[contribution guide](CONTRIBUTING.md).
