# Deploy to Cloudflare Pages Free

## Git-connected deployment

1. Push this repository to `kartoot2026/ai-digital-studio` on the `main` branch.
2. In Cloudflare, open **Workers & Pages → Create application → Pages → Import an existing Git repository**.
3. Authorize only the required repository when possible.
4. Select `main` as the production branch.
5. Framework preset: **None**.
6. Build command: `exit 0` (or leave blank if the dashboard permits).
7. Build output directory: `/`.
8. Deploy and verify the generated `*.pages.dev` URL, including `/404` behavior, navigation, and WhatsApp links.
9. Add the approved custom domain `arbisoft.biz`, follow Cloudflare’s DNS prompts, and verify HTTPS.

Every push to the production branch can deploy automatically; non-production branches can receive preview deployments. See [Cloudflare’s static HTML guide](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/) and [GitHub integration guide](https://developers.cloudflare.com/pages/configuration/git-integration/github-integration/).

## Launch checks

- Confirm ARBISOFT is displayed consistently and the canonical URL is `https://arbisoft.biz/`.
- Verify every WhatsApp CTA targets `+212 661 487 396` while preserving the encoded prompts.
- Have the privacy, terms, and refund drafts reviewed for the owner’s jurisdiction.
- Verify the custom domain, canonical URL strategy, and ownership/contact details.
- Do not add account secrets as repository variables; this static V1 requires none.

