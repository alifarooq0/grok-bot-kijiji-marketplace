# Kijiji Marketplace

Agent Plugin (skills-only) for buying and selling on [Kijiji](https://www.kijiji.ca). Built for **Grok Bot** using the Agent Plugins layout.

Marketplace logo: `assets/logo.png` (original plugin mark, not Kijiji trademark).

## Layout

```text
kijiji-marketplace/
├── plugin.json
├── skills/
│   ├── kijiji-search-listings/SKILL.md
│   ├── kijiji-draft-listing/SKILL.md
│   ├── kijiji-price-research/SKILL.md
│   └── kijiji-buyer-outreach/SKILL.md
├── README.md
├── LICENSE
└── CHANGELOG.md
```

No MCP server, hooks, rules, agents, or `.cursor-plugin/` folder.

## Skills

| Skill | When to use |
| --- | --- |
| `kijiji-search-listings` | Looking up items on Kijiji |
| `kijiji-draft-listing` | Creating or improving a Kijiji ad |
| `kijiji-price-research` | Checking fair market price |
| `kijiji-buyer-outreach` | Messaging a seller about a listing |

## Local testing

**Cursor IDE (documented):** this folder can live at `~/.cursor/plugins/local/kijiji-marketplace`. Reload the window, then try the skills via `/` or `@`.

**Grok Bot:** local plugin path is not the same as Cursor’s; verify against the current client. After marketplace install, open a new chat and try the skills above.

## Publish

1. Push to a public Git repo
2. Submit at https://cursor.com/marketplace/publish
3. Open source + manual review

`github.com/xai-org/plugin-marketplace` is not a submission destination.
