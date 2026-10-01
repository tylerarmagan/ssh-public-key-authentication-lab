# Security Notes

## Sensitive Material

This repository must never contain:

- SSH private keys or private-key screenshots
- Key passphrases or account passwords
- Unredacted secret values
- Authentication logs containing public addresses or unrelated user information
- Active credentials, tokens, or environment files

The included private-key screenshot contains no key material. Its body was completely redacted before publication.

If a private key is committed, removing the visible file is not sufficient. Revoke the corresponding public key from every server, replace the key pair, and remove the exposed material from Git history.

## Authorized Use

Use these procedures only on systems you own or are explicitly authorized to administer.
