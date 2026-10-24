# Brave Ads MCP Starter Kit — Manage Brave Ads with AI

> **This is a recipe repo.** The Synter MCP server itself lives at [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server): 19 ad platforms, campaign creation on 14, one-click install in Cursor, Claude, ChatGPT, and VS Code. Issues, releases, and ⭐ go there.

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: Brave Ads](https://img.shields.io/badge/Platform-Brave%20Ads-FB542B)](https://brave.com/brave-ads)

**Reach privacy-first users in Brave search and new tab.** Open this repo in Amp, Cursor, or VS Code and manage Brave Ads with AI — search, new-tab, and notification inventory — through Synter MCP.

---

## Why Brave Ads + AI?

Brave users block the default ad web on purpose. Brave Ads (and BAT-aware surfaces) are one of the few ways to show up in that browser: search, new-tab cards, and opt-in notifications. Creative has to respect the privacy bargain — no creepy remarketing copy.

An agent can map keywords to Brave search, keep claims tight, and compare Brave with Carbon and EthicalAds for a developer launch.

**Best for:** privacy products, crypto/BAT-adjacent tools, developer utilities, search challenger brands, VPN/security.

---

## Developer ad platforms compared

| Network | Typical inventory | Tracking posture | Best for |
|--------|-------------------|------------------|----------|
| **Brave Ads** | Search, new tab, notifications | Privacy-preserving / BAT | Users who already blocked the ad web |
| **Carbon Ads** | Developer blogs, Stack Overflow | Contextual + pixels | Classic developer media buy |
| **EthicalAds** | Read the Docs, OSS | No third-party cookies | Documentation-led OSS |

Companions: [carbon-ads-agent](https://github.com/Synter-Media-AI/carbon-ads-agent), [ethical-ads-agent](https://github.com/Synter-Media-AI/ethical-ads-agent).

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\\Claude\\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Search campaigns** | "Create a Brave search campaign for 'privacy analytics' and 'cookieless attribution'" |
| **New-tab units** | "Brief a Brave new-tab card for our developer VPN" |
| **BAT-aware copy** | "Write copy that respects Brave users — no surveillance claims" |
| **Compare** | "Brave vs EthicalAds vs Carbon for a privacy database" |
| **Performance** | "Pull Brave Ads spend, CTR, and conversions" |
| **Delivery QA** | "Validate my Brave Ads campaign structure for delivery issues" |

Hosted **Synter MCP** (`@synterai/mcp-server` / https://mcp.syntermedia.ai). Connect at [syntermedia.ai/credentials](https://syntermedia.ai/credentials). Not a first-party Brave Ads API client.

---

## Example Conversations

### 1. Privacy search launch

> **You:** Our users live in Brave. Set up search + new tab.
>
> **Agent:** I will separate intent (search keywords) from awareness (new tab). Copy will talk features, not tracking. Connect Brave in Synter and I will create the flights via MCP.

### 2. BAT and tone

> **You:** Should we mention BAT in the ad?
>
> **Agent:** Only if the product actually uses BAT. Otherwise lead with privacy UX. Mentioning BAT as a gimmick underperforms with this audience.

---

## FAQ

### Is there an MCP for Brave Ads?
Yes — this recipe pre-configures Synter MCP for Brave Ads in Amp, Cursor, VS Code, and Claude Desktop.

### Is this the Brave Rewards publisher dashboard?
No. This kit is for advertisers planning Brave Ads through Synter.

---

## Related Repos

- [carbon-ads-agent](https://github.com/Synter-Media-AI/carbon-ads-agent) — Carbon Ads / developer blog inventory
- [ethical-ads-agent](https://github.com/Synter-Media-AI/ethical-ads-agent) — EthicalAds privacy-first OSS inventory
- [brave-ads-agent](https://github.com/Synter-Media-AI/brave-ads-agent) — Brave Ads, search, and new-tab
- [twitch-ads-agent](https://github.com/Synter-Media-AI/twitch-ads-agent) — Twitch Ads for live gaming
- [discord-quests-agent](https://github.com/Synter-Media-AI/discord-quests-agent) — Discord Quests gamer acquisition
- [reddit-ads-agent](https://github.com/Synter-Media-AI/reddit-ads-agent) — Reddit community ads
- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Search intent capture
- [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) — Facebook & Instagram reach
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-channel management

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
