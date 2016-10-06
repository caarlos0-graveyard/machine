# machine [![Build Status](https://travis-ci.org/caarlos0/machine.svg?branch=master)](https://travis-ci.org/caarlos0/machine)

Machine setup, powered by Ansible.

I'm splitting my [dotfiles](https://github.com/caarlos0/dotfiles) repo
in two repos:

- dotfiles now handles only configuration
- machine (this) installs stuff (including my dotfiles)

For now, almost everything is a task, later I might migrate some of them
to roles, so they can evolve separately and be used by other people as well.

## Usage:

```console
$ wget https://github.com/caarlos0/machine/archive/master.zip
$ unzip master.zip
$ cd machine-master
```

At this point, you might want to edit the `main.yml` file and comment
out stuff you don't want, when you're done, simply run:

```console
$ ./setup
```

