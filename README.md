# Mbenya Attorneys — Independent Website Concept

Nine-page, static HTML/CSS/vanilla JavaScript law-firm website. Adapted from the inspected `abigail-ronald-louw-attorneys-production.zip` design, preserving its CSS geometry and JS navigation. Colours reflect the supplied navy-and-gold logo.

## Preview and deployment
Run `python3 -m http.server 8000` from the extracted `mbenya-attorneys` directory; open http://localhost:8000. Framework on Vercel: Other; root `.`; output `.`; no npm build.

## Status & approvals
**Independent demo only. NOT the firm’s official site.** Includes `noindex,nofollow` and robots disallow. Obtain authorisation for any publication, branding/portrait use and indexing. No live site has been published.

## Facts and provenance
- Name `Mbenya Attorneys` from supplied logo and client; Facebook now identifies as `Mbenya Attorneys Inc.` after the account was transferred from S. Modi Attorneys. URL still contains `/ModiAttorneys/`.
- Komani/Queenstown, Eastern Cape, criminal law and unlawful arrest/detention services from public Mbenya-era Facebook search result snippets (2026). See references below.
- Phone/WhatsApp `078 198 1383` appears in Mbenya-era Facebook posts. Firm publicly advertises WhatsApp. Confirm it remains current with the firm before official launch.
- No confirmed attorney full name, qualifications, street office address, company registration, opening hours or actual domain. **None invented.** Portraits supplied by client, not independently identity-verified.
- The Google Map is a **town/regional map**, NOT the firm’s precise office pin. Street address and exact pin must be verified before public handover.
- Form remains a client-side **WhatsApp draft launcher** and does NOT send to a backend. The separate clickable email link opens the visitor’s email application at `mbenyaattorneysinc@gmail.com`; no server-side email delivery is implemented.
- Illustrative photos load from external Pexels URLs. If offline, those do not load. See PHOTO-SOURCES.md.
- No actual published host is known. Canonical URLs/absolute OG URLs and a filled sitemap must be added **after** choosing an official approved host; no reference-firm URLs have been copied.

## Public Facebook research sources
- https://www.facebook.com/ModiAttorneys/photos/1653227830143249/ — Facebook page transfer announcement.
- https://www.facebook.com/ModiAttorneys/posts/%EF%B8%8F-mbenya-attorneys-incbased-in-komani-and-proudly-serving-clients-across-south-a/1659728116159887/ — Komani, criminal law, unlawful arrest and phone.
- https://www.facebook.com/ModiAttorneys/posts/%EF%B8%8F-mbenya-attorneys-protecting-your-rights-wherever-you-arefacing-criminal-charge/1667602338705798/ — phone/WhatsApp and areas.
- https://www.facebook.com/ModiAttorneys/ — current identity Mbenya Attorneys Inc.

These Facebook references were checked through indexed excerpts because Facebook blocks direct automated page/post/image retrieval; **the site's poster artwork and caption archive have not been exhaustively scraped**. No claim is made that Facebook image contents were fully reviewed.

## Remaining checks
Approval by firm; correct legal trading name; attorney's identity/role and portrait rights; exact street address and Google Maps pin; contact telephone re-confirmation; supplied firm email confirmation before official handover; social URLs; official domain/canonical/OG/sitemap; remote Pexels image loading at publish time; desktop and mobile visual QA in a browser.

## v3 — High-resolution photos, transparent footer and SEO/mobile checks
- Replaced Home standing portrait (old 206×206) with client's newer 525×704 original; About robes (old 206×206) with client's newer 662×994 original. Each portrait remains allocated to only one page.
- Removed the v2 artificial 235–260px image cap. Portraits now fill their original layout panels at responsive widths, using proportional `object-fit:cover` cropping.
- Created `assets/logo-footer-transparent.png`: white backdrop removed, original supplied logo outlines and gold retained, navy lettering rendered light to remain legible against the dark charcoal footer. Header logo is unchanged.
- Checked unique page titles and descriptions, LegalService structured data, page-specific social title/description, correct `en-ZA` locale, alt labels, and user interactions. Every content photo remains unique across pages.
- Preview remains `noindex,nofollow` with `robots.txt` disallow pending official authorisation. **SEO-ready is not the same as indexed.** Once official domain is approved, set absolute canonical URLs, absolute OpenGraph image URLs, domain-aware sitemap and allow crawling after consent. Never insert a fictional live domain.
- All external Pexels images require visual/network QA before publishing, and no physical office address or personal qualifications are asserted.

## v4 — Firm email update
- Client-provided screenshot identifies the firm email as `mbenyaattorneysinc@gmail.com`. It is user-provided and has not been independently mailbox-verified.
- Added clickable `mailto:` links to every page footer and the Contact page, plus an email alternative beneath the existing WhatsApp enquiry form.
- Included email in homepage `LegalService` structured data. Left the WhatsApp form functionality and all site images/styles unchanged.
