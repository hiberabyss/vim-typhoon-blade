# vim-typhoon-blade

---

Vim syntax plugin for [typhoon-blade](https://github.com/chen3feng/typhoon-blade).

## Installation

### vim-plug

Add to vimrc file:

    Plug 'hiberabyss/vim-typhoon-blade'

### Manual installation

Copy all files to vim plugin directory($HOME/.vim, vimfiles, $VIMRUNTIME, ...).

# Notes

This plugin have following configuration to disable default `blade` support in polyglot.

```vim
let  g:polyglot_disabled += ['blade']
```

