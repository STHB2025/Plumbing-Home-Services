# Plumbing & Home Services Website Template

A responsive Astro starter for independent plumbers and home maintenance businesses. The fictional Northline Plumbing Co. profile is demonstration content; replace or remove every sample detail before a client launch.

**Demo:** https://sthb2025.github.io/Plumbing-Home-Services/  
**Stack:** Astro, HTML, CSS, JavaScript; static GitHub Pages.

## Install and run
Requires a current Node.js LTS and npm.
```sh
npm install
npm run dev
npm run build
npm run preview
```
Static output is written to `dist/`. GitHub Pages project base is `/Plumbing-Home-Services/` in `astro.config.mjs`.

## Business configuration
Edit `src/data/business.js`: identity, logo, brand, SEO, contacts, address, hours, areas, emergency availability, enabled services, trust indicators, imagery, testimonials, social links, colours and privacy URL. Set a service's `enabled` to false to hide it. Emergency availability is disabled by default. All business profile content, areas, hours, photos and testimonials are samples. Do not present them as real.

### Logo and imagery
The header has a small inline plumbing mark; replace it with an approved logo if supplied. Gallery images use remote Unsplash URLs. Replace with licensed, client-approved, locally optimised photos and update descriptive alt text.

### Contact links
Set `phone` to create a telephone link. Set the client's email for mail links. Configure `whatsappNumber` using country code and digits only, e.g. `27821234567`; blank hides WhatsApp buttons. Update the greeting.

### Formspree
The static site cannot receive form submissions itself. With no endpoint, users see an email fallback and no fake success state. To activate the form, configure the client's own verified Formspree account and receiving address, then set `formEndpoint` to `https://formspree.io/f/FORM_ID`. `@formspree/ajax` provides loading, validation, error and success handling. Test a real enquiry and confirm it arrives. Enquiries are not confirmed appointments or guaranteed quotes.

## SEO, privacy and deployment
Edit `seoTitle` and `seoDescription`. The layout emits canonical and Open Graph metadata. Add a reviewed privacy URL and disclosures describing actual data handling. Workflow `.github/workflows/deploy.yml` builds pushes to `main` and manual runs. Configure Pages source to GitHub Actions. The current site/base target `https://sthb2025.github.io/Plumbing-Home-Services/`. Check the live page, assets and anchor links after Actions succeeds.

## Client handover checklist
- Confirm approved business name, logo, colours, copy, contacts and email.
- Verify enabled services and descriptions.
- Confirm hours, emergency availability, actual coverage and credentials.
- Replace/remove demo photos and sample testimonials.
- Configure phone, email and optional WhatsApp; test on a phone.
- If requested, configure Formspree, submit a real test and verify receipt.
- Add reviewed privacy policy and third-party form disclosure.
- Update domain, canonical URL/base and attribution.
- Inspect 1440px desktop and 390px/320px mobile; check keyboard focus and reduced motion.
- Build and review the deployed site; retain client ownership of repository and accounts.

Northline Plumbing Co. is fictional. The demo has no real contact number, WhatsApp, reviews, credentials, guaranteed coverage or 24/7 service. Jackson Personal Digital Services is credited as template creator.