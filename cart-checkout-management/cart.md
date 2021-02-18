# Cart

A **cart** belongs to a [customer] or a [guest].

A **cart** can contain multiple [offer].


## Relationships with other entities

| Entity | Relationship | Entity |
| --- |:--------:| --- |
| Cart | N - 1 | [Customer] |
| Cart | N - 1 | [Guest] |
| Cart | N - N | [Offer] |


[customer]: ../customer-management/customer.md
[Customer]: ../customer-management/customer.md
[guest]: ../customer-management/guest.md
[Guest]: ../customer-management/guest.md
[offer]: ../offer-management/offer.md
[Offer]: ../offer-management/offer.md