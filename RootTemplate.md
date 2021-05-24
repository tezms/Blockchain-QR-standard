# Specification for root template
## Version
Version: 1
<br>

## Revision Log
This is a draft version for an initial discussion.
<br>

## Data Objects
| Name | Map ID | Format | Presence | Comment |
| ---- | ------ | ------ | -------- | ------- |
| Version | 1 | Integer | M | Version information about the used message format. |
| Network | 2 | [NetworkTemplate](main-templates/NetworkTemplate.md)| M | Network template contains information about the blockchain |
| Context | 3 | Integer | O | Context contains contextual information | 
| Native Transaction | 4 | [NativeTransactionTemplate](main-templates/NativeTransactionTemplate.md) | O | Native transaction template contains information about a native transaction on a blockchain. |
| Tipping | 5 | [TippingTemplate](main-templates/TippingTemplate.md) | O | Tipping template to provide tipping information |
| RFU | 6-9 | RFU | O | Reserved numbers for future use |
| Blockchainspecific | 10 | [BlockchainSpecificTemplates](main-templates/BlockchainSpecificTemplates.md)| O | Blockchain specific templates|
| RFU | 11-X | RFU | O | Reserved identifiers for other blockchain templates |
<br>

## Data Object Value Assignments
### Context information (Map ID: 2)
- 01:  Online - Initiation Point is connected to the Internet
- 02:  Offline - Initiation Points is not connected to the Internet
- 03:  Static - Static QR is used for initiation 
- 04:  Dynamic - Dynamic QR is used for initiation
- 05:  Online & Dynamic
- 06:  Online & Static
- 07:  Offline & Dynamic
- 08:  Offline & Static

## Notes
## Requirement
## Extensibility
## Examples