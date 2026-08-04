# Shopify Upload Assets

Generated from the Johar matched upload package.

- Matched products prepared: 367
- Matched image files hosted in this repo: 1116
- Product-image placements in Shopify CSV: 1137
- Remaining products without matched new images: 475

Use `shopify_products_matched_only_GITHUB_IMAGE_URLS_PRODUCT_FIRST.csv` for Shopify re-imports. It keeps the same 367 matched products, but moves clean product photos ahead of lifestyle/model photos wherever a product image is available.

The original generated import remains as `shopify_products_matched_only_GITHUB_IMAGE_URLS.csv`. Both files point to raw GitHub URLs under `shopify_upload/matched_images/`.

Deletion note: Shopify's standard product CSV import does not delete existing products. Delete current Shopify products separately only after confirming the backup export is safe.
