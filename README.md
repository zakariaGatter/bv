# bv
Move/Rename files and directories with your editor

## table of Contents
    * [About](#about)
    * [Installation](#installation)
    * [Usage](#Usage)

### About

[BV] is a Interactive Move/Rename Tool inspire by [Vifm]() Rename method

[BV] Allows you to ...

* Move File(s) and Folder(s)
* Rename File(s) and Folder(s)
* Create the Move to Directory if not Exist
* Choose Which editor to use
* Choose the command to use for moving

[BV] can automatically ...

* check for File(s)/Folder(s) Permission
* Existing of target File(s)/Folder(s)

### Installation

* Requires:
    * [Bash]()
    * [Coreutils]()

    `Probably ther already installed`

* Setup [BV]:

    ```bash
    git clone https://gitlab.com/zakariaGatter/bv.git ~/bv
	mkdir -p ~/.local/bin
	cp ~/brash/bin/bv ~/.local/bin
	chmod +x ~/.local/bin/bv
    ```

### Usage

```
Bv Rename multi files

Usage: Bv [OPTIONS] ... FILES ...

OPTIONS
 -c <file> : Rename current file(s) name
 -r <file> : Rename root of current file(s)
 -f <file> : Rename anything on the file(s)
 -e        : Editor to use (default: $EDITOR)
 -m        : Mv command to use (default: mv)
 -v        : Explain what is being done
 -h        : Display this help and exit

VARIABLES
 BV_EDITOR   Editor to use (default: $EDITOR)
 BV_MV       MV command to use (default: mv)
```
