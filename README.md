hyphenate [![Build Status](https://travis-ci.org/mbutterick/hyphenate.svg?branch=master)](https://travis-ci.org/mbutterick/hyphenate)
---------

Racket implementation of the Knuth–Liang hyphenation algorithm.

Require it in your Racket file, in standard mode:

    (require hyphenate)
    (hyphenate "Hyphenation algorithm" #\-)
    
    > "Hy-phen-ation al-go-rithm"

Hacked to make hyphenation patterns settable:

    (set-local-patterns some-hashed-patterns)

Rendered obsolete by the rewrite of the original parent.
