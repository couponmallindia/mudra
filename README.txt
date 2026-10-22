# Mudra Architectural Consultants — Static HTML5 Website

This is a standalone static HTML5 build. It does not require PHP, a database, CodeIgniter, Node.js, or any server-side application.

## Files
- `index.html` — homepage
- `about.html` — about page
- `services.html` — services
- `projects.html` — responsive project gallery with category filters and image lightbox
- `contact.html` — enquiry form that prepares an email in the visitor's email application
- `privacy-policy.html`, `404.html`, `robots.txt`, `sitemap.xml`
- `assets/` — CSS, JavaScript, supplied images and logo

## Preview
Open `index.html` in a modern browser, or upload the entire folder to standard static hosting.

## Before going live
1. Confirm the correct official email, telephone number, office address, social links and project labels. These were not included as verifiable contact details in the supplied ZIP, so they were not invented.
2. The contact form is intentionally static and does not send/store data by itself. Configure a verified email address in the form's `mailto:` URL or connect a form provider (e.g. Formspree/Netlify Forms) if server-delivered enquiries are required.
3. Review image-to-project mapping and legal/regulatory service descriptions before publication.
4. Update canonical URLs and sitemap if the production domain or paths differ.
5. Google Fonts is loaded externally; the site remains usable if it is unavailable, with local system font fallbacks.

## Static conversion note
The original ZIP contains a CodeIgniter/PHP application and public assets, but no database dump was found in the provided archive. This build is a clean static redesign using the supplied logo and image assets rather than a live export of database-only records.
