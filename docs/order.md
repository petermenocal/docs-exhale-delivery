# Order

> Allows a mechanism to submit orders programatically from LTH website to exhale admin tools.

## Request

_Method:_ `POST`

_Headers_: `Content-Type: application/json`

_Example URI_ `https://exhalebrands.com/api/delivery`

### Body

```
{
	cart: [
		{
			product: {
				id: "ddd60b9a-a83a-4479-a17d-ff0fd8329027",
				name: "Bubba Skunk (1g) - Effex"
			}
		}
	],
	customer: "cap@avengers.com",
	u: {
		firstName: "Steve",
		lastName: "Rogers",
		phone: "7025555555"
	},
	notes: "Gate code is #5555",
	address: "5775 Polaris Ave.',
	postalCode: "89101,
	method: "delivery"
}
```
