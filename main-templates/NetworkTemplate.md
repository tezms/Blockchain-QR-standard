# Specification for network identifier
## Version
Version: 1
<br>

## Revision Log
This is a draft version for an initial discussion.
<br>

## Data Objects
| Name | Map ID | Format | Presence | Comment |
| ---- | ------ | ------ | -------- | ------- |
| Tezos | 1 | Integer | O | Tezos network idenitfication |
| Bitcoin | 2 | Integer | O | Bitcoin network identification |
| RFU | 3-X | RFU | O | Reserved identifiers for other blockchains |
<br>

## Data Object Value Assignments
### Tezos identifiers (Map ID: 1)
| Network | Id | 
| ------- | -- |
| Zeronet | -1 |
| Mainnet | 1 | 
| Florencenet | 2 |
| Granadanet | 3 |  
<br>

### Bitcoin identifiers (Map ID: 2)
| Network | Id | 
| ------- | -- |
| Mainnet | 1 | 
<br>


## Notes
## Requirement
## Extensibility
## Examples