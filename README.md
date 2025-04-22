# ARCHIVED as of 22/04/2025
Scripts will be managed from my [dotfiles](https://github.com/brabli/dotfiles) repo from now on.

# Bradley's Scripts

Here are some of my personal scripts. Some of them are very specific to me, others are general utilities that could be of use to anyone.

***

## Commands

### cleanup
Cleans up my desktop, albeit not very well. It's gross and needs rewriting.

### DEPRECATED ~~cmd-r~~
Simulates pressing `cmd + r`

### disamp
Test script I made for exploring disowned processes

### dockerstop
Find and stop all running Docker containers

### ip
Display and copy your current IP address to the clipboard

### lorem
Copy a passage of lorem ipsum to the clipboard

### newrust
Create a new Rust project and open in VS Code for editing

### newscript
Create a new shell script, symlinks it into `/usr/bin/local/` and open it in VS Code for editing

### reference
One liner that closes and reopens Reference 4

### rm-node
I had to remove Node that I installed manually ages ago so I could reinstall it with Homebrew, so I made this

### rustsandbox
Create a temporary Rust playground that opens in VS Code

### DEPRECATED ~~switch~~
Switch installed PHP versions using Homebrew

### mdd
"Merge to Develop and Delete" a git shortcut I use a lot when working on feature branches

### script-relink
Because `newscript` creates a new script and symlinks it, when I pulled down this repo I had all the scripts available but they weren't symlinked so I couldn't run them without modifing my PATH. This script goes through the available scripts and symlinks them, recreating where necessary.
