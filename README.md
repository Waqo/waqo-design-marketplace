# waqo-design marketplace

Marketplace repository for the `waqo-design` Claude plugin.

## Install in Claude

1. Push this repository to GitHub.
2. In Claude, open **Customize → Plugins → Personal → + → Add marketplace**.
3. Enter the GitHub repository as `owner/repo` or paste its Git URL.
4. Click **Sync**.
5. Open the new `waqo-design` marketplace and install the `waqo-design` plugin.

## Repository structure

```text
waqo-design-marketplace/
├── .claude-plugin/
│   └── marketplace.json
└── plugins/
    └── waqo-design/
        ├── .claude-plugin/
        │   └── plugin.json
        ├── .mcp.json
        ├── README.md
        ├── CONNECTORS.md
        ├── OPERATING_MODEL.md
        └── skills/
```
