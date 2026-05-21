# edu-papirus-dark-tela-grey

Grey-folder variant of `edu-papirus-dark-tela` — Papirus dark icon set with grey Tela folder icons swapped in. Part of the `~/EDU/` icon-theme series.

## What's in this repo

- `usr/share/icons/` — the icon theme assets.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Sibling variant

- [edu-papirus-dark-tela](https://github.com/erikdubois/edu-papirus-dark-tela) — colour-folder variant.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-papirus-dark-tela-grey
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-papirus-dark-tela-grey.git
cd edu-papirus-dark-tela-grey
sudo cp -r usr/share/icons/. /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/<theme-folder>
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "<theme-folder-name>"
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
