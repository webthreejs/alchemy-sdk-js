[alchemy-sdk](../README.md) / [Exports](../modules.md) / RefreshState

# Enumeration: RefreshState

The current state of the NFT contract refresh process.

## Table of contents

### Enumeration members

- [ALREADY\_QUEUED](RefreshState.md#already_queued)
- [DOES\_NOT\_EXIST](RefreshState.md#does_not_exist)
- [FINISHED](RefreshState.md#finished)
- [IN\_PROGRESS](RefreshState.md#in_progress)
- [QUEUED](RefreshState.md#queued)
- [QUEUE\_FAILED](RefreshState.md#queue_failed)

## Enumeration members

### ALREADY\_QUEUED

• **ALREADY\_QUEUED** = `"already_queued"`

The contract has already been queued for refresh.

#### Defined in

[src/types/types.ts:656](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L656)

___

### DOES\_NOT\_EXIST

• **DOES\_NOT\_EXIST** = `"does_not_exist"`

The provided contract is not an NFT or does not contain metadata.

#### Defined in

[src/types/types.ts:653](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L653)

___

### FINISHED

• **FINISHED** = `"finished"`

The contract refresh is complete.

#### Defined in

[src/types/types.ts:662](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L662)

___

### IN\_PROGRESS

• **IN\_PROGRESS** = `"in_progress"`

The contract is currently being refreshed.

#### Defined in

[src/types/types.ts:659](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L659)

___

### QUEUED

• **QUEUED** = `"queued"`

The contract refresh has been queued and await execution.

#### Defined in

[src/types/types.ts:665](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L665)

___

### QUEUE\_FAILED

• **QUEUE\_FAILED** = `"queue_failed"`

The contract was unable to be queued due to an internal error.

#### Defined in

[src/types/types.ts:668](https://github.com/alchemyplatform/alchemy-sdk-js/blob/145ea50/src/types/types.ts#L668)
