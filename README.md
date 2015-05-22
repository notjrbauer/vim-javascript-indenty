# vim-javascript-indenty

Extracted indent plugin from [vim-javascript](https://github.com/pangloss/vim-javascript).

I've found that the plugin was modifiying my colorschemes, making them less colorful. Since I've only used it for its indendation, I figured I'd just extract the plugin itself.

## Installation

### Install with [pathogen](https://github.com/tpope/vim-pathogen)

      git clone https://github.com/notjrbauer/vim-javascript-indenty.git ~/.vim/bundle/vim-javascript-indenty

## Shortcuts


```imap <C-c> <CR><Esc>O```: <CTRL - C> expands braces such that they're split above each other, with insert mode beginning in between.

```
function () {}
```

***becomes***

```
function () {
  <insert here>
}
  ```

