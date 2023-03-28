# **docheio Header**

docheio (Japan)

### **Description**

docheio standard header for vim editor.

![docheio header](img/docheio-header.png)

### **UNIX Setup**

Copy `stddocheioheader.vim` in your `~/.vim/plugin`, or use your favorite plugin
manager. Then set the user and mail variables as explained below.

#### Option 1: export USER and MAIL in your shell configuration file

Add in `~/.zshrc` your:

+ `USER`
+ `MAIL`

#### Option 2: set user and mail values directly in your vimrc

```vim
let g:user_docheio = 'yourLogin'
let g:mail_docheio = 'yourLogin@doche.io'
```

### **Usage**

In **NORMAL** mode you can use `:Stddocheioheader` or simply press the shortcut <kbd>F1</kbd>.

Under **Linux** you eventually need to disable the **help** shortcut of your **terminal** :

For **Terminator**, right click -> Preferences -> Shortcuts -> change help with something other than <kbd>F1</kbd>
