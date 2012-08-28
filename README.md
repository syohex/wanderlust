Wanderlust - Yet Another Message Interface on Emacsen
=====================================================

Wanderlust is a mail/news management system with [IMAP4rev1][1] support for
Emacs. It was originally developed by [Yuuichi Teranishi](teranisi@gohome.org).

For documentation, see also: [Wanderlust on EmacsWiki][2]


Features
========

  * Implementation in elisp only.

  * Support of [IMAP4rev1][3], [NNTP][4], POP([POP3][5]/APOP), MH and Maildir.

  * Integrated access to messages based on Folder Specifications like [Mew][6].

  * Key bindings and mark processing like Mew.

  * Management of threads and unread messages.
 
  * Folder mode to select and edit subscribed folders.

  * Message cache, Disconnected Operation.

  * MH-like Fcc (Fcc: %Backup is possible).

  * Full support of MIME (by SEMI).

  * Draft editing of mail and news as a same interface.

  * Icon based interface for the list of Folder (XEmacs and Emacs 21).

  * Skip fetching of a large message part of MIME(IMAP4).

  * Server side searching (IMAP4), internationalized searching is available.

  * Virtual folder.

  * Compressed folder.

  * Automatic expiration of old messages.

  * Automatic refiling.

  * Draft templates.


Installation
============

See: [INSTALL](INSTALL)


Mailing List
============

You can get information and help via the mailing list at:

  * English: [wl-en@ml.gentei.org]() ([archives][7])

  * Japanese: [wl@ml.gentei.org]() ([archives][8])

Emails to the English list are forwarded to the Japanese list.

To subscribe, send an email to [wl-ctl@ml.gentei.org]() (Japanese) or
[wl-en-ctl@ml.gentei.org]() (English). Use `subscribe YOUR NAME` as subject and
body. To unsubscribe, use `unsubscribe` as body. To get help, use `# guide` as
body.


Development
===========

Fork it on [GitHub][9].


[1]: http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol

[2]: http://www.emacswiki.org/emacs/WanderLust

[2]: http://tools.ietf.org/html/rfc2060 "M. Crispin, 'INTERNET MESSAGE ACCESS PROTOCOL - VERSION 4rev1', RFC 2060, 1996"

[3]: http://tools.ietf.org/html/rfc977 "B. Kantor and P. Lapsley, 'Network News Transfer Protocol: A Proposed Standard for the Stream-Based Transmission of News', RFC 977, 1986"

[4]: http://tools.ietf.org/html/rfc1939 "J. Myers, M. Rose, 'Post Office Protocol - Version 3', RFC 1939, 1996"

[5]: http://www.mew.org/ "'Mew - Messaging in the Emacs World', (Copyright (C) 1994, 1995, 1996, 1997, 1998 Mew developing team)"

[6]: ftp://ftp.jaist.ac.jp/pub/GNU/elisp/ "'tm - MIME package for GNU Emacs', (Copyright (C) 1994, 1995, 1996 MORIOKA Tomohiko)"

[7]: http://news.gmane.org/gmane.mail.wanderlust.general

[8]: http://news.gmane.org/gmane.mail.wanderlust.general.japanese

[9]: https://github.com/wanderlust/wanderlust
