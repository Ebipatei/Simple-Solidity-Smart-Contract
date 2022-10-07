# Simple-Solidity-Smart-Contract
Crating a simple smart contract using solidty. This repo follows a tutorial, so it is beginner friendly.

I'm a newbiw in the web3 space and this is my first smart contract. Feel free to call my attention to any errors you might find and I'll happily update as needed. Having said that, let's jump right it:

The project is a fundraising smart contract that the following properties:

owner : The owner of the project is trying to fundraise.

targetAmount : The amount of money the owner trying to raise in ETH.

donations : A list that maps the donator and how much they have donated in ETH. The address notes the person that donates to the project as an Ethereum wallet address. The ETH amount that a person donates to the project is stored as uint256 type.

raisedAmount : The accumulated total amount of all donations.

finishTime : The amount of time the project will run for whilst trying to reach the target. We set 3 weeks for the fundraising period.

The specification of the fundraising contract is as follows:
If the total amount of donations is greater or equal to the target amount, then all the funds in the contract will be transferred to the owner of the project.
If the total amount of donations is less than the donation target at the end of the contract, then people inside the donators list will receive a full refund.
