# AetherFlow Releases

![AetherFlow logo](assets/brand/aetherflow-logo.png)

Public download repository for AetherFlow CEP extension releases, checksums, and optional native AE plugin packages.

## Public Splash / Docs

Start here for install notes, screenshots, workflow overview, firewall allowlist, and public-facing documentation:

https://danrac.github.io/AetherFlow_Docs/

## Latest Release

Download the latest signed ZXP from the GitHub Releases page:

https://github.com/danrac/AetherFlow_Releases/releases/latest

## Native Plugin Packages

Platform-specific native AE plugin packages are also published through this repository when available. Runtime Manager uses these public release assets to install or update plugin add-ons without exposing source code.

## Verification

Each release includes a checksum file. To verify the downloaded ZXP:

```bash
shasum -a 256 AetherFlow_CEP.zxp
```

Compare the output with the checksum listed for that release.

## Support

Optional GitHub Sponsors support:

https://github.com/sponsors/danrac

## Source Code

This repository only contains public release downloads, checksums, and public release notes. AetherFlow source code and internal development materials are private.
