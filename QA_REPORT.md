# QA report

Status: implementation, local QA, and Cloudflare Pages production verification complete. Custom-domain DNS activation and final legal data remain.

## Acceptance checklist

- [x] Four approved services only
- [x] WhatsApp is the primary conversion path
- [x] No payment processor or payment form in the website
- [x] Bonsai/external payment workflow documented
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
- [ ] Custom domain verified after DNS propagation

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
