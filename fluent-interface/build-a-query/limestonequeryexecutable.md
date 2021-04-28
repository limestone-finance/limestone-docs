# LimestoneQueryExecutable

[limestone-api](https://github.com/limestone-finance/limestone-docs/tree/1c10aa6c007b11023008acedb55dcd94affec715/fluent-interface/README.md) / [Exports](https://github.com/limestone-finance/limestone-docs/tree/1c10aa6c007b11023008acedb55dcd94affec715/fluent-interface/modules.md) / LimestoneQueryExecutable

## Class: LimestoneQueryExecutable

### Type parameters

| Name |
| :--- |
| `QueryResultType` |

### Table of contents

#### Constructors

* [constructor](limestonequeryexecutable.md#constructor)

#### Properties

* [params](limestonequeryexecutable.md#params)

#### Methods

* [exec](limestonequeryexecutable.md#exec)

### Constructors

#### constructor

+ **new LimestoneQueryExecutable**\(`params?`: {}\): [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

**Type parameters:**

| Name |
| :--- |
| `QueryResultType` |

**Parameters:**

| Name | Type | Default value |
| :--- | :--- | :--- |
| `params` | _object_ | {} |

**Returns:** [_LimestoneQueryExecutable_](limestonequeryexecutable.md)

Defined in: [limestone-query.ts:173](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L173)

### Properties

#### params

• `Private` **params**: QueryParams

Defined in: [limestone-query.ts:173](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L173)

### Methods

#### exec

▸ **exec**\(\): _Promise_

Executes the query

**Returns:** _Promise_

Promise resolving the query result \(result type depends on the query\)

Defined in: [limestone-query.ts:187](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L187)

