# Nova Transit

A responsive, dependency-free courier website built with HTML, CSS, and minimal JavaScript. No forms, tracking, accounts, payments, database, remote fonts, or paid services.

## Preview

From this repository, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the local server in your browser. Stop it with Ctrl+C. No package installation or build is required. Phone, SMS, and email links open the device's configured apps; desktop computers may not have handlers installed.

## Files and branding

- `index.html`: editable business copy, contact actions, metadata, and semantic sections.
- `styles.css`: responsive layouts, brand colors, keyboard focus, and reduced-motion support.
- `script.js`: mobile navigation and copyright year.
- `assets/`: original SVG artwork, favicon, and six logo variants: horizontal, stacked, and icon-only, each for light or dark backgrounds. “Light” means use on light backgrounds; “dark” means use on dark backgrounds. Wordmarks use system Arial bold; SVG files remain editable.

The original geometric mark combines forward slashes and a diagonal bridge to suggest an N in motion. The delivery van and route are original illustrative artwork, not a claim about an owned vehicle or an exact service map.

## Owner review

Confirm the business name, `(682) 230-0842`, `JJGholdingsllc@gmail.com`, coverage, and service descriptions before launch. The About introduction is marked with an editing comment. Add only verified details. Same-day service is explicitly subject to route and scheduling availability. No certifications, medical handling qualifications, reviews, or delivery guarantees are asserted.

## Validation

Check desktop and mobile widths (320, 390, 768, and 1440px), all section links, keyboard focus and skip link, mobile menu open/close/Escape behavior, and call/text/email destinations. Check reduced-motion preferences. Contact links use `tel:+16822300842`, `sms:+16822300842`, and `mailto:JJGholdingsllc@gmail.com`; actual messages and calls require manual device testing. Automated browser checks validate navigation, images, links, overflow, and browser errors. No JavaScript build step is needed.

## Publish after approval

Nothing is deployed automatically. After owner approval and merge, this static site can be hosted using GitHub Pages: repository Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save. This intentionally publishes the website, so only do it after approval. Other static hosts can serve the repository root with no build command. No domain purchase is required. Once a final public URL exists, add an absolute canonical URL and social sharing image metadata as appropriate, then verify the live page and HTTPS. Do not place credentials or private business data in this public repository.
