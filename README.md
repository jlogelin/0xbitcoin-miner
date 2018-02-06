
# 0xBitcoin Miner

### Setup
1. Install NodeJS 7.6
2. Clone this repo
3. run 'npm install yarn -g' to install yarn
4. run 'yarn' to install dependencies for 0xbitcoin-miner


### Getting Started
1. Build a new mining account with 'npm run account new'
2. Write down these credentials
3. Mine 0xbitcoin tokens with the command 'npm run mine'

Note that it is necessary to fill the mining account with a small amount of ether.  Typically 0.005 eth is good enough to get started.  The ether is used for gas to make function calls to the token smart contract when your miner finds a solution to the Proof of Work.  When the gas is spent that means a solution has been found and if you are the first to find it, you will be rewarded with 0xbitcoin tokens.  

## The Smart Contract 
Read the smart contract here: 

https://github.com/0xbitcoin/0xbitcoin-token
