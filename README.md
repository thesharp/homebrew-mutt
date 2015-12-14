# homebrew-mutt [![Build Status](https://travis-ci.org/thesharp/homebrew-mutt.svg?branch=master)](https://travis-ci.org/thesharp/homebrew-mutt)

### Description

This is a [homebrew](http://brew.sh) [tap](https://github.com/Homebrew/homebrew/wiki/brew-tap) for [mutt](http://mutt.org) version 1.5.24 with some additional patches.

### Patches

  * [--with-sidebar-patch](http://www.lunar-linux.org/mutt-sidebar/): Adds a sidebar with folder list.
  * [--with-trash-patch](https://blog.x-way.org/Linux/2015/09/23/Homebrew-Tap-for-Mutt-1-5-24-with-trash_folder-patch.html): Adds support for Trash folder.

### How to install

    brew tap thesharp/homebrew-mutt
    brew install thesharp/homebrew-mutt/mutt --with-sidebar-patch --with-trash-patch

### License

Licensed under MIT.
