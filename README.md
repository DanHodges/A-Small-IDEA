# IDEA

Super minimal IntelliJ/PhpStorm/etc theme.

I really like vim bindings. Here's an example `.ideavimrc` (`.vimrc` equivilent for the ideaVim plugin) if you're into that type of thing. 

```
let mapleader=' '

set relativenumber
set number

noremap <leader>f :action FindUsages<CR>
noremap <leader>b :action ToggleLineBreakpoint<CR>
noremap <leader>p :action PhpListenDebugAction<CR>
noremap <leader><leader> :action GotoFile<CR>
noremap <leader>r :action Refactorings.QuickListPopupAction<CR>
noremap <leader>a :action Annotate<CR>

noremap <leader>i :action GotoDeclaration<CR>
noremap <leader>o :action Back<CR>

noremap <leader>h :action VimWindowSplitHorizontal<CR>
noremap <leader>v :action VimWindowSplitVertical<CR>
noremap <leader>d :action CloseEditor<CR>

noremap <C-h> :action VimWindowLeft<CR>
noremap <C-l> :action VimWindowRight<CR>
noremap <C-k> :action VimWindowUp<CR>
noremap <C-j> :action VimWindowDown<CR>
```

![screenshot](https://cloud.githubusercontent.com/assets/13152865/26688638/d63823e0-46b8-11e7-84e6-4af1cbf82139.png)
