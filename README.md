### These are my dotfiles!

To apply them on Fedora,
```bash
sudo dnf install kitty zsh
chsh -s $(which zsh)
sh -c "$(curl -fsLS get.chezmoi.io/lb)"
bash -c "$(curl --fail --show-error --silent --location https://raw.githubusercontent.com/zdharma-continuum/zinit/HEAD/scripts/install.sh)"
curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh
chezmoi init --apply --ssh therithwikrayani
```
Log out and back in to see all changes.
