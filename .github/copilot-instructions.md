## Security rules
- Never hard-code secrets; read from environment/vault
- Use parameterised queries only
- Validate & encode all external input
- Use approved crypto (no MD5/SHA1)
- Pin dependency versions; prefer packages with no known CVEs
- Least-privilege GITHUB_TOKEN in workflows; pin actions to SHA
- Log errors without sensitive data