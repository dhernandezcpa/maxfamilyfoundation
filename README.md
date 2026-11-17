# Max Family Foundation, Inc. — Website

A single-page static site for Max Family Foundation, Inc. It has no build step and no dependencies.

## Files
- `index.html` — the whole site (HTML, CSS and JavaScript in one file)
- `vercel.json` — sets clean URLs and basic security headers

## Before you deploy
1. **Email.** In `index.html`, set `FOUNDATION_EMAIL` near the bottom of the file to the foundation's real address. The contact form opens the visitor's email app addressed to it.
2. **Florida registration number.** Replace `CH__________` with the number FDACS assigns. It appears twice: in the Get Involved section and in the footer.
3. **Tax status.** When the IRS determination letter arrives, update the "Tax status" paragraph and the footer line.

## Deploy with GitHub + Vercel
1. Create a GitHub repository (for example `max-family-foundation-site`) and upload `index.html`, `vercel.json` and this README.
2. In Vercel, choose **Add New → Project**, import the repository, keep the framework preset set to **Other**, and click **Deploy**.
3. To use your own domain, add it under **Project → Settings → Domains**, then point the DNS records at Vercel as instructed there.

Every push to the main branch redeploys the site automatically.
