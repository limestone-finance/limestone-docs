---
description: query method is used to initialise a limestone query
---

# query

### Simple example

```javascript
const price = await limestone.query()
  .symbol("AR")
  .latest()
  .exec();

console.log(price.value); // latest price value for AR token (in USD)
console.log(price.timestamp); // the exact timestamp of the price
```

To learn more, visit [the Limestone Query page](../fluent-interface/build-a-query.md)

{% page-ref page="../fluent-interface/build-a-query.md" %}



