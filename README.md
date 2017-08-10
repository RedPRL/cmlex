CM-Lex: A lexer generator for Standard ML and Haskell
=====================================================

Installing
----------

First, ensure that CM-Lex's submodules are up to date:

    $ git submodule update --init --recursive

To install CM-Lex (for Standard ML)

    $ make mlton (or smlnj or win+smlnj)
    $ make install DESTDIR=/usr/local/ # for example
    $ cmlex
    Error: not enough input files
    Usage: cmlex file.cmlex [-o file.sml]
    (Default output file is file.cmlex.sml)

To install CM-Lex-HS (for Haskell)

    $ make mlton+hs (or smlnj+hs or win+smlnj+hs)
    $ make install+hs DESTDIR=/usr/local/ # for example
    $ cmlex
    Error: not enough input files
    Usage: cmlex-hs file.cmlex [-o file.hs]
    (Default output file is file.cmlex.hs)

