# Dotfiles-local
Win11-Specific dotfile.

## Useful Tools

* `ack`: grep-like search tool specifically optimized for searching source code.
* `ag`: a code searching tool similar to ack, with a focus on speed.
* `autojump`: a faster way to navigate your filesystem.
* `binutils`
* `coreutils`
* `ffmpeg`
* `font-hack-nerd-font`
* `fzf`: a general-purpose command-line fuzzy finder.
* `htop`: a cross-platform interactive process viewer.
* `nnn`: a full-featured terminal file manager.
* `ncdu`: a curses-based version of the well-known 'du'.
* `tldr`: collaborative cheatsheets for console commands.
* `tmux`: a terminal multiplexer.
* ~~`youtube-dl`~~: `yt-dlp`
* `zsh`: a powerful and highly customizable Unix shell.

## Installation

- Recommended position: `~/dotfiles-local`.
- Install tools like `ack`, `ag`, `fzf`, etc..
- Update submodules `git submodule foreach git pull origin master`.
- Link dotfiles `./install`

## Configuration

Modify `install.conf.yaml`, go check the template.

## References

* [HOW TO ADD PATH TO $PATH](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path)
* [ZSH CONFIG FILES AND DIFFERENCE](https://unix.stackexchange.com/questions/71253/what-should-shouldnt-go-in-zshenv-zshrc-zlogin-zprofile-zlogout)
* [the top of iterm2 screen keeps flashing in full mode on OSX Big Sur](https://gitlab.com/gnachman/iterm2/-/issues/9199#note_474219016)
* [Alt key in Vim on Mac OSX](https://stackoverflow.com/a/15399297/8069158)
* [tmux on mac: $PATH messing with conda](https://gist.github.com/ekreutz/995bb95e428358b9efa2b2f80b02143c)
* [tmux change to non-login shell and why to do that](https://wiki.archlinux.org/index.php/tmux#Start_a_non-login_shell)
