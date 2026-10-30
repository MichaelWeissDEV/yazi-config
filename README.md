# Yazi configuration

Terminal-Dateimanager mit Catppuccin-Mocha-Flavor und optionalem Shell-Verzeichniswechsel.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#yazi)** ·
[Shell-Integration](https://arch-dotfiles.readthedocs.io/en/latest/shell/) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- yazi
```

Paket: `arch-dotfiles-yazi`. Dateien: `~/.config/yazi/yazi.toml`, `theme.toml`,
`package.toml` und `flavors/`. `yazi` startet den Dateimanager; die Zsh-Funktion `y`
übernimmt anschließend das zuletzt besuchte Verzeichnis.

Hier unabhängig auf `main` pushen; nach erfolgreichem Registry-Build mit
`sudo pacman -Syu` aktualisieren. [PACKAGING.md](PACKAGING.md).

[![Package safety](https://github.com/MichaelWeissDEV/yazi-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/yazi-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE); die mitgelieferte Flavor behält ihre eigenen Lizenzen.
