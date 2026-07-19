# Security policy

## Official distribution

Download ZelixLens from this repository's [official GitHub Releases page](../../releases) or the Zelix Lens Discord [#download channel](https://discord.com/channels/1526369471256596560/1527019431836913766). Do not trust executables sent through direct messages or hosted on unofficial mirrors.

Each release includes SHA-256 checksums, authenticated updater metadata, a provenance record, and consolidated license notices. Follow [VERIFY.md](VERIFY.md) before running a newly downloaded package.

## Report a vulnerability privately

Use this repository's **Security → Report a vulnerability** option to report:

- suspected release-asset tampering
- signature or checksum verification failures
- updater or launcher security defects
- leaked credentials or access-control weaknesses
- accidental exposure of private customer information

Include the affected version, a concise reproduction, the expected result, and the observed result. Do not include live access keys, passwords, tokens, recovery codes, or unnecessary personal information.

If GitHub private vulnerability reporting is unavailable, open a private ticket in the [official ZelixLens Discord](https://discord.gg/KaA3YBZ43D) and ask for the security-reporting contact. Do not post vulnerability details in a public channel.

## Security-software reports

If security software flags a download, stop and confirm its source and SHA-256 value. A matching checksum establishes that the package matches the published official asset.

Do not disable operating-system security controls solely to force an unverified binary to run.
