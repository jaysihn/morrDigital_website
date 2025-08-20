
# MorrDigital — Static Portfolio (External Project Links)

This version links project cards to **external GitHub Pages** sites (e.g., `https://jaysihn.github.io/myHue_website/`) instead of hosting project pages under `morrdigital.com/<project>`.

## Editing links

Update the `href` values for each card on:
- `index.html` (home "Selected Projects")
- `projects/index.html` (projects listing)

Look for `TODO` placeholders and replace with the live GitHub Pages URLs. Example:
```html
<a class="card" href="https://jaysihn.github.io/myHue_website/" target="_blank" rel="noopener">
```

## Publish on GitHub Pages

1. Create a GitHub repo (e.g., `morrdigital-site`).
2. Push these files to the repo root.
3. Settings → Pages → Deploy from a branch → `main` / root.
4. Add custom domain `morrdigital.com` and **Enforce HTTPS**.

## DNS

A records (apex):
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Optional: `www` CNAME → `YOUR_GITHUB_USERNAME.github.io`

## Notes

- You can later assign a purchased domain directly to any project’s own repo (its Pages site) without changing this portfolio; just update the links.
- `.nojekyll`, `CNAME`, `robots.txt`, and `sitemap.xml` included.
