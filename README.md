# Raymond de Oliveira

AI product leader in San Francisco (VP Product at [Green](https://green.com); previously Klarity/Within, Limit, NEXT Insurance, and Bain). Outside my day job, I write algorithmic trading systems and build tiny, zero-dependency CLI utilities and MCP servers for 3D displays, AR glasses, and AI agents.

**[Website](https://www.raymonddeoliveira.com)** · **[Software Hub](https://www.raymonddeoliveira.com/software)** · **[Polar Store ($49 Bundle)](https://polar.sh/raymond-de-oliveira)** · **[Glama Verified MCPs](https://glama.ai/mcp/servers?query=raydeoliveira)** · **[Substack](https://raymonddeoliveira.substack.com/)** · **[X (@rayofolives)](https://x.com/rayofolives)** · **[LinkedIn](https://www.linkedin.com/in/raymonddeoliveira)**

---

## Spatial 3D Display & MCP Software Suite

Six clean-room C17, Swift, and Cloudflare Workers utilities (`142 KB` to `886 KB`, zero runtime dependencies, automatic 15-second hardware rollback, and `--json` + MCP interfaces for humans and AI agents).

**Try the free core on macOS Apple Silicon in 10 seconds:**

```bash
brew tap raydeoliveira/tap
brew install edidsmith xrctl depthpipe glassweave stereoweave
```

**Or grab all 4 Spatial Wedge CLIs in one perpetual license:** [**Spatial 3D Wedge Complete Bundle ($49 one-time, save $57 vs. $106 separately)**](https://buy.polar.sh/polar_cl_KTtCY3iQC4bzjqp93aC6LCog8UZqzZzuDgkAs3BvF74) (includes 4 perpetual keys for 3 devices each, all 12 checksummed `.tar.gz`/`.mcpb` downloads, and unlocked calls on `spatial-mcp-worker`).

| Utility | Size | What It Unlocks | Free Core / Pro | Links |
|---|---|---|---|---|
| **[EdidSmith](https://github.com/raydeoliveira/edidsmith)** | `886 KB` | VESA EDID 1.4 / CTA-861 / DisplayID 2.1 parser, CVT-RB2 link-budget solver & safe rollback overrides | Free Core / [$29 Pro](https://buy.polar.sh/polar_cl_pIMhrQJ83UQ82DxtgU7wU4yRWDOm9KHFbH32k35gjKV) | [Hub](https://www.raymonddeoliveira.com/software#edidsmith) · [Glama](https://glama.ai/mcp/servers/raydeoliveira/edidsmith) |
| **[xrctl](https://github.com/raydeoliveira/xrctl)** | `142 KB` | 4-vendor C17 AR glasses CLI (XREAL, VITURE, Rokid, RayNeo): 2D/3D SBS rollback, tint, 120 Hz, 1000 Hz IMU | Free Core / [$19 Pro](https://buy.polar.sh/polar_cl_xBuVDUMFZ51noqtr3hX44WD57cnL7LkElA3lL2Hy2Dc) | [Hub](https://www.raymonddeoliveira.com/software#xrctl) · [Glama](https://glama.ai/mcp/servers/raydeoliveira/xrctl) |
| **[DepthPipe](https://github.com/raydeoliveira/depthpipe)** | `857 KB` | Live Metal DIBR 2D-to-3D depth weaving, CoreML Depth Anything V2, MV-HEVC Spatial Video & SteamOS Vulkan layer | Free Core / [$29 Pro](https://buy.polar.sh/polar_cl_pM3CJwYQ9ilUfvBxDVLf0iMGnTBJltLssCFFj1YSozm) | [Hub](https://www.raymonddeoliveira.com/software#depthpipe) · [Glama](https://glama.ai/mcp/servers/raydeoliveira/depthpipe) |
| **[GlassWeave](https://github.com/raydeoliveira/glassweave)** | `849 KB` | Cross-OS eye-tracked glasses-free 3D display CLI (Samsung Odyssey 3D, Acer SpatialLabs, ASUS, Lenovo) | Free Core / [$29 Pro](https://buy.polar.sh/polar_cl_RVXA4XqANyC7aXm12WybluTFQ7u2cxvoClgln2MWxuk) | [Hub](https://www.raymonddeoliveira.com/software#glassweave) · [Glama](https://glama.ai/mcp/servers/raydeoliveira/glassweave) |
| **[StereoWeave](https://github.com/raydeoliveira/stereoweave)** | `630 KB` | All-in-one Apple Silicon macOS EDID 3D/RGB-4:4:4 override, 8-layout Metal stereo weaver & MV-HEVC converter | Free Core / [$29 Pro](https://buy.polar.sh/polar_cl_MrcR0NZr2XlxyaOUb0Mb1LfcYkpRB95tdMtpr1Okyyf) | [Hub](https://www.raymonddeoliveira.com/software#stereoweave) · [Glama](https://glama.ai/mcp/servers/raydeoliveira/stereoweave) |
| **[Spatial MCP Oracle](https://github.com/raydeoliveira/spatial-mcp-worker)** | Cloud | Remote Streamable HTTP MCP on Cloudflare Workers for CVT-RB2 budgets, EDID patching & lenticular optics | Free / $0.005–$0.01 x402 | [Connector](https://glama.ai/mcp/connectors/io.github.raydeoliveira/spatial-mcp-worker) · [Hub](https://www.raymonddeoliveira.com/software#spatial-mcp-worker) |

### For AI Agents & MCP Clients
- **Official MCP Registry:** `io.github.raydeoliveira/*` ([live registry query](https://registry.modelcontextprotocol.io/v0/servers?search=raydeoliveira))
- **Agent Skills (`skills.sh`):** `npx skills add raydeoliveira/edidsmith` (available across all 6 repos)
- **Live Remote HTTP MCP:** `https://spatial-mcp-worker.raymond-deoliveira.workers.dev/mcp` ([Server Card](https://spatial-mcp-worker.raymond-deoliveira.workers.dev/.well-known/mcp/server-card.json))

---

## Elsewhere
- **Full Site & Advisory:** [raymonddeoliveira.com](https://www.raymonddeoliveira.com) · [About](https://www.raymonddeoliveira.com/about) · [Work with me](https://www.raymonddeoliveira.com/work-with-me)
- **Writing & Talks:** [raymonddeoliveira.com/writing](https://www.raymonddeoliveira.com/writing) · [The Open Log (Substack)](https://raymonddeoliveira.substack.com/)
- **Contact:** `contact@raymonddeoliveira.com`
