# Translations

Pipsy ships with five storefront languages and the same five languages for the theme editor:

| Language | Storefront file | Editor file |
| --- | --- | --- |
| English (default) | `locales/en.default.json` | `locales/en.default.schema.json` |
| German | `locales/de.json` | `locales/de.schema.json` |
| Spanish | `locales/es.json` | `locales/es.schema.json` |
| French | `locales/fr.json` | `locales/fr.schema.json` |
| Italian | `locales/it.json` | `locales/it.schema.json` |

* **Storefront texts** are the fixed words of the theme: buttons ("Add to bag", "Write a review"), labels, messages, the 404 page, cart and account pages.
* **Editor texts** are the setting labels you see in the theme editor; Shopify picks them from your admin language.
* **Section texts** you type in the editor (headings, button labels, demo copy) are settings, not translation files. Translate them per language with Shopify's **Translate & Adapt** app.

## Change a default text

1. Go to **Online Store > Themes**.
2. Next to Pipsy, click **…** > **Edit default theme content**.
3. Choose the language at the top, search for the text (for example "Add to bag") and type your version.
4. Click **Save**.

Your edits are kept separately from the theme files, so they survive theme setting changes.

## Sell in more languages

1. Add the language in **Settings > Languages** and publish it.
2. Use **Translate & Adapt** for product, collection, page and section texts.
3. Turn on the language selector in the Header, Footer or Announcement bar so shoppers can switch.

{% hint style="warning" %}
The German, Spanish, French and Italian files have not all been reviewed by native speakers. Read through the texts that matter for your store before launching in those languages.
{% endhint %}
