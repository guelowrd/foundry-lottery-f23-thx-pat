# Proveably random raffle contract

## About

This code is to create a proveably random smart contract lottery

## What we want to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner after the draw
2. After X period of time, the lottery will automatically draw a winner
   1. And this will be done programatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger

## Tests 
1. Deploy scripts in ./script
2. Tests in ./test
   1. Work on a local chain
   2. Forked Testnet
   3. Forked Mainnet

# foundry-lottery-f23-thx-pat
