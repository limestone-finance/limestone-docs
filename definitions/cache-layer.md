---
description: >-
  A cache layer is a web service, that caches prices data signed by data
  providers.
---

# Cache layer

By default, Limestone API fetches data from the Limestone cache layer. It works faster than fetching directly from the Arweave Blockchain. This approach maintains data integrity thanks to built-in [signature verification](signature-verification.md).

### Fetching prices from Arweave Blockchain

We strongly recommend using the default fetching mechanism. However, anyone may fetch data directly from the  Arweave by initialising a new `LimestoneApi` client and setting `useCache` option to `false`.

```javascript
const limestoneArweaveClient = new limestone.LimestoneApi({
  useCache: false,
});

const price = await limestoneArweaveClient.getPrice("AR");

console.log(price.value); // AR price value fetched directly from Arweave
```

