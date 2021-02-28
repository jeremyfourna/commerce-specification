# Product

A **product** has a unique identifier (SKU for Stock Keeping Unit).

A **product** can be sold.

A **product** contains a mix of _cold_ or _hot_ data. _Cold_ data mean here, information that are not susceptible to change, like the product specification. _Hot_ data mean here, the opposite of _cold_ data, information that can change over time such as the customer rating, statistics.

A **product** can be part of multiple [meta products].


## Relationships with other entities

| Entity | Relationship | Entity |
| --- |:--------:| --- |
| Product | N - N | [Bundle] |
| Product | N - N | [Meta Product] |
| Product | 1 - N | [Localization] |


## Example

* Chocolate bar 70% cacao with hazelnuts in 100 grams package
* Chocolate bar 70% cacao with hazelnuts in 500 grams package
* Chocolate bar 70% cacao with salt in 100 grams package
* Chocolate bar 70% cacao with salt in 500 grams package
* Chocolate bar 85% cacao with hazelnuts in 100 grams package
* Chocolate bar 85% cacao without extra in 500 grams package
* Chocolate bar 90% cacao without extra in 100 grams package
* Chocolate bar 90% cacao without extra in 500 grams package



[Bundle]: ../bundle.md
[Localization]: ../localization.md
[meta products]: ../meta-product.md
[Meta Product]: ../meta-product.md
