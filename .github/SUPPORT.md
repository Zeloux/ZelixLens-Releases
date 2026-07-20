# Support

Use the official ZelixLens channels:

- [GitHub Releases](https://github.com/Zaroomx/ZelixLens-Releases/releases/latest) or the Zelix Lens Discord [#download channel](https://discord.com/channels/1526369471256596560/1527019431836913766) for downloads
- [GitHub Discussions](https://github.com/Zaroomx/ZelixLens-Releases/discussions) for public announcements and non-sensitive questions
- [Official Discord](https://discord.gg/KaA3YBZ43D) for access, account, and private installation support

## Before requesting help

1. Confirm that you downloaded the complete ZIP from GitHub Releases or the official Discord #download channel.
2. Follow [the download-verification guide](docs/VERIFY.md) and compare the package SHA-256 value.
3. Confirm that you are using Windows 10/11 x64 and the current supported CS2 release.
4. Record the ZelixLens version, the exact error message, and the step that failed.

## Antivirus, blocked downloads, or quarantine

Some antivirus products, including Windows Defender, may report a false positive or quarantine external overlay software. Verify the package before changing any security setting:

1. Confirm that it came from GitHub Releases or the official Discord #download channel.
2. Compare its SHA-256 value with the official `SHA256SUMS.txt` by following [the verification guide](docs/VERIFY.md).
3. Extract the complete, verified ZIP into a dedicated ZelixLens folder.

If the verified package is still blocked:

- Restore the file from quarantine and add a narrow allow rule or exclusion for the dedicated ZelixLens folder.
- Do not exclude your whole Downloads folder, drive, or another broad location.
- If real-time protection must be paused for a quick installation test, re-enable it immediately afterward.
- Never allow or exclude a copy that came from an unofficial mirror, direct message, or reupload.

## Include in a support request

- ZelixLens version and release tag
- Windows version and architecture
- whether the failure occurs during download, verification, update, license validation, or launch
- the exact error text, with access keys and personal information removed
- steps that consistently reproduce the problem

## Never share publicly

- access or license keys
- passwords, tokens, recovery codes, or payment information
- private KeyAuth or Discord account details
- unredacted screenshots containing personal information

Security vulnerabilities and suspected release tampering must be reported privately through [SECURITY.md](SECURITY.md), not through a public discussion.
