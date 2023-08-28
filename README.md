# CustomToken Smart Contract

## Description

The CustomToken smart contract showcases the creation of a custom ERC-20 token using the OpenZeppelin library. It provides functionalities for minting tokens, burning tokens, transferring tokens, and retrieving the total token supply. The contract inherits from ERC20 for token standards and Ownable for access control.

## Getting Started

### Prerequisites

To interact with and deploy the smart contract, you'll need:

- Ethereum development environment
- Solidity compiler (version >= 0.8.18)
- Access to the OpenZeppelin library ERC20

### Installation

1. Clone or download this repository.
2. Ensure you have the OpenZeppelin library installed. You can install it using npm:

   ```
   npm install @openzeppelin/contracts
   ```

3. Navigate to the project directory.

### Deployment

Deploy the compiled contract to an Ethereum-compatible blockchain network using your preferred deployment tool (e.g., Remix).

## Usage

1. After deploying the contract, interact with its functions using a compatible Ethereum wallet or a development environment.

2. **Minting Tokens**: Call the `mintTokens` function to mint a specific amount of tokens and assign them to a recipient. Only the contract owner can perform this action.

3. **Burning Tokens**: Use the `burnTokens` function to burn a specified amount of tokens from the sender's account. The function checks for sufficient balance before burning.

4. **Transferring Tokens**: Call the `transfer` function to send tokens to a specified recipient. The function also checks for valid recipient addresses.

5. **Getting Total Supply**: Use the `getTotalSupply` function to retrieve the total supply of tokens in circulation.

## Help

If you encounter any issues or have questions, feel free to [reach out](22BCT10001@cuchd.in).

## Authors

- Karimul Hasan
- Contact: 22BCT10001@cuchd.in

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
