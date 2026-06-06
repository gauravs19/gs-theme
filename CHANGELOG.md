# Changelog

## v3.0 — 2025-06-06
### Added
- Hero: 2-column layout with right-side CSS UI mockup (metric cards + bar chart)
- Hero: replaced on mobile — mockup hidden, full-width text retained
- Split sections: inline SVG illustrations (dashboard + workflow) — no external image deps
- `og.html`: OG image generator at 1200×630 — screenshot to produce `og-image.png`
- Floating accent palette picker (5 presets, fixed bottom-right)
- HTML swap-zone comments (`<!-- REPLACE: ... -->`) throughout template
- `.nojekyll`: disables Jekyll processing on GitHub Pages
- `404.html`: branded not-found page — dot grid, Playfair 404, back + home buttons
- `USAGE.md`: step-by-step find-replace checklist for adopters
- `favicon.svg`: 2×2 grid mark in accent blue

### Changed
- Accent switcher merged into palette picker — URL param (`?accent=emerald`) still works
- Footer restructured: brand column + 3-col nav (Product / Author / More tools) + bottom bar
- Footer nav scoped to `#main-nav` — fixes white background on footer links
- Mobile hero padding tightened

---

## v2.0 — 2025-06-06
### Added
- Professional slate/blue color palette (single consistent system — no multi-preset bleed)
- Commodity images: Unsplash photos in split sections, Pravatar avatars in testimonials
- Dot-grid hero texture + radial glow
- Second reversed split section
- Attribution footer credit + `LICENSE` + `README` documentation
- Scroll-spy: active nav link highlighted via IntersectionObserver

### Changed
- Footer nav scoped to `#main-nav` (was `nav {}`, caused white bg on footer links)
- Footer link opacity bumped from .38 → .55 for readability

---

## v1.0 — 2025-06-06
### Added
- Initial template: announce bar, sticky nav, dark hero, stat strip, 4-col feature cards
- Step list with time badges, comparison table, 3-col testimonials, persona cards
- Inline callout, share strip, full-width CTA, footer
- Scroll-reveal via IntersectionObserver
- Hamburger + mobile nav drawer
- CSS variable system — five vars retheme the entire page
