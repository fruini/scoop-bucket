# fruini's Scoop Bucket

[![Tests](https://github.com/fruini/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/fruini/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/fruini/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/fruini/scoop-bucket/actions/workflows/excavator.yml)

My personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Notes about this bucket

I don't include 32bit version in my personal manifests unless there's no 64bit version available.

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add fruini_scoop-bucket https://github.com/fruini/scoop-bucket
scoop install fruini_scoop-bucket/uzdoom
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
