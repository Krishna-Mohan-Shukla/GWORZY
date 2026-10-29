# GWORZY SEO launch checklist

## Included in this package
- Existing homepage retained and updated with clearer service-focused metadata and headline.
- Dedicated crawlable HTML landing pages for every service represented in the homepage service tabs.
- Unique page titles, meta descriptions, canonical URLs, Open Graph metadata, semantic headings, internal links, and Service JSON-LD on service pages.
- `robots.txt` and `sitemap.xml`.
- Service cards now navigate to dedicated service pages using mouse, keyboard, and touch.

## Required before production
1. Confirm `https://gworzy.agency/` is the real canonical domain. If not, replace it everywhere with the final domain.
2. The homepage contact form currently opens the visitor's email client; it does not securely submit to a server. Connect a real form endpoint/CRM before launch.
3. Replace any fictional portfolio projects, testimonials, or other claims in the original homepage with verified projects and approved customer quotes—or remove them. Avoid fabricated outcomes.
4. Add a real 1200×630 Open Graph image at `/og-image.jpg`; this package references that URL but does not create the image.
5. Deploy over HTTPS; verify redirects, status codes, canonical tags, and mobile behavior.
6. Verify the site in Google Search Console and Bing Webmaster Tools, submit `/sitemap.xml`, and monitor indexing and Core Web Vitals.
7. Add real favicon/app icons, privacy policy, terms, and cookie consent only where legally/technically applicable.
8. Add analytics only with appropriate privacy disclosures/consent and ensure event tracking is configured.
9. Create genuinely useful project case studies based on documented work; add relevant internal links from service pages.
10. Run Lighthouse, PageSpeed Insights, schema validation, and accessibility testing after deployment.

## Important SEO reality
No one can guarantee that the site will rank #1 for every query or be the first answer from every AI system. These changes improve crawlability, relevance, page targeting, and machine-readable context; rankings depend on competition, quality, authority, user intent, and time. Do not add keyword stuffing or fake reviews.

## CSS framework
The existing design uses custom CSS and has a substantial visual system already. Switching to Tailwind is not required for SEO and would add migration work without automatically improving rankings.
