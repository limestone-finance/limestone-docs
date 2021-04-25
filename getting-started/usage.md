---
description: Limestone-api usage
---

# Usage

```javascript
// Using Node.js `require()`
const limestone = require('limestone-api');

// Using ES6 imports
import limestone from 'limestone-api';
```

Then you can fetch the prices with just a single line of code

```javascript
const price = await limestone.getPrice("AR");

console.log(price.value); // latest price value for AR token (in USD)
console.log(price.timestamp); // the exact timestamp of the price
```

To read more advanced examples, visit the methods documentation:

* [getPrice](https://docs.limestone.finance/methods/getprice)
* [getHistoricalPrice](https://docs.limestone.finance/methods/gethistoricalprice)
* [getAllPrices](https://docs.limestone.finance/methods/getallprices)

You can also check out docs for the [limestone fluent interface](https://docs.limestone.finance/fluent-interface/build-a-query), which makes the price fetching even simpler for most popular query use cases.

