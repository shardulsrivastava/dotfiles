# DotFiles

This repository contains bash aliases, prompts and other configs I use.

## Install

Symlink `bashrc` to `.bashrc` and rest of the configs will be done automatically.

```sh
ln -s ./bashrc ~/.bashrc
```

If you want to make the aliases and other configs available to root, do the following.

```sh
ln -s /path/to/dotfiles/bashrc /root/.bashrc
```

But be aware about security issues.

## Modular Approach

You might not need all aliases at once, right? I have split up all the aliases into modules. Now you can load them based on your choice.

```
source /path/to/adb.alias
source /path/to/apt.alias
source /path/to/brew.alias
source /path/to/cd.alias
source /path/to/color.alias
source /path/to/core.alias
source /path/to/cups.alias
source /path/to/disk.alias
source /path/to/find.alias
source /path/to/git.alias
source /path/to/grep.alias
source /path/to/jekyll.alias
source /path/to/kubectl.alias
source /path/to/lang.alias
source /path/to/ls.alias
source /path/to/make.alias
source /path/to/media.alias
source /path/to/misc.alias
source /path/to/mqtt.alias
source /path/to/network.alias
source /path/to/pb.alias
source /path/to/picocom.alias
source /path/to/pwgen.alias
source /path/to/string.alias
source /path/to/term.alias
```

## Bash Alias Builder

Check out my another project [Bash Alias Builder](https://github.com/mdminhazulhaque/bash-alias-builder) to build your own bash alias file from lots of ready-made templates.
