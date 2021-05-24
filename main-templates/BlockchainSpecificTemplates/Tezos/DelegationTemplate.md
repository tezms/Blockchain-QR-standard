# Specification for Tezos Native Delegation
## Version
Version: 1
<br>

## Revision Log
This is a draft version for an initial discussion.
<br>

## Data Objects
| Name | Map ID | Format | Presence | Comment |
| ---- | ------ | ------ | -------- | ------- |
| Destination address | 1 | String | M | Destination address.|
| Amount | 2 | Integer | O | Amount to be transferred. |
| Fee | 3 | Integer | O | Delegator's current fee. |
| RFU | 3-9 | RFU | O | Reserved for future use. |
| HelperTemplates | 10 | HelperTemplate | O | Template structure for general helpers. |
| RFU | 11-X | RFU | O | Reserved for future use. |
<br>


## Notes
## Requirement
## Extensibility
## Examples