# Vido NSFW Plugin Registry

Plugin registry for NSFW-category Vido plugins. Vido can pull plugins from this registry when the registry URL is added in **Settings → Plugins → Plugin Registries**.

## Registry URL

```
https://raw.githubusercontent.com/Copenblend/vido-nsfw-plugin-registry/refs/heads/main/registry.json
```

## Available Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| **OSR2+** | 1.0.0 | OSR2+ stroker device control — syncs funscripts with video playback via TCode over Serial and UDP |

## Adding this Registry to Vido

1. Open Vido
2. Go to **Settings → Plugins → Plugin Registries**
3. Click **Add Registry**
4. Paste the registry URL above
5. Click **Save** — the OSR2+ plugin (and any future NSFW plugins) will appear in the plugin browser

## Structure

```
registry.json          — Plugin registry manifest
README.md              — This file
```

Plugin packages, icons, and documentation are hosted in each plugin's own repository.
