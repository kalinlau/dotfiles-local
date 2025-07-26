<!-- markdownlint-disable no-inline-html -->
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
- [ ] `nnn`: a full-featured terminal file manager.
- [ ] `ncdu`: a curses-based version of the well-known 'du'.
- [ ] `xclip`: MAC-Like `pbcopy`. Cmdline util for system with X11 implementation.
- [ ] `tldr`: collaborative cheatsheets for console commands.
- [ ] `tmux`: a terminal multiplexer.
- [ ] `tree`: tree view directory
- [ ] ~~`youtube-dl`~~: `yt-dlp`
- [ ] `zsh`: a powerful and highly customizable Unix shell.

### Vim Plugins
- [?] [`webapi-vim`](https://github.com/mattn/webapi-vim): an interface to WEB APIs.
- [ ] [`vimtex`](): .
- [ ] [`vim-vagrant`](): .
- [ ] [`vim-toml`](): .
- [ ] [`vim-tmux`](): .
- [ ] [`vim-surround`](): .
- [ ] [`vim-solidity`](): .
- [ ] [`vim-snippets`](): .
- [ ] [`vim-signature`](): .
- [ ] [`vim-scala`](): .
- [ ] [`vim-racket`](): .
- [ ] [`ack.vim`]:
- [ ] [`ctrlp.vim`]:
- [ ] [`editorconfig-vim`]:
- [ ] [`gist-vim`]:
- [ ] [`gundo.vim`]:
- [ ] [`haskell-vim`]:
- [ ] [`incsearch-easymotion.vim`]:
- [ ] [`incsearch.vim`]:
- [ ] [`lightline.vim`]:
- [x] [`nerdcommenter`](https://github.com/preservim/nerdcommenter): smart function commenters.
- [ ] [`nerdtree`]:
- [ ] [`rust.vim`]:
- [ ] [`smarty.vim`]:
- [ ] [`supertab`]:
- [ ] [`syntastic`]:
- [ ] [`typescript-vim`]:
- [ ] [`ultisnips`]:
- [ ] [`vim-argwrap`]:
- [ ] [`vim-buffergator`]:
- [ ] [`vim-bundler`]:
- [ ] [`vim-coffee-script`]:
- [ ] [`vim-colors-solarized`]:
- [x] [`vim-easymotion`](https://github.com/easymotion/vim-easymotion): vim motion on speed.
- [ ] [`vim-git`]:
- [ ] [`vim-javascript`]:
- [ ] [`vim-js`]:
- [ ] [`vim-json`]:
- [ ] [`vim-jsx-pretty`]:
- [ ] [`vim-liquid`]:
- [ ] [`vim-markdown`]:
- [ ] [`vim-over`]:
- [ ] [`vim-racket`]:
- [ ] [`vim-scala`]:
- [ ] [`vim-signature`]:
- [ ] [`vim-smt2`]:
- [ ] [`vim-snippets`]:
- [ ] [`vim-solidity`]:
- [ ] [`vim-surround`]:
- [ ] [`vim-tmux`]:
- [ ] [`vim-toml`]:
- [ ] [`vim-vagrant`]:
- [ ] [`vim-visual-multi`](https://github.com/mg979/vim-visual-multi): sublime-like multi-cursor.
- [ ] [`vimtex`]:
- [ ] [`webapi-vim`]:


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
