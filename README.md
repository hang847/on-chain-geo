
# On-Chain Geo

A simple app for setting up and validating on-chain geo-fencing on the Aptos blockchain.

## Features

-   Define geo-fenced areas on-chain.
    
-   Validate user locations against predefined zones.
    
-   Decentralized and tamper-proof geo-validation using Aptos smart contracts.
    

## Prerequisites

Before running the project, ensure you have the following installed:

-   Aptos CLI
    
-   Rust and Move language toolchain
    
-   Node.js and npm (for frontend, if applicable)
    

## Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/hang847/on-chain-geo.git
    cd on-chain-geo
    ```
    
2.  Install dependencies:
    
    ```
    npm install  # If frontend exists
    ```
    
3.  Compile and deploy smart contracts:
    
    ```
    aptos move compile
    aptos move publish --profile default
    ```
    

## Usage

-   To define a geo-fenced area, submit a transaction to the smart contract.
    
-   To validate a user’s location, call the contract’s validation function.
    

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
