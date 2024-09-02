![nvim logo](https://upload.wikimedia.org/wikipedia/commons/4/4f/Neovim-logo.svg)

# My awesome NvChad dotfiles

How to install?

- Make a backup of your current Neovim files:
```
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

- Switch to `nvchad` branch before cloning
```
git clone https://github.com/ilosrim/dotfiles.git ~/.config/nvim
```

- Remove the .git folder, so you can add it to your own repo later
```
rm -rf ~/.config/nvim/.git
```

- Start Neovim!
```
nvim
```
