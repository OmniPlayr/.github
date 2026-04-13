# OmniPlayr

**Open source, self-hosted music player built around a plugin system.**

OmniPlayr lets you play music from any source through a single, unified interface. Every audio source is a plugin. The core stays lean. You stay in control.

---

## What is OmniPlayr?

Most music players are either locked to one service or require giving up your data to a cloud. OmniPlayr takes a different approach: it runs entirely on your own hardware, connects to whatever audio sources you want via plugins, and exposes everything through one consistent API and interface.

No accounts to OmniPlayr itself. No cloud dependency. No telemetry.

---

## Repositories

| Repository | Description |
|---|---|
| [OmniPlayr-server](https://github.com/OmniPlayr/OmniPlayr-server) | The main server - backend, frontend, plugin system |
| [OmniPlayr-CLI](https://github.com/OmniPlayr/OmniPlayr-CLI) | CLI tool for installing and publishing plugins |
| [OmniPlayr-docs](https://github.com/OmniPlayr/OmniPlayr-docs) | Website and documentation source |
| [homebrew-tap](https://github.com/OmniPlayr/homebrew-tap) | Homebrew formula for the CLI |
| [scoop-bucket](https://github.com/OmniPlayr/scoop-bucket) | Scoop manifest for the CLI on Windows |

---

## Getting Started

You need Docker and Python 3.12+.

```bash
git clone https://github.com/OmniPlayr/OmniPlayr-server.git
cd OmniPlayr-server
python3 setup.py
```

Then open `http://localhost:8223` in your browser.

Full installation guides for [Linux](https://omniplayr.wokki20.nl/docs/installation/linux), [Windows](https://omniplayr.wokki20.nl/docs/installation/windows), and [macOS](https://omniplayr.wokki20.nl/docs/installation/macos) are available in the docs.

---

## Plugin System

OmniPlayr is built around plugins. Each audio source is its own plugin. You can install community plugins, build your own, or publish to the registry.

```bash
npm install -g @omniplayr/cli
omniplayr install my-plugin
```

See the [plugin development guide](https://omniplayr.wokki20.nl/docs/plugins/building) to get started building your own.

---

## Contributing

Contributions are welcome. Before you start, please read:

- [Code of Conduct](https://omniplayr.wokki20.nl/legal/code-of-conduct)
- [Contributor License Agreement](https://omniplayr.wokki20.nl/legal/cla)

Then check open issues or discussions for something to work on, or open a new issue to propose a change.

---

## Community

- [GitHub Discussions](https://github.com/orgs/OmniPlayr/discussions) - questions, ideas, general chat
- [Reddit](https://reddit.com/r/OmniPlayer_Community)
- [Bluesky](https://bsky.app/profile/omniplayr.bsky.social)
- [Mastodon](https://mastodon.social/@omniplayr)

---

## License

OmniPlayr is MIT licensed. See [LICENSE](https://omniplayr.wokki20.nl/legal/license) for the full text.
