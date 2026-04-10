# Local-First Tools

[![License: MIT](https://img.shields.io/github/license/ResourceChest/local-first-tools)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ResourceChest/local-first-tools)](https://github.com/ResourceChest/local-first-tools/commits/main)
[![GitHub Stars](https://img.shields.io/github/stars/ResourceChest/local-first-tools)](https://github.com/ResourceChest/local-first-tools/stargazers)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/ResourceChest/.github/blob/main/CONTRIBUTING.md)
[![Link Check](https://github.com/ResourceChest/local-first-tools/actions/workflows/link-check.yml/badge.svg)](https://github.com/ResourceChest/local-first-tools/actions/workflows/link-check.yml)

> A curated list of tools and software that embrace the **local-first** philosophy: your data lives on your device, works offline by default, and syncs only when you choose.

## Why Local-First?

**Local-first** software keeps your data on your own hardware. The network is optional, not required. This means:

- **Privacy** -- Your data never has to leave your device. No third-party servers scanning your notes, files, or conversations.
- **Speed** -- No round-trips to a remote server. Everything loads instantly from local storage.
- **Ownership** -- You control your data. If a company shuts down, your files are still right where you left them.
- **Offline** -- Works on a plane, in a cabin, or anywhere without Wi-Fi. The internet is a feature, not a dependency.

This list collects the best tools that respect these principles -- from note-taking apps and office suites to encryption utilities and developer libraries.

---

## Contents

- [Note-Taking \& Knowledge Management](#note-taking--knowledge-management)
- [Writing \& Documents](#writing--documents)
- [Task Management \& Productivity](#task-management--productivity)
- [Communication](#communication)
- [File Storage \& Sync](#file-storage--sync)
- [Development Tools](#development-tools)
- [Media \& Creative](#media--creative)
- [Password \& Security](#password--security)
- [Browsers \& Web](#browsers--web)
- [More from ResourceChest](#more-from-resourcechest)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

---

## Note-Taking & Knowledge Management

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Obsidian](https://obsidian.md/) | Markdown-based knowledge base with a local vault, plugin ecosystem, and graph view. Your notes are plain `.md` files on disk. | Win/Mac/Linux/Mobile | No |
| [Logseq](https://github.com/logseq/logseq) | Open-source outliner and knowledge graph. Block-based editing with local Markdown and Org-mode storage. | Win/Mac/Linux/Mobile | Yes |
| [Joplin](https://github.com/laurent22/joplin) | Open-source note-taking and to-do app with E2E encrypted sync. Supports Markdown, notebooks, and tags. | Win/Mac/Linux/Mobile | Yes |
| [Zettlr](https://github.com/Zettlr/Zettlr) | Markdown editor built for academics and researchers. Integrates with Zotero, supports citations, and stores everything locally. | Win/Mac/Linux | Yes |
| [Anytype](https://anytype.io/) | Local-first, E2E encrypted workspace for notes, tasks, and databases. Data lives on your device with optional P2P sync. | Win/Mac/Linux/Mobile | Yes |
| [SiYuan](https://github.com/siyuan-note/siyuan) | Local-first personal knowledge management system with block-level referencing, E2E encrypted sync, and a built-in database. | Win/Mac/Linux/Mobile | Yes |
| [Trilium Notes](https://github.com/zadam/trilium) | Hierarchical note-taking application designed for building large personal knowledge bases. Self-hosted with optional sync. | Win/Mac/Linux | Yes |

## Writing & Documents

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [LibreOffice](https://www.libreoffice.org/) | Full-featured office suite (docs, spreadsheets, presentations) that works entirely with local files. No cloud required. | Win/Mac/Linux | Yes |
| [CryptPad](https://github.com/cryptpad/cryptpad) | E2E encrypted collaborative document suite (docs, sheets, presentations, kanban). Self-hostable with zero-knowledge architecture. | Web (self-hosted) | Yes |
| [Typst](https://github.com/typst/typst) | Modern typesetting system and alternative to LaTeX. Compiles locally, produces beautiful documents from markup. | Win/Mac/Linux | Yes |
| [Mark Text](https://github.com/marktext/marktext) | Simple and elegant open-source Markdown editor with live preview. Distraction-free writing with local file storage. | Win/Mac/Linux | Yes |

## Task Management & Productivity

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Todoist](https://todoist.com/) | Popular task manager with a robust offline mode. Tasks sync when connectivity returns. | Win/Mac/Linux/Mobile/Web | No |
| [Super Productivity](https://github.com/johannesjo/super-productivity) | Open-source time tracker and to-do list with Jira/GitHub/GitLab integration. All data stored locally by default. | Win/Mac/Linux/Mobile | Yes |
| [Vikunja](https://github.com/go-vikunja/vikunja) | Open-source to-do and project management application. Self-hostable with lists, kanban boards, and Gantt charts. | Web (self-hosted) | Yes |
| [Taskwarrior](https://github.com/GothenburgBitFactory/taskwarrior) | Command-line task management tool. All data stored in local files. Powerful filtering, reporting, and scripting. | Win/Mac/Linux | Yes |
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | Open-source Notion alternative built with Flutter and Rust. Local-first with optional self-hosted sync. | Win/Mac/Linux/Mobile | Yes |

## Communication

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Signal](https://signal.org/) | E2E encrypted messaging with disappearing messages, sealed sender, and no ads or trackers. | Win/Mac/Linux/Mobile | Yes |
| [Element](https://github.com/element-hq/element-web) / [Matrix](https://matrix.org/) | Decentralized, self-hostable chat built on the Matrix protocol. Federated E2E encryption with bridges to other platforms. | Win/Mac/Linux/Mobile/Web | Yes |
| [Briar](https://briarproject.org/) | Peer-to-peer encrypted messaging that works over Tor, Wi-Fi, or Bluetooth. Designed to function without internet infrastructure. | Android/Linux | Yes |
| [Thunderbird](https://www.thunderbird.net/) | Free, open-source email client. Email stored locally with full offline access. Supports PGP encryption via OpenPGP. | Win/Mac/Linux | Yes |

## File Storage & Sync

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Syncthing](https://github.com/syncthing/syncthing) | Continuous peer-to-peer file synchronization. No cloud, no sign-up -- devices talk directly to each other over encrypted channels. | Win/Mac/Linux/Android | Yes |
| [Nextcloud](https://github.com/nextcloud/server) | Self-hosted file storage and collaboration platform. Calendar, contacts, office docs, and more -- all under your control. | Win/Mac/Linux/Mobile/Web | Yes |
| [Resilio Sync](https://www.resilio.com/individuals/) | Peer-to-peer file sync powered by BitTorrent technology. Fast, private, and no cloud storage needed. | Win/Mac/Linux/Mobile | No |
| [IPFS](https://github.com/ipfs/kubo) | Distributed, peer-to-peer file system. Content-addressed storage that works without centralized servers. | Win/Mac/Linux | Yes |

## Development Tools

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Git](https://git-scm.com/) | The original local-first tool. Distributed version control with full repo history on every machine. | Win/Mac/Linux | Yes |
| [SQLite](https://www.sqlite.org/) | Serverless, zero-configuration, self-contained SQL database engine. The most widely deployed database in the world -- and it runs entirely on your machine. | Win/Mac/Linux | Yes |
| [PouchDB](https://github.com/pouchdb/pouchdb) / [CouchDB](https://github.com/apache/couchdb) | Local-first database that syncs. PouchDB runs in the browser; CouchDB handles the server side. Built-in conflict resolution. | Win/Mac/Linux/Web | Yes |
| [Automerge](https://github.com/automerge/automerge) | CRDT library for building local-first collaborative applications. Automatic conflict-free merging across devices. | Win/Mac/Linux/Web | Yes |
| [Yjs](https://github.com/yjs/yjs) | High-performance CRDT framework for real-time collaboration. Powers local-first editing in many apps. | Web | Yes |
| [ElectricSQL](https://github.com/electric-sql/electric) | Local-first sync layer for PostgreSQL. Keep a local SQLite database in sync with Postgres, with offline support and conflict resolution. | Win/Mac/Linux/Web | Yes |
| [Dolt](https://github.com/dolthub/dolt) | Git for data -- a SQL database with version control. Branch, merge, diff, and clone your data like source code. | Win/Mac/Linux | Yes |

## Media & Creative

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Krita](https://krita.org/) | Professional digital painting application. Fully offline with brush engines, animation tools, and HDR support. | Win/Mac/Linux | Yes |
| [GIMP](https://www.gimp.org/) | Powerful image editing and manipulation. A free, local alternative to Photoshop with decades of development. | Win/Mac/Linux | Yes |
| [Kdenlive](https://github.com/KDE/kdenlive) | Non-linear video editor with multi-track editing, effects, and transitions. All processing happens locally. | Win/Mac/Linux | Yes |
| [Audacity](https://github.com/audacity/audacity) | Multi-track audio editor and recorder. Record, edit, and export audio entirely offline. | Win/Mac/Linux | Yes |
| [Blender](https://www.blender.org/) | Complete 3D creation suite -- modeling, animation, rendering, compositing, and video editing. Fully local. | Win/Mac/Linux | Yes |

## Password & Security

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [KeePassXC](https://keepassxc.org/) | Cross-platform password manager. Database stored locally in an encrypted `.kdbx` file. No cloud, no account required. | Win/Mac/Linux | Yes |
| [Bitwarden](https://github.com/bitwarden/server) | Open-source password manager that can be entirely self-hosted with Vaultwarden. Full control over your credential storage. | Win/Mac/Linux/Mobile/Web | Yes |
| [age](https://github.com/FiloSottile/age) | Simple, modern file encryption tool. No configuration, no boilerplate -- just encrypt and decrypt files. | Win/Mac/Linux | Yes |
| [VeraCrypt](https://github.com/veracrypt/VeraCrypt) | Disk encryption software for creating encrypted volumes. Successor to TrueCrypt with active security audits. | Win/Mac/Linux | Yes |

## Browsers & Web

| Tool | Description | Platform | Open Source |
|---|-------|-------|:--------:|
| [Firefox](https://www.mozilla.org/firefox/) | Privacy-respecting browser backed by a non-profit. Enhanced Tracking Protection, containers, and a vast extension ecosystem. | Win/Mac/Linux/Mobile | Yes |
| [Brave](https://brave.com/) | Privacy-focused browser with built-in ad and tracker blocking. Chromium-based with shields enabled by default. | Win/Mac/Linux/Mobile | Yes |
| [Tor Browser](https://www.torproject.org/) | Browse anonymously through the Tor network. Defends against surveillance and circumvents censorship. | Win/Mac/Linux/Android | Yes |

---

## More from ResourceChest

| Repository | Description |
|:--------|:------|
| [Chrome Privacy Extensions](https://github.com/ResourceChest/chrome-privacy-extensions) | Curated Chrome extensions for privacy and security |
| [Custom GPTs](https://github.com/ResourceChest/custom-gpts) | Community-curated catalog of useful Custom GPTs with ratings |
| [AI Agents](https://github.com/ResourceChest/ai-agents) | Practical AI agents, frameworks, and tools for developers |
| [FinOps Tools](https://github.com/ResourceChest/finops-tools) | Vendor-neutral tools for cloud cost optimization |
| [Dev Tools (No Signup)](https://github.com/ResourceChest/dev-tools-no-signup) | Free developer tools that work instantly without an account |
| [AI & LLM Papers](https://github.com/ResourceChest/ai-llm-papers) | Foundational and frontier AI/LLM research papers reading list |

> **[Follow ResourceChest](https://github.com/ResourceChest)** for more curated resource collections.

---

## Contributing

Contributions are welcome! If you know of a local-first tool that belongs on this list, please open a pull request.

**Guidelines:**
- Make sure the tool genuinely works offline or stores data locally by default
- One tool per pull request for easier review
- Follow the existing table format: `| [Name](link) | Description | Platform | Open Source |`
- Keep descriptions concise (one to two sentences)
- Add new entries in alphabetical order within their category
- Check that all links are valid before submitting

See [CONTRIBUTING.md](https://github.com/ResourceChest/.github/blob/main/CONTRIBUTING.md) for more details.

## Disclaimer

This list is provided for informational purposes only. Inclusion does not imply endorsement, and the tools listed may change their features, privacy practices, or licensing at any time. Always review a tool's current documentation and privacy policy before relying on it for sensitive use cases. ResourceChest is not affiliated with any of the tools listed unless explicitly stated.

---

If you find this list useful, consider giving it a star and sharing it with others who value digital privacy and data ownership.
