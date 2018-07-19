# jgarber623-gov's dotfiles

This is how I work.

## Installation

First, make sure that Python is installed:

```sh
sudo apt update
sudo apt install build-essential python python-dev python-setuptools
```

Then, clone this repository and run the following commands:

```sh
git clone -b pixelbook git@github.com:jgarber623-gov/dotfiles ~/.dotfiles
cd ~/.dotfiles
make bootstrap
make provision
```

## Acknowledgments

Significant portions of this work are based on the following projects:

- [Chavez's mac-ansible](https://github.com/mtchavez/mac-ansible)
- [Mathias Bynens' dotfiles](https://github.com/mathiasbynens/dotfiles)
- [Ryan Bates' dotfiles](https://github.com/ryanb/dotfiles)
- [Robby Russell's oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

The rest is picked up from various sources online, co-workers, friends, and others. Thanks, everyone!

## License

This code is freely available under the [MIT License](https://opensource.org/licenses/MIT). Use it, learn from it, fork it, improve it, change it, tailor it to your needs.
