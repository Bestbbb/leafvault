# LeafVault

A planned free and fully open-source Markdown notes app, with a comfortable desktop editor and self-hosted sync.

**Status: planning only.** This repository contains product and engineering plans. There is no application, installer, sync server, or deployment image yet. Everything described below is a target.

[中文说明](README.zh-CN.md) · [Product plan](docs/PRODUCT_PLAN.zh-CN.md) · [Roadmap](docs/ROADMAP.zh-CN.md)

## Project principles

- All first-party clients and the sync server are open source under **AGPL-3.0-only**.
- Official software releases will be free to download and use, including commercial use, with no feature paywalls, license keys, or device-count paywalls.
- Local editing works offline and requires no project-operated account or service.
- Notes remain ordinary Markdown files with ordinary attachments.
- Self-hosted sync is a first-class part of the product, including conflict recovery and backup documentation.
- No advertising or behavioral telemetry. Diagnostic information is shared only through an explicit user action.

Hosting, storage, bandwidth, and platform distribution can incur costs. Free software does not promise free infrastructure. The license permits commercial activity; the no-paywall policy describes this project's official releases.

## Planned first release

Start with macOS and make one complete workflow reliable:

**Open a folder → write → link notes → search → close and reopen → recover earlier content.**

The desktop alpha targets Markdown editing with live preview, Chinese input, pasted images, wikilinks, backlinks, tags, quick switching, and local history. Self-hosted sync follows as a separate milestone. Windows and Linux require their own validation before being listed as supported.

Obsidian-compatible file formats are a migration goal. Plugin execution, themes, Canvas, and every Obsidian syntax extension are outside the initial compatibility promise. LeafVault is an independent project.

## Planning documents

| Document | Purpose |
| --- | --- |
| [Product plan](docs/PRODUCT_PLAN.zh-CN.md) | Users, experience, scope, and free-software policy |
| [Architecture proposal](docs/ARCHITECTURE.zh-CN.md) | Candidate stack, file ownership, recovery, and compatibility |
| [Self-hosted sync proposal](docs/SYNC.zh-CN.md) | Deployment target, conflict rules, backups, and privacy boundaries |
| [Roadmap and acceptance criteria](docs/ROADMAP.zh-CN.md) | Milestones, dependencies, effort ranges, and release gates |
| [Research notes](docs/RESEARCH.zh-CN.md) | Primary sources and questions to validate |

Plans are primarily in Chinese at this stage. Technical choices remain proposals until the corresponding experiments pass.

## Contributing

Product feedback, use cases, compatibility examples, and documentation improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md). Please use synthetic notes in public examples.

## License

Copyright © 2026 LeafVault contributors.

Except where separately identified, original repository content is licensed under the **GNU Affero General Public License, version 3 only** (`AGPL-3.0-only`). See [LICENSE](LICENSE).
