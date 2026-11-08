## Sellat

**One proof. Three ways to use it.** Anyone can verify it, without trusting Sellat.

| | |
|---|---|
| **People** | Protect your photos and documents in seconds at [sellat.app](https://sellat.app). The fingerprint is computed on your device; the file is not uploaded. |
| **Businesses** | Build proof into your processes through the [API](https://sellat.app/en/developers): orders, accepted terms, contracts or records. The file never leaves your server. |
| **AI agents** | Every log, decision or result gets a verifiable proof that it existed at that moment and has not changed since. With an API key or pay-per-call over x402. |

How it works: Sellat registers a file's SHA-256 fingerprint (never the file), anchors it in Merkle batches on Polygon and attests it on Bitcoin through OpenTimestamps. On request it adds a qualified eIDAS electronic timestamp (RFC 3161).

### Open source

| Repository | What it does |
|---|---|
| [sellat-verify](https://github.com/sellatapp/sellat-verify) | Offline verifier. Checks a proof against the public blockchain without trusting Sellat. |
| [sellat-cli](https://github.com/sellatapp/sellat-cli) | Command line client and the Sellat Agent Skill. |
| [sellat-mcp](https://github.com/sellatapp/sellat-mcp) | MCP server for Claude, ChatGPT and other assistants. |

### Links

[sellat.app](https://sellat.app) · [llms.txt](https://sellat.app/llms.txt) · [OpenAPI](https://sellat.app/openapi.json) · [skill.md](https://sellat.app/skill.md)

A proof shows that exact bytes existed no later than the anchoring time and have not changed since. It does not prove authorship, ownership or that the content is true.
