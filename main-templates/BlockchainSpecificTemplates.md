# Specification for Native Transaction template

## Revision Log
This is a draft version for an initial discussion.
<br>

## Data Objects
| Name | Map ID | Format | Presence | Comment |
| ---- | ------ | ------ | -------- | ------- |
| Tezos | 1 | Integer | O | Identifier for Tezos specific templates|
| Bitcoin | 2 | Integer | O | Identifier for Bitcoin specific templates|
| RFU | 2-X | RFU | O | Reserved for other blockchainss. |
<br>

## Data Object Value Assignments
### Tezos template identifiers (Map ID: 1)
| Template | Id | 
| ------- | -- |
| [FA1.2TransferTemplate](BlockchainSpecificTemplates/Tezos/FA1.2TranferTemplate.md) | 1 | 
| [FA2TransferTemplate](BlockchainSpecificTemplates/Tezos/FA2TransferTemplate.md) | 2 |
| [DelegationTemplate](BlockchainSpecificTemplates/Tezos/DelegationTemplate.md)| 3 |
| zkChannelPaymentTemplate | 4 |  
<br>

### Bitcoin template identifiers (Map ID: 2)
None yet defined.
<br>

## Notes
- Variant would be to skip this intermediary layer by directly identifying the blockchain via the network template. The template id could then e.g. be defined by using blockchain reserved main template identifiers.

## Requirement
## Extensibility
## Examples