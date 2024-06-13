conda-shell
===========

A simple pair of Bash scripts for activating a conda environment in a
Bash subshell.


Prerequisites
-------------

You need to have the `conda` command-line tool installed and on your
path.  You do not, however, need to let the conda installer modify
your `.bashrc` file in the, ummm, idiosyncratic way it does by
default.

You also need to be using Bash (the default Linux shell).  (But
modifying these scripts to work with e.g. Zsh would likely not be
difficult.)


Installation
------------

Copy `conda-shell` and `conda-shell-helper` to somewhere
on your `PATH` and then do `hash -r`.


Use
---

Run `conda-shell <environment name>` in Bash to launch a subshell and
activate the named environment in it.  To 'deactivate' the
environment, use `exit` to exit the subshell.

