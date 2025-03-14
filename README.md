
# multicontract_fib

## Overview

`multicontract_fib` is a smart contract project built on the Aptos blockchain. This project demonstrates the implementation of multiple contracts working together to compute Fibonacci numbers in a decentralized manner.

## Features

-   **Smart Contract-Based Computation**: Implements Fibonacci sequence calculations using Move smart contracts.
    
-   **Modular Architecture**: Contracts are designed to interact seamlessly for scalability and efficiency.
    
-   **Aptos Blockchain**: Utilizes Aptos' high-performance and low-cost transaction framework.
    
-   **Secure and Reliable**: Ensures safe contract execution with Move's resource-oriented programming.
    

## Installation

### Prerequisites

Ensure you have the following installed:

-   Aptos CLI
    
-   Rust (for Move development)
    
-   Move Prover (optional, for contract verification)
    

### Setup

1.  Clone the repository:
    
    ```
    git clone https://github.com/rhondacruz20001027/multicontract_fib.git
    cd multicontract_fib
    ```
    
2.  Install dependencies:
    
    ```
    aptos init
    ```
    
3.  Compile the contracts:
    
    ```
    aptos move compile
    ```
    
4.  Deploy to a local testnet or devnet:
    
    ```
    aptos move publish --profile dev
    ```
    

## Usage

-   Invoke the Fibonacci contract with an input value:
    
    ```
    aptos move run --function 0xYourAddress::Fibonacci::calculate --args u64:10
    ```
    
-   Retrieve computed results from the blockchain.
    

## Contributing

Pull requests are welcome! Please ensure any changes are well-documented and tested before submitting.

## License

This project is licensed under the MIT License.

