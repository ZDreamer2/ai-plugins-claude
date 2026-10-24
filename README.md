# AI Plugins for Claude Code

This repository contains the generated Claude Code distribution of [AI Plugins](https://github.com/ZDreamer2/ai-plugins).

## Install

Requires Claude Code with plugin support and Git. Run in your terminal:

```sh
claude plugin marketplace add https://github.com/ZDreamer2/ai-plugins-claude.git
claude plugin install ai-doc@zd-plugins
claude plugin install ai-marketplace@zd-plugins
```

Install either plugin or both, then start a new Claude Code session. For updates, run `claude plugin marketplace update zd-plugins`, followed by `claude plugin update ai-doc@zd-plugins` and/or `claude plugin update ai-marketplace@zd-plugins`, then restart the session.

## Usage and documentation

See the [main repository](https://github.com/ZDreamer2/ai-plugins) for available plugins, examples and documentation. Building from source is unnecessary for installation.

## Source and changes

This repository is replaced automatically during publication. Report issues and propose changes in the [source repository](https://github.com/ZDreamer2/ai-plugins), rather than editing generated files here.

## License

See `LICENSE` and the bundled third-party license notices.
