# fed

I build practical, open-source tools for Windows users and self-hosters.

My focus is simple: take everyday workflows that are fragmented, expensive, or harder than they need to be and turn them into dependable software with clear interfaces, safe defaults, and transparent behavior.

## Current projects

| Project | Purpose |
| --- | --- |
| [OpenGameSave](https://github.com/informent/OpenGameSave) | Atomic game-save snapshots with copied-byte integrity and linked-path protection; rejects output inside save roots ([v1.3.0 release](https://github.com/informent/OpenGameSave/releases/tag/v1.3.0), [master fix #6](https://github.com/informent/OpenGameSave/pull/6)) |
| [OpenFix](https://github.com/informent/OpenFix) | Read-only Windows health scoring with privacy-safe support bundles, deadlock-safe activation checks, and resilient temp-tree scanning ([v1.0.1](https://github.com/informent/OpenFix/releases/tag/v1.0.1)) |
| [OpenShare](https://github.com/informent/OpenShare) | Encrypted Windows file sharing with receiver approval, integrity checks, and local transfer receipts ([v1.0.0](https://github.com/informent/OpenShare/releases/tag/v1.0.0)) |
| [OpenBackup](https://github.com/informent/OpenBackup) | Atomic verified snapshots, restore preflight, safe scheduling, and validated retention planning ([v1.5.0](https://github.com/informent/OpenBackup/releases/tag/v1.5.0)) |
| [OpenSpace](https://github.com/informent/OpenSpace) | Fault-tolerant storage analysis with exact aggregation and visible inaccessible-path evidence; linked scan roots are reported and skipped ([v1.2.0 release](https://github.com/informent/OpenSpace/releases/tag/v1.2.0), [master fix #4](https://github.com/informent/OpenSpace/pull/4)) |
| [OpenRename](https://github.com/informent/OpenRename) | Transactional batch renaming with swaps, rollback, and restart-safe persistent undo; invalid previews clear stale actions ([v1.2.0 release](https://github.com/informent/OpenRename/releases/tag/v1.2.0), [master fix #4](https://github.com/informent/OpenRename/pull/4)) |
| [OpenClip](https://github.com/informent/OpenClip) | Private clipboard history with secret exclusion, corruption recovery, multi-instance write safety, and stable selection across refreshes ([v1.2.0 release](https://github.com/informent/OpenClip/releases/tag/v1.2.0), [master fix #4](https://github.com/informent/OpenClip/pull/4)) |
| [OpenPackager](https://github.com/informent/OpenPackager) | Windows packaging with strict manifest parsing, exact SHA-256 payload coverage, and source-bundle junction rejection ([v3.2.0 release](https://github.com/informent/OpenPackager/releases/tag/v3.2.0), [master fix #4](https://github.com/informent/OpenPackager/pull/4)) |
| [OpenServerOps](https://github.com/informent/OpenServerOps) | Read-only server audits with health grades and metadata-preserving atomic JSON/HTML exports ([v2.0.1](https://github.com/informent/OpenServerOps/releases/tag/v2.0.1)) |

## In progress

- [OpenDesk](https://github.com/informent/OpenDesk): a free, open-source Discord community bot with tickets, moderation, native AutoMod, embeds, polls, durable reminders and giveaways, games, roles, warnings, coins, optional XP, welcomes, and join-burst alerts. Source version 0.2.0 has no premium gates. See the [feature roadmap](https://github.com/informent/OpenDesk/blob/main/ROADMAP.md) and [changelog](https://github.com/informent/OpenDesk/blob/main/CHANGELOG.md). Automated tests pass; live Discord operation remains unverified. Full antinuke, voice/music, social integrations, and complete competitor parity remain planned.

## What I care about

- Useful software over novelty
- Local-first workflows and user-owned data
- Safe previews, explicit actions, and recoverable changes
- Small tools that are easy to understand, test, and maintain

Published projects include source and release history for review. OpenDesk is source-only and has no packaged release yet.

## Engineering range

- Windows desktop development with C#, .NET, WPF, and self-contained distribution
- Filesystem safety: atomic writes, transactional operations, path-boundary validation, SHA-256 manifests, and restore preflight
- Security and privacy: encrypted transfers, certificate pinning, sensitive-data exclusion, redaction, and local-first storage
- Systems and operations: server auditing, storage analysis, backup scheduling, release automation, and failure recovery
- Delivery discipline: regression tests, packaged-app smoke tests, least-privilege CI permissions, issue tracking, code review, and reproducible releases

## Maintenance

Dependencies and GitHub Actions are maintained through reviewable pull requests with CI checks. Release links point to the latest published builds; maintenance changes do not imply a new app release.

## Release standard

Major updates are tested on Windows, published with self-contained executable packages, and kept visible through GitHub Actions and release history. Projects prefer local-first operation, explicit user consent, reversible changes, and no mandatory accounts.
