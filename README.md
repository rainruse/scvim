# Local Fork of SCVim

CAUTION: This is a heavily modified fork. I only kept the syntax highligting.

For the full plugin and documentation, refer to the upstream repo at
[supercollider/scvim](https://github.com/supercollider/scvim).


## INSTALL

Telling vim to use `*.sc` and `*.scd` file types for supercollider requires a
file in `~/.vim/ftdetect/`. Specifying the pattern and string matches for the
syntax highlighting requires a file in `~/.vim/syntax/`.

To make that work:

1. Clone this repo somewhere
2. Copy [ftdetect/supercollider.vim](ftdetect/supercollider.vim) into your
   `~/.vim/ftdetect/` directory.
3. Copy [syntax/supercollider.vim](syntax/supercollider.vim) into your
   `~/.vim/syntax` directory.

Alternately:
```
mkdir -p ~/.vim/ftdetect ~/.vim/syntax
cd ~/.vim/ftdetect
curl https://raw.githubusercontent.com/rainruse/scvim/refs/heads/main/ftdetect/supercollider.vim \
  -o supercollider.vim
cd ~/.vim/syntax
curl https://raw.githubusercontent.com/rainruse/scvim/refs/heads/main/syntax/supercollider.vim \
  -o supercollider.vim
```
