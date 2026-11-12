# North Idaho Labs

The main project here replaces the point-and-click steps of reality capture software with AI reasoning. You give an AI agent the objective for the job, and it plans each scanner setup from the last scan and ties each new station into the ones before it until the job is done. And you can ask your favorite chatbot about the point cloud and get real measurements back, like window sizes and wall heights. Claude and Grok can both run it. Registering drone point clouds is next.

## Projects

| Repository | What it is | License |
| --- | --- | --- |
| [trimble-x9-bridge](https://github.com/northidaholabs/trimble-x9-bridge) | Bridge service for the Trimble X9 laser scanner: one HTTP API for agents, apps and scripts, with approvals, aiming, exports and recipe runs. Rust; Linux x86_64 and aarch64 (Raspberry Pi) releases | AGPL-3.0-or-later |
| [TrimbleX9-mcp](https://github.com/northidaholabs/TrimbleX9-mcp) | MCP server that gives any MCP-capable AI agent the scanner's tools, directly or through the bridge | AGPL-3.0-or-later |
| [trimble-tzf](https://github.com/northidaholabs/trimble-tzf) | Decoder for the TZF point-cloud format: levelled XYZ, PLY and LAS export | Apache-2.0 |
| [fix-dji-geo](https://github.com/northidaholabs/fix-dji-geo) | Writes an OpenDroneMap geo.txt from DJI mapping photos, using takeoff height plus RelativeAltitude and a GPS-to-shutter lag correction | Apache-2.0 |

For a commercial license to trimble-x9-bridge and TrimbleX9-mcp, see [northidaholabs.com/license](https://northidaholabs.com/license/).

The three scanner repositories are interoperability projects for equipment we have access to. Each has a
`PROVENANCE.md` that records how its format or API knowledge was obtained.
They are independent and **not affiliated with or endorsed by Trimble Inc.**;
"Trimble" and "X9" are trademarks of their respective owners.

fix-dji-geo is an independent interoperability project. It contains no DJI software, and it is **not affiliated with or endorsed by DJI**. "DJI" is a trademark of its owner.
