# Remotely · CCA Prep

Free study path for the **Claude Certified Architect — Foundations (CCAF)** exam, curated for the Remotely network.

## Live page

Once GitHub Pages is enabled, the live URL is:

**https://horacioliva.github.io/remotely-cca-prep/**

## What's in here

- `index.html` — the full one-page site (single-file; Roobert + Inter fonts inlined as base64 data URIs)
- This README

## Enable GitHub Pages (one-time setup)

1. **Settings** → **Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `main`, **Folder**: `/ (root)`
4. Save. First publish takes ~1 minute.

## Updating the page

Replace `index.html` with a new version and commit — Pages re-deploys automatically (~30 seconds).

## Analytics — Plausible

The page loads [Plausible](https://plausible.io/) with `data-domain="cca.remotely.works"` (placeholder).

**Before launch**, update `data-domain` in `index.html` (inside the `<head>`) to match the final deployed hostname. The script auto-tracks page views, UTM parameters, and outbound link clicks (Typeform, Luma).

## UTM conventions for inbound campaigns

Use the same `utm_source` consistently per channel so the Plausible dashboard groups traffic correctly:

| Channel  | Suffix to append to the page URL |
| -------- | -------------------------------- |
| Email    | `?utm_source=email&utm_medium=outreach&utm_campaign=ccaf-jul15` |
| Slack    | `?utm_source=slack&utm_medium=community&utm_campaign=ccaf-jul15` |
| LinkedIn | `?utm_source=linkedin&utm_medium=organic&utm_campaign=ccaf-jul15` |
| Lemlist  | `?utm_source=lemlist&utm_medium=email&utm_campaign=ccaf-jul15` |

Per-segment variants — append `&utm_content=segmentA` (or B, C1, C2, C3, D-Founder, D-CTO) to distinguish them in the Plausible dashboard.

## Pending before public launch

- Plausible `data-domain` updated to the final hostname
- Headshots for Architects gallery
- Consent confirmed for testimonial + Architects attribution
- Verify Luma event URL still active (https://luma.com/upaj4zmw)
- Brand polish pass once migrated to remotely.works subdomain

## Disclaimer

Claude and the Claude Certified Architect program are Anthropic products. This page is a community-curated study aid for members of the Remotely network and is not endorsed by Anthropic.
