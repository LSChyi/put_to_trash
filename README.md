# put_to_trash
Running the command `rm` in shell often causes catastrophic result if deleting the wrong file. There are many replacements for `rm`, such as [trash-cli](https://github.com/andreafrancia/trash-cli), but non of them combines the native workflow in macOS.

This `put_to_trash` is a simple script which uses the `Finder` application to put the file into system trash can, thus one can recover it back from the GUI with the native experience of deleting things.

## Installation
Put the script `put_to_trash` to `/usr/local/bin` with adding the executable permission, and replace the command `rm` with setting alias `alias rm=put_to_trash` in the `.rc` files, such as `.bashrc` or `.zshrc`.

If you want to run the real `rm`, you can still delete things with running `$ \rm files`.
