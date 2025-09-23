# dotfiles

These dotfiles are managed using [chezmoi](https://www.chezmoi.io/).

## Setting up a new computer

```sh
brew install chezmoi
chezmoi init --apply git@github.com:aldreth/dotfiles.git
```

Config is stored at `~/.config/chezmoi/chezmoi.toml`, but is managed with a [template in this repository](./.chezmoi.toml.tmpl).
