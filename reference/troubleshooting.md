# FAQ and troubleshooting

### Sizes show no heights, or the size range badge is missing

* The product needs an option named **Size** (or the word for size in your storefront language).
* Age sizes must be written with an en dash (`2–3Y`, not `2-3Y`) and must match a `size_range` **Label** exactly.
* If you created `size_range` metaobjects, their definition needs **Storefront access**. While none exist, the [built-in table](../product-page/size-data.md#built-in-fallback-table) is used.

### The Size guide page shows a simple table instead of my chart

The tab shows its **Fallback table** until a `size_chart` metaobject with the handle set in the Size chart block exists and has storefront access.

### The Reviews band does not appear

The band is hidden on the storefront until it has a reviews app block or the product has ratings. Add the app's block to the **Product reviews** section. See [Product reviews](../product-page/reviews.md).

### Stars do not show on product cards

Turn on **Theme settings > Product tiles > Show product rating**. Stars only show for products with reviews: the app must write `reviews.rating` and `reviews.rating_count`.

### I see "4.6 / 5 from 128 reviews" but have no reviews

That is the editor-only preview score. Customers never see it.

### A button or tile link from the demo is missing

The link points to a collection or page your store does not have, so Pipsy hides it. Re-pick the link. See [How links behave](links.md).

### The logo does not show, or the header shows text

Upload your logo in **Theme settings > Logo**. Without a logo the header shows the **Wordmark** text from the Header section. The footer has its own logo setting.

### A top-level menu item opens a small dropdown instead of the mega panel

The **Menu item** of the Mega panel block must match the menu item title exactly. See [Header and mega menu](../header-footer/header-and-mega-menu.md#mega-panel-blocks).

### The set builder shows a saving but checkout charges the full price

The set builder only displays the saving. Create the matching automatic discount in **Discounts**.

### A home section (set builder or product pins) disappeared

Sections that need products hide when their products are missing or unavailable. Pick available products in the editor.

### Filters are missing on the collection page

Install the **Search & Discovery** app and add filters there. Check **Enable filtering** in the Product grid section.

### The Order tracking page has no order number form

Shopify themes cannot look up orders without an app. Add an order tracking app's block to the page. See [Order tracking](../content-pages/order-tracking.md).

### Pinned scrolling (forecast wardrobe, testimonials) does not move in the editor

Pinned scroll effects are off in the theme editor and for visitors with reduced motion. Preview the storefront to see them.

### Express checkout buttons do not show in the bag drawer

Turn on **Show accelerated buttons** in the Cart drawer section and set up an accelerated payment method (for example Shop Pay) in **Settings > Payments**.

### The footer sign-up card is missing on the home page

**Footer > Hide on the home page** is on by default, because the home page has its own Email signup section.

### A page uses the plain layout

Assign its template in the page's **Template** field in the admin. See [Creating content pages](../content-pages/creating-pages.md).
