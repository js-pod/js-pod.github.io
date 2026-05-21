# js-pod.github.io

Landing page for [jspod](https://github.com/JavaScriptSolidServer/jspod), the friendly CLI for [JSS](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

Served at **[jspod.org](https://jspod.org/)** via GitHub Pages (custom domain via `CNAME`).

## Editing

```bash
git clone git@github.com:js-pod/js-pod.github.io.git
cd js-pod.github.io
python3 -m http.server 8087
# open http://localhost:8087/
```

Edit `index.html` / `style.css` / `og.png` / `favicon.svg` and push. GitHub Pages picks it up in a minute.

## DNS

`CNAME` file pins the custom domain. Records on the registrar (e.g. Namecheap, Cloudflare):

```
jspod.org   ALIAS  js-pod.github.io.
```

(or four A records to the GitHub Pages IPs — see [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).)

## License

AGPL-3.0-only (matches jspod itself).
