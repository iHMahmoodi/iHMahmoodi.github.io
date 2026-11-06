# GutenX v6 — Component structure and image integrity
Date: 2026-11-06
Preview: https://ihmahmoodi.com/gutenx-preview-20261105/
WordPress preview 23830. Production 22990 not modified.

## Requested changes implemented
- Preserve main imagery and overview copy; present three separate feature cards with vector icon, heading and description under each of five major sections.
- Create 15 bespoke SVG icons with consistent geometry, dark outlines and orange accents; host through sanitized WordPress SVG upload. Reuse three icons in the existing benefit row for a consistent family (18 SVG instances).
- WooCommerce: six equal-width cards in three two-column rows; native Columns stretch gives equal heights. Each image uses a 16:10 frame with object-fit:contain. Natural source ratios are preserved; no fixed height forces stretching. Full-screen native image enlargement retained.
- Image-to-title gap 24px; title-to-body gap 16px. Remove artificial title minimum height after measuring the actual titles.
- Mobile feature: one centered phone visual in a labelled presentation frame, replacing two unrelated adjacent images.
- Hooks visuals: matching labelled frames; stack natively on mobile.
- Hero thumbnails share a 3:5 crop frame (object-fit:cover) with full originals available in lightbox.
- Replace Details with native Spectra uagb/faq + dynamic uagb/faq-child, matching LyriX's accordion component. Eight original Q/A pairs retained, plus/minus controls and single-open behavior. Schema generation disabled to avoid duplication.
- Core and Spectra block settings only; no custom HTML block, custom page stylesheet, new plugin or site-wide setting change.

## Observed verification
- Desktop Chrome CSS viewport 1348px: no document horizontal overflow.
- Megamenu cards: 384px wide, 260px tall each.
- All six WooCommerce cards: 588px wide, 534px tall each.
- All six shop image boxes: 498 × 311px; computed object-fit:contain.
- Title spacing computed 16px.
- All article images loaded, one H1, all article fragment links resolve.
- FAQ item toggles to active; opening second closes first. After transition first content display:none, second display:block.
- Automated PageSpeed mobile audit: Accessibility 100/100, Best Practices 100/100; only missing-source-maps informational diagnostic. Not a full manual accessibility certification.
- Browser surface exposes no viewport resizing. A local responsive QA harness was blocked by browser URL policy and not pursued via an alternate route. No manual mobile/tablet screenshot or visual pass is claimed.
- Existing wider launch backlog (actual entitlement/package verification, checkout/delivery/activation, conversion tracking and user approval) remains.

Sources: before.blocks.html, preview.blocks.html, icons/*.svg, icon-media.json.
