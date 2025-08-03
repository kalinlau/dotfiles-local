# Dotfiles-local

Win11-specific dotfiles.

## Useful Tools

- Master Sword:
  - Display: `lsd` + `hack-nerd-font`.
  - Editor:
    - graphical: `vscode`.
    - terminal: `vim`.
  - Git: version control system, `git`.
    - diff pro: `delta`
    - tag/commit sign: `gpg`
  - GnuPG: signature and encryption, `gpg`.
  - Multiplexer: `tmux`.
  - Regular expression
  - Zsh
- Royal Guard's Claymore:
  - `htop`
  - `tldr`: helpages for command tools.
  - `xlip`: copy STDOUT to system's clipboard.
- Royal Claymore:
- Knight's Claymore:
- Ancient Bladewas:
- Great Flameblade:
- Great Thunderblade:
- Great Frostblade:

### Shell Utils

- [x] content-search tools
  - [x] `ack`: GREP-Like search tool optimized for source code.
  - [x] `ag`: a code searching tool similar to ack, with a focus on speed.
- [ ] `autojump`: a faster way to navigate your filesystem.
- [x] [`bat`](https://github.com/sharkdp/bat): Better `cat` + `less`.
- [ ] `binutils`
- [ ] `coreutils`
- [x] [`delta`](https://github.com/dandavison/delta.git): pager for git, diff, and grep output.
- [ ] [`fd`](https://github.com/sharkdp/fd): simple, fast Linux `find`.
- [ ] `ffmpeg`
- [x] [`fzf`](https://github.com/junegunn/fzf): a command-line fuzzy finder.
- [ ] `htop`: a cross-platform interactive process viewer.
- [x] `jq`: sed for JSON data.
- [ ] `ncdu`: a curses-based version of the well-known 'du'.
- [ ] `nnn`: a full-featured terminal file manager.
- [x] `prettier`: formatter (fixer) for markdown, json, js, etc..
- [ ] `tldr`: collaborative cheatsheets for console commands.
- [ ] `tmux`: a terminal multiplexer.
- [ ] `tree`: tree view directory
- [ ] [`vale`](https://github.com/errata-ai/vale.git): cmdline that brings code-like linting to prose.
- [ ] `xclip`: MAC-Like `pbcopy` for system with X11 implementation.
- [ ] ~~`youtube-dl`~~: `yt-dlp`
- [ ] `zsh`: a powerful and highly customizable Unix shell.

### Vim Plugins

- [x] [`ack-vim`](https://github.com/mileszs/ack.vim.git): ack in vim.
- [x] [`ale`](https://github.com/dense-analysis/ale.git): check and fix syntax asynchronously.
  - [x] Python: `yapf` + `pylint`.
  - [x] Markdown: `prettier` + `markdownlint`.
- [x] fuzzy finder:
  - [x] [`ctrlp`](https://github.com/ctrlpvim/ctrlp.vim.git): pure-vimscript fzf.
  - [x] [`fzf-vim`](https://github.com/junegunn/fzf.vim.git): fzf-plugin for vim.
- [?] [`webapi-vim`](https://github.com/mattn/webapi-vim): an interface to WEB APIs.
- [x] [`vim-tmux`](https://github.com/tmux-plugins/vim-tmux): vim plugin for `.tmux.conf`.
- [x] [`vimtex`](https://github.com/lervag/vimtex):
- [x] [`nerdcommenter`](https://github.com/preservim/nerdcommenter): smart function commenters.
- [x] [`vim-easymotion`](https://github.com/easymotion/vim-easymotion): vim motion on speed.
- [x] [`vim-over`](https://github.com/osyo-manga/vim-over.git): substitute preview.
- [x] [`vim-visual-multi`](https://github.com/mg979/vim-visual-multi): sublime-like multi-cursor.
<!-- Snippet Plugins -->
- [x] [`emmet-vim`](https://github.com/mattn/emmet-vim.git): snippet for html,css.
- [x] [`UltiSnips`](https://github.com/SirVer/ultisnips.git): general snippets.
- [x] [`vim-over`](https://github.com/osyo-manga/vim-over.git): substitute preview.
- [x] [`vim-snippet`](https://github.com/honza/vim-snippets.git): community-maintained snippet files.

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
