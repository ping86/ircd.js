0.0.5 / 2011-12-03
==================

  * Added a fix from [treeform](https://github.com/treeform) for `NICK`, detailed in [#16](https://github.com/alexyoung/ircd.js/issues/16)

Previous Releases
=================

* [2011-10-22] Now based around EventEmitter, changed sha1 passwords to bcrypt
* [2011-10-22] Removed server link code (it was overcomplicating development too much, I'll come back to it later)
* [2011-09-09] Fixed bug #9: WHO on nonexistent channel.  Improved unit tests
* [2010-12-27] More work on server links (broadcasting of SERVER commands)
* [2010-12-11] Now installable from npm, server now checks for config in /etc/ircdjs/config.json
* [2010-12-11] First steps towards linked servers, major restructuring
* [2010-12-04] Added user mode w and WALLOPS
* [2010-12-01] Split code into channel.js, user.js, server.js
* [2010-11-28] Added KICK
* [2010-11-23] Added OPER command that uses sha1 passwords in the config file
* [2010-11-23] Added invisible user mode and user support for WHO command
* [2010-11-19] Added AWAY
* [2010-11-18] Added VERSION, TIME, WHOWAS
* [2010-11-16] Added +i and INVITE
* [2010-11-14] Added +k (channel key)
* [2010-11-12] Added +l (user limit)
* [2010-11-11] Added voice/devoice support, and removing channel modes on part
* [2010-11-07] Added ban support, commands are no-longer case sensitive
