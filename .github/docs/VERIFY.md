# Verify an official download

Use these steps before running a newly downloaded ZelixLens package.

## 1. Download from an official source

Download `ZelixLens-CS2-Edition.zip` from the [latest GitHub release](https://github.com/Zaroomx/ZelixLens-Releases/releases/latest) or the Zelix Lens Discord [#download channel](https://discord.com/channels/1526369471256596560/1527019431836913766).

Then download `SHA256SUMS.txt` from the GitHub release for the published verification value.

Do not use copies sent through direct messages or hosted on unofficial mirrors.

## 2. Calculate the SHA-256 value

Open PowerShell in the folder containing the downloaded ZIP and run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\ZelixLens-CS2-Edition.zip
```

Open `SHA256SUMS.txt` and confirm that the value beside `ZelixLens-CS2-Edition.zip` exactly matches the value printed by PowerShell.

You can also calculate all downloaded release-asset hashes with:

```powershell
Get-ChildItem -File | Get-FileHash -Algorithm SHA256 | Format-Table Hash, Path -AutoSize
```

## 3. Check the release record

The release also publishes:

- `update-manifest.txt` - updater asset metadata
- `update-manifest.sig` - signature for the updater manifest
- `ZelixLens-CS2-Edition.provenance.json` - release provenance record
- `ZelixLens-CS2-Edition-NOTICES.txt` - product and third-party notices

The ZelixLens launcher verifies authenticated updater metadata before accepting an automatic runtime update.

## What verification means

A matching SHA-256 value confirms that your file is byte-for-byte identical to the asset published in the official release. It does not independently establish that software is safe, compatible, permitted by a game platform, or suitable for your computer.

If the values do not match, delete the downloaded copy and report the mismatch privately through the [security policy](../SECURITY.md).
