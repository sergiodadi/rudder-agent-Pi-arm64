# rudder-agent-Pi-arm64

I have a little homelab with Raspberry and Intel N100. I created packages for my homelab to use rudder agent with

- Raspberry **Debian** arm64
- Raspberry **Ubuntu** arm64

since I couldn't find a ready-made rudder-agent package, I tried to compile them.

Rudder is an open source project, which means that you can freely download and modify the source code while respecting open source licenses.

Rudder encourages and welcomes any form of contribution, not just code changes: comments, reviews, help on Gitter/IRC or mailing lists, and of course code and documentation improvements.

The official Rudder website is https://www.rudder.io/open-source/

## Installation

Download the package for your system from the [Releases](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases) page, then:

```
sha256sum rudder-agent_<version>.<distribution>_arm64.deb   # compare with SHA256SUMS of the release
sudo apt install ./rudder-agent_<version>.<distribution>_arm64.deb
```

Then configure the agent as described in the [official documentation](https://docs.rudder.io/).

## Release history

| Version | Debian 12 (Bookworm) | Debian 13 (Trixie) | Ubuntu 24.04 (Noble) | Ubuntu 26.04 (Resolute) |
|---|---|---|---|---|
| 9.1.5 | [v9.1.5-debian-bookworm](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.1.5-debian-bookworm) | [v9.1.5-debian-trixie](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.1.5-debian-trixie) | [v9.1.5-ubuntu-noble](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.1.5-ubuntu-noble) | [v9.1.5-ubuntu-resolute](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.1.5-ubuntu-resolute) |
| 9.1.4 | [v9.1.4-debian-bookworm](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.1.4-debian-bookworm) | | | |
| 9.0.4 | [v9.0.4-debian-bookworm](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.4-debian-bookworm) | | | |
| 9.0.3 | [v9.0.3-debian-bookworm](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.3-debian-bookworm) | | [v9.0.3-ubuntu-noble](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.3-ubuntu-noble) | |
| 9.0.2 | [v9.0.2-debian-bookworm](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.2-debian-bookworm) | | [v9.0.2-ubuntu-noble](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.2-ubuntu-noble) | |
| 9.0.1 | [v9.0.1](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.1) | | [v9.0.1-ubuntu-noble](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.1-ubuntu-noble) | |
| 9.0.0 | [v9.0.0](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.0) | | [v9.0.0-ubuntu-noble](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v9.0.0-ubuntu-noble) | |
| 8.3.8 | [v8.3.8](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.3.8) | | | |
| 8.3.7 | | | [v8.3.7](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.3.7) | |
| 8.3.1 | [v8.3.1](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.3.1) (distribution not specified) | | | |
| 8.2.6 | [v8.2.6](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.2.6) (distribution not specified) | | | |
| 8.2.5 | [v8.2.5](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.2.5) | | | |
| 8.1.12 | [v8.1.12](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v8.1.12) | | | |
| 7.2.11 | [v7.2.11](https://github.com/sergiodadi/rudder-agent-Pi-arm64/releases/tag/v7.2.11) | | | |

## Sources

- Rudder agent: https://github.com/Normation/rudder-agent
- Rudder packaging: https://github.com/Normation/rudder-packages
- Official changelogs: https://docs.rudder.io/changelogs/current/index.html

## Credits

These packages were built, tested and published with the help of **Claude**, the AI assistant by [Anthropic](https://www.anthropic.com/).
