# Omarchy plugins

Personal [Omarchy](https://omarchy.org) plugins. Each plugin lives in its own
directory (`local.<name>/`) with a `manifest.json` and, where useful, its own
README for setup and options.

Install by linking or copying a plugin folder into
`~/.config/omarchy/plugins/`, then restart the shell (or rescan plugins).

## Plugins

### [`local.watts`](local.watts/) - Power draw

Bar widget that reads battery sysfs (`BAT0`) and shows live power draw, with
optional capacity, time remaining, and charge direction. Left-click opens a
metrics menu to toggle fields, drag-reorder them, set padding / sample interval,
and manage the charge limiter (defaults to the kernel's current end-threshold).
Hover tooltip stays open and updates with each sample.

See [local.watts/README.md](local.watts/README.md) for details.
