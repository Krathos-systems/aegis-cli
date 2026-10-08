# Aegis CLI

Releases of the `aegis` command-line tool and its Claude Code plugin, for customers of [Aegis](https://krathos.systems).

## Install

macOS and Linux:

```bash
curl -fsSL https://krathos.systems/install.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://krathos.systems/install.ps1 | iex
```

You need your organisation's Aegis URL and an API key from its administrator. The [install guide](https://krathos.systems/docs/user-guide/cli/install/) covers the options.

## Release contents

Each [release](https://github.com/Krathos-systems/aegis-cli/releases) carries:

| File | What it is |
|---|---|
| `aegis-<os>-<arch>` | the CLI for macOS, Linux and Windows (`.exe` on Windows) |
| `aegis-plugin.tar.gz` | the Claude Code plugin |
| `install.sh`, `install.ps1` | the installers |
| `SHA256SUMS` | checksums of every file above; the installers check them |

This repository holds release binaries only; the source is not published.

## Security

Report a vulnerability as described in our [disclosure policy](https://krathos.systems/legal/vulnerability-disclosure).

## Licence

Proprietary. See [LICENSE](LICENSE).
