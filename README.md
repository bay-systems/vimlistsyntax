# vimlistsyntax

Bash script which lists all available syntax hightlight styles for Vim.

- use Vim's :redir to output 'echo &rtp' to text file
- search Vim runtimepath (rtp) for .vim syntax definition files
- use Python os.scandir() for fast searches of directories


## Installation

Copy `vimlistsyntax` to a chosen direcory in $PATH such as `$HOME/bin` or `/usr/local/bin`


## Usage
```bash
vimlistsyntax
```
