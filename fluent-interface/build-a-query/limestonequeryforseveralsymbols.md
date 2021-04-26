[limestone-api](../README.md) / [Exports](../modules.md) / LimestoneQueryForSeveralSymbols

# Class: LimestoneQueryForSeveralSymbols

## Hierarchy

* [*LimestoneQueryForSingleOrSeveralSymbols*](limestonequeryforsingleorseveralsymbols.md)<{ [symbol: string]: PriceData;  }\>

  ↳ **LimestoneQueryForSeveralSymbols**

## Table of contents

### Constructors

- [constructor](limestonequeryforseveralsymbols.md#constructor)

### Properties

- [params](limestonequeryforseveralsymbols.md#params)

### Methods

- [atDate](limestonequeryforseveralsymbols.md#atdate)
- [getExecutableQuery](limestonequeryforseveralsymbols.md#getexecutablequery)
- [hoursAgo](limestonequeryforseveralsymbols.md#hoursago)
- [latest](limestonequeryforseveralsymbols.md#latest)

## Constructors

### constructor

\+ **new LimestoneQueryForSeveralSymbols**(`params`: QueryParams): [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

#### Parameters:

| Name | Type |
| :------ | :------ |
| `params` | QueryParams |

**Returns:** [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

Overrides: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:166](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L166)

## Properties

### params

• `Protected` **params**: QueryParams

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md).[params](limestonequeryforsingleorseveralsymbols.md#params)

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

## Methods

### atDate

▸ **atDate**(`date`: ConvertableToDate): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

Configures query to fetch the price for a specific date.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `date` | ConvertableToDate | Date for the historical price (date \| timestamp \| string) |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:97](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L97)

___

### getExecutableQuery

▸ `Protected`**getExecutableQuery**<T\>(`update`: *any*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<T\>

#### Type parameters:

| Name |
| :------ |
| `T` |

#### Parameters:

| Name | Type |
| :------ | :------ |
| `update` | *any* |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<T\>

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:65](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L65)

___

### hoursAgo

▸ **hoursAgo**(`hoursCount`: *number*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

Configures query to fetch the price for X hours ago.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `hoursCount` | *number* | Number of hours ago |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

___

### latest

▸ **latest**(): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

Configures query to fetch the latest price/prices
It doesn't support any params

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<{ [symbol: string]: PriceData;  }\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)
