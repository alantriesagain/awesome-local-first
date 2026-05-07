# Awesome Local-First [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated collection of local-first projects, tools, and resources for building offline-capable, privacy-focused, and collaborative applications on the web.

## Contents

- [What is Local-First?](#what-is-local-first)
- [Applications](#applications)
- [Frameworks & Platforms](#frameworks--platforms)
- [CRDT Libraries](#crdt-libraries)
- [Database Solutions](#database-solutions)
- [Sync & Networking](#sync--networking)
- [Authentication & Authorization](#authentication--authorization)
- [File Systems & Storage](#file-systems--storage)
- [Developer Tools](#developer-tools)
- [Educational Resources](#educational-resources)
- [Related Projects](#related-projects)

## What is Local-First?

Local-first software prioritizes local data storage and processing while enabling seamless sync and collaboration when online.

### Core Reading

- 📄 [Local-first software - You own your data, in spite of the cloud](https://www.inkandswitch.com/local-first/) - The seminal Ink & Switch essay | [PDF](https://martin.kleppmann.com/papers/local-first.pdf)
- 📄 [Local-First Web Development](https://localfirstweb.dev/) - Comprehensive guide to local-first principles on the web
- 📄 [Building Local-First Software](https://joelhooks.com/local-first-software) - Practical perspectives on implementation

### Videos

- 🎥 [Automerge: Making servers optional for real-time collaboration](https://www.youtube.com/watch?v=PHz17gwiOc8) - Martin Kleppmann
- 🎥 [CRDTs for Mortals](https://www.youtube.com/watch?v=DEcwa68f-jY) - James Long
- 🎥 [Local-First Software: The Future of App Development](https://www.youtube.com/watch?v=KrPsyr8Ig6M) - Johannes Schickling

### Research Papers

- [Verifying strong eventual consistency in distributed systems](https://dl.acm.org/doi/10.1145/3133933) - Victor B. F. Gomes, et al.
- [Automerge: Real-time data sync between edge devices](https://arxiv.org/abs/1608.03960) - Martin Kleppmann, et al.

## Applications

### Productivity & Knowledge Management

- [**Actual**](https://github.com/actualbudget/actual) - Privacy-focused personal finance management
- [**AFFiNE**](https://github.com/toeverything/AFFiNE) - Next-gen knowledge base combining planning, sorting, and creating. Open-source Notion alternative
- [**Anytype**](https://github.com/anyproto/anytype-ts) - Local-first, P2P knowledge management and collaboration tool
- [**Bangle.io**](https://github.com/bangle-io/bangle-io) - Web-native markdown note-taking app with local storage
- [EchoTalk](https://alisolphp.github.io/EchoTalk/) - Privacy-first offline shadowing practice PWA. All recordings stored locally, AI pronunciation feedback.
- [**Logseq**](https://github.com/logseq/logseq) - Privacy-first, open-source knowledge base with bidirectional linking
- [**Obsidian**](https://obsidian.md/) - Powerful knowledge base on top of local markdown files
- [**Notesnook**](https://github.com/streetwriters/notesnook) - Privacy-focused, end-to-end encrypted note-taking app
- [**TidGi**](https://github.com/tiddly-gittly/TidGi-Desktop) - Personal knowledge base with Git backup
- [**TiddlyWiki**](https://github.com/Jermolene/TiddlyWiki5) - Self-contained JavaScript wiki
- [**Volon**](https://github.com/danielgolden/volon) - Plain text, markdown-focused notes app

### Design & Creative

- [**Penpot**](https://github.com/penpot/penpot) - Open-source design and prototyping platform (local-first capable)
- [**tldraw**](https://github.com/tldraw/tldraw) - Infinite canvas SDK with local-first multiplayer

### Development Tools

- [**Linear**](https://linear.app/) - Issue tracking with exceptional offline support (proprietary)
- [**Radicle**](https://github.com/radicle-dev/radicle-interface) - P2P code collaboration built on Git

### Communication

- [**Secure Scuttlebutt**](https://github.com/ssbc/ssb-server) - P2P communication protocol and social network
- [**Berty**](https://github.com/berty/berty) - Privacy-first messaging app with offline-first capabilities

## Frameworks & Platforms

### Full-Stack Frameworks

- [**ElectricSQL**](https://github.com/electric-sql/electric) - Local-first sync layer for Postgres with React hooks
- [**Jazz**](https://github.com/gardencmp/jazz) - Instant sync with collaborative values as the core primitive
- [**Replicache**](https://github.com/rocicorp/replicache) - Fast, easy local-first with optimistic UI
- [**PowerSync**](https://github.com/powersync-ja/powersync-js) - Real-time sync layer for SQLite on edge/mobile
- [**Triplit**](https://github.com/aspen-cloud/triplit) - Full-stack database with built-in sync and optimistic updates
- [**Verdant**](https://github.com/a-type/verdant) - Framework for local-first React applications
- [**VLCN (cr-sqlite)**](https://github.com/vlcn-io/cr-sqlite) - Convergent, replicated SQLite for distributed apps
- [**Zero**](https://github.com/rocicorp/zero) - Local-first, reactive database sync for TypeScript
- [**Ditto**](https://github.com/getditto/ditto) - P2P database for edge and mobile (commercial)

### Starter Kits & Boilerplates

- [**DIPLOMATIC**](https://github.com/diplomatic-app/diplomatic) - Zero-to-lofi starter with auth and sync
- [**Socket Supply**](https://github.com/socketsupply/socket) - Framework for local-first P2P applications
- [**Instant**](https://github.com/instantdb/instant) - Client-side database with zero-latency writes

## CRDT Libraries

### Production-Ready

- [**Automerge**](https://github.com/automerge/automerge) - JSON-like CRDT for concurrent editing
- [**Yjs**](https://github.com/yjs/yjs) - High-performance CRDT for shared editing
- [**Loro**](https://github.com/loro-dev/loro) - Reimagined CRDT framework with time-travel and rich-text
- [**diamond-types**](https://github.com/josephg/diamond-types) - Experimental high-performance CRDT

### Specialized

- [**Automerge-Repo**](https://github.com/automerge/automerge-repo) - Batteries-included Automerge with networking
- [**y-crdt**](https://github.com/y-crdt/y-crdt) - Rust port of Yjs
- [**y-sweet**](https://github.com/drifting-in-space/y-sweet) - Yjs sync backend as a service
- [**SyncedStore**](https://github.com/YousefED/SyncedStore) - Yjs with an easy state-based API

## Database Solutions

### Embedded Databases

- [**RxDB**](https://github.com/pubkey/rxdb) - Reactive, offline-first database for JavaScript
- [**PGlite**](https://github.com/electric-sql/pglite) - Lightweight Postgres in WASM for the browser
- [**SQLite WASM**](https://github.com/sqlite/sqlite-wasm) - Official SQLite compiled to WebAssembly
- [**WatermelonDB**](https://github.com/Nozbe/WatermelonDB) - Reactive database for powerful React/React Native apps
- [**absurd-sql**](https://github.com/jlongster/absurd-sql) - SQLite for the web with IndexedDB backend
- [**DuckDB-WASM**](https://github.com/duckdb/duckdb-wasm) - Analytical database in the browser

### Graph & Document Databases

- [**Gun**](https://github.com/amark/gun) - Decentralized graph database
- [**OrbitDB**](https://github.com/orbitdb/orbit-db) - P2P database on IPFS
- [**Fireproof**](https://github.com/fireproof-storage/fireproof) - Embeddable CRDT database with verifiable storage

## Sync & Networking

### Sync Engines

- [**Automerge-Repo**](https://github.com/automerge/automerge-repo) - Complete sync solution for Automerge
- [**Partykit**](https://github.com/partykit/partykit) - Multiplayer infrastructure with local-first patterns
- [**Liveblocks**](https://github.com/liveblocks/liveblocks) - Real-time collaboration infrastructure
- [**Evolu**](https://github.com/evoluhq/evolu) - Local-first platform with E2E encryption

### P2P Protocols

- [**Hypercore Protocol**](https://github.com/hypercore-protocol/hypercore) - Distributed append-only log
- [**IPFS**](https://github.com/ipfs/ipfs) - P2P hypermedia protocol
- [**libp2p**](https://github.com/libp2p/js-libp2p) - Modular P2P networking stack
- [**WebRTC**](https://webrtc.org/) - Direct peer-to-peer communication in browsers
- [**Hyperswarm**](https://github.com/hyperswarm/hyperswarm) - P2P networking stack

## Authentication & Authorization

- [**Lucia**](https://github.com/lucia-auth/lucia) - Simple, flexible auth for TypeScript
- [**NextAuth.js**](https://github.com/nextauthjs/next-auth) - Authentication for Next.js with offline support
- [**Clerk**](https://clerk.com/) - Modern auth with offline-first capabilities
- [**Amplify Auth**](https://github.com/aws-amplify/amplify-js) - AWS authentication with offline support

## File Systems & Storage

### Virtual File Systems

- [**BrowserFS**](https://github.com/jvilk/BrowserFS) - Unix-like file system for the browser
- [**Filer**](https://github.com/filerjs/filer) - POSIX-like file system for browsers
- [**LightningFS**](https://github.com/isomorphic-git/lightning-fs) - Simple file system for isomorphic-git

### Storage Abstractions

- [**localforage**](https://github.com/localForage/localForage) - Offline storage with simple localStorage API
- [**idb**](https://github.com/jakearchibald/idb) - IndexedDB wrapper with promises
- [**Dexie.js**](https://github.com/dexie/Dexie.js) - Minimalistic IndexedDB wrapper
- [**IndexedDB API**](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - Native browser storage

## Developer Tools

### Debugging & Monitoring

- [**Automerge DevTools**](https://github.com/automerge/automerge-devtools) - Chrome extension for Automerge
- [**Y-WebRTC Monitor**](https://github.com/yjs/y-webrtc) - Network monitor for Yjs

### Testing

- [**fake-indexeddb**](https://github.com/dumbmatter/fakeIndexedDB) - IndexedDB implementation for testing
- [**MSW**](https://github.com/mswjs/msw) - API mocking for offline scenarios

### CLI Tools

- [**isomorphic-git**](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript Git implementation
- [**sql.js**](https://github.com/sql-js/sql.js) - SQLite compiled to JavaScript

## Educational Resources

### Tutorials & Guides

- [**localfirstweb.dev**](https://localfirstweb.dev/) - Comprehensive local-first web guide
- [**CRDT.tech**](https://crdt.tech/) - Educational resource on CRDTs
- [**Automerge Tutorial**](https://automerge.org/docs/tutorial/) - Official Automerge guide

### Community

- [**Local-First Web Discord**](https://discord.gg/localfirst) - Active community discussions
- [**lofi.so**](https://lofi.so/) - Links and resources for local-first software

### Example Apps

- [**Automerge Examples**](https://github.com/automerge/automerge/tree/main/examples) - Official examples
- [**Yjs Demos**](https://github.com/yjs/yjs-demos) - Various Yjs implementations
- [**Jazz Examples**](https://github.com/gardencmp/jazz/tree/main/examples) - Jazz framework demos

## Related Projects

### Curated Lists

- [**schickling/awesome-local-first**](https://github.com/schickling/awesome-local-first) - Another awesome list
- [**zhongkechen/awesome-local-first**](https://github.com/zhongkechen/awesome-local-first) - Additional resources
- [**radical-data/awesome-local-first**](https://github.com/radical-data/awesome-local-first) - Focus on data sovereignty

### Research Groups

- [**Ink & Switch**](https://www.inkandswitch.com/) - Research lab exploring local-first concepts
- [**Martin Kleppmann**](https://martin.kleppmann.com/) - Academic research on CRDTs and distributed systems

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
