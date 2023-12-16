# Entertainment Platform Smart Contract

## Overview

This Solidity smart contract, named `EntertainmentPlatform`, serves as a decentralized entertainment platform where users can buy tickets to access entertainment content and rate movies. The contract is deployed on the Ethereum blockchain and is governed by the MIT License.

## Contract Features

### Admin

- The contract has an `adminAddress` variable representing the address of the contract administrator. This address is set to the deployer's address during contract deployment.

### Ticket Purchase

- Users can buy tickets through the `buyTicket` function. The contract ensures that a user can only purchase a ticket once.

### Movie Rating

- Users who have purchased a ticket can rate movies using the `rateEntertainment` function. Ratings are limited to a scale of 1 to 5.

### Events

- The contract emits two events:
  - `TicketBought`: Triggered when a user successfully purchases a ticket.
  - `MovieRated`: Triggered when a user rates a movie.

### Ticket Status Check

- Users can check their ticket purchase status using the `checkTicketStatus` function.

## Usage

1. Deploy the contract on the Ethereum blockchain.
2. The deployer's address becomes the contract administrator (`adminAddress`).
3. Users can interact with the contract by calling functions such as `buyTicket` and `rateEntertainment`.
4. Events (`TicketBought` and `MovieRated`) are emitted to track ticket purchases and movie ratings.
5. Users can check their ticket status using the `checkTicketStatus` function.

## License

This smart contract is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Author

Ankush singha roy

ankushsingharoy6@gmail.com
