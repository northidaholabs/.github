# North Idaho Labs

North Idaho Labs (NIL) builds open tools for **AI-first reality capture**: a person
states the outcome ("measure this window for a replacement"), and an AI agent
plans, aims, scans and checks its own work in the field, through an open API with
safety rules.

## Projects

| Repository | What it is |
| --- | --- |
| [trimble-x9-bridge](https://github.com/northidaholabs/trimble-x9-bridge) | Bridge service for the Trimble X9 laser scanner: one HTTP API for agents, apps and scripts, with approvals, aiming, exports and recipe runs. Rust; Linux x86_64 and aarch64 (Raspberry Pi) releases |
| [TrimbleX9-mcp](https://github.com/northidaholabs/TrimbleX9-mcp) | MCP server that gives any MCP-capable AI agent the scanner's tools, directly or through the bridge |
| [trimble-tzf](https://github.com/northidaholabs/trimble-tzf) | Decoder for the TZF point-cloud format: levelled XYZ, PLY and LAS export |

All three are interoperability projects for equipment we own. Each has a
`PROVENANCE.md` that records how its format or API knowledge was obtained.
They are independent and **not affiliated with or endorsed by Trimble Inc.**;
"Trimble" and "X9" are trademarks of their respective owners.
