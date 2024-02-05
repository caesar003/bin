# bin

These are small scripts that I use to automate repetitive tasks

- `clear-nvim`
- `start-project`
- `clear-nvim`
- `reclone-astronvim`

## `clear-nvim`

I mess around a lot with neovim configuration, and when I do so instead of figuring out what went wrong I would clean everything and reclone the repo and start new

## `reclone-astronvim`

This is the follow up script of above command

## `start-project`

This initialize my development environment with tmux and neovim. It does these:

- initialize tmux session with two windows,
- first window has my neovim
- second window divided into two panes vertically, top one has npm server running, and the second one is ready for git or any command I need while I'm coding

## `switch-theme`

When coding outside, I feel light theme is better for my eyes, this script simply switches light to dark theme or vice versa to my tmux and neovim configuration
