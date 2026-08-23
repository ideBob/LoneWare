<p align="center">
  <img src="assets/logo/loneware-mark.svg" alt="LoneWare" width="200">
</p>

<h1 align="center">LoneWare</h1>

<p align="center">
  <strong>A polished, modular Roblox Blade Ball script hub</strong><br>
  Built with <a href="https://github.com/Footagesus/WindUI">WindUI</a>
</p>

<p align="center">
  <a href="https://github.com/ideBob/LoneWare/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/Download_Source-0A0A0C?style=for-the-badge&logo=github&logoColor=7C3AED" alt="Download Source"></a>
  &nbsp;
  <a href="src/LoneWare.lua"><img src="https://img.shields.io/badge/View_Source-7C3AED?style=for-the-badge&logo=lua&logoColor=white" alt="View Source"></a>
  &nbsp;
  <a href="docs/"><img src="https://img.shields.io/badge/Documentation-1E1B4B?style=for-the-badge" alt="Docs"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/ideBob/LoneWare?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/version-1.0.0-7C3AED?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/WindUI-runtime-8B5CF6?style=flat-square" alt="WindUI">
</p>

---

## About

LoneWare is a production-oriented Luau hub for **Blade Ball**: feature isolation, safe enable/disable, connection cleanup, and a WindUI window (Main, Parry, Theme, FFlag).

| Area | Contents |
|------|----------|
| **Combat** | Auto Parry, Auto Dash, Ball Tracker |
| **Utilities** | Infinite Jump, No Fog, Full Bright, Remove Jitter, ESP, Debug Mode |
| **UI** | Four tabs · five themes |
| **FFlag** | JSON editor, validation, presets, rejoin (no setfflag) |

---

## Installation

1. [Download ZIP](https://github.com/ideBob/LoneWare/archive/refs/heads/main.zip) or clone this repo.
2. Open `src/LoneWare.lua`.
3. Join Blade Ball → inject executor → run the script.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/ideBob/LoneWare/main/src/LoneWare.lua"))()
```

---

## Documentation

- [Installation](docs/installation.md)
- [Features](docs/features.md)
- [Configuration](docs/configuration.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Changelog](CHANGELOG.md)
- [Contributing](CONTRIBUTING.md)

---

## Disclaimer

Educational / personal use. Scripts may violate Roblox ToS. Use at your own risk.

## License

MIT — see [LICENSE](LICENSE). WindUI remains under its own MIT license.
