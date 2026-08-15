[![CI](https://github.com/kenzo101-codeit/hack-client_for-1.21.1-neoforge/actions/workflows/ci.yml/badge.svg)](https://github.com/kenzo101-codeit/hack-client_for-1.21.1-neoforge/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://choosealicense.com/licenses/mit/)


# Mod Client for 1.21.1 (NeoForge Minecraft)

---
## tewaltpro Contribution

# BLUR FIX + MENU RESIZE
Credit to Kenzo101_studios for the original Wurst derived Hack Client for NeoForge. 
I, tewaltpro, have since addressed some issues with it including the accidental blur overlay of the ClickGUI along with a resizing of the mod menu. Enjoy!

### I would like to again restate the importance of using code responsibly. While Minecraft mods may not cause real harm or damage, online ethics are important and this software should be used for informative, experimental, and appropriate use always. As makers, it's our responsibility to not just make tools, but use them in ways that are kind and acceptable. I encourage you to only use this mod when you have permission to! Happy Minecraft'ing.

---

A Wurst-like mod injector client for Minecraft 1.21.1 with a NeoForge target.

## Quick start

- Build AND Locate .JAR files for NeoForge:
  - `chmod +x ./scripts/build-jars.sh && ./scripts/build-jars.sh`
- Run NeoForge client for development:
  - `./gradlew :neoforge:runClient --debug`

## Development / Quick-start

If you want to contribute or run the project locally, see `CONTRIBUTING.md` for a full guide. Quick commands:

- Build: `./gradlew build --no-daemon`
- Build AND Locate .JAR files for NeoForge: `chmod +x ./scripts/build-jars.sh && ./scripts/build-jars.sh`
- Run NeoForge client for testing: `./gradlew :neoforge:runClient --debug`

## Features

- Configurable click-UI keybinds (default: Right Ctrl)
- Ported modules: AutoAttack, SpeedHack (configurable multiplier), MobVision, FullBright

## Contributing

Contributions welcome — please see `CONTRIBUTING.md` for contribution guidelines.

## License

MIT — see `LICENSE` for details.

