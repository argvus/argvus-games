# ARGVUS Games

Meta-package for the official ARGVUS games. Installing `argvus-games` installs
every game package of the ARGVUS desktop, the same way `argvus-themes` installs
the official themes.

[![CI](https://github.com/argvus/argvus-games/actions/workflows/ci.yml/badge.svg)](https://github.com/argvus/argvus-games/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Language: Shell](https://img.shields.io/badge/Shell-POSIX-4EAA25?logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Platform: Arch Linux | Wayland](https://img.shields.io/badge/platform-Arch%20Linux%20%7C%20Wayland-1793D1?logo=archlinux&logoColor=white)](https://archlinux.org/)
[![Pull requests](https://img.shields.io/github/issues-pr/argvus/argvus-games)](https://github.com/argvus/argvus-games/pulls)
[![Issues](https://img.shields.io/github/issues/argvus/argvus-games)](https://github.com/argvus/argvus-games/issues)
[![Last commit](https://img.shields.io/github/last-commit/argvus/argvus-games)](https://github.com/argvus/argvus-games/commits/main)
[![Docs](https://img.shields.io/badge/docs-project-blue)](./docs/)

This repository ships no game code. Each game lives in its own package and
repository; this package only declares the games that are part of the
official set.

## Included games

| Game | Package | Command |
| --- | --- | --- |
| Snake | `argvus-game-snake` | `argvus game-snake` |

## Install

Install every official game:

```sh
sudo pacman -S argvus-games
```

Install a single game:

```sh
sudo pacman -S argvus-game-snake
```

## Build from source

On Arch Linux or a compatible distribution:

```sh
sudo pacman -S --needed base-devel git shellcheck
make validate
make build
make install
```

`make build` creates a deterministic local source archive in
`build/artifacts/` and a package in `build/dist/`. See
[packaging/arch/README.md](packaging/arch/README.md) for the difference
between local and release builds.

## Documentation

The game documentation is kept in this repository, in
[docs/en](docs/en/index.md) and [docs/pt-br](docs/pt-br/index.md), and is
published on the ARGVUS website.

- [DEVELOPMENT.md](DEVELOPMENT.md) — layout, checks, and releases
- [CONTRIBUTING.md](https://github.com/argvus/.github/blob/main/CONTRIBUTING.md) — contribution workflow
- [SECURITY.md](https://github.com/argvus/.github/blob/main/SECURITY.md) — private vulnerability reports
- [Code of Conduct](https://github.com/argvus/.github/blob/main/policies/CODE_OF_CONDUCT.md) — community standards
- [AI usage policy](https://github.com/argvus/.github/blob/main/policies/IA_USAGE.md) — rules for AI-assisted contributions

## License

SPDX: `GPL-3.0-only`. See [LICENSE](LICENSE).
