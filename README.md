# Loyalty Points Smart Contract

The LoyaltyPointsContract is a Solidity smart contract that allows users to earn and spend loyalty points. It provides functionalities to create user accounts, earn points, and spend points.

## Getting Started

To interact with the LoyaltyPointsContract, you'll need a development environment with the following prerequisites:

Node.js
npm (Node Package Manager)
Truffle (a development framework for Ethereum)
Ganache (a personal Ethereum blockchain for development)

## Installation

Clone the repository:
bash

Copy code
git clone https://github.com/your-username/loyalty-points-contract.git

Change into the project directory:
bash

Copy code
cd loyalty-points-contract

Install project dependencies:
bash

Copy code
npm install

Compile the smart contract:
bash

Copy code
truffle compile

Deploy the contract to Ganache (or any other development network):
bash

Copy code
truffle migrate --network development

## Usage

The contract provides the following functions to interact with the loyalty points system:

1. createUserAccount()
This function allows users to create their accounts in the loyalty points system. Each user can create an account only once.

2. getPoints()
This function returns the number of loyalty points owned by the calling user.

3. earnPoints(uint256 points)
Users can call this function to earn additional loyalty points. The points parameter specifies the number of points to be added to the user's account.

4. spendPoints(uint256 points)
Users can use this function to spend their loyalty points. The points parameter specifies the number of points to be deducted from the user's account. The function will check if the user has sufficient points before deducting.

## Author 

Aditya Singh

## license

This project is licensed under the MIT License.
