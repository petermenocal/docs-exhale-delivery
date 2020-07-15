# Products

> Provides a live snapshot of sellable inventory from Green Bits.

## Request

_Method:_ `GET`

_Example URI_ `https://exhalebrands.com/api/allProducts`

## Response

```
{
    "products": [
        {
            "id": "4678c18a-5a5f-49a2-90ad-1908312e6235",
            "active": false,
            "category_id": "0c006283-1cf1-4531-89cb-c0e64c7260e9",
            "collect_excise_tax": true,
            "id": "7f5b9dc6-962b-45d7-a749-fb1462096bad",
            "latest_sku": "3156156207772758",
            "name": "Girl Scout Cookies 3.5g",
            "pricing_type": 0,
            "product_type_id": "24516e82-e9d6-4695-890f-fa8b312b4163",
            "brand_id": "28ac6528-7c0d-48fc-a033-c403d636086f",
            "strain_id": "6fe59013-8b12-41a5-8a69-aa80896cad45",
            "quantity": 10,
            "sell_price": 2500,
            "vendor": "Blewett Pass Farms",
            "weight": "3.5",
            "tags": ['expiring', 'on sale'],
            "description": "Girl Scout Cookies, or GSC, is an OG Kush and Durban Poison hybrid cross whose reputation grew too large to stay within the borders of its California homeland",
            "internal_notes": "3/7/15: We need to order more of these. -AK",
            "test_results_thc": "0.1",
            "test_results_cbd": "0.003",
            "flower_type": 3,
            "metadata": {
              "external_id": "5"
            }
        }
    ],

}
```
