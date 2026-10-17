# xnx

I build Windows utilities and self-hosted software for online communities.

I came from online circles where people out of work made money through crime. I work overtime every week; outside work, I build useful free software.

[Projects](#projects) | [Latch](#latch) | [Repositories](https://github.com/informent?tab=repositories)

<details>
<summary>ASCII artwork (open full size)</summary>

<p align="center"><a href="./assets/profile-art.svg"><img src="./assets/profile-art.svg" alt="High contrast ASCII artwork with credits"></a></p>

</details>

## Currently building

**[Backstop](https://github.com/informent/Backstop)**

Local file backups with snapshot comparison and restore previews.

[Latest release](https://github.com/informent/Backstop/releases/latest) · [Documentation](https://github.com/informent/Backstop#readme)

**[Latch](https://github.com/informent/Latch)**

A free Discord bot you host yourself, with moderation, tickets, roles, community tools, and a complete command reference.

[Browse commands](https://github.com/informent/Latch/blob/main/COMMANDS.md) · [Set up Latch](https://github.com/informent/Latch#start-here)

## Projects

Windows tools include setup installers with the .NET runtime bundled and portable ZIP downloads. Choose an installer for guided setup or a ZIP for a folder-based install.

### Files and everyday use

| Project | What it does | Latest release |
| --- | --- | --- |
| [Backstop](https://github.com/informent/Backstop) | Back up files and review snapshot comparisons and restores. | [v1.7.0](https://github.com/informent/Backstop/releases/tag/v1.7.0) |
| [Savepoint](https://github.com/informent/Savepoint) | Back up and compare PC game saves. | [v1.5.0](https://github.com/informent/Savepoint/releases/tag/v1.5.0) |
| [Courier](https://github.com/informent/Courier) | Transfer files over a local network and verify receipts. | [v1.0.0](https://github.com/informent/Courier/releases/tag/v1.0.0) |
| [Batchwork](https://github.com/informent/Batchwork) | Preview and recover batch file renames. | [v1.3.1](https://github.com/informent/Batchwork/releases/tag/v1.3.1) |
| [Footprint](https://github.com/informent/Footprint) | Inspect disk use and export CSV reports. | [v1.3.1](https://github.com/informent/Footprint/releases/tag/v1.3.1) |
| [Cliptray](https://github.com/informent/Cliptray) | Keep clipboard history on your device with deletion and secret filters. | [v1.3.1](https://github.com/informent/Cliptray/releases/tag/v1.3.1) |

### Systems and development

| Project | What it does | Latest release |
| --- | --- | --- |
| [Checkup](https://github.com/informent/Checkup) | Check Windows health and collect troubleshooting reports. | [v1.2.0](https://github.com/informent/Checkup/releases/tag/v1.2.0) |
| [Rackwatch](https://github.com/informent/Rackwatch) | Inspect Windows servers and local ports. | [v2.2.0](https://github.com/informent/Rackwatch/releases/tag/v2.2.0) |
| [Packbench](https://github.com/informent/Packbench) | Package desktop projects and verify ZIP contents. | [v3.4.0](https://github.com/informent/Packbench/releases/tag/v3.4.0) |

## Latch

**Free and open source. Bring your own hosting.**

Latch is distributed as a source prerelease. Automated checks run on Windows and Linux; live Discord acceptance testing is still pending. Courier is also a preview; testing between two physical computers is pending.

[Latest prerelease](https://github.com/informent/Latch/releases/tag/v0.35.0) · [Commands](https://github.com/informent/Latch/blob/main/COMMANDS.md) · [Setup](https://github.com/informent/Latch#start-here)

## What I care about

- Useful software over novelty
- Local-first workflows and user-owned data
- Safe previews, explicit actions, and recoverable changes
- Small tools that are easy to understand, test, and maintain

## Engineering range

- Windows desktop development with C#, .NET, WPF, and self-contained distribution
- Filesystem safety: atomic writes, transactional operations, path-boundary validation, SHA-256 manifests, and restore preflight
- Security and privacy: encrypted transfers, certificate pinning, sensitive-data exclusion, redaction, and local-first storage
- Systems and operations: server auditing, storage analysis, backup scheduling, release automation, and failure recovery
- Delivery discipline: regression tests, packaged-app smoke tests, least-privilege CI permissions, issue tracking, code review, and reproducible releases

## Development

Source, setup instructions, release history, and issue trackers live in each repository. Release notes record changes and verification details. Bug reports are welcome. Code contributions are by invitation; repository access, merges, and releases are managed by me.
