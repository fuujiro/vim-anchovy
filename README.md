# vim-anchovy
🐟Awesome-vim-config for C/C++ users

![1](https://github.com/fuujiro/vim-anchovy/blob/master/pics/Anchovy_logo1.png)

> `vim-anchovy` is a minimal & awesome config for C/C++/Markdown users. 

* Q: Why use `anchovy` as the name of this project?

* A: 
  1.  `anchovy` in werstern people's life is indispensable, same as this config for vim-user. 
  2.  the taste of `anchovy` like salted fish, which means "philosophical as buddhist" (佛系) in Chinese, also my attitude towards life.

### 0. new vimer's Guide

If you are new to vim, the following two posts I recommended: 
* [English-vim-Guide-Recommended](https://buildmedia.readthedocs.org/media/pdf/vimguide/latest/vimguide.pdf)
* [my-Chinese-blog-vim-Guide](https://blog.fuujiro.com/2018/03/10/Vim-%E8%93%9D%E8%89%B2%E6%98%9F%E7%90%83%E8%BF%84%E4%BB%8A%E4%B8%BA%E6%AD%A2%E6%9C%80%E5%BC%BA%E5%A4%A7%E7%9A%84%E7%BC%96%E8%BE%91%E5%99%A8%EF%BC%88%E6%8C%81%E7%BB%AD%E6%9B%B4%E6%96%B0/)

### 1. Code Completions

Such as completions for variable names and function names(neocomplcache), expanding snippets(snipMate), auto closing brackets/brace/quote(delimitMate) and fast expand expressions to HTML(ZenCoding).

* [neocomplcache](https://github.com/Shougo/neocomplcache.vim) - Ultimate auto completion system for Vim.
* [snipMate](https://github.com/garbas/vim-snipmate) - Plugin for using TextMate-style snippets in Vim.
* [supertab](https://github.com/ervandew/supertab) - Perform all your vim insert mode completions with Tab.
* [delimitMate](https://github.com/Raimondi/delimitMate) - Provides auto-balancing and some expansions for parens, quotes, etc.

### 2. Shortcuts
* `Tab` -> Rotate across the completion list
* `Tab` -> Expand snippets or jump to the next placeholder of snippet
* `Ctrl + j` -> Call zen-coding expansion on html tags
* `%` -> Jump between brackets and html/xml tags
* `<leader>` + `w` -> Beginning of the word.
* `<leader>` + `f` + `{char}` -> Find {char} to the right.

### 3. Fast navigation

* matchit - Extended % matching for HTML, LaTeX, and many other languages.
* EasyMotion - Vim motions on speed!

### 4. Tutorial
```bash
:help easymotion
:help text-objexts
:help surround
:help tabular
```
### 5. <leader> Key

`<leader>-key` = `,`

### 6. Themes

`vim-anchovy` use `molokai` as the default theme.

* [molokai](https://github.com/tomasr/molokai) - Molokai color scheme for Vim
* [tomorrow](https://github.com/chriskempson/vim-tomorrow-theme) - Tomorrow Theme for Vim

### 7. Installation

```bash
# backup your old .vim & .vimrc config
mv ~/.vim ~/.vim.old
mv ~/.vimrc ~/.vimrc.old
# get new vim-config
git clone https://github.com/fuujiro/vim-anchovy.git
mv vim-anchovy/.vimrc ~/.vimrc
mv vim-anchovy/ ~/.vim
```

#### 7.1 vundle.vim

If you want to upgrade your vundle.vim in this config,

1. remove your old vundle

```bash
rm -rf ~/.vim/bundle/Vundle.vim
```

2. Upgrade new vundle from git

```bash
 git clone https://github.com/VundleVim/Vundle.vim ~/.vim/bundle/Vundle.vim
```

#### 7.2 Install bundles. Launch vim(ignore the errors and they will disappear after installing needed plugins)and run:

```bash
 :PluginInstall
```

### 8. Uninstallation

so easy to Uninstall.

```bash
rm -rf ~/.vim ~/.vimrc
```

### 9. Screenshots

![shot1](https://raw.githubusercontent.com/fuujiro/vim-anchovy/master/pics/split-vim.png)

### 10. How to manage this vimrc?
All plugins are listed in file vundles.vim with detailed comments, just add plugins as you like.

* `:PluginClean` to clean up unused plugins
* `:PluginInstall` to install newly added plugins
* `:PluginInstall!` to upgrade all plugins
Other configurations are also well organized in vimrc.

### 11. Contribution

If you will to contribute to this open-source program, You can launch a issue at this repo. Thanks.




