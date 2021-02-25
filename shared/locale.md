# Locale

A **locale** is an identifier to a language such as _fr_ for french, _en_ for english.
You can happen a country code to define a locale specific to this country such as _fr-FR_ for french in France, _en-US_ for english in the USA, _en-GB_ for english in the UK.

You can define translations for a product for multiple locale like _fr_, _fr-CH_, _en_.

## Fallback Locale

You can use a fallback logic between locales. If you want to build content for the locale _fr-CH_, you can search for any content defined in this locale and if it missing, look for some content defined in the locale _fr_.


## Relationships with other entities

| Entity | Relationship | Entity |
| --- |:--------:| --- |
| Locale | 1 - N | [Localised Product] |
| Locale | N - 1 | Fallback Locale |



[Localised Product]: ../product-information-management/localised-product.md