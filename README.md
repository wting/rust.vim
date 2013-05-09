# rust.vim

## Description

This is a vim plugin provides [Rust][r] file detection and syntax highlighting.

It is synchronized daily to the vim support code in [mozilla/rust][mr]'s
incoming branch via cronjob. Consequently, the syntax may be *slightly*
different if you're using a stable release.

## Installation

Use [vundle][v] and add this line to your `~/.vimrc`:

    Bundle 'wting/rust.vim'

Afterwards run the vim command:

    :BundleInstall

*Note:* Vundle will not automatically detect Rust files properly if `filetype
on` is executed before Vundle. Please check the [quickstart][vqs] for more
details.

[mr]: https://github.com/mozilla/rust
[r]: https://en.wikipedia.org/wiki/Rust_language
[v]: https://github.com/gmarik/vundle
[vqs]: https://github.com/gmarik/vundle#quick-start
