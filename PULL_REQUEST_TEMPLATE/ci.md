### CI/CD workflow change
- What workflow changed and why?

### Safety
- [ ] Public pipelines do NOT deploy (lint/validate/plan only)
- [ ] Forked PRs require approval before running
- [ ] No long-lived cloud keys in CI; use OIDC if needed (plan only)

Reference: [docs/security-checklist.md](docs/security-checklist.md)


> Branch naming: `feat/<short-name>`, `fix/<short-name>`, `docs/<short-name>`, `ci/<short-name>`, `chore/<short-name>`
