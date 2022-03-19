# faith-arch
Repository providing Arch Linux packages for `x86_64` and `aarch64`.

## Usage

Append the following to `/etc/pacman.conf`

```
[faith-arch]
SigLevel = Optional TrustedOnly
Server = https://repo.tomsons.me/$repo/$arch
```

## Data Notice

* This site and binary content is hosted by **Microsoft Content Delivery Network**. What information Microsoft collects is described [here](https://privacy.microsoft.com/en-us/privacystatement).