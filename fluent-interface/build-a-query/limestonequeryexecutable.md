[limestone-api](../README.md) / [Exports](../modules.md) / LimestoneQueryExecutable

# Class: LimestoneQueryExecutable<QueryResultType\>

## Type parameters

| Name |
| :------ |
| `QueryResultType` |

## Table of contents

### Constructors

- [constructor](limestonequeryexecutable.md#constructor)

### Properties

- [params](limestonequeryexecutable.md#params)

### Methods

- [exec](limestonequeryexecutable.md#exec)

## Constructors

### constructor

\+ **new LimestoneQueryExecutable**<QueryResultType\>(`params?`: {}): [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

#### Type parameters:

| Name |
| :------ |
| `QueryResultType` |

#### Parameters:

| Name | Type | Default value |
| :------ | :------ | :------ |
| `params` | *object* | {} |

**Returns:** [*LimestoneQueryExecutable*](limestonequeryexecutable.md)<QueryResultType\>

Defined in: [limestone-query.ts:173](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L173)

## Properties

### params

• `Private` **params**: QueryParams

Defined in: [limestone-query.ts:173](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L173)

## Methods

### exec

▸ **exec**(): *Promise*<QueryResultType\>

Executes the query

**Returns:** *Promise*<QueryResultType\>

Promise resolving the query result (result type depends on the query)

Defined in: [limestone-query.ts:187](https://github.com/limestone-finance/limestone-api/blob/3d4422c/src/limestone-query.ts#L187)
