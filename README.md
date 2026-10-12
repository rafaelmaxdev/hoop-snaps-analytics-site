# Hoop Snaps Analytics — public information site

Buildless, dependency-free HTML/CSS. This repository contains ONLY the public information pages, not the private video/analytics application or its credentials.

## GitHub Pages

In repository Settings → Pages, choose Deploy from a branch, select the default branch and `/ (root)`, then Save. Intended URLs, once deployment succeeds:

- Home: https://rafaelmaxdev.github.io/hoop-snaps-analytics-site/
- Privacy: https://rafaelmaxdev.github.io/hoop-snaps-analytics-site/privacy.html
- Terms: https://rafaelmaxdev.github.io/hoop-snaps-analytics-site/terms.html

These are deployment targets, not proof the site is live. Confirm HTTP 200 before adding them in Google Auth Platform. Google may require ownership verification or a custom verified domain; GitHub Pages publication alone does not guarantee OAuth approval.

## Content accuracy

Content reviewed against the local application's OAuth scopes, token storage, upload behavior and editorial use of channel-learning summaries. The current implementation does not enforce automatic data-retention deletion, and this limitation is disclosed. Public policies do not themselves implement retention or certify compliance, provider data practices, or OAuth approval. Review the policy whenever the application changes.

No forms, external fonts, JavaScript, tracking or third-party images. Hosting access logs are governed by GitHub's policies. Do not commit API keys, OAuth clients, refresh tokens, analytics reports or private channel data here.
