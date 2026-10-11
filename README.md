# QC Research Vault Backup public website

This repository contains static informational pages for https://researchvault.site/ and https://researchvault.site/privacy/.

The backup engine and its credentials must remain in the separate private repository. No private archive data belongs here.

## Publish

1. Upload the site files including the `privacy` folder to the public repository's `main` branch root.
2. In Settings > Pages, choose **Deploy from a branch**, **main**, **/(root)** and save.
3. Set the custom domain to `researchvault.site` (also declared in `CNAME`).
4. Set the Namecheap apex DNS A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153` with Host `@`.
5. Set a `CNAME` record Host `www`, Value `jasobros.github.io` (no URL protocol). Remove conflicting Namecheap default parking/redirect records for those hosts.
6. When the domain resolves and GitHub issues the certificate, check **Enforce HTTPS** in Pages settings.
7. Verify both pages load on HTTPS before using them in Google OAuth Branding.

Keep the policy accurate as application behavior changes.
