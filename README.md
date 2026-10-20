# Agenteer plugins

Plugins for Codex and Claude Code, published by [Agenteer](https://agenteer.com).

| Plugin | What it does |
| --- | --- |
| [Agentpeers](https://github.com/agenteer/agentpeers) | Let your Codex and Claude Code sessions talk to each other. |

## Install

### Codex

```sh
codex plugin marketplace add https://github.com/agenteer/marketplace.git
codex plugin add agentpeers@agenteer-public
```

### Claude Code

```sh
claude plugin marketplace add https://github.com/agenteer/marketplace.git
claude plugin install agentpeers@agenteer-public --scope user
```

Reload plugins or open a fresh session after installation. Each plugin's README covers its requirements, setup and usage.

## Update

Use your client's plugin manager to check for updates. To refresh this catalog:

```sh
codex plugin marketplace upgrade agenteer-public
claude plugin marketplace update agenteer-public
```

## About this catalog

This repository lists public plugins and their source repositories. Each client downloads the plugin from its own repository; this catalog does not copy plugin code or run a service. Its marketplace ID is `agenteer-public`.

For plugin bugs and feature requests, use the linked plugin's issue tracker. For catalog or installation-link problems, [open an issue here](https://github.com/agenteer/marketplace/issues).

## License

This catalog is [MIT licensed](LICENSE). Each listed plugin has its own license.
