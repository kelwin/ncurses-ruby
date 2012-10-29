ncurses-ruby
============

Patched version for OSX and ruby 1.9
author: <kelwya@gmail.com>

This patch handled building errors below:

    ncurses_wrap.c:818: error: dereferencing pointer to incomplete type
    ncurses_wrap.c:835: error: dereferencing pointer to incomplete type
    ncurses_wrap.c:854: error: dereferencing pointer to incomplete type

or:

    undefined symbol: STR2CSTR
