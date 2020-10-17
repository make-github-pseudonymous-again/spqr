# :dagger: spqr

> Generate a QR code payload for initiating a SEPA transfer.

[![AUR package](https://img.shields.io/aur/version/spqr)](https://aur.archlinux.org/packages/spqr)

## Install

```sh
make DESTDIR=/ PREFIX=/usr install
```

## Usage

```sh
> spqr -n NAME -i IBAN -c CURRENCY -a AMOUNT ... | qrencode -t UTF8 -l Q
```
