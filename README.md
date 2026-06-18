# ORGAN-III: Ergon .github

Organization profile and default community-health repository for
[`organvm-iii-ergon`](https://github.com/organvm-iii-ergon).

This repository is the public meta surface for ORGAN-III: Ergon, the
commerce/product organ of the organvm system. It provides the organization
landing-page README, shared contributor expectations, security reporting
guidance, issue and pull request templates, Dependabot configuration, and the
`seed.yaml` automation contract consumed by downstream orchestration.

## Activation Audit

- Task: `GH-organvm-iii-ergon-github-6`
- Issue: [`organvm-iii-ergon/.github#6`](https://github.com/organvm-iii-ergon/.github/issues/6)
- Classification: `actually-live`
- Ship status: `ship-now`
- Shipped test: `PASS` - `profile/README.md` renders on the public
  [`organvm-iii-ergon`](https://github.com/organvm-iii-ergon) organization
  landing page.
- Last validated: `2026-06-18`

## Live Surfaces

| Surface | Path |
|:--------|:-----|
| Organization profile | [`profile/README.md`](profile/README.md) |
| Contributor guide | [`CONTRIBUTING.md`](CONTRIBUTING.md) |
| Code of conduct | [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) |
| Security policy | [`SECURITY.md`](SECURITY.md) |
| Issue templates | [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) |
| Pull request template | [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) |
| Dependency automation | [`.github/dependabot.yml`](.github/dependabot.yml) |
| Automation contract | [`seed.yaml`](seed.yaml) |

## Validation

The minimal CI workflow checks that the shipped `.github` surfaces remain
present, that YAML contracts parse, that the profile README still identifies
ORGAN-III: Ergon, and that common secret patterns are absent.
