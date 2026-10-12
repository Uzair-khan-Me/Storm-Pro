# Storm Pros Roofing & Restoration LLC — Website

Live: https://storm-pro.vercel.app (repo: Uzair-khan-Me/Storm-Pro)

## AI Receptionist — Live Voice Call (Retell AI)

A call button connects visitors to the Storm Pros AI receptionist for instant voice
conversations (agent `agent_e3af15d300e98eb89f8c28a5a3`).

**Entry points:** floating call button (bottom-left) · hero CTA · demo-video CTA ·
contact card · FAQ CTA. Closing the window (✕ / Escape / click-outside) ends the call
and releases the microphone. "Open in a new tab" fallback included. The button sits on
the bottom-left so it never collides with the Botpress chat launcher (bottom-right) or
the mobile sticky call bar.

## SEO Implementation (Oct 2026)

Keyword basis: "roofing contractor the woodlands", "roof repair north houston", "storm
damage roof repair", "hail damage roof", "insurance roof claim", "metal roofing the
woodlands", "free roof inspection", plus roofing PAA queries (cost, insurance, timeline).

### On-page
- Keyword-first title + description ("Roofing Contractor in The Woodlands, TX")
- Local keywords in headings/copy: The Woodlands, Conroe, Spring, Tomball, Magnolia,
  North Houston, TX
- New **FAQ section** (6 PAA-targeting questions) + matching FAQPage schema
- Service-area copy in footer (NAP consistency), keyword-rich internal links

### Technical
- Canonical, robots meta (rich-snippet friendly), geo meta (US-TX)
- Open Graph + Twitter cards
- **Static JSON-LD `@graph`: RoofingContractor** (address 1601 Primrose St, Conroe TX,
  geo, opening hours, aggregateRating 4.9/81 — matches visible reviews) **+ WebSite +
  FAQPage**
- SVG favicon (no more missing-favicon 404)
- XML sitemap + robots.txt for storm-pro.vercel.app
- Form label/`for` accessibility fixes
- HTML validated: zero tag errors, no duplicate IDs

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full site + AI call widget + SEO |
| `sitemap.xml` | XML sitemap |
| `robots.txt` | Crawl rules + sitemap pointer |

## Notes
- `demo.mp4` in the repo is a broken 2-byte file and is not referenced — safe to delete.
- Deploy: push to `main` in Uzair-khan-Me/Storm-Pro; Vercel redeploys automatically.
