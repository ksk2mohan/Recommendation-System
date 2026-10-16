# Manual acceptance tests

1. Open `website/index.html`: landing page and product cards should appear.
2. Search `tomato`: only matching product(s) appear.
3. Click Vegetables: list is filtered; click All to restore.
4. Select Price: low to high: visible prices ascend.
5. Add Tomato: cart count increases and onion recommendation appears if pop-ups enabled.
6. Click pop-up Add to basket: suggested item is added and cart opens.
7. Change quantities in cart: totals and counts update; decrement to zero removes product.
8. Move budget slider: budget label and remaining/over-budget status update.
9. Choose Sambar and Build my basket: missing ingredients are added once.
10. Disable Smart pop-ups and add products: no contextual pop-up should appear.
11. Reload page: cart, budget and pop-up preference persist in the same browser.
12. Test at mobile width: product grid, search and cart should remain usable.
13. Click checkout: explicit demo-only notice appears; no real payment occurs.
