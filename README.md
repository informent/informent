# fed

I build practical, open-source tools for Windows users and self-hosters.

My focus is simple: take everyday workflows that are fragmented, expensive, or harder than they need to be and turn them into dependable software with clear interfaces, safe defaults, and transparent behavior.

## Current projects

| Project | Purpose |
| --- | --- |
| [OpenGameSave](https://github.com/informent/OpenGameSave) | Atomic game-save snapshots with SHA-256 verification and whole-restore collision preflight ([v1.1.0](https://github.com/informent/OpenGameSave/releases/tag/v1.1.0)) |
| [OpenFix](https://github.com/informent/OpenFix) | Read-only Windows health scoring with privacy-safe HTML/JSON support bundles and verified manifests ([v1.0.0](https://github.com/informent/OpenFix/releases/tag/v1.0.0)) |
| [OpenShare](https://github.com/informent/OpenShare) | Encrypted Windows file sharing with receiver approval, integrity checks, and local transfer receipts ([v1.0.0](https://github.com/informent/OpenShare/releases/tag/v1.0.0)) |
| [OpenBackup](https://github.com/informent/OpenBackup) | Atomic verified snapshots, restore preflight, safe scheduling, and validated retention planning ([v1.5.0](https://github.com/informent/OpenBackup/releases/tag/v1.5.0)) |
| [OpenSpace](https://github.com/informent/OpenSpace) | Fault-tolerant storage analysis with exact aggregation and visible inaccessible-path evidence ([v1.1.0](https://github.com/informent/OpenSpace/releases/tag/v1.1.0)) |
| [OpenRename](https://github.com/informent/OpenRename) | Transactional batch renaming with swaps, rollback, and restart-safe persistent undo ([v1.1.0](https://github.com/informent/OpenRename/releases/tag/v1.1.0)) |
| [OpenClip](https://github.com/informent/OpenClip) | Private clipboard history with sensitive-content exclusion, bounded storage, and corruption recovery ([v1.0.0](https://github.com/informent/OpenClip/releases/tag/v1.0.0)) |
| [OpenPackager](https://github.com/informent/OpenPackager) | Windows packaging with strict manifest parsing and exact SHA-256 payload coverage verification ([v3.1.0](https://github.com/informent/OpenPackager/releases/tag/v3.1.0)) |
| [OpenServerOps](https://github.com/informent/OpenServerOps) | Read-only server audits with health grades and exportable JSON/HTML evidence ([v2.0.0](https://github.com/informent/OpenServerOps/releases/tag/v2.0.0)) |

## What I care about

- Useful software over novelty
- Local-first workflows and user-owned data
- Safe previews, explicit actions, and recoverable changes
- Small tools that are easy to understand, test, and maintain

Everything here is built to be useful in the real world, with the source and release history available for review.

## Engineering range

- Windows desktop development with C#, .NET, WPF, and self-contained distribution
- Filesystem safety: atomic writes, transactional operations, path-boundary validation, SHA-256 manifests, and restore preflight
- Security and privacy: encrypted transfers, certificate pinning, sensitive-data exclusion, redaction, and local-first storage
- Systems and operations: server auditing, storage analysis, backup scheduling, release automation, and failure recovery
- Delivery discipline: regression tests, packaged-app smoke tests, GitHub Actions, issue tracking, code review, and reproducible releases

## Release standard

Major updates are tested on Windows, published with self-contained executable packages, and kept visible through GitHub Actions and release history. Projects prefer local-first operation, explicit user consent, reversible changes, and no mandatory accounts.
