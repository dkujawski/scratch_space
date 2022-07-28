# scratch_space

bash alias to quickly create a new scratch directory tracked by git

## Requirements

- assumes Bash
- uses words from ``/usr/share/dict/words``
- uses ``shuf`` command for random index
- uses ``tr`` to make all words lowercase
- uses ``git`` to track contents of created dir

## Setup

source this file from your `.bashrc`

```bash
[ -f .bash_scratch_space ] && source .bash_scratch_space 
```

## Usage

```
$ scratch
```
