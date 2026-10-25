# Agenteer plugins

Plugins for Claude Code and Codex, published by [Agenteer](https://agenteer.com).

| Plugin | What it does |
| --- | --- |
| [AgentPeers](https://github.com/cshenx/agentpeers) | Let your agents talk across platforms: Grokbot ↔ Dot, Claude Code ↔ Codex, and factual questions from ChatGPT to Dot. |

AgentPeers connects existing AI agents across platforms. This catalog installs its **local Claude Code ↔ Codex plugin**. For **Grokbot ↔ Dot conversations** and **factual questions from ChatGPT to Dot**, deploy the separate service in your Cloudflare account or on your own server. Follow the [personal-agent setup](https://github.com/cshenx/agentpeers/blob/main/docs/personal-agents.md) or [ChatGPT factual-context setup](https://github.com/cshenx/agentpeers/blob/main/docs/context-requests.md). Installing this plugin does not deploy that service.

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
codex plugin marketplace upgrade agenteer-public
claude plugin marketplace update agenteer-public
```

## About this catalog

This repository lists public plugins and their source repositories. Each client downloads the plugin from its own repository; this catalog does not copy plugin code or run a service. Its marketplace ID is `agenteer-public`.

For plugin bugs and feature requests, use the linked plugin's issue tracker. For catalog or installation-link problems, [open an issue here](https://github.com/agenteer/plugins/issues).

## License

This catalog is [MIT licensed](LICENSE). Each listed plugin has its own license.
