[Ryan Tomayko's dotfiles](https://github.com/rtomayko/dotfiles)

* Destination: root
* Shell: bash

[Ryan Bates' dotfiles](https://github.com/ryanb/dotfiles)

* Destination: .dotfiles
* Shell: bash

[Zach Holman's dotfiles](https://github.com/holman/dotfiles)

* Destination: .dotfiles
* Shell: zsh
* Philosophy: <http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/>

## About "Destination"

There seem to be two ideas on where to place (clone) the files:

1. In a .dotfiles directory
2. In the root directory

When the files are cloned to a .dotfiles dir, it is common to perform "installation" (i.e. symlinking) via a `rake` task.
