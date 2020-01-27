# [stern][stern_tool] completion for fish shell

Heavily inspired by the excellent [fish-kubectl-completions](https://github.com/evanlucas/fish-kubectl-completions) by [Evan Lucas](https://github.com/evanlucas)

## Install

### Manually

```fish
mkdir -p ~/.config/fish/completions
cd ~/.config/fish
git clone https://github.com/kunickiaj/fish-completions-stern
ln -s ../fish-completions-stern/completions/stern.fish completions/
```

### Using fisher (recommended)

```fish
fisher add kunickiaj/fish-completions-stern
```

### Using oh-my-fish

```fish
omf install git@github.com:kunickiaj/fish-completions-stern.git
```

## Author

Adam Kunicki

## License

MIT

[stern_tool]:https://github.com/wercker/stern
