HaskellNet
==========

[![Build Status](https://travis-ci.org/lemol/HaskellNet.svg)](https://travis-ci.org/lemol/HaskellNet)

**NOTE: I am seeking a maintainer for this package. If you are interested, let me know!**

This package provides client support for the E-mail protocols POP3,
SMTP, and IMAP.

Some examples of how to use the library are contained in the example/
directory.  You should be able to run them by adjusting the file for
your mail server settings and then loading the file in ghci and type
'main'. eg.

  ghci -hide-package monads-fd example/smtpMimeMail.hs
  main

If you encounter problems and want to debug the ghci
debugger works well:

  :set -fbreak-on-exception
  :trace main
