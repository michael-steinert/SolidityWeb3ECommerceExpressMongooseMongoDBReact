## Architecture Diagram

![Architecture Diagram](https://user-images.githubusercontent.com/29623199/123064257-67bcf700-d40e-11eb-8aaf-cde72bc08594.JPG)

## Stable Coin

* A Stable Coin is a Coin which Value does not change (like the DAI Coin: One DAI Coin equals One Dollar)
* It uses an Oracle to interacts with the real World (like getting the current One Dollar)

## Dependencies

| Dependency | Description |
| --- | --- |
| @openzeppelin/contracts | Library for secure Smart Contract Development |

## Truffle Commands

| Command | Description |
| --- | --- |
| truffle init | Initialize Truffle Project |
| truffle develop | Run a local Network - Ganache |
| truffle develop Console | |
| migrate --reset | Deploying Smart Contracts by using the Migration Script |
| .exit | Leave Truffle Develop Console |

## Solidity
### Events
* Events causes the Arguments to be stored in the Log of the Transaction
* The Log of the Transaction exists as long as the Block in the Blockchain exists (in Theory forever)
* Evetns log Changes into the Blockchain and make it true forever

### Address
* Every Account and Smart Contract has an Address
* It is used to send and receive Ether from one Account to another

### Mapping
* Data Type used to store Associations that allow to get a Value for a corresponding Key

### Require
* Convenience Function that guarantees Vailidity of Conditions that cannot be detected before Execution
