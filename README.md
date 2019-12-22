# Aliases

I can't and don't want to remember stupidly long commands, so if I think I'm ever going to use a command more than once, I'll write an alias for it. Or... I'll make my life easier by giving something a "clever" name. 

## Examples

* `clear-var-log` which will create a backup of the current `/var/log` folder and remove everything inside of it.
* `kk` to shorten the commonly used `kubectl` command. 

## How to use/install

* `git clone https://github.com/GregSharpe1/alias ~/.alias`

Place `for f in $(find $HOME/.alias/ -type f); do source $f; done` into ~/.`$SHELL`rc file, to source make sure all aliases are available.