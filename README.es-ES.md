

# Awesome Local-First [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Una colección curada de proyectos, herramientas y recursos de enfoque local-first para crear aplicaciones web con capacidad offline, centradas en la privacidad y colaborativas.

## Contenidos

- [¿Qué es Local-First?](#what-is-local-first)
- [Aplicaciones](#applications)
- [Frameworks y Plataformas](#frameworks--platforms)
- [Bibliotecas CRDT](#crdt-libraries)
- [Soluciones de Base de Datos](#database-solutions)
- [Sincronización y Redes](#sync--networking)
- [Autenticación y Autorización](#authentication--authorization)
- [Sistemas de Archivos y Almacenamiento](#file-systems--storage)
- [Herramientas para Desarrolladores](#developer-tools)
- [Recursos Educativos](#educational-resources)
- [Proyectos Relacionados](#related-projects)

## ¿Qué es Local-First?

El software de enfoque local-first prioriza el almacenamiento y procesamiento de datos locales, al tiempo que habilita una sincronización y colaboración fluidas cuando se está en línea.

### Lectura Fundamental

- 📄 [Local-first software - You own your data, in spite of the cloud](https://www.inkandswitch.com/local-first/) - El ensayo seminal de Ink & Switch | [PDF](https://martin.kleppmann.com/papers/local-first.pdf)
- 📄 [Local-First Web Development](https://localfirstweb.dev/) - Guía integral sobre los principios local-first en la web
- 📄 [Building Local-First Software](https://joelhooks.com/local-first-software) - Perspectivas prácticas sobre la implementación

### Videos

- 🎥 [Automerge: Making servers optional for real-time collaboration](https://www.youtube.com/watch?v=PHz17gwiOc8) - Martin Kleppmann
- 🎥 [CRDTs for Mortals](https://www.youtube.com/watch?v=DEcwa68f-jY) - James Long
- 🎥 [Local-First Software: The Future of App Development](https://www.youtube.com/watch?v=KrPsyr8Ig6M) - Johannes Schickling

### Artículos de Investigación

- [Verifying strong eventual consistency in distributed systems](https://dl.acm.org/doi/10.1145/3133933) - Victor B. F. Gomes, et al.
- [Automerge: Real-time data sync between edge devices](https://arxiv.org/abs/1608.03960) - Martin Kleppmann, et al.

## Aplicaciones

### Productividad y Gestión del Conocimiento

- [**Actual**](https://github.com/actualbudget/actual) - Gestión de finanzas personales centrada en la privacidad
- [**AFFiNE**](https://github.com/toeverything/AFFiNE) - Base de conocimiento de próxima generación que combina planificación, organización y creación. Alternativa de código abierto a Notion
- [**Anytype**](https://github.com/anyproto/anytype-ts) - Herramienta de gestión del conocimiento y colaboración P2P de enfoque local-first
- [**Bangle.io**](https://github.com/bangle-io/bangle-io) - Aplicación nativa web para tomar notas en markdown con almacenamiento local
- [**EchoTalk**](https://alisolphp.github.io/EchoTalk/) - PWA de práctica de shadowing offline con enfoque en la privacidad. Todas las grabaciones se almacenan localmente, con retroalimentación de pronunciación por IA.
- [**Kuku**](https://kuku.mom) - Espacio de trabajo Markdown local-first de código abierto con ediciones asistidas por IA, enlaces inversos, navegación por grafo y sincronización encriptada opcional
- [**Logseq**](https://github.com/logseq/logseq) - Base de conocimiento de código abierto con enfoque en la privacidad y enlaces bidireccionales
- [**Obsidian**](https://obsidian.md/) - Potente base de conocimiento sobre archivos markdown locales
- [**Notesnook**](https://github.com/streetwriters/notesnook) - Aplicación para tomar notas con enfoque en la privacidad y cifrado de extremo a extremo
- [**TidGi**](https://github.com/tiddly-gittly/TidGi-Desktop) - Base de conocimiento personal con respaldo en Git
- [**TiddlyWiki**](https://github.com/Jermolene/TiddlyWiki5) - Wiki autocontenida en JavaScript
- [**Volon**](https://github.com/danielgolden/volon) - Aplicación de notas en texto plano con enfoque en markdown
- [**Screenpipe**](https://github.com/mediar-ai/screenpipe) - Grabación de pantalla y micrófono con IA local 24/7 para construir aplicaciones de IA con contexto. Alternativa 100% local y centrada en la privacidad a Rewind.ai

### Diseño y Creatividad

- [**Penpot**](https://github.com/penpot/penpot) - Plataforma de diseño y prototipado de código abierto (capaz de modo local-first)
- [**tldraw**](https://github.com/tldraw/tldraw) - SDK de lienzo infinito con multijugador local-first

### Herramientas de Desarrollo

- [**Linear**](https://linear.app/) - Seguimiento de problemas con soporte offline excepcional (propietario)
- [**Claw Task Hub**](https://github.com/Catfish-75/claw-task-hub) - Hub de tareas local-first respaldado por SQLite para agentes de IA y flujos de trabajo de orquestación de agentes
- [**Radicle**](https://github.com/radicle-dev/radicle-interface) - Colaboración de código P2P construida sobre Git

### Comunicación

- [**Secure Scuttlebutt**](https://github.com/ssbc/ssb-server) - Protocolo de comunicación P2P y red social
- [**Berty**](https://github.com/berty/berty) - Aplicación de mensajería con enfoque en la privacidad y capacidades offline-first

### Salud y Fitness

- [**nobro.app**](https://nobro.app/) - Rastreador de programas de entrenamiento offline-first minimalista. El estado y el programa editable residen en localStorage, sin backend. PWA, 11 idiomas

## Frameworks y Plataformas

### Frameworks Full-Stack

- [**ElectricSQL**](https://github.com/electric-sql/electric) - Capa de sincronización local-first para Postgres con hooks de React
- [**Jazz**](https://github.com/gardencmp/jazz) - Sincronización instantánea con valores colaborativos como primitiva central
- [**Replicache**](https://github.com/rocicorp/replicache) - Local-first rápido y fácil con interfaz optimista
- [**PowerSync**](https://github.com/powersync-ja/powersync-js) - Capa de sincronización en tiempo real para SQLite en edge/móvil
- [**Triplit**](https://github.com/aspen-cloud/triplit) - Base de datos full-stack con sincronización integrada y actualizaciones optimistas
- [**Verdant**](https://github.com/a-type/verdant) - Framework para aplicaciones React local-first
- [**VLCN (cr-sqlite)**](https://github.com/vlcn-io/cr-sqlite) - SQLite convergente y replicado para aplicaciones distribuidas
- [**Zero**](https://github.com/rocicorp/zero) - Sincronización de base de datos reactiva local-first para TypeScript
- [**Ditto**](https://github.com/getditto/ditto) - Base de datos P2P para edge y móvil (comercial)

### Kits de Inicio y Plantillas Base

- [**DIPLOMATIC**](https://github.com/diplomatic-app/diplomatic) - Kit de inicio de cero a lofi con autenticación y sincronización
- [**Socket Supply**](https://github.com/socketsupply/socket) - Framework para aplicaciones P2P local-first
- [**Instant**](https://github.com/instantdb/instant) - Base de datos del lado del cliente con escritura de latencia cero

## Bibliotecas CRDT

### Listas para Producción

- [**Automerge**](https://github.com/automerge/automerge) - CRDT tipo JSON para edición concurrente
- [**Yjs**](https://github.com/yjs/yjs) - CRDT de alto rendimiento para edición compartida
- [**Loro**](https://github.com/loro-dev/loro) - Framework CRDT reimplementado con viaje en el tiempo y texto enriquecido
- [**diamond-types**](https://github.com/josephg/diamond-types) - CRDT experimental de alto rendimiento

### Especializadas

- [**Automerge-Repo**](https://github.com/automerge/automerge-repo) - Automerge completo con capacidades de red
- [**y-crdt**](https://github.com/y-crdt/y-crdt) - Versión de Yjs en Rust
- [**y-sweet**](https://github.com/drifting-in-space/y-sweet) - Backend de sincronización Yjs como servicio
- [**SyncedStore**](https://github.com/YousefED/SyncedStore) - Yjs con una API basada en estado fácil de usar

## Soluciones de Base de Datos

### Bases de Datos Empotradas

- [**RxDB**](https://github.com/pubkey/rxdb) - Base de datos reactiva y offline-first para JavaScript
- [**PGlite**](https://github.com/electric-sql/pglite) - Postgres ligero en WASM para el navegador
- [**SQLite WASM**](https://github.com/sqlite/sqlite-wasm) - SQLite oficial compilado a WebAssembly
- [**WatermelonDB**](https://github.com/Nozbe/WatermelonDB) - Base de datos reactiva para aplicaciones poderosas de React/React Native
- [**absurd-sql**](https://github.com/jlongster/absurd-sql) - SQLite para la web con backend de IndexedDB
- [**DuckDB-WASM**](https://github.com/duckdb/duckdb-wasm) - Base de datos analítica en el navegador

### Bases de Datos de Grafo y Documentos

- [**Gun**](https://github.com/amark/gun) - Base de datos de grafo descentralizada
- [**OrbitDB**](https://github.com/orbitdb/orbit-db) - Base de datos P2P sobre IPFS
- [**Fireproof**](https://github.com/fireproof-storage/fireproof) - Base de datos CRDT empotrable con almacenamiento verificable

## Sincronización y Redes

### Motores de Sincronización

- [**Automerge-Repo**](https://github.com/automerge/automerge-repo) - Solución de sincronización completa para Automerge
- [**Partykit**](https://github.com/partykit/partykit) - Infraestructura multijugador con patrones local-first
- [**Liveblocks**](https://github.com/liveblocks/liveblocks) - Infraestructura de colaboración en tiempo real
- [**Evolu**](https://github.com/evoluhq/evolu) - Plataforma local-first con cifrado E2E

### Protocolos P2P

- [**Hypercore Protocol**](https://github.com/hypercore-protocol/hypercore) - Registro distribuido de solo agregación
- [**IPFS**](https://github.com/ipfs/ipfs) - Protocolo de hipermultimedia P2P
- [**libp2p**](https://github.com/libp2p/js-libp2p) - Pila de networking P2P modular
- [**WebRTC**](https://webrtc.org/) - Comunicación peer-to-peer directa en navegadores
- [**Hyperswarm**](https://github.com/hyperswarm/hyperswarm) - Pila de networking P2P

## Autenticación y Autorización

- [**Lucia**](https://github.com/lucia-auth/lucia) - Autenticación simple y flexible para TypeScript
- [**NextAuth.js**](https://github.com/nextauthjs/next-auth) - Autenticación para Next.js con soporte offline
- [**Clerk**](https://clerk.com/) - Autenticación moderna con capacidades offline-first
- [**Amplify Auth**](https://github.com/aws-amplify/amplify-js) - Autenticación de AWS con soporte offline

## Sistemas de Archivos y Almacenamiento

### Sistemas de Archivos Virtuales

- [**BrowserFS**](https://github.com/jvilk/BrowserFS) - Sistema de archivos tipo Unix para el navegador
- [**Filer**](https://github.com/filerjs/filer) - Sistema de archivos tipo POSIX para navegadores
- [**LightningFS**](https://github.com/isomorphic-git/lightning-fs) - Sistema de archivos simple para isomorphic-git

### Abstracciones de Almacenamiento

- [**localforage**](https://github.com/localForage/localForage) - Almacenamiento offline con una API simple de localStorage
- [**idb**](https://github.com/jakearchibald/idb) - Wrapper de IndexedDB con promesas
- [**Dexie.js**](https://github.com/dexie/Dexie.js) - Wrapper minimalista de IndexedDB
- [**IndexedDB API**](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - Almacenamiento nativo del navegador

## Herramientas para Desarrolladores

### Depuración y Monitoreo

- [**Automerge DevTools**](https://github.com/automerge/automerge-devtools) - Extensión de Chrome para Automerge
- [**Y-WebRTC Monitor**](https://github.com/yjs/y-webrtc) - Monitor de red para Yjs

### Pruebas

- [**fake-indexeddb**](https://github.com/dumbmatter/fakeIndexedDB) - Implementación de IndexedDB para pruebas
- [**MSW**](https://github.com/mswjs/msw) - Simulación de API para escenarios offline

### Herramientas CLI

- [**isomorphic-git**](https://github.com/isomorphic-git/isomorphic-git) - Implementación de Git en JavaScript puro
- [**sql.js**](https://github.com/sql-js/sql.js) - SQLite compilado a JavaScript

## Recursos Educativos

### Tutoriales y Guías

- [**localfirstweb.dev**](https://localfirstweb.dev/) - Guía integral de web local-first
- [**CRDT.tech**](https://crdt.tech/) - Recurso educativo sobre CRDTs
- [**Automerge Tutorial**](https://automerge.org/docs/tutorial/) - Guía oficial de Automerge

### Comunidad

- [**Local-First Web Discord**](https://discord.gg/localfirst) - Discusiones activas de la comunidad
- [**lofi.so**](https://lofi.so/) - Enlaces y recursos para software local-first

### Aplicaciones de Ejemplo

- [**Automerge Examples**](https://github.com/automerge/automerge/tree/main/examples) - Ejemplos oficiales
- [**Yjs Demos**](https://github.com/yjs/yjs-demos) - Varias implementaciones de Yjs
- [**Jazz Examples**](https://github.com/gardencmp/jazz/tree/main/examples) - Demos del framework Jazz

## Proyectos Relacionados

### Listas Curadas

- [**schickling/awesome-local-first**](https://github.com/schickling/awesome-local-first) - Otra lista awesome
- [**zhongkechen/awesome-local-first**](https://github.com/zhongkechen/awesome-local-first) - Recursos adicionales
- [**radical-data/awesome-local-first**](https://github.com/radical-data/awesome-local-first) - Enfoque en soberanía de datos

### Grupos de Investigación

- [**Ink & Switch**](https://www.inkandswitch.com/) - Laboratorio de investigación que explora conceptos local-first
- [**Martin Kleppmann**](https://martin.kleppmann.com/) - Investigación académica sobre CRDTs y sistemas distribuidos

---

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, lee las [guías de contribución](CONTRIBUTING.md) primero.

## Licencia

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

En la medida de lo posible según la ley, los contribuyentes han renunciado a todos los derechos de autor y derechos relacionados con esta obra.
