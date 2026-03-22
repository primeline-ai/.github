# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any PrimeLine project, please report it responsibly.

**Do NOT open a public issue.**

Instead, email **security@primeline.cc** or use [GitHub's private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) on the affected repository.

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

## Response Timeline

- **Acknowledgement:** within 48 hours
- **Assessment:** within 7 days
- **Fix:** as soon as possible, depending on severity

## Scope

This policy applies to all repositories under [github.com/primeline-ai](https://github.com/primeline-ai).

## Important Notes

- PrimeLine tools run locally on your machine. They do not transmit data to external servers unless you explicitly configure MCP servers or API integrations.
- `--dangerously-skip-permissions` (used in tmux orchestration workers) grants full file system access. Only use on development machines with version-controlled code.
