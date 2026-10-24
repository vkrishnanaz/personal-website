# Vivek Krishnan — academic website

A small static academic website. No build tools or dependencies.

## Preview
Open `index.html` in a browser. Navigate using the top links.

## Publish using GitHub Pages
1. Create a public GitHub repository (GitHub Pages on the free plan requires a public repository).
2. Upload all files **and folders** from this directory to the repository root.
3. Under Settings → Pages, select Deploy from a branch, `main`, `/ (root)`.
4. After the site works on the GitHub Pages URL, set the custom domain to `vivekrkrishnan.com` in Pages settings.
5. At Porkbun, configure the DNS records GitHub currently documents for apex custom domains, and verify HTTPS. Configure `vrkrishnan.com` as a permanent redirect to `https://vivekrkrishnan.com` using Porkbun forwarding; verify HTTPS support for the forwarding domain.

## Change the primary domain later
The site uses relative internal links and contains no hard-coded canonical domain. Update the GitHub Pages custom domain, DNS records, and the secondary-domain redirect. No source rewrite is needed.

## Update the photo
Replace `assets/portrait-placeholder.svg` with a photo file and update the `src` in `index.html`.

## Privacy check before publication
The bundled CV is the uploaded CV and includes a telephone number. Consider replacing `Vivek_Krishnan_CV.pdf` with a public version without your personal phone number.

## Edit
Edit `index.html`, `research.html`, and `publications.html` to update content. Shared styles live in `assets/style.css`.
