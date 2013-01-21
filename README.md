# rust.vim

## Description

This is a vim plugin provides [Rust][r] file detection and syntax highlighting.
It's used for installation with [vundle][v]. [Pathogen][p] is untested but may
be supported.

It copies the vim support code from the [mozilla/rust][mr] repo for those who
want Rust support without cloning the git repo and manually copying / symlinking
all the requisite files.

The syntax is copied from the `incoming` branch, so it may be slightly different
if you're using a stable release.

A daily cron job that updates this plugin.

## Installation

Use [vundle][v] and add this line to your `~/.vimrc`:

    Bundle 'wting/rust.vim'

Afterwards run the vim command:

    :BundleInstall

[mr]: https://github.com/mozilla/rust
[r]: https://en.wikipedia.org/wiki/Rust_language
[v]: https://github.com/gmarik/vundle
[p]: https://github.com/tpope/vim-pathogen
