# dotfiles
My personal dotfiles, currently for Fedora. Now with GNU Stow support.

## Install & Usage:
Install `stow` and `git` then:

`git clone --recursive https://github.com/ranguli/dotfiles && cd ./dotfiles && stow `

## What are dotfiles?
Dotfiles (i.e:   .examplefile) are text-based files that are a hugely popular method of configuring applications in the UNIX world. Most UNIX software has some kind of configuration file that it relies on. We can create peronalized configurations of the software we use to increase productivity or tailor to preference. A common practice is to "track" these files in a VCS like `git` in order to share with others, keep a copy that won't get lost between upgrades, maintain uniformity between your laptop and desktop, quickly provision a new machine, and to keep branches of your dotfiles that are guranteed to work vs. your experimental configs. We can take this another step further however, by using a utility called `stow` to easily push or pull the dotfiles onto our systems configuration directory at once.




