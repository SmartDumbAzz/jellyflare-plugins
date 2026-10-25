# 🔌 JellyFlare Community Plugins Repository

This repository hosts official and community plugins for [JellyFlare](https://github.com/SmartDumbAzz/JellyFlare).

## Repository URL
Add this repository URL in your JellyFlare Settings & Dashboard to automatically discover and install all current and future plugins:
```
https://raw.githubusercontent.com/SmartDumbAzz/jellyflare-plugins/main/repository.json
```

## Available Plugins
* **VidSrc Stream Provider (`vidsrc`)**: Stream movies and TV episodes directly from VidSrc embeds using TMDB IDs with watch progress tracking.

## Adding New Plugins
To add a new plugin to this repository:
1. Create a folder under `plugins/<plugin-id>/`.
2. Add a `manifest.json` describing the plugin.
3. Add the plugin entry to `repository.json`.
4. Once committed to `main`, every connected JellyFlare client and web dashboard will automatically display the new plugin in the available plugins catalog!