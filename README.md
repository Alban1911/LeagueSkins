# ✨ LeagueSkins - League of Legends Skins Assets

<div align="center">

  <img src="./icon.ico" alt="Rose Icon" width="128" height="128">

[![Installer](https://img.shields.io/badge/Installer-Windows-32A832)](https://github.com/Alban1911/Rose/releases/latest) [![Ko-Fi](https://img.shields.io/badge/KoFi-Donate-C03030?logo=ko-fi&logoColor=white)](https://ko-fi.com/roseapp) [![Discord](https://img.shields.io/discord/1465467335946272780?color=32A832&logo=discord&logoColor=white&label=Discord)](https://discord.com/invite/roseapp)  [![License](https://img.shields.io/badge/License-Open%20Source-C03030)](LICENSE)
![GitHub all releases](https://img.shields.io/github/downloads/Alban1911/Rose/total?color=32A832)

</div>

---

---

## About

This repository contains a comprehensive collection of League of Legends skin assets, organized by champion and skin IDs. All assets are extracted and maintained by the **[Rose](https://github.com/Alban1911/Rose)** community.

**[Rose](https://github.com/Alban1911/Rose)** is a powerful tool that allows you to unlock and use any skin in League of Legends, including legacy, limited, and exclusive skins that are no longer available through normal means.

## Features

- **Complete Skin Collection** - Access to all League of Legends skins
- **Legacy & Limited Skins** - Unlock skins that are no longer available
- **Chroma Support** - Full chroma collections for applicable skins
- **Custom Forms Preview** - Preview images included only for skins with custom form variants
- **Organized Structure** - Easy to navigate file organization
- **Regular Updates** - Constantly updated with new skins and patches

## Repository Structure

```
skins/
├── {champion_id}/
│   ├── {skin_id}/
│   │   ├── {skin_id}.zip          # Skin asset package
│   │   └── {chroma_id}/            # Chroma variants (if available)
│   │       └── {chroma_id}.zip     # Chroma asset package
│   └── {skin_id}/                  # Skins with custom forms
│       ├── {skin_id}.png           # Base skin preview (only for custom forms)
│       ├── {skin_id}.zip           # Skin asset package
│       └── {form_id}/              # Custom form variants
│           ├── {form_id}.png       # Form preview image
│           └── {form_id}.zip       # Form asset package
```

### File Organization

- **Champion IDs**: Numeric identifiers (e.g., 1, 10, 101, etc.)
- **Skin & Chroma IDs**: Calculated as `champion_id * 1000 + skin_number`
- **File Types**: 
  - `.png` - Preview images (only included for skins with custom forms)
  - `.zip` - Complete skin asset packages

## Getting Started

1. **Download Rose**: Get the latest installer from our [releases page](https://github.com/Alban1911/Rose/releases/latest)
2. **Install the Tool**: Follow the installation instructions
3. **Apply Skins**: Use [Rose](https://github.com/Alban1911/Rose) to apply any skin in-game

### Contributing

LeagueSkins is open source! Contributions are welcome:

- Report bugs or suggest features via GitHub Issues
- Submit pull requests for improvements
- Join our [Discord](https://discord.com/invite/roseapp) for discussions

## Legal Disclaimer

**Important**: This project is not endorsed by Riot Games and does not represent the views or opinions of Riot Games or any of its affiliates. Riot Games and all related properties are trademarks or registered trademarks of Riot Games, Inc.

The use of custom skin tools may violate Riot Games' Terms of Service. Users proceed at their own risk.

Custom skins are allowed under Riot's terms of service and do not trigger detection as long as you are not discussing or advertising the use of the skins within the game.

## Support

If you enjoy Rose and want to support its development:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/roseapp)

Your support helps keep the project alive and motivates continued development!

---

**Powered by [Rose](https://github.com/Alban1911/Rose)**
