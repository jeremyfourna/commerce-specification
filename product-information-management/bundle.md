# Bundle

A **bundle** is a [product] that contains a group of [products] that are sold together.

You can see the **bundle** as a [product] type.

## Bundle types

You can find multiple types of **bundles**:

* A single [product] that acts as **bundle**
* Multiple [products] tied together as a **bundle**

### Single product as bundle

You might have see in video game shop a **bundle** for a game console plus a video game, sold together in a single package. When the **bundle** is sold, your system record the sale of 1 product, the **bundle** and not the sale of game console and a video game.

### Multiple products as bundle

The main difference here compared to the _Single product as bundle_ is that here, the stock of **bundle** depends on the stock of the underlying products that compose it. When the **bundle** is sold, your system record the sale of 2 products, the sale of game console and a video game.

## Bundle price

The [price] of a **bundle** can be defined for the whole **bundle** or can be the sum of the price of the products contained inside the **bundle** (with or without a discount to make it more interesting).

If the [price] of the **bundle** is the sum of the products contained inside it, it can be calculated dynamically whenever the price of any of the products change.


## Relationships with other entities

| Entity | Relationship | Entity |
| --- |:--------:| --- |
| Bundle | N - N | [Product] |
| Bundle | 1 - N | [Localization] |



[Localization]: ../localization.md
[price]: ../price-management/price.md
[product]: ../product-information-management/product.md
[products]: ../product-information-management/product.md
[Product]: ../product-information-management/product.md
