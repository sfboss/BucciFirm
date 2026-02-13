# Site Documentation Catalog

This site is a single-page application (`index.html`) with section anchors that behave like distinct page views for navigation and documentation purposes.

## Crawl/session notes

- Requested approach: Selenium session.
- Environment limitation: Selenium could not be installed due package registry/proxy restrictions, so screenshots were captured with the available browser automation tooling instead.
- Local site served at `http://127.0.0.1:8000` during capture.

## Page/section inventory with screenshots

| View | Route/Anchor | Screenshot |
|---|---|---|
| Home | `/` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/home.png` |
| About | `/#about` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/about.png` |
| Practice Areas | `/#practice` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/practice.png` |
| Fractional GC | `/#fractional` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/fractional.png` |
| Insights/Blog | `/#blog` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/blog.png` |
| Contact | `/#contact` | `browser:/tmp/codex_browser_invocations/9b2429e0a8a3a9a1/artifacts/artifacts/screenshots/contact.png` |

## Coverage conclusion

- The repository currently contains one HTML page (`index.html`) with in-page anchor sections.
- All primary navigable sections exposed in the top navigation were captured and cataloged above.
