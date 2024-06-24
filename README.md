# Project Raffle Contracts

## About

Welcome to the Project Raffle Contracts repository! This project aims to create a provably random smart contract lottery, leveraging Chainlink VRF for randomness and Chainlink Automation for time-based triggers. The smart contract ensures fairness and transparency in selecting the lottery winner, providing an exciting and reliable raffle experience for users.

## Functionality

The smart raffle contract offers the following features:

- **User Participation**: Users can enter the raffle by purchasing a ticket. Each ticket represents one entry into the lottery.
- **Ticket Fees**: The fees collected from ticket sales are accumulated and awarded to the winner.
- **Automatic Winner Selection**: After a specified period, the contract automatically draws a winner using a provably random mechanism.
- **Chainlink VRF Integration**: Chainlink's Verifiable Random Function (VRF) ensures that the winner is selected randomly and fairly.
- **Chainlink Automation**: Time-based triggers handled by Chainlink Automation ensure that the lottery drawing occurs at the predetermined intervals without manual intervention.

## How It Works

1. **Entering the Raffle**: Users send a predefined amount of cryptocurrency to the smart contract to purchase a ticket.
2. **Accumulating Fees**: The smart contract collects and holds the ticket fees.
3. **Drawing the Winner**: At the end of the raffle period, the contract requests a random number from Chainlink VRF.
4. **Announcing the Winner**: The contract uses the random number to select a winner from the pool of ticket holders. The accumulated fees are then transferred to the winner's address.

## Usage

### Prerequisites

- A web3-enabled browser or wallet (e.g., MetaMask)
- Cryptocurrency to purchase raffle tickets
- Access to the Ethereum network (or a compatible testnet)

### Entering the Raffle

1. Connect your wallet to the Ethereum network.
2. Send the required ticket fee to the smart contract address.
3. Wait for the raffle period to end and for the winner to be drawn.

### Drawing the Winner

- The winner is selected automatically by the smart contract at the end of the raffle period.
- The contract interacts with Chainlink VRF to obtain a random number.
- The winner is chosen based on the random number, and the accumulated ticket fees are transferred to their address.

## Development

This project was developed as part of the Foundry Fundamentals 101 course by Cyfrin. The course provided the foundational knowledge and guidance necessary to build and deploy this smart raffle contract.

### Credits

Special thanks to Cyfrin for offering the course materials and support throughout the development of this project.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
