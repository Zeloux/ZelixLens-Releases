# Privacy notice

This notice summarizes the data flows used by the current ZelixLens CS2 Edition customer release. It is intended to make the binary distribution easier to understand; it does not replace the terms or privacy notices of third-party services.

## License verification

The launcher uses KeyAuth for access verification. A verification request may include:

- the access key entered by the customer
- a device or hardware identifier used to bind and protect the license
- the ZelixLens application name and version
- standard network metadata processed by the remote service, such as IP address and request time

KeyAuth processes this information as an independent service provider under its own terms and policies.

## Local storage

- A saved access key is protected with Windows current-user encryption (DPAPI).
- User-created visual presets and application preferences remain on the local computer unless the user chooses to share them.
- Session-only activation data is not intended to be stored as a reusable plaintext credential.

## Updates and downloads

The launcher contacts GitHub to retrieve authenticated release metadata and approved update assets. GitHub may process standard connection and download metadata under GitHub's own privacy terms.

## Support services

Discord is used for sales, account support, and installation help. Information voluntarily submitted in Discord is processed under Discord's policies and the access rules of the official ZelixLens server.

Never submit passwords, recovery codes, payment-card information, or unrelated personal information in a support request. Do not post a license key in a public channel.

## Questions and requests

For questions about ZelixLens-held account or support information, open a private ticket in the [official Discord](https://discord.gg/KaA3YBZ43D). Requests involving KeyAuth, GitHub, or Discord data may also need to be directed to the relevant service provider.

This notice should be updated whenever a release materially changes its authentication, storage, update, analytics, or support data flows.
