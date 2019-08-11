
[![license](https://img.shields.io/github/license/riftbit/w32.svg)](LICENSE)
[![GoDoc](http://img.shields.io/badge/go-documentation-blue.svg?style=flat-square)](https://godoc.org/github.com/riftbit/w32)
[![Coverage Status](https://coveralls.io/repos/github/riftbit/w32/badge.svg?branch=master)](https://coveralls.io/github/riftbit/w32?branch=master)
[![Build Status](https://travis-ci.org/riftbit/w32.svg?branch=master)](https://travis-ci.org/riftbit/w32)
[![Go Report Card](https://goreportcard.com/badge/github.com/riftbit/w32)](https://goreportcard.com/report/github.com/riftbit/w32)
[![Release](https://img.shields.io/badge/release-v1.0.0-blue.svg?style=flat)](https://github.com/riftbit/w32/releases)

About w32
==========

w32 is a wrapper of windows apis for the Go Programming Language.

It wraps win32 apis to "Go style" to make them easier to use.

**Work in progress! Pull requests are welcome!**

**API of this package can be changed till 1.0.0 version will be released!**

## Notes
This library was originally a clone of [JamesHovious/w32](https://github.com/JamesHovious/w32). 

This library aims to mirror the win32 api and other Windows system dlls, without additional abstractions built on top of it. It attempts to be as organized/documented as possible. 

This mirror has some of my own additions plus updates from other forks of the original project. I've attempted to document where I've pulled code from someone else. 

I add new API functions in if my current project needs them. If your project needs a particular function please submit a PR or issue. I also add in additional functions as I see other forks, or Go libraries that have them.


Example
=====
```
package main

import (
	"github.com/riftbit/w32"
)

func main() {
	w32.MessageBox(0, "Hello World!", "Hello, World!", 0)
}
```

For more examples, look at the example folder.

Setup
=====

1. [Install Go](https://golang.org/dl/).
2. Get a GCC compiler. I recommend the [WinBuilds version](http://win-builds.org/doku.php/download_and_installation_from_windows).
3. From the command line, type `go get github.com/riftbit/w32`
4. Create a new file, and try the example above.

Contribute
==========

Contributions in form of design, code, documentation, bug reporting or other ways you see fit are very welcome.

Thank You!
