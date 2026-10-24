# Vivek Krishnan academic website

Preview: open index.html in a browser, or run `python3 -m http.server 8000` here.

Deploy: create a GitHub repository, upload the files, enable GitHub Pages under Settings > Pages (main branch, root), and test the github.io URL. Set custom domain to `vivekrkrishnan.com` (confirm spelling in Porkbun). At Porkbun configure apex A records to 185.199.108.153, 185.199.109.153, 185.199.110.153, and 185.199.111.153. Then enable Enforce HTTPS after certificate provisioning. Configure vrkrishnan.com as a permanent redirect to https://vivekrkrishnan.com using Porkbun URL forwarding, verifying both HTTP and HTTPS behavior. GitHub Pages supports one custom domain per site; secondary-domain forwarding is configured separately.

The HTML uses relative asset paths, so changing primary domains later does not require rewriting the website. The placeholder portrait is embedded as SVG in HTML; replace the `.photo` contents with an image when ready.

Before publishing: review all text, and consider whether to make the CV publicly downloadable (it contains your telephone number). Public GitHub Pages repositories expose source and assets publicly. Verify the precise domain spelling.
