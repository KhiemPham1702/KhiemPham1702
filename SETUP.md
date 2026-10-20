# GitHub Profile V3 — Setup

1. Create (or open) the **public** repository `KhiemPham1702/KhiemPham1702`.
2. Upload `README.md` and the **entire** `assets/` directory to the repository root.
3. Commit to the default branch. Visit https://github.com/KhiemPham1702 to view your profile.

## Files
- `assets/hero.svg`: custom typography hero, subtle SVG pulse.
- `assets/domains.svg`: responsive-width domain summary (fixed intrinsic ratio).
- `assets/products/*.png`: rounded, bordered, consistent-size product previews created from your supplied screenshots.

## Notes
- GitHub sanitizes arbitrary CSS and JavaScript. This package uses GitHub-compatible Markdown/HTML, static rounded PNGs and SVG animations. Some clients may disable SVG animation.
- Google Play package links were carried forward from the conversation. **Verify the app listing URLs** before publishing.
- Professional achievements are summarized from the supplied CVs. Only publish company-related details you are permitted to disclose.
- To remove external GitHub stats, delete the `github-readme-stats.vercel.app` image near the bottom.
- Images are local, so the profile does not depend on a third-party image host.


## V4.1 — Rounded image fix
- Product previews are **RGBA PNG with truly transparent rounded corners**, not dark rectangular backgrounds.
- No CSS border-radius is required (GitHub strips most CSS).
- If GitHub shows the old images, hard-refresh or wait for its image proxy cache to update.
- Keep the `assets/products/` folder structure unchanged.


## V4.2 SVG compatibility fix
- Fixed `assets/domains.svg`: escaped the raw ampersand in `FINTECH & TRADING` as `&amp;` (required by XML/SVG).
- Validated and raster-rendered all three SVG assets.
- Upload `assets/domains.svg` to replace the broken file; README and other assets remain compatible.
