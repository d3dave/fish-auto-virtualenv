A [fish](https://fishshell.com) plugin to automatically (de)activate virtualenv in the current
directory.

![screencast](https://user-images.githubusercontent.com/1116272/146308178-226cf7ec-155e-4eb2-9610-5b5d22895ee3.gif)

The variable `auto_virtualenv_dirs` is a list of directory names to try when looking for an existing
virtualenv directory. The default list has `.venv` and `venv`.

## Install

Using [Fisher](https://github.com/jorgebucaran/fisher):

```console
fisher install d3dave/fish-auto-virtualenv
```
