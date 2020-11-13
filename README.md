# figma-shared-plugin-data
> List of Figma Plugins and their shared data

## Introduction

The idea of this repository is to collect Figma Plugins who set their data via the `setSharedPluginData` API. Together with the name of the plugin, its namespace, the keys and also what data structure it's using, we can make it easier for plugins to work with each other.

More information about `setSharedPluginData` here: https://www.figma.com/plugin-docs/api/properties/nodes-setsharedplugindata/

### Shared Data

| Community Page | Plugin Name | Source Code | Namespace | Key | Structure of value | Set on Node Type |
|-------------------------------------------------------------------|-------------|------------------------------------------|-----------|-------|-------------------------------------|---|
| [Figma Community Page](https://www.figma.com/community/plugin/735098390272716381/Iconify) | Iconify     | https://github.com/iconify/iconify-figma | `iconify`   | `props` | JSON string with `name`, `color` and `props` | `FrameNode` |
