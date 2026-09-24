<img src="icon.png" alt="" width="64" height="64">

# TCG MSRP

A browser extension that shows the official MSRP next to trading card game products in online 
retailer search results, so you can see at a glance how a listing compares to retail price.

Currently supports:

- Pokémon TCG products, using list prices from Pokémon Center
- Amazon.com

This repository hosts the price catalog the extension uses.

## catalog.json

[`catalog.json`](catalog.json) is the list of products and prices. Example:

```json
{
  "schema": 1,
  "exportedAt": "2026-09-23T19:26:07.166Z",
  "products": [
    {
      "sku": "100-10326",
      "name": "Pokémon TCG: Scarlet & Violet-Journey Together Sleeved Booster Pack (10 Cards)",
      "msrp": 4.49,
      "seenAt": "2026-09-23T19:26:07.166Z"
    }
  ]
}
```

- `exportedAt`: when the catalog was last updated.
- `seenAt`: when the product was last listed by the official store. Products that are no longer
  listed keep their last known price.

## Privacy

The extension does not collect personal data nor analytics.

## Disclaimer

TCG MSRP is an unofficial, independent project. It is not affiliated with, endorsed by or sponsored
by The Pokémon Company, Nintendo, Creatures, GAME FREAK, Pokémon Center or Amazon. All trademarks
belong to their respective owners.

Prices are provided for reference only and may be out of date. Check the retailer before any purchases.
