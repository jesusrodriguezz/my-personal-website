# J Rodriguez Web Studio

Starter website for J Rodriguez Web Studio. Plain HTML, CSS and a little
vanilla JavaScript, with no framework and no build step.

## Folder structure

```
index.html        Home
about.html        About
services.html     Services
portfolio.html    Portfolio
contact.html      Contact
404.html          "Page not found" page
css/styles.css    The only stylesheet (colors, fonts and spacing are CSS variables at the top)
js/main.js        Mobile menu toggle
images/           Favicon and future images
```

## Preview the site locally

**Quickest:** double-click `index.html` to open it in your browser.

**Better (works like a real host):** run a small local web server from this
folder, then open http://localhost:8000.

- Python (macOS/Linux usually have it): `python3 -m http.server 8000`
- Node.js: `npx serve .`
- VS Code: install the "Live Server" extension, then click **Go Live**.

Stop the server with `Ctrl + C`.

## Editing

- **Header and footer:** each page has its own copy. When you change the
  nav or footer, update all six HTML files.
- **Colors, fonts, spacing:** edit the variables in the `:root` block at the
  top of `css/styles.css`.
- **SEO:** each page has a `<title>` and a placeholder
  `<meta name="description">`. Replace every `TODO` description before launch.
- **Favicon:** `images/favicon.svg` is a placeholder. Replace it with the
  final logo.

## Hosting

The site is plain static files, so any static host can serve it as-is.
Links are relative, so it also works from a subfolder. Most hosts show
`404.html` automatically for missing pages. Its links and styles assume it is
served from the site root.
