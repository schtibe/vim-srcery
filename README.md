srcery.vim
================================

Colorscheme that focus ease of use and clearly defined contrasting colors with a slightly earthy tone. Heavily inspired by [Gruvbox](https://github.com/morhetz/gruvbox), [base16](https://chriskempson.github.io/base16), [flattened](https://github.com/morhetz/gruvbox) and [solarized](http://ethanschoonover.com/solarized).

### TODO:
 * improve vimdiff comparison.

## Requirements

### GUI
You don’t need to do anything for this colorscheme to work in GVim or MacVim.

### TUI
Srcery's only requirement is that you change your terminal emulator’s so-called “ASCII” colors to the ones in the table below.
I've included colorscheme files for various terminals in the term_color folder, but since I haven't tested all of them some issues may arrise. If your terminal is different or the file won't work please let me know so I can add/update/fix the file in question.

```
TERMCOL   HEX       RGB
-------   -------   -------------
black     #1C1B19   28,  27,  25
red       #FF3128   255, 49,  40
green     #519F50   81,  159, 80
yellow    #FBB829   251, 184, 41
blue      #5573A3   85,  115, 163
magenta   #E02C6D   224, 44,  109
cyan      #0AAEB3   10, 174, 179
gray      #918175   145, 129, 117

brblack   #2D2B28   45,  43,  40
brred     #F75341   247, 83, 65
brgreen   #98BC37   152, 188, 55
bryellow  #FED06E   254, 208, 110
brblue    #8EB2F7   142, 178, 247
brmagenta #E35682   227, 86,  130
brcyan    #53FDE9   83, 253, 233
white     #FCE8C3   252, 232, 195
```
![preview](https://roosta.sh/blog/img/srcery/preview.png)

## Installation

Put `srcery.vim` in `~/.vim/colors/` (on unix-like systems) or `%userprofile%\vimfiles\colors\` (on Windows).

Using a [plugin](https://github.com/junegunn/vim-plug) [manager](https://github.com/tpope/vim-pathogen) for vim.
```vimrc
Plug 'roosta/srcery'
```

## Configuration

I've included a few toggles due to discrepancies in the various setups possible.

#### g:srcery_bold

Enables bold text.
default: 1

#### g:srcery_italic

Enables italic text.
default: gui 1, term 0

#### g:srcery_underline

Enables underlined text.
default: 1

#### g:srcery_undercurl

Enables undercurled text.
default: 1

#### g:srcery_inverse

Enables inverse colors.
default: 1

## Usage
```
:color srcery
```

If you like what you see and decide to make srcery your default colorscheme, add the relevant line to your vimrc:
```
colorscheme srcery
```
## Screenshots.

![vim](https://roosta.sh/blog/img/srcery/vim.png)

![sh](https://roosta.sh/blog/img/srcery/sh.png)

![clj](https://roosta.sh/blog/img/srcery/clj.png)
