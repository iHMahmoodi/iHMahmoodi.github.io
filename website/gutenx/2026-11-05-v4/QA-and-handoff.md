# GutenX v4 — Preview delivery / 2026-11-05

## Result
- Preview: https://ihmahmoodi.com/gutenx-preview-20261105/
- Preview page ID: 23830. Published only as a separate review URL; noindex,nofollow confirmed in rendered HTML; canonical points to original sales page.
- Original production page 22990 remains byte-for-byte unchanged against the captured source.
- GitHub issue: https://github.com/iHMahmoodi/iHMahmoodi.github.io/issues/2
- TickTick: https://ticktick.com/webapp/#p/6aa5669a8f0815166f6b04bf/tasks/6aec75c58f08b205a8c165b5
- Preview screenshot: https://ihmahmoodi.com/wp-content/uploads/2026/11/GutenX-v4-Preview-Final-20261105.webp

## Implemented
- Fresh hero, dedicated navigation/footer, clearer positioning based on Blocksy Pro and Gutenberg.
- Two verified current site screenshots; discarded a failed Cloudflare screenshot and replaced it with a verified current capture.
- Three original transparent soft ceramic/glass icons coordinated with NotionX/LyriX. WebP sizes: blocks 76,250 B; design 64,678 B; commerce 54,966 B.
- Six editable Persian capability demonstrations (design, headers, conditional content, menu, shop, editor), labelled as illustrative examples.
- Clear package scope, three-step start, existing $99 annual / one-site and 30m toman setup prices preserved.
- Existing variable annual renewal and 7-day refund with deduction for completed services preserved.
- Native Details FAQ, with readable dark summary typography.
- Removed unsupported synthetic speed metrics and the broken YarGasht live-demo link.
- Built solely from 377 native Core blocks: button, buttons, column, columns, details, group, heading, image, paragraph.
- No Custom HTML block, page style tag, page-specific CSS, global theme setting mutation, new plugin, or code snippet.

## Verification performed
- Real browser checks at 320, 390, 768, 1280 and 1440 CSS px.
- 320 px: document clientWidth=305 and scrollWidth=305 (15 px scrollbar); no element wider than content viewport.
- 390 px: clientWidth=375, scrollWidth=375.
- 768 px: clientWidth=753, scrollWidth=753.
- 1440 px: clientWidth=1425, scrollWidth=1425.
- Final native constraint wrapper change rechecked at 320 px; no overflow, all 9 images loaded, all fragment links resolve.
- All 9 images loaded successfully in the browser. No missing alt attributes. Decorative icons have empty alt because adjacent copy names the feature.
- Exactly one H1. Backend HTML audit reports no heading-level skip.
- Internal navigation tested; FAQ summary opens using Enter and becomes the focused SUMMARY.
- Licence-request link reached /contact/?gutenx=license-v4. This is a contact page with Telegram/Bale/email, not checkout or a form. Copy was corrected accordingly. Nothing was submitted.
- Final HTML HTTP 200, expected text present, no failed same-site assets in bounded asset audit, no mixed content.
- Title/description/robots/canonical verified in rendered HTML.
- Original page source equality checked after preview completion.
- Saved markup differs from generated input only by WordPress normalizing empty block attribute objects in comments.

## Limits / launch backlog
- The inherited theme resets focus outlines on SUMMARY (computed outline-style:none; no shadow), despite keyboard activation working. Native focus styling must be resolved before calling this a full accessibility pass.
- No full screen-reader, Firefox, Safari/WebKit, real-device or 200% browser-zoom test was performed.
- Native column breakpoint/reflow was inspected; a universal accessibility certification is not claimed.
- No Lighthouse/CWV performance numbers are claimed for this page. Nine loaded image instances use five unique WebP assets.
- Product deliverables/licence entitlements/update distribution/installation guide must be verified against actual package before launch.
- Automated checkout/payment/delivery/activation were not implemented or tested; current conversion path is an explicitly labelled request/contact path.
- Matomo conversion events/goals and demand/price validation remain before launch.
- YarGasht critical error remains an independent dependency before returning it to the live showcase.
- Original sales URL has NOT been replaced. User review of this preview precedes promotion.

## Tool limitations encountered
- MCPX handles staging, metadata, SEO, media uploads and auditing. Its update-content sanitizer rejected the new block source; the standard authenticated WordPress REST route saved it instead. Saved content was read back for comparison and the rendered result verified.
- The browser viewport override applies to the selected tab; the actual innerWidth was checked rather than assuming resize succeeded.
- Initial expiring preview query could serve the homepage through cache. Final review uses the stable separate noindex URL.
