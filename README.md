# Mosyle Downloads

This repository contains scripts and versioned release assets distributed to
managed Apple devices through Mosyle MDM.

## Security

All content in this repository is publicly accessible.

Do not commit passwords, access tokens, private keys, confidential
configuration, customer data, or proprietary software that cannot legally be
redistributed.

## File types

- Shell scripts and text configuration templates are stored in the repository.
- PKG, DMG, ZIP, and other binary payloads are published as GitHub Release assets.
- Each binary release includes a SHA-256 checksum.

## Publishing requirements

1. Validate scripts with ShellCheck.
2. Verify package signatures and notarization where applicable.
3. Generate and publish SHA-256 checksums.
4. Test the direct download URL.
5. Test installation on a limited Mosyle scope before production deployment.
