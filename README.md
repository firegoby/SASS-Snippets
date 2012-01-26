# CSS & SASS Snippets for Vim's Snipmate Plugin

* Author: Chris Batchelor, [Firegoby Design](http://firegoby.com)
* Version: 0.2
* Date: 26 Jan 2012
* License: See UNLICENSE file

## Installation

### Required
* Install [SnipMate](http://www.vim.org/scripts/script.php?script_id=2540)

### Recommended - Install via [Vundle](https://github.com/gmarik/vundle)
* Add `Bundle 'firegoby/SASS-Snippets'` to your *.vimrc*
* Reload Vim (or `:source ~/.vimrc`)
* Call `:BundleInstall` from Vim's commandline

### Manual Installation
* Put `scss.snippet` in your chosen SnipMate's `snippets/` dir
* Restart Vim
* Call `:set filetype=scss` or,
* have `filetype on` in your *.vimrc* (recommended)

## Notes
(See `scss.snippets` for the actual snippets)

*	most commonly used features use single letter abbreviations
* the standard CSS declarations use two letters (occasionally three)
* SASS functions use the first three letters of the function (occ. four)

