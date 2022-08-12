# all-my-bash-aliases

Imports all my favourite bash aliases.


## Installation

1. Open up your home directory in a terminal window.

```shell
cd $HOME
```

2. Clone this repository.

```shell
git clone https://github.com/vishnuMohanan01/all-my-bash-aliases.git .all-my-bash-aliases
```

3. In your `.bashrc`, add:

```shell
# For setting all-my-bash-aliases
source $HOME/.all-my-bash-aliases/import_all.sh > /dev/null 2>&1
```

4. Reload your shell by:

```shell
source $HOME/.bashrc
```

All the aliases must be added by now.

## Verify

To see all the available aliases under your shell session, type in and enter:

```shell
alias
```

## Add your own aliases

To add your own aliases, open up `$HOME/.all-my-bash-aliases/mine.sh` in your favourite text editor (preferrably vim or nano) and add aliasing command.
Example: 

```shell
alias la="ls -A";
```

This aliases the command `ls -A` with the keyword `la`. You can check more about aliasing in the [Official Mannual](https://www.man7.org/linux/man-pages/man1/alias.1p.html).

If you prefer reading in simple words, go check this [article in linuxize](https://linuxize.com/post/how-to-create-bash-aliases/).





>
>
> Please note that `all-my-bash-aliases` works in shells other than bash too. i.e, in case your are using `zsh` as the default shell then you must be
> using `$HOME/.zshrc`
> whenever this installation guide refers to `$HOME/.bashrc`.

