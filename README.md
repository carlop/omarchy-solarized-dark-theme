# Solarized Dark (Omarchy theme)

A dark theme for [Omarchy](https://omarchy.org/) based on the
[Solarized](https://ethanschoonover.com/solarized/) color palette by Ethan
Schoonover.

## Install

```bash
omarchy theme install <url-de-este-repo>
```

Or, to use it without installing from a repo:

```bash
cp -r solarized-dark ~/.config/omarchy/themes/
omarchy theme set solarized-dark
```

## Contents

- `colors.toml` — all theme colors mapped from the Solarized Dark palette
- `icons.theme` — icon theme (Yaru-blue)
- `backgrounds/` — drop your background images here

When installed from a repo, Omarchy regenerates the executable configs
(`hyprland.lua`, terminal configs, Neovim, VS Code, …) from `colors.toml`
automatically.
