# Skript.sk

**A collection of useful Minecraft Skript systems, utilities, and tools.**

Skript.sk aims to provide practical, configurable scripts with clear installation instructions, documented dependencies, and compatibility information.

> **Project status:** Early development. Scripts are being organized and tested. Compatibility is not guaranteed until a script has been tested on the documented server setup.

## Features

- Utility and quality-of-life scripts
- Economy and shop systems
- Minigames and PvP systems
- Administration tools
- Installation and compatibility documentation

## Repository Structure

    Skript.sk/
    ├── scripts/
    │   ├── administration/
    │   ├── economy/
    │   ├── minigames/
    │   └── utility/
    ├── compatibility/
    │   ├── legacy/
    │   └── modern/
    ├── docs/
    ├── .github/
    │   └── ISSUE_TEMPLATE/
    ├── CONTRIBUTING.md
    ├── CHANGELOG.md
    └── LICENSE

## Installation

1. Install a Minecraft server and a compatible version of Skript.
2. Check the selected script's documentation for Minecraft, server, Skript, and addon requirements.
3. Download the `.sk` file.
4. Place it in `plugins/Skript/scripts/`.
5. Run `/sk reload <script-name>`.
6. Test the script before using it on a live server.

Do not assume that a script works with every Skript version or addon combination.

## Project Standards

- **GUI size:** All inventory GUIs must use 6 rows (54 slots).
- **Compatibility:** Document tested versions and known incompatibilities.
- **Dependencies:** List required addons and plugins.
- **Safety:** Validate player input and handle inventory and economy operations carefully.
- **Documentation:** Include installation, configuration, commands, permissions, and examples.

## Releases

A release is planned for every **10 completed independent scripts**.

Supporting files, configuration files, and documentation do not count as independent scripts.

Scripts should be reviewed and tested before being marked complete.

## Contributing

Contributions, suggestions, and bug reports are welcome.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a contribution.

## License

This project is licensed under the [MIT License](LICENSE).
