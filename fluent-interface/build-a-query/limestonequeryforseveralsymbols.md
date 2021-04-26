# LimestoneQueryForSeveralSymbols

[limestone-api](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/README.md) / [Exports](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/modules.md) / LimestoneQueryForSeveralSymbols

## Class: LimestoneQueryForSeveralSymbols

### Hierarchy

* [_LimestoneQueryForSingleOrSeveralSymbols_](limestonequeryforsingleorseveralsymbols.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

  ↳ **LimestoneQueryForSeveralSymbols**

### Table of contents

#### Constructors

* [constructor](limestonequeryforseveralsymbols.md#constructor)

#### Properties

* [params](limestonequeryforseveralsymbols.md#params)

#### Methods

* [atDate](limestonequeryforseveralsymbols.md#atdate)
* [getExecutableQuery](limestonequeryforseveralsymbols.md#getexecutablequery)
* [hoursAgo](limestonequeryforseveralsymbols.md#hoursago)
* [latest](limestonequeryforseveralsymbols.md#latest)

### Constructors

#### constructor

+ **new LimestoneQueryForSeveralSymbols**\(`params`: QueryParams\): [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `params` | QueryParams |

**Returns:** [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

Overrides: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:166](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L166)

### Properties

#### params

• `Protected` **params**: QueryParams

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md).[params](limestonequeryforsingleorseveralsymbols.md#params)

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

### Methods

#### atDate

▸ **atDate**\(`date`: ConvertableToDate\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

Configures query to fetch the price for a specific date.

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `date` | ConvertableToDate | Date for the historical price \(date \| timestamp \| string\) |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:97](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L97)

#### getExecutableQuery

▸ `Protected`**getExecutableQuery**\(`update`: _any_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

**Type parameters:**

| Name |
| :--- |
| `T` |

**Parameters:**

| Name | Type |
| :--- | :--- |
| `update` | _any_ |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:65](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L65)

#### hoursAgo

▸ **hoursAgo**\(`hoursCount`: _number_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

Configures query to fetch the price for X hours ago.

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `hoursCount` | _number_ | Number of hours ago |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

#### latest

▸ **latest**\(\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

Configures query to fetch the latest price/prices It doesn't support any params

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)&lt;{ \[symbol: string\]: PriceData; }&gt;

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)

