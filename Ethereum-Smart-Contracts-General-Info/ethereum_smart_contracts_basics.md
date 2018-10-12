# Ethereum and Smart Contracts Basics

### Ethereum

* What is Ethereum?
1.  **Decentralized database**
2. Database contains transactions
	- Between:
		- People <--> People
		- Contracts <--> Contracts
		- People <--> Contracts
3. A network of computers that runs code *very slowly* at an expensive monetary price
	- Runs code that:
		1. Anyone can *anonymously* create
		2. No one can change
		3. Anyone can see
		4. Anyone can run
		5. Lives forever
		6. In *most* cases is very trustworthy
4. Ethereum vs Ether
	* Ethereum = network
	* Ether = fuel (used to power network)
		- Pay transaction fees
		- Launch a contract
		- Call functions from a contract
	* You buy ether, but invest in the ethereum network 


### What problem did Ethereum solve?
* Shouldn't there be one blockchain that everyone can build their decentralized applications on?
	- Ethereum creator: Vitalik Buterin
	- Similar to having **1 internet** where **MANY websites** reside on
	- Ethereum allows us to have **1 blockchain** which **MANY DApps** utilize for their decentralized code and logic
		- Allows developers to build DApps and not focus on building a blockchain, which is done by ethereum
* Ethereum is a general purpose blockchain that developers use to create decentralized applications
	- Does what Bitcoin does (sends transactions between accounts) + more!

### Blockchain

* What is Blockchain?
	- Digitized, decentralized, public ledger of all transactions
	- Is constantly growing as ‘completed’ blocks that are the most recent transactions
	- Completed blocks are recorded and added to it in chronological order
	- Allows participants to keep track of transactions without central recordkeeping
	- Each node (a computer connected to the network) gets a copy of the blockchain, which is downloaded automatically
	- Resource:  https://www.investopedia.com/terms/b/blockchain.asp#ixzz5TgYxvV1M 
* Limitations of Bitcoin
	- Doesn't have a *general purpose programming language* that applications can use to build DApps.

## Differences between Blockchain and Ethereum
* Bitcoin is capped at 21 million coins forever but Ethereum has no limit
* Ethereum has an annual limit up to 18 million ether that can be created each year
* Different block rewards
	- Bitcoin is 12.5 btc
	- Ethereum is 5 eth
* New blocks are discovered at different rates
	- Bitcoin is 10 minutes
	- Ethereum is 15 seconds

### Ethereum Virtual Machine (EVM)
* Ethereum = network of computers (nodes/clients)
* EVM = program that the network of computers run
	- EVM runs **smart contracts**

### Ethereum Node
* Ethereum Node = Ethereum Client
* Nodes/ clients parse and verify the blockchain, its smart contracts and everything related
* Provide interface to create transactions and mine blocks = key for any blockchain interaction
* Not all nodes/ clients perform smart contract execution

### Smart Contracts
1. Languages used to create smart contracts
	- Serpent
	- Viper
	- Solidity
2. What are Smart Contracts
	- Stores state (data)
	- Code that manipulates the data

### Smart Contract Deployment
1. Deploy a smart contract
	- Anyone can use solidity to write and deploy a smart contract to the ethereum blockchain
2. Lifecycle of deployment process:
	1. Write Code
	2. Compile solidity smart contract down to EVM bytecode
	3. Send the bytecode as part of a transaction to the ethereum network
	4. Transaction is put into a block and verified =  mining
	5. **Smart Contract is deploed to blockchain and the smart contract is given a public address**
	6. Anyone can interact with the smart contract
		- Send transactions to its address and specify the method to invoke
		- Result of the method call is written to the blockchain after the subsequent transaction is mined

### Gas
* What is gas?
	- Unit of measurement that determines how much computation the EVM needs
	- Cost of invoking a smart contract method
	- Gas Price
		- Price of 1 unit of gas is set in Ether
		- More complex the commands to execute, the more gas you have to pay



#### Further Questions
- How is bitcoin's smart contract language different than Ethereum's?
- The language is limited because it can't store state. Does state refer to data?
- Why are the scripts referred to as simple versions of smart contracts?
- So Ethereum runs an EVM and an EVM runs smart contracts?

