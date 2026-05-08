# scoop-bucket

[Scoop](https://scoop.sh) bucket for [conduit](https://github.com/Icehunter/conduit) and other Icehunter tools (Windows).

## Usage

```powershell
scoop bucket add icehunter https://github.com/Icehunter/scoop-bucket
scoop install conduit
```

## Updating

The `bucket/` directory is updated automatically by GoReleaser whenever a new
`v*` tag is pushed to `Icehunter/conduit`. Do not edit manifests by hand —
changes will be overwritten on the next release.

## License

Each manifest is governed by its upstream project's license. The bucket itself
is MIT.
