# rust.vim

## Description

This is a vim plugin provides [Rust][r] file detection and syntax highlighting.
It's used for installation with [vundle][v]. [Pathogen][p] is untested but may
be supported.

It copies the vim support code from the [mozilla/rust][mr] repo, `incoming
branch`.  As a result, the syntax may be *slightly* different if you're using
a stable release.

A daily cron job updates this plugin.

## Note

Vundle will not automatically detect Rust files properly if `filetype on` is
executed before Vundle. Please check the [quickstart][vqs] for more details.

## Installation

Use [vundle][v] and add this line to your `~/.vimrc`:

    Bundle 'wting/rust.vim'

Afterwards run the vim command:

    :BundleInstall

[mr]: https://github.com/mozilla/rust
[r]: https://en.wikipedia.org/wiki/Rust_language
[v]: https://github.com/gmarik/vundle
[vqs]: https://github.com/gmarik/vundle#quick-start
[p]: https://github.com/tpope/vim-pathogen
