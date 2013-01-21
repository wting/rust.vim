# rust.vim

## Description

This is a vim plugin provides [Rust][r] file detection and syntax highlighting.
It's used for installation with [vundle][v].

It copies the vim support code from the [mozilla/rust][mr] repo for those who
want Rust support without cloning the git repo and manually copying / symlinking
all the requisite files.

The syntax is copied from the `incoming` branch, so it may be slightly different
if you're using a stable release of the Rust compiler.

## Installation

Use [vundle][v] and add this line to your `~/.vimrc`:

    Bundle 'wting/rust.vim'

Afterwards run the vim command:

    :BundleInstall

Pathogen may work but it's untested.

## Updates

I have a cron job that notifies me if there's an update, so this plugin
shouldn't fall behind the `incoming` branch too much.

[mr]: https://github.com/mozilla/rust
[r]: https://en.wikipedia.org/wiki/Rust_language
[v]: https://github.com/gmarik/vundle
