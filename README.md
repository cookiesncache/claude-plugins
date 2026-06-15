# cookiesncache Claude Plugins

Official plugin marketplace for Claude Code plugins by cookiesncache.

## Install

[Add the marketplace](https://code.claude.com/docs/en/discover-plugins#add-from-github) using `cookiesncache/claude-plugins`, then [install](https://code.claude.com/docs/en/discover-plugins#install-plugins) any plugin by name — e.g. `travel-planner@cookiesncache-marketplace`.

## Versioning

The marketplace catalog (`marketplace.json`) is versioned independently from individual plugins. The catalog version tracks changes to the catalog itself (plugins added, SHAs updated); each plugin tracks its own version in its own `plugin.json`.

## Update

For update instructions, see the [official docs](https://code.claude.com/docs/en/discover-plugins#configure-auto-updates). Auto-update can be enabled via `/plugin` → **Marketplaces** → `cookiesncache-marketplace` → **Enable auto-update**.

Note: plugins in this marketplace are pinned to specific commit SHAs. When a new version is published, the marketplace catalog is updated — run `/plugin marketplace update cookiesncache-marketplace` to pull the latest catalog, then update individual plugins from the **Installed** tab.

## Plugins

| Plugin | Description |
|---|---|
| [Travel planner](https://github.com/cookiesncache/travel-planner) | End-to-end trip planning with a multi-step workflow |
