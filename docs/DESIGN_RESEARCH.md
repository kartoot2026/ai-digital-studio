# Design research

Research date: 2026-10-02.

## Direction selected

The market is saturated with interchangeable AI landing pages built from purple gradients, floating glass cards, and ungrounded performance claims. This site instead uses editorial-scale typography, an operating-system grid, a compact service index, and a pale “principle” interruption. The visual thesis is **editorial precision meets technical systems**.

## Open-source and implementation references

- [Motion](https://github.com/motiondivision/motion) demonstrates spring-based, interruptible interaction patterns and is MIT licensed. The V1 borrows the principle of purposeful motion, but uses the native Intersection Observer and CSS to avoid a runtime dependency.
- [Motion Components](https://github.com/tgomilar/motion-components) is MIT licensed and reinforces consistent playback patterns for web animation. No source code was copied.
- [Cloudflare Pages static HTML guidance](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/) confirms a buildless static directory can be deployed directly and should contain a top-level `index.html`.
- [Cloudflare Pages GitHub integration](https://developers.cloudflare.com/pages/configuration/git-integration/github-integration/) supports automatic production deployments and branch previews after repository authorization.

## Applied principles

- Mobile-first layout with a single-column primary flow below 900px.
- 16px minimum body text, 44px minimum interactive targets, semantic landmarks, a skip link, focusable native controls, and reduced-motion support.
- Two original, non-representational studio images support the systems narrative: a glass architectural network in the hero and a many-inputs-to-one-output workflow in the process section. Both were generated specifically for this site without text, logos, people, or third-party assets.
- No testimonials, logos, case studies, metrics, awards, or delivery claims without owner-provided evidence.
- Motion is progressive enhancement; the full experience remains readable if JavaScript is unavailable or reduced motion is requested.

## License decision

No third-party source, font, icon package, or stock image is shipped. The final site uses original HTML/CSS/JavaScript, system fonts, and original generated artwork, eliminating third-party attribution obligations for V1.

