![nvim logo](https://upload.wikimedia.org/wikipedia/commons/4/4f/Neovim-logo.svg)

# My awesome dotfiles

How to install?
> Make sure your neovim version is equal to or higher than v0.10.x before installing the program

- Make a backup of your current Neovim files:
```
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

- Clone the repo

> If you want to use NvChad, which has a lot of functionality and themes, first go to the `nvchad` branch and clone it, or after cloning, go to the `nvchad` branch through the terminal, write `git pull origin nvchad` and then run the program. Detailed information is available on the official website of [NvChad](https://nvchad.com/).
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
