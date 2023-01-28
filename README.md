# Vim For Everyone

Course resources for "Vim For Everyone" on The Taggart Institute.

This repo is intended to be used in conjunction with the instructional materials in the course. You can certainly use the repo by itself, but it'll be much less valuable. The course is free, so why not enroll?

## Setup

The course requires Vim, so you'll want to install it on our operating system of choice.

### Linux

While your distro may already have Vim installed, you want to make sure you have all the features we'll use. Specifically, we want Vim compiled with the `clipboard` feature. 

To check whether your version has this, run:

```shell
vim --version
```

There will be a lot of output, but you're looking for the `+clipboard` option. If you see `-clipboard`, you'll want to install `vim-gtk3` instead.

### Windows

Download the stable version of gVim listed on [vim.org](https://www.vim.org/download.php). Alternatively, you could live dangerously and install the [latest build](https://github.com/vim/vim-win32-installer/releases/latest).

This will install both a windowed and terminal (PowerShell) version of Vim.

### macOS

You knew this was coming:

```shell
brew install vim
```

### Repl.it

If you would rather experiment in the cloud, our recommendation is to create a project on [repl.it](repl.it/). 

## Usage

Each Unit for the course has its own directory. Each Unit has lesson directories, containing README files with instructions for completing the checks for understanding for that lesson. Use Vim to complete each check, and move on!

## Acknowledgments

Special thanks go out to Matt (HuskyHacks) and Praxaeus from the [Taggart Institute Discord](https://discord.gg/thetaggartinstitute) for QA on this course.


Thanks to the developers of [Screenkey](https://www.thregr.org/~wavexx/software/screenkey/) for an amazing tool!
