# rsync

rsync 3.3.0: copies and synchronises files (over ssh with the openssh package)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install rsync
```

| | |
|---|---|
| Version | 3.3.0 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`bash`](https://github.com/Artfical/tpkg-bash) |
| Needs tOS build | 619 or newer |
| Size | 301401 bytes (569048 unpacked) |
| SHA-256 of the `.tpkg` | `7d6a3c47dc1a8574b003aa2fe419134f76fba4385ba1ba695ba5450943d0374a` |

## Commands it adds

| Command | Runs |
|---|---|
| `rsync` | `bin/rsync` |
| `rsync-ssl` | `bin/rsync-ssl` |

## Download

The package file (`rsync-3.3.0.tpkg`) and the sources it was built from are the assets of the
[v3.3.0 release](https://github.com/Artfical/tpkg-rsync/releases/tag/v3.3.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `rsync-3.3.0.tar.gz`

Check a download: `sha256sum rsync-3.3.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
