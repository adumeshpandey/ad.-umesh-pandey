# SEO deployment checklist

The portfolio already includes a descriptive page title, meta description, mobile-friendly viewport, and `LegalService`/`LocalBusiness` JSON-LD schema for Sultanpur. It also contains visible civil-law practice-area content so search engines can understand the services offered.

## Required before publishing

1. Upload `advocate-portfolio-v2.html` as `index.html`, together with `umesh-chandra-pandey.png`, `sns-logo.png`, and `robots.txt`, at the root of the live website.
2. Replace `YOUR-LIVE-DOMAIN.example` in `sitemap.xml.template` with the actual HTTPS domain, then rename the file to `sitemap.xml`.
3. Replace the commented `Sitemap:` line in `robots.txt` with the same live `https://.../sitemap.xml` address.
4. Add these two tags inside the HTML `<head>` using the final public URL:

   ```html
   <link rel="canonical" href="https://YOUR-LIVE-DOMAIN.example/">
   <meta property="og:url" content="https://YOUR-LIVE-DOMAIN.example/">
   ```

5. Add and verify the website in Google Search Console, then submit `https://YOUR-LIVE-DOMAIN.example/sitemap.xml`.

## Local visibility

For Google Maps and local searches, create or claim the advocate's Google Business Profile using accurate details only. Use **Lawyer** as the primary category, add only practice areas actually offered, and keep the same name, phone numbers, Civil Court address, opening hours, and website URL as on this portfolio.

## Important

Search engines decide ranking; no file can guarantee first position or appearance for every search category. Accurate information, a public HTTPS site, a verified Business Profile, genuine reviews, and time for crawling are all needed for local visibility.
