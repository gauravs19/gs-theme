# Using gs-theme

A find-replace checklist for adapting this template to your own project.

---

## Step 1 — Find and replace these strings

Open `index.html` and replace every occurrence of each placeholder:

| Placeholder | Replace with | Where |
|---|---|---|
| `YOURTOOL` | Your tool name (e.g. `CORTEX`) | Logo, footer logo |
| `Your Tool Name` | Same tool name, natural case | Hero eyebrow, page title |
| `Your Name` | Your name | Footer copyright |
| `2025` | Current year | Footer copyright |
| `#` | Your app or repo URL | CTA buttons, nav logo |

---

## Step 2 — Update meta tags

In `<head>`, update:

```html
<title>YOURTOOL — One-line description</title>
<meta name="description" content="...">
<meta property="og:title" content="YOURTOOL — ...">
<meta property="og:description" content="...">
<meta property="og:image" content="https://yourdomain.github.io/yourrepo/og-image.png">
<meta property="og:url" content="https://yourdomain.github.io/yourrepo/">
<meta name="twitter:image" content="...same as og:image...">
```

---

## Step 3 — Replace images

| Element | Current URL | Replace with |
|---|---|---|
| Split section 1 | `images.unsplash.com/photo-1551288049...` | Your app screenshot |
| Split section 2 | `images.unsplash.com/photo-1522071820...` | Your team or workflow photo |
| Testimonial avatar 1 | `i.pravatar.cc/80?img=33` | Real photo or keep placeholder |
| Testimonial avatar 2 | `i.pravatar.cc/80?img=47` | Real photo or keep placeholder |
| Testimonial avatar 3 | `i.pravatar.cc/80?img=12` | Real photo or keep placeholder |
| OG image | `og-image.png` | Screenshot of your landing page (1200×630px) |

---

## Step 4 — Update nav links

```html
<a href="#features">Features</a>      <!-- anchor to section id="features" -->
<a href="#how-it-works">How it works</a>
<a href="#who">Who it's for</a>
<a href="https://github.com/YOURHANDLE/YOURREPO">GitHub</a>
```

---

## Step 5 — Update footer columns

Three footer columns are included: **Product**, **Author**, and **More tools**.
- Product: links to sections within the page (`#features` etc.)
- Author: your personal links (portfolio, blog, LinkedIn, GitHub)
- More tools: links to your other projects — delete this column if not needed

---

## Step 6 — Change accent color (optional)

In `<style>`, update these five variables at the top of `:root`:

```css
--accent:        #1d4ed8;
--accent-light:  #2563eb;
--accent-pale:   #eff6ff;
--accent-border: #bfdbfe;
--accent-text:   #93c5fd;
```

Common presets are documented in `README.md`.

You can also preview any preset live without editing: append `?accent=indigo` (or `emerald`, `rose`, `amber`) to the URL.

---

## Step 7 — Update favicon

Replace `favicon.svg` with your own SVG icon (32×32 recommended).
For PNG fallback, add:
```html
<link rel="icon" href="favicon.png" type="image/png" sizes="32x32">
```

---

## Step 8 — Attribution

Keep the footer credit line intact, or add this to your README instead:

```markdown
Built with [gs-theme](https://gauravs19.github.io/gs-theme/) by [Gaurav Sharma](https://gauravs19.github.io/portfolio/).
```

---

## Deploying to GitHub Pages

1. Push `index.html` (and other files) to your repo's `main` or `master` branch.
2. Go to **Settings → Pages → Source** → set to `main` / root.
3. Your site will be live at `https://YOURHANDLE.github.io/YOURREPO/`.

The `.nojekyll` file in this repo prevents GitHub Pages from running Jekyll, which speeds up builds and avoids processing conflicts.
