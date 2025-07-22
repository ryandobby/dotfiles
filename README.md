# dotfiles

## Install

Install chezmoi and apply files, requires curl to be installed

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply git@github.com:$ryandobby/dotfiles.git
```

## bash

- bashrc, aliases, exports, completions

- minimal, safe sourcing and pathing, fallbacks if tools aren't installed
