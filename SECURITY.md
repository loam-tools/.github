# Security policy

Please do not publish secrets, signing material, private tokens, exact private-location data, or exploitable security details in a public issue.

For a suspected vulnerability, open a private security advisory on the affected repository when available. If the affected repository is private, report it through the repository's private issue/security channel.

## Sensitive material

Never commit:

- Android keystores or Base64-encoded keystores;
- GitHub, API or release tokens;
- service credentials;
- private user location histories;
- production signing passwords;
- private routing datasets that are not licensed for redistribution.

## Scope

Security reports are particularly important when they affect updater integrity, APK signing, route-data validation, location privacy, file parsing, network transport or supply-chain dependencies.

Do not rely on security through obscurity: private repositories still require explicit validation, least privilege and safe handling of external data.
