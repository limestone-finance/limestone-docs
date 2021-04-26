[limestone-api](../README.md) / [Exports](../modules.md) / LimestoneQuery

# Class: LimestoneQuery

## Table of contents

### Constructors

- [constructor](limestonequery.md#constructor)

### Properties

- [params](limestonequery.md#params)

### Methods

- [allSymbols](limestonequery.md#allsymbols)
- [symbol](limestonequery.md#symbol)
- [symbols](limestonequery.md#symbols)

## Constructors

### constructor

\+ **new LimestoneQuery**(`params?`: {}): [*LimestoneQuery*](limestonequery.md)

#### Parameters:

| Name | Type | Default value |
| :------ | :------ | :------ |
| `params` | *object* | {} |

**Returns:** [*LimestoneQuery*](limestonequery.md)

Defined in: [limestone-query.ts:15](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L15)

## Properties

### params

• `Protected` **params**: QueryParams

Defined in: [limestone-query.ts:15](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L15)

## Methods

### allSymbols

▸ **allSymbols**(): [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

Configures query to fetch prices for all supported tokens.
It doesn't support any params

**Returns:** [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

query object

Defined in: [limestone-query.ts:49](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L49)

___

### symbol

▸ **symbol**(`symbol`: *string*): [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

Sets a token symbol to fetch

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `symbol` | *string* | Token symbol string |

**Returns:** [*LimestoneQueryForSingleSymbol*](limestonequeryforsinglesymbol.md)

query object

Defined in: [limestone-query.ts:29](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L29)

___

### symbols

▸ **symbols**(`symbols`: *string*[]): [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

Sets token symbols to fetch

#### Parameters:

| Name | Type | Description |
| :------ | :------ | :------ |
| `symbols` | *string*[] | Array of strings (token symbols) |

**Returns:** [*LimestoneQueryForSeveralSymbols*](limestonequeryforseveralsymbols.md)

query object

Defined in: [limestone-query.ts:40](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L40)
