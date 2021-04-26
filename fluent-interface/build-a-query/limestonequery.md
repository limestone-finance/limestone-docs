# LimestoneQuery

[limestone-api](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/README.md) / [Exports](https://github.com/limestone-finance/limestone-docs/tree/e56f4e97ffe8229804276eb19e84c082fe4e179e/fluent-interface/modules.md) / LimestoneQuery

## Class: LimestoneQuery

### Table of contents

#### Constructors

* [constructor](limestonequery.md#constructor)

#### Properties

* [params](limestonequery.md#params)

#### Methods

* [allSymbols](limestonequery.md#allsymbols)
* [symbol](limestonequery.md#symbol)
* [symbols](limestonequery.md#symbols)

### Constructors

#### constructor

+ **new LimestoneQuery**\(`params?`: {}\): [_LimestoneQuery_](limestonequery.md)

**Parameters:**

| Name | Type | Default value |
| :--- | :--- | :--- |
| `params` | _object_ | {} |

**Returns:** [_LimestoneQuery_](limestonequery.md)

Defined in: [limestone-query.ts:15](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L15)

### Properties

#### params

• `Protected` **params**: QueryParams

Defined in: [limestone-query.ts:15](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L15)

### Methods

#### allSymbols

▸ **allSymbols**\(\): [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

Configures query to fetch prices for all supported tokens. It doesn't support any params

**Returns:** [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

query object

Defined in: [limestone-query.ts:49](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L49)

#### symbol

▸ **symbol**\(`symbol`: _string_\): [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

Sets a token symbol to fetch

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `symbol` | _string_ | Token symbol string |

**Returns:** [_LimestoneQueryForSingleSymbol_](limestonequeryforsinglesymbol.md)

query object

Defined in: [limestone-query.ts:29](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L29)

#### symbols

▸ **symbols**\(`symbols`: _string_\[\]\): [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

Sets token symbols to fetch

**Parameters:**

| Name | Type | Description |
| :--- | :--- | :--- |
| `symbols` | _string_\[\] | Array of strings \(token symbols\) |

**Returns:** [_LimestoneQueryForSeveralSymbols_](limestonequeryforseveralsymbols.md)

query object

Defined in: [limestone-query.ts:40](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L40)

