# Scoop bucket for the HodeiShield CLI

A [Scoop](https://scoop.sh) manifest for [`hodeishield`](https://github.com/Hodeitek/hodeishield-cli),
the read-only command-line client for [HodeiShield](https://hodeishield.com), on Windows x86_64.

## Install

```powershell
scoop bucket add hodeishield https://github.com/Hodeitek/scoop-hodeishield
scoop install hodeishield
```

The manifest is published from the first CLI release that includes it; until then, use the `.zip`
on the [releases page](https://github.com/Hodeitek/hodeishield-cli/releases).

## How it is maintained

The manifest is written by the CLI's release workflow from the release's own archive and
`SHA256SUMS`, so it always points at the file that release published and signed. To check that file
independently, see
[Verifying releases](https://github.com/Hodeitek/hodeishield-cli/blob/main/docs/verifying-releases.md).

Report problems in the [CLI repository](https://github.com/Hodeitek/hodeishield-cli/issues).

## License

[Apache License 2.0](LICENSE).
