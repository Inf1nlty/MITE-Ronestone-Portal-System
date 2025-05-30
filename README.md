# MITE-Runestone-Portal-System

The runestone portal system based on MITE (Minecraft Is Too Easy)

## Description

This project implements a runestone portal system inspired by the MITE mod for Minecraft. It allows players to create magical portals using different types of runestones for teleportation across vast distances.

## Features

- **Mithril Runestone Portals**: Short-range teleportation (5000 block radius)
- **Adamantium Runestone Portals**: Long-range teleportation (40000 block radius)
- **MITE-Compatible Logic**: Faithful recreation of the original MITE portal mechanics
- **Safe Landing System**: Automatically finds safe landing spots for teleportation
- **Seed-Based Destinations**: Deterministic portal destinations based on runestone configuration

## Installation

1. Download the latest release from the [Releases](https://github.com/Inf1nlty/MITE-Ronestone-Portal-System/releases) page
2. Place the mod file in your Minecraft mods folder
3. Ensure you have the required dependencies installed
4. Launch Minecraft and enjoy!

## Usage

### Creating a Portal

1. Build a rectangular frame using runestones
2. Place the same type of runestones at all four corners:
   - **Mithril Runestones** for short-range portals
   - **Adamantium Runestones** for long-range portals
3. Activate the portal (implementation-specific)
4. Step through to teleport!

### Runestone Types

The system supports all 16 MITE runestone types:
- nul, quas, por, an, nox, flam, vas, des
- ort, tym, corp, lor, mani, jux, ylem, sanct

## Requirements

- Minecraft [Version]
- Minecraft Forge [Version]
- [Other dependencies]

## Building from Source

```bash
git clone https://github.com/Inf1nlty/MITE-Ronestone-Portal-System.git
cd MITE-Ronestone-Portal-System
./gradlew build
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Original MITE mod creators for the inspiration
- Minecraft modding community for their support and resources

## Contact

- Project Link: [https://github.com/Inf1nlty/MITE-Ronestone-Portal-System](https://github.com/Inf1nlty/MITE-Ronestone-Portal-System)
- Issues: [https://github.com/Inf1nlty/MITE-Ronestone-Portal-System/issues](https://github.com/Inf1nlty/MITE-Ronestone-Portal-System/issues)

## Changelog

### [Unreleased]
- Initial implementation of runestone portal system
- MITE-compatible teleportation logic
- Safe landing spot detection

---

*Made with ❤️ for the Minecraft modding community*
