# QA report

Status: implementation, local QA, and Cloudflare Pages production verification complete. The custom domain is live; Stripe review, sender-email verification, and final legal review remain.

## Acceptance checklist

- [x] Four approved services only
- [x] WhatsApp is the primary conversion path
- [x] No payment processor or payment form in the website
- [x] Zoho Invoice/external payment workflow documented
- [x] No invented testimonials, client logos, legal identity, or delivery evidence
- [x] Responsive mobile-first layouts
- [x] Semantic header, navigation, main, sections, footer, dialog, and native buttons
- [x] Skip link, reduced-motion mode, useful labels, and large touch targets
- [x] Static metadata, favicon, robots file, security headers, and 404 page
- [x] Core content remains accessible without JavaScript
- [x] Owner-approved WhatsApp number inserted
- [x] Owner-approved brand and domain inserted
- [x] Owner identity and CEO role verified against the company formation document
- [x] New natural-looking service, collaboration, and workspace imagery added
- [x] Owner-approved support email inserted
- [x] Legal entity and jurisdiction inserted from the owner-provided formation document
- [ ] Owner-approved business address inserted
- [ ] Policies reviewed for the applicable jurisdiction
- [x] Live Cloudflare Pages URL verified
- [x] Custom domain verified at `https://arbisoft.biz/`
- [x] Brand mark broadened from AI to A — ARBISOFT
- [x] Public payment workflow aligned with Zoho Invoice
- [x] Free technical SEO foundation: canonical URLs, sitemap, robots declaration, Open Graph data, and structured data
- [x] Honest internal operational case study added without invented client claims or metrics
- [x] Free Cloudflare Web Analytics site created and official beacon installed on every public HTML page

## Verification record

Verified on 2026-10-02:

- JavaScript syntax check passed.
- Local HTTP serving passed with no browser console errors.
- Mobile viewport (375px rendered width): no horizontal overflow; hero, CTA, and typography render correctly.
- Desktop viewport (1425px rendered width): no horizontal overflow; navigation, service grid, and responsive composition render correctly.
- Mobile menu opens and closes; service details expand; Privacy dialog opens and closes.
- Four service records and required anchors are present.
- Source scan found no API keys, account credentials, client records, testimonials, or invented legal identity.
- Progressive enhancement was corrected so content remains visible when JavaScript is disabled.
- Two original generated images were verified at mobile width: both load successfully, retain readable overlays, and introduce no horizontal overflow.
- The light editorial redesign was verified at 1425x990 desktop and 375x811 mobile viewports with no horizontal overflow or browser console errors.
- The navigation, mobile menu, service expansion, policy dialog, and WhatsApp CTA were re-tested after the redesign.
- Standalone About, Contact, Privacy, Terms, Refund, and Payment pages were added and all local page links resolve.
- Contact and Payment pages were verified at 375px mobile and 1425px desktop rendered widths with no horizontal overflow; the approved support email uses a working `mailto:` link.
- Six generated editorial images were added. Collaboration imagery is explicitly identified as illustrative rather than a portrait of the named team.
- Visual comparison against the approved redesign reference passed with no critical, major, or moderate discrepancies. See `design-qa.md`.
- Cloudflare Pages deployment completed successfully at `https://arbisoft.pages.dev/`; the live document title, ARBISOFT branding, four services, images, navigation, and WhatsApp links were verified from the public deployment.
- Namecheap nameservers were changed to `dorthy.ns.cloudflare.com` and `sterling.ns.cloudflare.com`; Cloudflare reported that DNS propagation was still pending at the time of this report.

Verified on 2026-10-03:

- Production domain `https://arbisoft.biz/` loads with the A — ARBISOFT mark.
- Updated broad positioning, service titles, Zoho Invoice workflow, and internal case study render correctly.
- Desktop viewport and 390×844 mobile viewport passed visual inspection with no horizontal overflow.
- JavaScript syntax and `git diff --check` passed.
- `robots.txt` points to `https://arbisoft.biz/sitemap.xml`.
- Each public information page has a canonical URL and unique meta description.
- Stripe remains under review; no claim of active card processing is published.
- Cloudflare Web Analytics was configured for `arbisoft.biz` with aggregate, non-advertising measurement.
