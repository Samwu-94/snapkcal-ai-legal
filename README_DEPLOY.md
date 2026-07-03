# SnapKcal AI Legal Public Site

This directory is ready to deploy as a static website.

## Files

| Public Path | File |
| --- | --- |
| `/privacy/` | `privacy/index.html` |
| `/terms/` | `terms/index.html` |
| `/subscription-terms/` | `subscription-terms/index.html` |
| `/privacy.html` | `privacy.html` |
| `/terms.html` | `terms.html` |
| `/subscription-terms.html` | `subscription-terms.html` |

## Recommended Final URLs

After deploying this directory to a public HTTPS domain, use these URLs:

```text
SNAPKCAL_PRIVACY_URL=https://<domain>/privacy/
SNAPKCAL_TERMS_URL=https://<domain>/terms/
SNAPKCAL_SUBSCRIPTION_TERMS_URL=https://<domain>/subscription-terms/
```

Use the same URLs in:

- iOS release environment variables.
- App Store Connect Privacy Policy URL.
- App Store Connect Review Notes.
- Subscription review notes.
- QA final regression checklist.

## Before App Store Submission

Confirm:

- The three HTTPS URLs open without login.
- Mobile layout is readable.
- Pages do not show draft, placeholder, API, token, or internal AI provider/model text.
- The effective date and support email are correct.
- The developer/entity wording matches the App Store Connect developer account or the confirmed operating entity.

