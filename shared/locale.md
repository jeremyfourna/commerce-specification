# Locale

A **locale** is an identifier to a language such as _fr_ for French, _en_ for English.
You can append a country code to define a locale specific to this country such as _fr-FR_ for French in France, _en-US_ for English in the USA, _en-GB_ for English in the UK.

You can define translations for a product for multiple locale like _fr_, _fr-CH_, _en_.

## Fall-back Locale

You can use a fall-back logic between locales. If you want to build content for the locale _fr-CH_, you can search for any content defined in this locale and if it missing, look for some content defined in the locale _fr_.


## Relationships with other entities

| Entity | Relationship | Entity |
| --- |:--------:| --- |
| Locale | 1 - N | [Localized Product] |
| Locale | N - 1 | Fall-back Locale |



[Localized Product]: ../product-information-management/localised-product.md