# Hi, I'm compact161

I build and run a self-hosted homelab and write small Linux tools around it.

## What I work on

I run and document a self-hosted homelab the way I'd run a small company network:
declarative, monitored, backed up, and documented from its verified state.

- **Virtualisation:** Proxmox VE with VMs and LXC containers, built with
  cloud-init; backups to Proxmox Backup Server with tested restores.
- **Networking:** Ubiquiti UniFi gateway and Wi-Fi, VLAN segmentation,
  firewall and content-filter policies, local DNS, WireGuard VPN, network
  boot (netboot.xyz, iVentoy).
- **Services:** everything in Docker Compose, kept in Git, behind a reverse
  proxy with automatic TLS (ACME, DNS challenge).
- **Identity and access:** single sign-on with Authelia, secrets in 1Password
  service accounts instead of files, intrusion blocking with CrowdSec.
- **Monitoring and alerting:** Prometheus and Grafana, external uptime checks,
  alerts pushed to my own Matrix server.
- **Self-hosted apps:** GitLab with CI runners and Renovate, Nextcloud,
  Paperless-ngx, Matrix (Tuwunel, Element), PrivateBin, SearXNG, BentoPDF,
  Reactive Resume, Homepage, Home Assistant, Jellyfin, Cockpit, UpSnap,
  NanoKVM.
- **AI agents in operations:** local models (self-hosted LLM server in
  my homelab) and cloud assistants (Claude, Codex) working on real
  infrastructure, with least-privilege credentials, a shared task tracker,
  and a human approving anything risky.
- **Linux desktop (Arch, KDE Plasma on Wayland):** small tools and tray
  applets that make everyday hardware behave.
- **Hardware:** configuring input devices without vendor software, fixes and
  tools around the Flipper Zero.

## Public projects

| Project | What it does |
|---|---|
| [g502-editor](https://github.com/compact161/g502-editor) | GTK 4 editor for the onboard profiles of the Logitech G502 X PLUS: buttons, G-Shift layer, DPI and lighting, through Solaar's library. |

## Contributions

- [qFlipper #259](https://github.com/flipperdevices/qFlipper/pull/259): fix for
  a stuck remote-control key and input after disconnect (open).

## AI use

**Most of my work here is done with heavy help from AI coding assistants.**

I want to be open about that, so here is how it works:

- **What the assistant does:** analysis, code, tests, commit messages and
  pull request texts are often written by an assistant.
- **What I do:** I decide what gets built, read the changes, test them on my
  own systems and only publish what works for me.
- **How you can tell:** commits written with an assistant carry a
  `Co-Authored-By: Claude …` line. Pull requests to other projects include an
  "AI disclosure" section that says what I tested myself.
- **Other projects' rules:** before contributing, I read the project's rules on
  AI-generated contributions and follow them.

Treat my code like any third-party code: read it before you rely on it.
Everything comes without warranty; see each repository's licence.

## Contact

Open an issue in the repository concerned.
