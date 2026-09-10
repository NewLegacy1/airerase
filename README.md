# AERASE site

The existing static Sites setup and first-order route are retained. The original section sequence is adapted for body hair removal, using the existing gallery, accordion, navigation drawer, modal, marquee, carousel and product-selection hooks.

## Editing
- `dist/index.html`: page content, metadata, product gallery, FAQs and footer.
- `dist/pages/first-order/index.html`: matching first-order route. Keep this synchronized with the root page.
- `dist/template.css`: AERASE palette, typography and responsive presentation.
- `dist/template.js`: existing standalone interaction flow adapted for AERASE quantities and usage guidance.
- `dist/store-config.js`: prices, currency and checkout links per quantity. Prices are totals for the selected option. Supply checkout URLs that already select the correct quantity.
- `dist/assets/aerase/`: supplied product artwork, copied without altering bottle shape or label design. The header uses an editorial serif wordmark; the supplied raster logo is retained as an optional asset.
- `dist/assets/aerase-base.css`: retained utility/component stylesheet with legacy brand selectors renamed.

## Details still needed
- Approved price, currency and checkout URL for each quantity; confirm whether a two-bottle option is offered.
- Full final label, ingredients, patch-test instructions, maximum contact time and approved removal/rinsing instructions. The owner described waiting ten minutes, but the page defers to final pack directions rather than publishing unverified formula timing.
- Shipping, returns, contact details, terms and privacy policy.
- Newsletter service and consent terms. Signup remains disabled and collects no information.
- Genuine customer reviews with permission to publish. No invented testimonials or ratings appear; the original review carousel is adapted into routine cards.

Ordering remains disabled until a valid price, currency and HTTPS checkout URL exist for the selected quantity. No payment or personal data is collected by this static site. Existing hosting access remains private.

## Validation
Both routes, local assets, navigation anchors, accordion targets and JavaScript syntax checked. Browser visual QA was not requested. The optional WebMCP configure_product tool is adapted to quantities; a supported live WebMCP validation context was not available.
