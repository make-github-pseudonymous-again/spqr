:dagger: spqr
[![License](https://img.shields.io/github/license/aureooms/spqr.svg?style=flat)](https://raw.githubusercontent.com/aureooms/spqr/main/LICENSE)
[![Build status](https://img.shields.io/travis/aureooms/spqr/main.svg)](https://travis-ci.org/aureooms/spqr/branches)
==

Generate a QR code payload for initiating a SEPA transfer.

## :minidisc: Install [![AUR package](https://img.shields.io/aur/version/spqr)](https://aur.archlinux.org/packages/spqr)

```sh
make DESTDIR=/ PREFIX=/usr install
```

## :woman_astronaut: Usage

```sh
> spqr -n <NAME> -i <IBAN> -c <CURRENCY> -a <AMOUNT> <...> | qrencode -t UTF8 -l Q
```

## :open_book: Help

```sh
> spqr -h
```
