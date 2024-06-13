conda-shell
===========

A simple pair of Bash scripts for activating a conda environment in a
subshell.

Installation
------------
Copy `conda-shell` and `conda-shell-helper` to somewhere
on your path and then do `hash -r` (or the equivalent for non-Bash
shells) to rescan the path.

Use
---
Run `conda-shell <environment name>` in Bash to launch a subshell and
activate the named environment in it.  To 'deactivate' the
environment, use `exit` to exit the subshell.

