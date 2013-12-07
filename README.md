asterisk-vim
============

Vim syntax highlight and SnipMate snippets for Asterisk config files.

Snippets for extensions.conf:
 * exten\<TAB> - takes exten from the previous string where available
 * same\<TAB>

Installation
------------

Using Pathogen:
```sh
cd ~/.vim/bundle
git clone git://github.com/ipoddubny/asterisk-vim.git
```

Manual installation:
Copy the files in syntax directory to ~/.vim/syntax/ and place asterisk.snippets to snipmate's snippets directory.

What's new
----------
 * support for multiline comments ;-- --;
 * correct handling of escaped semicolon \; - it's not a comment
 * support for "same =>" prefix in extensions.conf
 * fixed hostname in "host=" for sip.conf, iax.conf, etc
 * a few minor fixes for extensions.conf
