# Avila Auto Publisher

Public documentation and platform-verification pages for a private, single-operator publishing system used to schedule short-form content across owned brands.

This repository intentionally contains only the public web surface required for platform review and legal transparency. The publishing automation, credentials, access tokens, brand configuration, and operational data are not included.

## Public pages

- [Product overview](https://aurelioavila.github.io/avila-auto-publisher/)
- [Privacy policy](https://aurelioavila.github.io/avila-auto-publisher/privacy.html)
- [Terms of service](https://aurelioavila.github.io/avila-auto-publisher/terms.html)
- TikTok platform-verification documents required for application review

## How it is used

The system supports a single operator who manages multiple owned brands. It
coordinates approved media, scheduling metadata, and publishing requests while
keeping platform credentials outside this public repository. Each connected
social account remains under the direct control of the same operator.

The public site exists so platform reviewers and visitors can verify the
purpose of the integration, understand how account data is handled, and find
the applicable legal policies from a stable, indexable location.

## Privacy model

- No public registration or user-generated content
- No third-party customer accounts
- No credentials, access tokens, or operational datasets in this repository
- Access limited to the accounts and brands owned by the operator
- Platform permissions requested only when required for publishing

## Repository structure

| Path | Purpose |
| --- | --- |
| `docs/index.html` | Product and platform-review overview |
| `docs/privacy.html` | Privacy policy |
| `docs/terms.html` | Terms of service |
| `docs/robots.txt` | Crawler directives |
| `docs/sitemap.xml` | Indexable public pages |

GitHub Pages publishes the `docs` directory. The sitemap intentionally excludes
callback and verification endpoints that do not provide useful search content.

## Security

Do not submit credentials or access tokens through this repository. Report a security concern privately by following the account-wide [security policy](https://github.com/AurelioAvila/.github/blob/master/SECURITY.md).

## Scope

This is not a reusable publishing framework or a hosted service. It documents a private operational tool and exposes no public API.
