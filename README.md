# pyenv-brew-link

pyenv-brew-link is a [pyenv](https://github.com/pyenv/pyenv) plugin that provides a `pyenv brew-link` command to generate pyenv versions (links) for homebrew installed python versions.


## Installation

Installing pyenv-brew-link will give you access to the `pyenv brew-link` and `pyenv brew-unlink` commands.

    $ git clone https://github.com/pyenv/pyenv-brew-link.git $(pyenv root)/plugins/pyenv-brew-link

This will install the latest development version of pyenv-brew-link into the `$(pyenv root)/plugins/pyenv-brew-link` directory. From that directory, you can check out a specific release tag.
To update pyenv-brew-link, run `git pull` to download the latest changes.


## Usage

    pyenv brew-link
    pyenv brew-unlink


## Version

0.0.1
