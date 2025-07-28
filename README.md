# Dotfiles-local

Win11-specific dotfiles.

## Useful Tools

- editor:
  - graphical: vscode
  - terminal: vim
- font: `hack-nerd-font`

### Shell Utils

- [ ] `ack`: GREP-Like search tool optimized for source code.
- [ ] `ag`: a code searching tool similar to ack, with a focus on speed.
- [ ] `autojump`: a faster way to navigate your filesystem.
- [x] [`bat`](https://github.com/sharkdp/bat): Better `cat` + `less`.
- [ ] `binutils`
- [ ] `coreutils`
- [ ] [`fd`](https://github.com/sharkdp/fd): simple, fast Linux `find`.
- [ ] `ffmpeg`
- [x] [`fzf`](https://github.com/junegunn/fzf): a command-line fuzzy finder.
- [ ] `htop`: a cross-platform interactive process viewer.
- [ ] `ncdu`: a curses-based version of the well-known 'du'.
- [ ] `nnn`: a full-featured terminal file manager.
- [ ] `tldr`: collaborative cheatsheets for console commands.
- [ ] `tmux`: a terminal multiplexer.
- [ ] `tree`: tree view directory
- [ ] [`vale`](https://github.com/errata-ai/vale.git): cmdline that brings code-like linting to prose.
- [ ] `xclip`: MAC-Like `pbcopy` for system with X11 implementation.
- [ ] ~~`youtube-dl`~~: `yt-dlp`
- [ ] `zsh`: a powerful and highly customizable Unix shell.

### Vim Plugins

- [x] [`ale`](https://github.com/dense-analysis/ale.git): check and fix syntax asynchronously.
  - [x] Python: `yapf` + `pylint`.
  - [x] Markdown: `prettier` + `markdownlint`.
- [?] [`webapi-vim`](https://github.com/mattn/webapi-vim): an interface to WEB APIs.
- [x] [`vim-tmux`](https://github.com/tmux-plugins/vim-tmux): vim plugin for `.tmux.conf`.
- [x] [`vimtex`](https://github.com/lervag/vimtex):
- [x] [`nerdcommenter`](https://github.com/preservim/nerdcommenter): smart function commenters.
- [x] [`vim-easymotion`](https://github.com/easymotion/vim-easymotion): vim motion on speed.
- [x] [`vim-visual-multi`](https://github.com/mg979/vim-visual-multi): sublime-like multi-cursor.

## Installation

- Recommended position: `~/dotfiles-local`.
- Install tools like `ack`, `ag`, `fzf`, etc..
- Update submodules `git submodule foreach git pull origin master`.
- Link dotfiles `./install`

## Configuration

Modify `install.conf.yaml`, go check the template.

## References

- [HOW TO ADD PATH TO $PATH](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path)
- [ZSH CONFIG FILES AND DIFFERENCE](https://unix.stackexchange.com/questions/71253/what-should-shouldnt-go-in-zshenv-zshrc-zlogin-zprofile-zlogout)
- [the top of iterm2 screen keeps flashing in full mode on OSX Big Sur](https://gitlab.com/gnachman/iterm2/-/issues/9199#note_474219016)
- [Alt key in Vim on Mac OSX](https://stackoverflow.com/a/15399297/8069158)
- [tmux on mac: $PATH messing with conda](https://gist.github.com/ekreutz/995bb95e428358b9efa2b2f80b02143c)
- [tmux change to non-login shell and why to do that](https://wiki.archlinux.org/index.php/tmux#Start_a_non-login_shell)
