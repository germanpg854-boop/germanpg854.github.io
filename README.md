# GermanPG854 website

A responsive static website for GitHub Pages. Built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — main website
- `language.html` — German language guide
- `approbation.html` — Approbation and recognition guide
- `exams.html` — FSP and Kenntnisprüfung guide
- `residency.html` — specialty training and residency guide
- `styles.css` — responsive styling
- `script.js` — mobile navigation and current year
- `404.html` — custom not-found page
- `sitemap.xml` and `robots.txt` — basic search-engine discovery files
- `assets/favicon.svg` — site icon

## Publish for free with GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a **public** repository named exactly `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
3. Upload the contents of this folder to the repository root. `index.html` must be at the root, not inside another folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for the Pages deployment to finish. The site address will be `https://YOUR-USERNAME.github.io/`.

## Before launch
- If your GitHub username is not `germanpg854`, change the canonical URL in `index.html`, and the URLs in `robots.txt` and `sitemap.xml` to your actual Pages URL.
- Replace the example email `hello@germanpg854.com` with an email address you control, or remove those mail links.
- Check every external link and update content with your own verified information.
- The site uses Google Fonts; if you prefer no third-party font request, remove the Google Fonts lines in `index.html`. The design falls back to Georgia and Arial.
- This is a static site: it does not include a database, login, contact form backend, comments or newsletter signup.

## Google indexing
1. Add the deployed site as a URL-prefix property in Google Search Console.
2. Verify ownership using one of the methods offered by Search Console. A DNS verification record is easiest after you own a custom domain; for a GitHub Pages subdomain use an available HTML-file or meta-tag verification method.
3. Submit `https://YOUR-USERNAME.github.io/sitemap.xml` in the Sitemaps section.
4. Use URL Inspection to request indexing for the home page.
Indexing and ranking are not guaranteed and can take time.

## Add a custom .com domain later
1. Register a domain with a reputable registrar (domain registration is normally paid; renewals are also paid).
2. In the repository, open **Settings → Pages → Custom domain**, enter your domain (for example `www.example.com`) and save.
3. At your registrar, configure the DNS records exactly as GitHub's current custom-domain guide instructs. DNS values can change, so copy the values from GitHub's documentation rather than relying on an old tutorial.
4. Wait for DNS propagation, enable **Enforce HTTPS** when available, and update the canonical URL in `index.html`, plus `robots.txt` and `sitemap.xml`.
5. Add the new domain as a property in Google Search Console and submit the updated sitemap.

Official guides:
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
- https://search.google.com/search-console/about

## Important content note
This website is a general educational starting point, not legal, immigration, employment or medical licensing advice. State-specific rules and individual eligibility vary. Verify all requirements with the competent German state authority and relevant professional bodies before acting.
