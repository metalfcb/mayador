# Mayador launch website — smart and healthy kids positioning

This is a single-page static website that can be hosted free on GitHub Pages.

The landing page positions Mayador as a story-led way to help parents raise smart, healthy and kind children. Personalisation is presented as the mechanism that makes each habit, value or life lesson felt and remembered.

## Publish with GitHub Pages

1. Create a public GitHub repository named `mayador-website`.
2. Upload `index.html` from this package to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Once the preview works, enter `www.mayador.in` under **Custom domain**.

## Hostinger DNS records

Add a CNAME record:

- Name: `www`
- Target: `YOUR-GITHUB-USERNAME.github.io`

Add four A records for `@`:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Do not delete email-related MX or TXT records. DNS changes can take up to 24 hours.

## Details to update before launch

Search inside `index.html` and replace:

- `hello@mayador.in` with the final email, if different.
- `https://instagram.com/` with the Mayador Instagram URL.
- Story names or wording if the collection changes.

The waitlist currently opens the visitor's email application. For automatic collection later, connect a free form service such as Tally, Google Forms or Formspree.
