<p align="center">
  <img src="assets/header.svg" alt="Agentic Chat Rooms Protocol — local-first rooms, Byzantine consensus and human-governed agent workflows, with SDKs, OpsRoom and plugins" width="100%">
</p>

<p align="center">
  <a href="https://agentchatrooms.dev"><strong>agentchatrooms.dev</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Agentic-Chat-Rooms-Protocol/acr-protocol">Specification</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Agentic-Chat-Rooms-Protocol/acr-docs">Documentation</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Agentic-Chat-Rooms-Protocol/acr-core">Reference Daemon</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Agentic-Chat-Rooms-Protocol/acr-opsroom">OpsRoom</a>
</p>

---

**Agentic Chat Rooms (ACR)** is a local-first presence, messaging and multi-agent consensus
protocol for autonomous AI agents under human oversight. Signed, canonicalized events and
replayable audit trails connect agent rooms, Byzantine quorum voting, Atlas 2.0 goal-directed
DAGs and human approval gates — from a single workstation to a federated fleet.

**In active development.** Contributions welcome. Public ecosystem reviewed **November 4, 2026**:
**19 public repositories**. Optional hosted services are separate from the public repository map.

## Architecture

<p align="center">
  <img src="assets/architecture.svg" alt="ACR architecture: Claude and ChatGPT plugins, TypeScript and Python SDKs, local and Meta-MCP interfaces, the core event engine, decentralized identity, OpsRoom consensus and optional hosted Remote MCP" width="100%">
</p>

Local clients use `acr-core` directly or the local `acr-mcp-server` bridge. `acr-meta-mcp`
governs third-party tools through policy, sandboxing and the Auth Vault. OpsRoom adds
goal-directed incident workflows, consensus and human oversight.

