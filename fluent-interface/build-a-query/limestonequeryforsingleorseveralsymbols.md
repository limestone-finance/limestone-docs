[limestone-api](../README.md) / [Exports](../modules.md) / LimestoneQueryForSingleOrSeveralSymbols

# Class: LimestoneQueryForSingleOrSeveralSymbols<QueryResultType\>

## Type parameters

| Name |
| :------ |
| `QueryResultType` |

## Hierarchy

* **LimestoneQueryForSingleOrSeveralSymbols**

  ↳ [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

  ↳ [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

## Table of contents

### Constructors

- [constructor](limestonequeryforsingleorseveralsymbols.md#constructor)

### Properties

- [params](limestonequeryforsingleorseveralsymbols.md#params)

### Methods

- [atDate](limestonequeryforsingleorseveralsymbols.md#atdate)
- [getExecutableQuery](limestonequeryforsingleorseveralsymbols.md#getexecutablequery)
- [hoursAgo](limestonequeryforsingleorseveralsymbols.md#hoursago)
- [latest](limestonequeryforsingleorseveralsymbols.md#latest)

## Constructors

### constructor

\+ **new LimestoneQueryForSingleOrSeveralSymbols**<QueryResultType\>(`params`: QueryParams): [*LimestoneQueryForSingleOrSeveralSymbols*](limestonequeryforsingleorseveralsymbols.md)<QueryResultType\>

#### Type parameters:

| Name |
| :------ |
| `QueryResultType` |

#### Parameters:

| Name | Type |
| :------ | :------ |
| `params` | QueryParams |

**Returns:** [*LimestoneQueryForSingleOrSeveralSymbols*](limestonequeryforsingleorseveralsymbols.md)<QueryResultType\>

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

## Properties

### params

• `Protected` **params**: QueryParams

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

## Methods

### atDate

▸ **atDate**(`date`: ConvertableToDate): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

Configures query to fetch the price for a specific date.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `date` | ConvertableToDate | Date for the historical price (date \| timestamp \| string) |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

query object

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

Defined in: [limestone-query.ts:65](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L65)

___

### hoursAgo

▸ **hoursAgo**(`hoursCount`: *number*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

Configures query to fetch the price for X hours ago.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `hoursCount` | *number* | Number of hours ago |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

query object

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

___

### latest

▸ **latest**(): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

Configures query to fetch the latest price/prices
It doesn't support any params

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

query object

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)
