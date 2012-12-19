asterisk-vim
============

Vim syntax highlight and SnipMate snippets for Asterisk config files

Snippets for extensions.conf:
 * exten<TAB> - takes exten from the previous string where available
 * same<TAB>

Installation:

Copy files in syntax directory to your ~/.vim/syntax/ and place asterisk.snippets in the snippets directory of SnipMate 

What's new:
 * multiline comments ;-- --;
 * correct handling of escaped semicolon \; - it's not a comment
 * "same =>" prefix in extensions.conf
 * fixed hostname in "host=" for sip.conf, iax.conf, etc
 * few other minor fixes
