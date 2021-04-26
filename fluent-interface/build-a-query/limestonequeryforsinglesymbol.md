# LimestoneQueryForSingleSymbol

[limestone-api](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/README.md) / [Exports](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/modules.md) / LimestoneQueryForSingleSymbol

## Class: LimestoneQueryForSingleSymbol

### Hierarchy

* [_LimestoneQueryForSingleOrSeveralSymbols_](limestonequeryforsingleorseveralsymbols.md)

  ↳ **LimestoneQueryForSingleSymbol**

### Table of contents

#### Constructors

* [constructor](limestonequeryforsinglesymbol.md#constructor)

#### Properties

* [params](limestonequeryforsinglesymbol.md#params)

#### Methods

* [atDate](limestonequeryforsinglesymbol.md#atdate)
* [forLastDays](limestonequeryforsinglesymbol.md#forlastdays)
* [forLastHours](limestonequeryforsinglesymbol.md#forlasthours)
* [fromDate](limestonequeryforsinglesymbol.md#fromdate)
* [getExecutableQuery](limestonequeryforsinglesymbol.md#getexecutablequery)
* [hoursAgo](limestonequeryforsinglesymbol.md#hoursago)
* [latest](limestonequeryforsinglesymbol.md#latest)
* [toDate](limestonequeryforsinglesymbol.md#todate)

### Constructors

#### constructor

+ **new LimestoneQueryForSingleSymbol**\(`params`: QueryParams\): [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `params` | QueryParams |

**Returns:** [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

Overrides: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:102](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L102)

### Properties

#### params

• `Protected` **params**: QueryParams

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md).[params](limestonequeryforsingleorseveralsymbols.md#params)

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

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:97](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L97)

#### forLastDays

▸ **forLastDays**\(`daysCount`: _number_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price for the last few days

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `daysCount` | _number_ | Number of days in the time range |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Defined in: [limestone-query.ts:154](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L154)

#### forLastHours

▸ **forLastHours**\(`hoursCount`: _number_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price for the last few hours

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `hoursCount` | _number_ | Number of hours in the time range |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Defined in: [limestone-query.ts:139](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L139)

#### fromDate

▸ **fromDate**\(`date`: ConvertableToDate\): [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

Configures query to fetch the price in a time range. It is important to use fromDate with toDate query methods

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `date` | ConvertableToDate | Start date/time for the time range |

**Returns:** [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

query object

Defined in: [limestone-query.ts:113](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L113)

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

▸ **hoursAgo**\(`hoursCount`: _number_\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price for X hours ago.

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `hoursCount` | _number_ | Number of hours ago |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

#### latest

▸ **latest**\(\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the latest price/prices It doesn't support any params

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)

#### toDate

▸ **toDate**\(`date`: ConvertableToDate\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Configures query to fetch the price in a time range. toDate method should go after the fromDate

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `date` | ConvertableToDate | End date/time for the time range |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

query object

Defined in: [limestone-query.ts:126](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L126)

