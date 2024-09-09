# GameT Token (GTE) - ERC20

This repository contains the smart contract for GameT Token (GTE), an ERC20 token deployed on the Ethereum blockchain. The `GameT` contract allows for minting tokens and includes an admin role with exclusive minting control.

## Contract Details 📜

- **Token Name:** GameT
- **Symbol:** GTE
- **Decimals:** 18
- **Initial Total Supply:** 100,000 GTE (minted to the deployer/admin)
- **Contract Version:** Solidity 0.8.23

## Key Features ⭐

- **ERC20 Standard:** Adheres to the ERC20 standard, ensuring compatibility with ERC20-compliant wallets and exchanges.
- **Admin Role:** The deployer of the contract is designated as the admin and has exclusive rights to mint new tokens.
- **Minting Functionality:** Admin can mint additional tokens using the `safeMint()` function.

## Contract Address 🏷️

The contract is deployed and verified at:
Address: 0x1C1e5B455623DCc59277255a5C4b04ac152c362f

## How to Interact 🔧

To interact with the contract, you’ll need:

1. **Ethereum Wallet:** Use a wallet like MetaMask or another Ethereum-compatible wallet to interact with the blockchain.
2. **Ether:** Ensure you have some ETH in your wallet to cover gas fees for transactions.

### Functions

- **`constructor()`**: Initializes the contract, mints the initial supply of tokens to the deployer/admin.
- **`onlyAdmin`**: Modifier that restricts access to certain functions to only the admin.
- **`safeMint(address to, uint256 value)`**: Allows the admin to mint new tokens to a specified address.

## Deployment

To deploy the contract, you can use tools like Remix IDE, Hardhat, or Truffle. Follow these steps:

1. **Compile the Contract:** Ensure the contract compiles successfully with Solidity version 0.8.23.
2. **Deploy the Contract:** Deploy using your preferred Ethereum network (e.g., Rinkeby, Mainnet).
3. **Verify the Contract:** Verify the contract on Etherscan for transparency.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
