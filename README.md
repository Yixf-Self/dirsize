dirsize
========

Summarize size of directories and files in directories.

Install
-------
This package is "go-gettable", just:

    go get github.com/shenwei356/util/dirsize

Usage
-----
    
    Usage: dirsize [OPTION]... [DIR]...

    Summarize size of directories and files in directories.

    OPTION:
      -a=false: sort by Alphabet.
      -r=false: sort by Size.
      -s=true: reverse order while sorting.

Example
-------
    
    dirsize -s -r .

Result:

    .:   6.54 KB
    505.00  B	.gitattributes
    596.00  B	README.md
    628.00  B	.git
      2.08 KB	.gitignore
      2.77 KB	main.go

Copyright (c) 2013, Wei Shen (shenwei356@gmail.com)

[MIT License](https://github.com/shenwei356/dirsize/blob/master/LICENSE)