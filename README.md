# yuncun marketplace

A small marketplace of Claude Code plugins. Install in any Claude Code session:

```
/plugin marketplace add Yuncun/yuncun-marketplace
/plugin install <plugin-name>@yuncun
```

`yuncun` is the personal catalog name. The separate work repository,
`gim-home/yuncun`, uses `yuncun-work`; its tools and access requirements are not
part of this catalog. Register only the catalogs and install only the packages
you want in each client.

Standalone skills can also be installed from their source repositories using
`npx skills add`. Choose one installation route per skill and client rather than
loading both a plugin and a separate copy. Updating a source repository does not
update an installed copy; use the selected installer's update mechanism.

## Plugins

- **[social-credit](https://github.com/Yuncun/ai-social-credit)** — Quietly tracks how kindly you treat Claude across sessions. Receipts notarized to the Bitcoin blockchain.
- **[omakase-harness](https://github.com/Yuncun/omakase-harness)** — Install a personal repository harness with rules and git-hook gates.
- **[superpowers-for-shopping](https://github.com/Yuncun/superpowers-for-shopping)** — ADHD-helper for considered purchases. Takes "I need a sweater" to a populated cart with one click.

- **[research-evidence](https://github.com/Yuncun/research-evidence)** — Research with human evidence: ranks sources by recent adoption (stars, points, dates); scripts for HN, Reddit, X, GitHub.

- **[terminal-visuals](https://github.com/Yuncun/terminal-visuals)** — Visuals for replies read in a terminal: shape-by-question guide, examples, box-and-arrow renderer.

## Adding to this marketplace

Edit `.claude-plugin/marketplace.json` and open a PR.
