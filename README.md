# Usage

This config adds **ultra fast download helpers** into your terminal.

- Install `aria2c` before all

  - see [https://github.com/aria2/aria2/releases/](https://github.com/aria2/aria2/releases/)

- Copy these files into `~/.aria2`

```bash
git clone https://github.com/funatsufumiya/aria2-configs ~/.aria2
```

- Write aliases on `~/.bashrc` or `~/.zshrc` like below.

```bash
alias "aria-x3"="aria2c --conf-path=$HOME/.aria2/x3.conf"
alias "aria-x5"="aria2c --conf-path=$HOME/.aria2/x5.conf"
alias "aria-x7"="aria2c --conf-path=$HOME/.aria2/x7.conf"
alias "aria-x10"="aria2c --conf-path=$HOME/.aria2/x10.conf"
alias "aria-x16"="aria2c --conf-path=$HOME/.aria2/x16.conf"
```
- Finally, reload your shell.

```bash
exec $SHELL -l
```
