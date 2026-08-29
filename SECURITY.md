# Security

## Reporting a security concern

Do not disclose credentials, tokens, private keys, customer data, or exploit details in a public GitHub issue.

Until Gryph Labs publishes a dedicated public security-reporting address/process, contact the organization owner through a private established channel for sensitive reports.

## Repository hygiene

Never commit:

- passwords or API keys
- access or refresh tokens
- private keys or certificates containing private material
- production customer data
- secret-bearing configuration files

If a secret is accidentally committed, treat it as compromised: revoke/rotate it and preserve the incident/audit trail rather than relying only on deleting the file from the latest commit.

Project repositories may define stricter requirements.
