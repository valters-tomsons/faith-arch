# faith-arch
Repository providing Arch Linux packages for `x86_64` and `aarch64`.

## Usage

Append the following to `/etc/pacman.conf`

```
[faith-arch]
SigLevel = Optional TrustedOnly
Server = https://repo.tomsons.me/$repo/$arch
```
