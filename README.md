# ✨ LeagueSkins - League of Legends Skins Assets

<div align="center">
  <img src="./icon.ico" alt="Rose Icon" width="128" height="128">
  
  [![Installer](https://img.shields.io/badge/Installer-Windows-blue)](https://github.com/Alban1911/Rose/releases/latest) [![Discord](https://img.shields.io/discord/1426680928759189545?color=5865F2&logo=discord&logoColor=white&label=Discord)](https://discord.com/invite/cDepnwVS8Z) [![License](https://img.shields.io/badge/License-Open%20Source-green)](LICENSE)
</div>

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
- **Skin & Chroma IDs**: Calculated as `champion_id * 1000 + skin_number` - can be 4, 5, or 6 digits (e.g., 1000, 10000, 100000)
- **File Types**: 
  - `.png` - Preview images (only included for skins with custom forms)
  - `.zip` - Complete skin asset packages

## Getting Started

1. **Download Rose**: Get the latest installer from our [releases page](https://github.com/Alban1911/Rose/releases/latest)
2. **Install the Tool**: Follow the installation instructions
3. **Apply Skins**: Use Rose to apply any skin in-game

### Contributing

LeagueSkins is open source! Contributions are welcome:

- Report bugs or suggest features via GitHub Issues
- Submit pull requests for improvements
- Join our [Discord](https://discord.com/invite/cDepnwVS8Z) for discussions

## ⚖️ Legal Notice

This project is for educational and personal use only. Please respect Riot Games' intellectual property rights and terms of service. Rose and this asset collection are not affiliated with or endorsed by Riot Games.

## License

This repository is open source. The skin assets are property of Riot Games and are used under fair use for educational purposes.

---

**Powered by [Rose](https://github.com/Alban1911/Rose)**.
