# jgarber623-gov's dotfiles

This is how I work.

## Installation

First, make sure that the necessary dependencies are installed:

```sh
sudo apt update
sudo apt install build-essential
```

Then, clone this repository and run the following commands:

```sh
git clone -b ubuntu git@github.com:jgarber623-gov/dotfiles ~/.dotfiles
cd ~/.dotfiles
make bootstrap
make provision
```

To expose certificates on a hardware device to Chrome, issue the following command:

```sh
modutil -dbdir sql:$HOME/.pki/nssdb/ -add "CAC Module" -libfile /usr/lib/x86_64-linux-gnu/pkcs11/opensc-pkcs11.so
```

**Note:** Use `dpkg -L opensc-pkcs11` to easily locate the `opensc-pkcs11.so` file.

## Acknowledgments

Significant portions of this work are based on the following projects:

- [Chavez's mac-ansible](https://github.com/mtchavez/mac-ansible)
- [Mathias Bynens' dotfiles](https://github.com/mathiasbynens/dotfiles)
- [Ryan Bates' dotfiles](https://github.com/ryanb/dotfiles)
- [Robby Russell's oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

The rest is picked up from various sources online, co-workers, friends, and others. Thanks, everyone!

## License

This code is freely available under the [MIT License](https://opensource.org/licenses/MIT). Use it, learn from it, fork it, improve it, change it, tailor it to your needs.
