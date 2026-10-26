# s8int

I build software for people who want control over their tools: self-hosted licensing, Discord utilities, and Windows desktop apps.


[Projects](#projects) | [Keydock](https://github.com/informent/Keydock) | [Latch](#latch) | [Repositories](https://github.com/informent?tab=repositories)

<details>
<summary>ASCII artwork (open full size)</summary>

<p align="center"><a href="./assets/profile-art.svg"><img src="./assets/profile-art.svg" alt="High contrast ASCII artwork with credits"></a></p>

</details>

## Currently building

**[Keydock](https://github.com/informent/Keydock)**

Self-hosted software licensing for developers. Manage products, customers, license keys, device limits, and entitlements from one console. Includes a licensing API, JavaScript and Python clients, and signed offline leases.

The console is being refined for PC workflows: readable tables, compact views, and room to work across products and customer records. Early release; an independent security audit is still pending.

[Source and setup](https://github.com/informent/Keydock#readme) · [JavaScript client](https://github.com/informent/Keydock/tree/main/sdk/javascript) · [Python client](https://github.com/informent/Keydock/tree/main/sdk/python)

**[Guildkit](https://informent.github.io/Guildkit/)**

A free, private Discord message studio with reusable templates, event timestamps, and game-night team and bracket draws. Runs in your browser without accounts or bot tokens.

[Open the app](https://informent.github.io/Guildkit/) · [Source and limits](https://github.com/informent/Guildkit#readme)

**[Backstop](https://github.com/informent/Backstop)**

Local file backups with snapshot comparison and restore previews.

[Latest release](https://github.com/informent/Backstop/releases/latest) · [Documentation](https://github.com/informent/Backstop#readme)

**[Latch](https://github.com/informent/Latch)**

A free Discord bot you host yourself, with moderation, tickets, roles, community tools, and a complete command reference.

[Browse commands](https://github.com/informent/Latch/blob/main/COMMANDS.md) · [Set up Latch](https://github.com/informent/Latch#start-here)

## Projects

Check each repository for setup instructions, available downloads, and current limitations. Windows releases generally offer an installer and a portable ZIP; preview projects may still require a source build.

### Licensing, Discord, and media

| Project | What it does | Start here |
| --- | --- | --- |
| [Keydock](https://github.com/informent/Keydock) | Host your own software licensing service with keys, device limits, customer records, and offline leases. | [Run the console](https://github.com/informent/Keydock#run-keydock) |
| [Guildkit](https://github.com/informent/Guildkit) | Draft Discord messages, reuse templates, format timestamps, and organize game-night teams. | [Open the app](https://informent.github.io/Guildkit/) |
| [UploadFit](https://github.com/informent/UploadFit) | Compress local clips to an upload limit, with trimming and batch processing. | [Source and status](https://github.com/informent/UploadFit#readme) |
| [Latch](https://github.com/informent/Latch) | Self-hosted Discord moderation, tickets, roles, and community tools. | [Setup and limits](https://github.com/informent/Latch#start-here) |

UploadFit is still in development. Latch needs live Discord acceptance testing; Courier needs testing between two physical PCs.

### Files and everyday use

| Project | What it does | Downloads |
| --- | --- | --- |
| [Backstop](https://github.com/informent/Backstop) | Back up files and review snapshot comparisons and restores. | [Downloads](https://github.com/informent/Backstop/releases/latest) |
| [Savepoint](https://github.com/informent/Savepoint) | Back up and compare PC game saves. | [Downloads](https://github.com/informent/Savepoint/releases/latest) |
| [Courier](https://github.com/informent/Courier) | Transfer files over a local network and verify receipts. | [Downloads](https://github.com/informent/Courier/releases/latest) |
| [Batchwork](https://github.com/informent/Batchwork) | Preview and recover batch file renames. | [Downloads](https://github.com/informent/Batchwork/releases/latest) |
| [Footprint](https://github.com/informent/Footprint) | Inspect disk use and export CSV reports. | [Downloads](https://github.com/informent/Footprint/releases/latest) |
| [Cliptray](https://github.com/informent/Cliptray) | Keep clipboard history on your device with opt-in capture, deletion and secret filters. | [Downloads](https://github.com/informent/Cliptray/releases/latest) |

### Systems and development

| Project | What it does | Downloads |
| --- | --- | --- |
| [Checkup](https://github.com/informent/Checkup) | Check Windows health and collect troubleshooting reports. | [Downloads](https://github.com/informent/Checkup/releases/latest) |
| [Rackwatch](https://github.com/informent/Rackwatch) | Inspect Windows servers and local ports. | [Downloads](https://github.com/informent/Rackwatch/releases/latest) |
| [Packbench](https://github.com/informent/Packbench) | Package desktop projects and verify ZIP contents. | [Downloads](https://github.com/informent/Packbench/releases/latest) |

## Latch

**Free and open source. Bring your own hosting.**

Latch is distributed as a source prerelease. Automated checks run on Windows and Linux; live Discord acceptance testing is still pending. Courier is also a preview; testing between two physical computers is pending.

[Releases and prereleases](https://github.com/informent/Latch/releases) · [Commands](https://github.com/informent/Latch/blob/main/COMMANDS.md) · [Setup](https://github.com/informent/Latch#start-here)

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
