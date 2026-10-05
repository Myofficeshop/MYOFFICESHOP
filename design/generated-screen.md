# Generated Screen: A4 Copier Paper to eMAG

## Screen job
Help a Romanian office buyer find the A4 copier-paper offer and continue to its eMAG listing, where the buyer can verify the current product details and purchase.

## User moment
- **Before:** The buyer needs copier paper and arrives on MYOFFICESHOP.
- **After:** The buyer opens the linked eMAG page and checks the current listing before ordering.

## Implementation
Implemented in the root `index.html` as a single responsive landing screen. The offer card names the category, clearly labels eMAG as the purchase destination, and places a short listing-verification note beside the outbound action. A three-step strip explains the product loop without adding another purchase path.

The existing Archivo typeface, palette, content width and type scale are retained. No product image, price, stock level, package quantity, delivery promise, contact detail or on-site checkout is shown.

## Data boundary
The existing repository supplied an eMAG URL and the broad A4 copier-paper category. The URL and the exact product/listing match have not been independently verified as current. The screen therefore directs the user to verify the offer in the listing; the destination must be checked before production release. The course presentation was not present in the repository or referenced conversation attachments during this implementation.

## Refused mechanic
No on-site cart or checkout was added. The single primary action leaves MYOFFICESHOP for eMAG, matching the current sales path recorded in `day-one.md` and `product-loop.md`.
