# Deploying simamanotha.com

Everything in this folder is safe to publish. Upload the **whole folder**, keeping the structure.

## Files

    index.html                    the website
    support.js                    required — the site will not render without it
    uploads/                      photo, CV, research paper, 10 certificates

## Easiest way to get it online

1. Go to app.netlify.com/drop
2. Drag this entire `site` folder onto the page
3. It goes live in seconds on a temporary address like `random-name-123.netlify.app`
4. Test it on your phone at that address before connecting your domain
5. To use simamanotha.com: Site settings → Domain management → Add custom domain, then follow their instructions for updating your domain's DNS

Free, no account needed to test, and you can drag an updated folder over the top any time to republish.

## Alternatives

- **GitHub Pages** — free, better if you already use GitHub. Push this folder to a repo, then Settings → Pages → deploy from branch.
- **Cloudflare Pages** or **Vercel** — same drag-and-drop idea as Netlify.

## Before you publish — check

- [ ] Open `uploads/Simama-Ngidi-CV.pdf` and confirm it is the version WITHOUT your street address and without your referees' phone numbers
- [ ] Your own mobile number appears in the CV PDF but not on the web page itself
- [ ] Open the site on a phone and decide whether the layout works for you

## A note on the CV

`uploads/Simama-Ngidi-CV.pdf` is the cleaned version: no street address, and references shown as "Available upon request". Whenever you replace it, check both of those before republishing.

The earlier drafts that carried your street address and your referees' phone numbers have been deleted from the project. Never place either on a web server.
