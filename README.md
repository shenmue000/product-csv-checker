# Free Product CSV Checker

**Use it here: https://shenmue000.github.io/product-csv-checker/**

Checks a Shopify, WooCommerce or other store's product CSV for:
- possible duplicate products (sizes, colours, refills and multi-packs are recognised as different products)
- the same SKU or barcode on more than one row
- barcodes damaged by a spreadsheet (scientific notation, lost leading zeros, trailing ".0") or failing the check digit
- prices with currency symbols, separators or errors, and missing titles or prices
- brands or product types spelled more than one way, and hidden extra spaces

Your file never leaves your computer: the whole check runs in your browser from a single `index.html`, with no uploads, analytics or outside scripts. It only reads the file and never changes it.

Results are automatic suggestions, so please check them before changing your store. Need it fixed for you? See the [clean-up service on Upwork](https://www.upwork.com/services/product/admin-customer-support-clean-your-shopify-or-woocommerce-product-csv-and-find-duplicate-products-2123377446444905038).
