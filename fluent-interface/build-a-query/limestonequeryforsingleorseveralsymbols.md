# LimestoneQueryForSingleOrSeveralSymbols

[limestone-api](https://github.com/limestone-finance/limestone-docs/tree/1c10aa6c007b11023008acedb55dcd94affec715/fluent-interface/README.md) / [Exports](https://github.com/limestone-finance/limestone-docs/tree/1c10aa6c007b11023008acedb55dcd94affec715/fluent-interface/modules.md) / LimestoneQueryForSingleOrSeveralSymbols

## Class: LimestoneQueryForSingleOrSeveralSymbols

### Type parameters

| Name |
| :--- |
| `QueryResultType` |

### Hierarchy

* **LimestoneQueryForSingleOrSeveralSymbols**

  ↳ [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

  ↳ [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

### Table of contents

#### Constructors

* [constructor](limestonequeryforsingleorseveralsymbols.md#constructor)

#### Properties

* [params](limestonequeryforsingleorseveralsymbols.md#params)

#### Methods

* [atDate](limestonequeryforsingleorseveralsymbols.md#atdate)
* [getExecutableQuery](limestonequeryforsingleorseveralsymbols.md#getexecutablequery)
* [hoursAgo](limestonequeryforsingleorseveralsymbols.md#hoursago)
* [latest](limestonequeryforsingleorseveralsymbols.md#latest)

### Constructors

#### constructor

+ **new LimestoneQueryForSingleOrSeveralSymbols**\(`params`: QueryParams\): [_LimestoneQueryForSingleOrSeveralSymbols_](limestonequeryforsingleorseveralsymbols.md)

**Type parameters:**

| Name |
| :--- |
| `QueryResultType` |

**Parameters:**

| Name | Type |
| :--- | :--- |
| `params` | QueryParams |

**Returns:** [_LimestoneQueryForSingleOrSeveralSymbols_](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

### Properties

#### params

• `Protected` **params**: QueryParams

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

### Methods

#### atDate

▸ **atDate**\(`date`: ConvertableToDate\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price for a specific date.

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `date` | ConvertableToDate | Date for the historical price \(date \| timestamp \| string\) |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

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

Defined in: [limestone-query.ts:65](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L65)

#### hoursAgo

▸ **hoursAgo**\(`hoursCount`: _number_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price for X hours ago.

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `hoursCount` | _number_ | Number of hours ago |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

#### latest

▸ **latest**\(\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the latest price/prices It doesn't support any params

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)

