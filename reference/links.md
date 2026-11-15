# How links behave

## Demo links hide themselves on stores without the demo data

The demo templates link to collections, pages and the blog with Shopify resource links (`shopify://collections/puddle-season`, `shopify://pages/size-guide`). In the editor they appear as picked resources, and Shopify adds the language prefix for translated storefronts.

When the linked collection, page or blog **does not exist on your store**, Pipsy prints no link and **hides the button, tile link or chip** that uses it, instead of sending shoppers to a "page not found". This applies to the mega panel strip, hero buttons and tiles, the forecast button, word swap buttons, height tiles, plan chips, FAQ answer links, content buttons, topic tiles and the About bands.

To show such a link, either create the collection or page with the same handle, or pick another link in the editor.

These always pass through unchanged: `/collections/all`, `/collections/vendors`, `/collections/types`, product links, external URLs, and any other store route.

{% hint style="info" %}
If a demo button seems to be missing on your store, this is the reason. Re-pick its link.
{% endhint %}

## Links with an anchor

A link to a spot on a page, such as `/pages/faqs#faq-swaps`, is stored as a typed path, because Shopify drops the `#anchor` part from `shopify://` links. The demo uses these anchors:

| Link | Jumps to |
| --- | --- |
| `/pages/faqs#faq-swaps` | FAQ group with Anchor ID `faq-swaps` |
| `/pages/faqs#faq-care` | FAQ group with Anchor ID `faq-care` |
| `/pages/about-us#made` | About band with Anchor ID `made` |

For an anchor to work, the target section or block needs the same **Anchor ID** (FAQ hub > Question group, About > Colour band, Help accordion, Questions with card). If your page handle is different, edit the link path.
