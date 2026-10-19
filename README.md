# ARGVUS Games

Meta-package for the official ARGVUS games. Installing `argvus-games` installs
every game package of the ARGVUS desktop, the same way `argvus-themes` installs
the official themes.

[![CI](https://github.com/argvus/argvus-games/actions/workflows/ci.yml/badge.svg)](https://github.com/argvus/argvus-games/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)

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
- [CONTRIBUTING.md](CONTRIBUTING.md) — contribution workflow
- [SECURITY.md](SECURITY.md) — private vulnerability reports

## License

SPDX: `GPL-3.0-only`. See [LICENSE](LICENSE).
