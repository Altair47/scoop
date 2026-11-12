# Altair47 Scoop Bucket

[![Excavator](https://github.com/Altair47/scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/Altair47/scoop/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for apps by Nick Petropoulos
([github.com/Altair47](https://github.com/Altair47)).

## Apps

| App | What it is |
|---|---|
| [hexiso](https://github.com/Altair47/hexiso) | Fast portable disc image toolkit: open, edit, extract, build, convert, compress, mount and burn ISO images. |

## Install

```pwsh
scoop bucket add altair47 https://github.com/Altair47/scoop
scoop install altair47/hexiso
```

## Updates

The Excavator action checks each app's GitHub releases every 4 hours and updates the version and
hash in `bucket/` by itself. After that, `scoop update hexiso` gets the new version.

## Contributing

To report a broken manifest, open an issue. For changes, read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md) and the [App
Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) wiki page.
