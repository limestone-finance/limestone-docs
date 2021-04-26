[limestone-api](../README.md) / [Exports](../modules.md) / LimestoneQueryForSingleSymbol

# Class: LimestoneQueryForSingleSymbol

## Hierarchy

* [*LimestoneQueryForSingleOrSeveralSymbols*](limestonequeryforsingleorseveralsymbols.md)<PriceData\>

  ↳ **LimestoneQueryForSingleSymbol**

## Table of contents

### Constructors

- [constructor](limestonequeryforsinglesymbol.md#constructor)

### Properties

- [params](limestonequeryforsinglesymbol.md#params)

### Methods

- [atDate](limestonequeryforsinglesymbol.md#atdate)
- [forLastDays](limestonequeryforsinglesymbol.md#forlastdays)
- [forLastHours](limestonequeryforsinglesymbol.md#forlasthours)
- [fromDate](limestonequeryforsinglesymbol.md#fromdate)
- [getExecutableQuery](limestonequeryforsinglesymbol.md#getexecutablequery)
- [hoursAgo](limestonequeryforsinglesymbol.md#hoursago)
- [latest](limestonequeryforsinglesymbol.md#latest)
- [toDate](limestonequeryforsinglesymbol.md#todate)

## Constructors

### constructor

\+ **new LimestoneQueryForSingleSymbol**(`params`: QueryParams): [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

#### Parameters:

| Name | Type |
| :------ | :------ |
| `params` | QueryParams |

**Returns:** [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

Overrides: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:102](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L102)

## Properties

### params

• `Protected` **params**: QueryParams

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md).[params](limestonequeryforsingleorseveralsymbols.md#params)

Defined in: [limestone-query.ts:58](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L58)

## Methods

### atDate

▸ **atDate**(`date`: ConvertableToDate): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

Configures query to fetch the price for a specific date.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `date` | ConvertableToDate | Date for the historical price (date \| timestamp \| string) |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:97](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L97)

___

### forLastDays

▸ **forLastDays**(`daysCount`: *number*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

Configures query to fetch the price for the last few days

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `daysCount` | *number* | Number of days in the time range |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

query object

Defined in: [limestone-query.ts:154](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L154)

___

### forLastHours

▸ **forLastHours**(`hoursCount`: *number*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

Configures query to fetch the price for the last few hours

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `hoursCount` | *number* | Number of hours in the time range |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

query object

Defined in: [limestone-query.ts:139](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L139)

___

### fromDate

▸ **fromDate**(`date`: ConvertableToDate): [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

Configures query to fetch the price in a time range. It is important to use fromDate with toDate query methods

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `date` | ConvertableToDate | Start date/time for the time range |

**Returns:** [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

query object

Defined in: [limestone-query.ts:113](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L113)

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

▸ **hoursAgo**(`hoursCount`: *number*): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

Configures query to fetch the price for X hours ago.

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `hoursCount` | *number* | Number of hours ago |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:86](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L86)

___

### latest

▸ **latest**(): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

Configures query to fetch the latest price/prices
It doesn't support any params

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData\>

query object

Inherited from: [LimestoneQueryForSingleOrSeveralSymbols](limestonequeryforsingleorseveralsymbols.md)

Defined in: [limestone-query.ts:77](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L77)

___

### toDate

▸ **toDate**(`date`: ConvertableToDate): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

Configures query to fetch the price in a time range. toDate method should go after the fromDate

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `date` | ConvertableToDate | End date/time for the time range |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<PriceData[]\>

query object

Defined in: [limestone-query.ts:126](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L126)
