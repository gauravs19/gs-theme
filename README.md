# gs-theme

A clean, professional GitHub Pages landing template. Single HTML file, zero dependencies, zero build step.

**Live demo:** https://gauravs19.github.io/gs-theme/

---

## What's included

| Component | Description |
|---|---|
| Announce bar | Dismissable top strip for release notes or changelogs |
| Sticky nav | Logo · links · GitHub ghost btn · primary CTA · mobile hamburger |
| Hero | Dark bg · dot-grid texture · radial glow · Playfair title · trust chips |
| Stat strip | 3-col bordered grid for pain points or proof metrics |
| Feature cards | 4-col dark grid, responsive to 2 → 1 col |
| Split sections | Text + image (normal and reversed), two included |
| Comparison table | Before/After with ✓/✗ rows |
| Step list | Numbered workflow rows with time badges |
| Testimonials | 3-col quote cards with avatar photos |
| Who it's for | 3-col persona cards |
| Inline callout | Accent-tinted box with CTA for cross-tool links |
| Share strip | Copy-link bar |
| CTA section | Full-width dark closing section |
| Footer | Logo · links · copyright · attribution |

---

## Usage

1. Copy `index.html` into your repo root (or `docs/` for GitHub Pages).
2. Find and replace `YOURTOOL` with your tool name.
3. Update the nav links, hero copy, and section content.
4. Swap the Unsplash image URLs with your own screenshots.
5. Push — GitHub Pages serves it directly, no build required.

### Theming

All colors are CSS variables at the top of `<style>`. Change these five to retheme the whole page:

```css
--accent:        #1d4ed8;   /* primary button, labels, links */
--accent-light:  #2563eb;   /* hover state */
--accent-pale:   #eff6ff;   /* card backgrounds, callout fill */
--accent-border: #bfdbfe;   /* card and callout borders */
--accent-text:   #93c5fd;   /* accent on dark backgrounds */
```

Common accent swaps:

| Tone | `--accent` | `--accent-light` | `--accent-pale` | `--accent-border` | `--accent-text` |
|---|---|---|---|---|---|
| Blue (default) | `#1d4ed8` | `#2563eb` | `#eff6ff` | `#bfdbfe` | `#93c5fd` |
| Indigo | `#4f46e5` | `#6366f1` | `#eef2ff` | `#c7d2fe` | `#a5b4fc` |
| Emerald | `#059669` | `#10b981` | `#ecfdf5` | `#a7f3d0` | `#6ee7b7` |
| Rose | `#e11d48` | `#f43f5e` | `#fff1f2` | `#fecdd3` | `#fda4af` |

---

## Attribution

gs-theme is free to use under the MIT License. **One ask:** keep the attribution line in the footer intact.

```html
<!-- attribution — please keep this line -->
<p class="footer-credit">
  Built with <a href="https://gauravs19.github.io/gs-theme/">gs-theme</a>
  by <a href="https://gauravs19.github.io/portfolio/">Gaurav Sharma</a>
</p>
```

If you remove the footer credit, a link back from your README is an acceptable alternative:

```markdown
Built with [gs-theme](https://gauravs19.github.io/gs-theme/) by [Gaurav Sharma](https://gauravs19.github.io/portfolio/).
```

---

## License

MIT — see [LICENSE](./LICENSE).

---

**Author:** [Gaurav Sharma](https://gauravs19.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/gauravs19/) · [Blog](https://techtradeoff.substack.com/)
