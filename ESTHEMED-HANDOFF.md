# Maison Rosé Atelier — project handoff

Production URL: https://beauty-business-template-vert.vercel.app/
Repository: djokatapetrov/beauty-business-template
Production branch: main
Latest approved design: Maison Rosé Atelier (25 October 2026).

## Work on this version
The complete current site is in index.html, with inline CSS and JavaScript. The older styles.css belongs to the previous design and is not linked by the current page.
Vercel deploys main automatically. Check the deployment and the live page after changing files.
Do not merge the older draft design PR #1 over this version: its design is superseded.

## Current functionality
- Responsive Bulgarian salon demo with rose/cream/burgundy styling.
- Three-question ritual selection, treatment detail dialogs, service carry-over to the form.
- Time preference selection, sample ritual builder with totals.
- Gift card name preview.
- Salon brand-name preview and Rosé / Champagne / Noir palettes.
- Original brand restoration, keyboard dialog closing, reduced-motion support.

## Deliberate demo boundaries
Maison Rosé is a fictional demo brand. Photos are illustrative stock images, not client results.
Prices, durations and treatment combinations are examples.
The form only renders an in-browser preview. It sends no email, creates no booking and processes no payment.
Personal contact fields are not stored. Only the selected service may be kept in sessionStorage.
No real customer records, medical data, fabricated testimonials or fake availability.

## Publishing and future client sites
Keep the demo notice and noindex,nofollow while this is a demonstration.
Before a real salon launch, agree the scope and supply verified salon information, domain, images, services, prices and staff details.
Implement and test email delivery, provider/resource scheduling, confirmations, cancellations, privacy information and any required consent before representing those as working.
Do not publish unapproved recurring fees or new equipment prices.
The EstheMed sales-site prices and the proposed annual service model are managed separately and are not approved tariffs for this demo.

## Quick checks
- Bulgarian text and all images render; one H1; no duplicate IDs or broken internal anchors.
- Face base 50 minutes / 65 EUR plus sample hand care 10 minutes / 12 EUR = 60 minutes / 77 EUR.
- Consultation selection disables the extra; ritual moves to booking preferences.
- Personalized name/palette restores correctly.
- Mobile navigation and dialogs work; no horizontal overflow at 390 px.

No build step or package installation is required for this static demo.
