# Deploy this portfolio on Vercel

This is a static website, so Vercel does not need a build command.

## Recommended: GitHub + Vercel

1. Create a new GitHub repository and upload every file from `umesh-chandra-pandey-portfolio`.
2. On Vercel, choose **Add New → Project**, import that GitHub repository, and select **Other** as the framework preset.
3. Leave the build command blank and set the output directory to `.` (the project root) if Vercel asks.
4. Click **Deploy**. Vercel will give the website a secure `*.vercel.app` URL.

## CLI alternative

From inside the `umesh-chandra-pandey-portfolio` folder, after logging into Vercel:

```powershell
npm i -g vercel
vercel --prod
```

## Immediately after the live URL is available

1. Replace `YOUR-LIVE-DOMAIN.example` in `sitemap.xml.template` with the Vercel URL or final custom domain, then rename it to `sitemap.xml`.
2. Update the commented sitemap line in `robots.txt` with the same full sitemap URL.
3. Add the canonical and `og:url` tags listed in `SEO-SETUP.md`, using the same final URL.
4. Redeploy, then submit the live sitemap in Google Search Console.

Keep `index.html`, the two image files, `robots.txt`, and the completed `sitemap.xml` in the project root.
