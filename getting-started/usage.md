---
description: Limestone api usage
---

# Usage

First, you need to import limestone module

{% tabs %}
{% tab title="Node.js require" %}
```javascript
// Using Node.js `require()`
const limestone = require('limestone-api');
```
{% endtab %}

{% tab title="ES6 import" %}
```javascript
// Using ES6 imports
import limestone from 'limestone-api';
```
{% endtab %}
{% endtabs %}

Then you can fetch the prices with just a single line of code

```javascript
const price = await limestone.getPrice("AR");

console.log(price.value); // latest price value for AR token (in USD)
console.log(price.timestamp); // the exact timestamp of the price
```

See more examples in the documentation of the following methods:

* [getPrice](https://docs.limestone.finance/methods/getprice)
* [getHistoricalPrice](https://docs.limestone.finance/methods/gethistoricalprice)
* [getAllPrices](https://docs.limestone.finance/methods/getallprices)

You can also check out docs for the [limestone fluent interface](https://docs.limestone.finance/fluent-interface/build-a-query), which makes the price fetching even simpler thanks to human readable syntax.

