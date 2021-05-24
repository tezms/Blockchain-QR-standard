# Specification for Tezos zkChannel Payment Request
## Version
Version: 1
<br>

## Revision Log
This is a draft version for an initial discussion.
<br>


## Data Objects
| Name | Map ID | Format | Presence | Comment |
| ---- | ------ | ------ | -------- | ------- |
| Destination identifier | 1 | String | M | Destination identifier.|
| Amount | 2 | Integer | O | Amount to be transferred. |
| zkHUB identifier | 3 | ??? | M | Identification of the zkHUB. |
| RFU | 4-9 | RFU | O | Reserved for future use. |
| HelperTemplates | 10 | HelperTemplate | O | Template structure for general helpers. |
| RFU | 11-X | RFU | O | Reserved for future use. |
<br>


## Notes
## Requirement
## Extensibility
## Examples