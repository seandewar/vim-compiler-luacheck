# vim-compiler-luacheck

Vim compiler plugin for [luacheck](https://github.com/luarocks/luacheck).

## Usage:

```vim
:compiler luacheck
```

Optionally, you can set `g:luacheck_makeprg_type` before invoking the above to
change the initial value of `makeprg`:

* `let g:luacheck_makeprg_type = 'cd'` sets `makeprg` to `luacheck .` to check
    files in the current directory.
* `let g:luacheck_makeprg_type = 'cfile'` sets `makeprg` to `luacheck %:S` to
    check the current file.