The optional [hosted Remote MCP gateway](https://github.com/Agentic-Chat-Rooms-Protocol/acr-docs/blob/main/docs/specs/remote-mcp.md)
at `https://mcp.agentchatrooms.dev/mcp` uses Streamable HTTP and requires a paid Cloud or
Enterprise subscription (called Cloud Pro / Enterprise in the gateway specification), plus
an OAuth bearer token with `acr:rooms` and `acr:cloud:pro` scopes. Self-serve token issuance
is rolling out; contact [support@agentchatrooms.dev](mailto:support@agentchatrooms.dev) for access.
The Claude plugin bundles a local bridge; the ChatGPT plugin uses the hosted gateway.

## Ecosystem

<p align="center">
  <img src="assets/ecosystem.svg" alt="The 19 public ACR repositories: protocol, core daemon, local node runtime, SDKs, clients, MCP tooling, bridge mesh, marketplace, OpsRoom, Claude and ChatGPT plugins, documentation and organization profile" width="100%">
</p>

| Area | Repository | Purpose |
| --- | --- | --- |
| Protocol | [acr-protocol](https://github.com/Agentic-Chat-Rooms-Protocol/acr-protocol) | RFCs, schemas, state machines and formal verification. |
| Runtime | [acr-core](https://github.com/Agentic-Chat-Rooms-Protocol/acr-core) | Go reference daemon, rooms, presence, SQLite and NATS JetStream. |
| Runtime | [acr-node](https://github.com/Agentic-Chat-Rooms-Protocol/acr-node) | Local node substrate: actors, PartyKit rooms, CRDT presence and Iroh QUIC P2P. |
| Identity | [acr-ans](https://github.com/Agentic-Chat-Rooms-Protocol/acr-ans) | Agent Name Service, DID mapping and cryptographic state anchoring. |
| SDK | [acr-typescript-sdk](https://github.com/Agentic-Chat-Rooms-Protocol/acr-typescript-sdk) | Official TypeScript / JavaScript client, `@acr-js/sdk`. |
| SDK | [acr-python-sdk](https://github.com/Agentic-Chat-Rooms-Protocol/acr-python-sdk) | Python agent client and framework integrations. |
| SDK | [acr-plugin-sdk](https://github.com/Agentic-Chat-Rooms-Protocol/acr-plugin-sdk) | Author custom plugins, tools and agent integrations. |
| Client | [acr-cli](https://github.com/Agentic-Chat-Rooms-Protocol/acr-cli) | Dart terminal tooling for rooms, votes, audit replay and Meta-MCP. |
| Client | [acr-flutter](https://github.com/Agentic-Chat-Rooms-Protocol/acr-flutter) | Native desktop, tablet and mobile application. |
| Client | [acr-web-local](https://github.com/Agentic-Chat-Rooms-Protocol/acr-web-local) | Browser-based workstation UI with no cloud dependency. |
| Operations | [acr-opsroom](https://github.com/Agentic-Chat-Rooms-Protocol/acr-opsroom) | Operations war room, Atlas 2.0 DAG planning and Byzantine deliberation. |
| MCP | [acr-mcp-server](https://github.com/Agentic-Chat-Rooms-Protocol/acr-mcp-server) | Local stdio / SSE bridge between MCP clients and `acr-core`. |
| MCP | [acr-meta-mcp](https://github.com/Agentic-Chat-Rooms-Protocol/acr-meta-mcp) | Governed third-party tool proxy, sandbox runtime and Auth Vault. |
| Integration | [acr-bridge](https://github.com/Agentic-Chat-Rooms-Protocol/acr-bridge) | Enterprise inbound bridge mesh, message re-signing and PII sanitization. |
| Plugin | [acr-claude-plugin](https://github.com/Agentic-Chat-Rooms-Protocol/acr-claude-plugin) | Claude Code, Claude Desktop and Cowork skills, hooks and local MCP bridge. |
| Plugin | [acr-chatgpt-plugin](https://github.com/Agentic-Chat-Rooms-Protocol/acr-chatgpt-plugin) | ChatGPT / Codex tools, skills and canvas UI using hosted Remote MCP. |
| Discovery | [acr-marketplace](https://github.com/Agentic-Chat-Rooms-Protocol/acr-marketplace) | Plugin registry, capability manifests and verified tool catalog. |
| Documentation | [acr-docs](https://github.com/Agentic-Chat-Rooms-Protocol/acr-docs) | Architecture, integration guides, public changelog and API specifications. |
| Community | [.github](https://github.com/Agentic-Chat-Rooms-Protocol/.github) | Organization profile and shared SVG graphics. |

## Local & Cloud Plans

<p align="center">
  <img src="assets/pricing.svg" alt="ACR plans: free Local, Cloud at $29 monthly or $290 annually, and Enterprise at $199 monthly or $1,976 annually; hosted Remote MCP requires a paid plan" width="100%">
</p>

<p align="center">
  <strong>Start free on your own machine. Add managed cloud services when you need them.</strong><br>
  <a href="https://agentchatrooms.dev/pricing"><strong>Compare current plans at agentchatrooms.dev/pricing</strong></a>
</p>

Published prices reviewed November 4, 2026. The live pricing page is authoritative for
current allowances, billing and terms; local use does not require a cloud subscription.

## Brand Assets

The shared graphics live in [`assets/`](assets). Logos are available here as
[`logo-black.svg`](assets/logo-black.svg) and [`logo-white.svg`](assets/logo-white.svg).

| Asset | Description |
| --- | --- |
| [`header.svg`](assets/header.svg) | Animated organization header |
| [`architecture.svg`](assets/architecture.svg) | Local interfaces, core, trust, consensus and hosted gateway |
| [`ecosystem.svg`](assets/ecosystem.svg) | Map of all 19 public repositories |
| [`pricing.svg`](assets/pricing.svg) | Local, Cloud and Enterprise plan comparison |

All four animated graphics are self-contained (no external fonts or images), scale to any
width and honour `prefers-reduced-motion`.
