# Agenteer plugins

Plugins for Claude Code and Codex, published by [Agenteer](https://agenteer.com).

| Plugin | What it does |
| --- | --- |
| [AgentPeers](https://github.com/cshenx/agentpeers) | Let your Claude Code and Codex sessions talk to each other. |

## Install

### Claude Code

```sh
claude plugin marketplace add https://github.com/agenteer/plugins.git
claude plugin install agentpeers@agenteer-public --scope user
```

### Codex

```sh
codex plugin marketplace add https://github.com/agenteer/plugins.git
codex plugin add agentpeers@agenteer-public
```

Reload plugins or open a fresh session after installation. Each plugin's README covers its requirements, setup and usage.

## Update

Use your client's plugin manager to check for updates. To refresh this catalog:

```sh
claude plugin marketplace update agenteer-public
codex plugin marketplace upgrade agenteer-public
```

## About this catalog

This repository lists public plugins and their source repositories. Each client downloads the plugin from its own repository; this catalog does not copy plugin code or run a service. Its marketplace ID is `agenteer-public`.

For plugin bugs and feature requests, use the linked plugin's issue tracker. For catalog or installation-link problems, [open an issue here](https://github.com/agenteer/plugins/issues).

## License

This catalog is [MIT licensed](LICENSE). Each listed plugin has its own license.
