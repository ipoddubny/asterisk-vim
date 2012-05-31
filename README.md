asterisk-vim
============

Vim syntax highlight for Asterisk configuration

I've tried to fix a few annoying bugs in the syntax highlighting for Asterisk that comes with Vim by default.
Just place the files in the syntax directory in your Vim runtime path, for Linux it is usually ~/.vim/syntax/.

What's new:
 * multiline comments ;-- --;
 * correct handling of escaped semicolon \; - it's not a comment
 * "same =>" prefix in extensions.conf
 * fixed hostname in "host=" for sip.conf, iax.conf, etc
 * few other minor fixes