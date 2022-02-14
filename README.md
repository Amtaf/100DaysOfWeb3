# 100DaysOfWeb3
It can be a little bit confusing on where to start off once you hop onto the Web3 train.Here's my journey on what i learnt on the #100DaysOfWEb3

## Day 1: DApps
-How DApps are developed.
-Learnt that DApps can be written in an OOP language (solidity) in the Ethereum blockchain.
-Differences between web3.0 and web2.0
-The DApp you want to build will determine what type of blockchain you opt for private or public.

## Day 2:Contracts
-Solidity is a contract oriented language highly influenced by Python,C++ & JavaScript.
-Wrote my first contract code,you first specify the version of solidity using terms 
Pragma solidity (and the version)
-All the variables live in the contract braces.
## Day 3:Contracts continuation...
-In other OOP languages a class is a blueprint for creating objects,in solidity a contract is like a class.
-You can inherit from a contract to share a common interface 
## Day 4: IDEs & Smart Contracts
-Learnt how to use the Remix ide( for the 50th timeRolling on the floor laughing) it's the best IDE for writing,compiling and deploying smart contracts. You can also use VScode save your file with a .sol extension
-How IPFS can be used to store files.
-IPFS to search for files in a specific node
-Datatypes(string,uint,uint8,byte32,int,and address)Structs,Arrays.
## Day 5: Data types in-depth and DataStructures
-Differences between uint8,uint and uint256
✓uint256 is used if the number needs to be big.
✓uint8 is used to optimize performance.uint example:
uint count = 0;
-Structs are custom data structures.
Struct example
you start with the keyword struct.
```
struct person{
     uint ID;
     string name;
}
```
## Day 6: Arrays,Mapping and functions
-There are two types of arrays in solidity fixed and dynamic.A dynamic array has no fixed size.
```
uint[] myArray;
```
You can also declare an array as public so other contracts can read from it but not write to.
Mappings are DataStructures like arrays but better than arrays because they store items with IDs that start with 1 unlike arrays with indices starting with 0.They store data in key-value pairs
![image](https://user-images.githubusercontent.com/9764833/152503098-872881a6-59a6-40fd-bdba-d7be6b701bd0.png)
## Day 7: More on Functions and DeFi
-I became confident in writing smart contracts.I wrote a counter DApp and more small projects.
-Solidity functions are public by default meaning anyone can call your contract's function .The best approach is to declare your functions private
![image](https://user-images.githubusercontent.com/9764833/152503351-15483aff-cfc3-4ad6-9b02-391c10ea802c.png)
-Learnt the differences between traditional finance and DeFi
-How DeFi works
## Day 8: Smart Contracts Anatomy
-Data in smart contracts must be assigned a location either in storage(stored on the blockchain) or memory(stored temporarily on the blockchain)
-Function visibility public,private,internal and external
## Day 9: Repeated what I learnt from the first Day.
As they say "Repetition is mastery".
-Played around with cryptozombies tutorials.
 ## Day 10: 
-Completed chapter 2 of cryptoZombies.
 ## Day 11: Advanced Solidity concepts & Tokens 
-Completed 3rd lesson of cryptoZombies 
-Looked at different tokens,compared them and their use cases.
ERC20,ERC721,ERC223,ERC777 &ERC115.
-ERC20 Fungible Tokens can be used for event tickets,company share
-ERC721 (NFT) for non-fungible assets,can be used for art & cryptocollectibles & in real estate 
-ERC223 &ERC777 Is the same as ERC20
-ERC1155 For both Fungible and Non-Fungible assets
 ## Day 12: 
-I was following along @dabit3 tutorial on how to develop a fullstack Blockchain app 
-I installed all dependencies,but got stuck with errors while running hardhat ( A local Ethereum network designed for development)
## Day 13:
-Read about DAOs and how they operate.
## Day 14: #100DaysOfWeb3 #100DaysOfBlockchain
Repeated advanced solidity concepts
-Looked into immutability of contracts. Once deployed they cant be modified
-Function modifiers,They look like any function but use the keyword "modifier"
-Fixed errors on a project .
I found a way around the error "HH1: You are not inside a hardhat project" I was get when running npx hardhat.I Switched from using Git bash to CMD I'm on windows 10.
 ## Day 15: Building fullstack DApp
-Learnt how to compile smart contracts I'm using Vscode.
-learnt to check on available local blockchain nodes
-Learnt how to deploy smart contracts using hardhat
 ## Day 16: Fullstack DApp
-Learnt how to link local blockchain nodes created using hardhat with metamask( crypto wallet).
- learning to develop the frontend that interacts with the Blockchain 
## Day 17: 
-Finished the frontend for updating messages on the Blockchain
-Learnt about the ABI(Application Binary Interface) which is used to interact with frontend applications
-Learnt about the various APIs used to check is using an Ethereum wallet
## Day 18: Fullstack DApp
-Skipped deployment of a smart contract live test network (Ropsten),I just wasnt feeling itFace with hand over mouth.
-I am learning how to develop a token from scratch. 
 ## DAY 19: Fullstack DApp
-Learnt how to deploy a contract on live test network(Ropsten)
-I can now develop a token from scratch with two basic functions send and transfer On my own
 ## DAY 20: ERC20 (Fungible Token)
-I can now develop an ERC 20 token.But I have to repeat the process again.I need to know how to add burning and minting capabilities.
## Day 21: #100DaysOfWeb3
-Just Finished publishing my first article. I don't think ill be doing anything else after this, Don't forget to go through it. 
How To Get In To Blockchain
 ## Day 22: Eth Smart Contract Best Practices
-I read on smart contract security and learnt so much.
-The cost of failure on Smart Contracts is high and change can be difficult as compared to how you program the web.
  ### Some of the best practices involve:
-Catching bugs before release and preparing for failure
-Keeping contracts simple by use of libraries
-Be aware of #blockchain properties such as malicious agents
 ## Day 23: OpenZeppelin contracts
-Since yesterday I read on Smart contracts security and one of the measures to put in place was to use already written tool.
-I wrote an ERC20 contract using the OpenZeppelin library.
## Day 24: ERC721
-Today I'm all about NFTs.
When I'm done I'll talk all about what I've learnt from the contract development,minting and anything else I'll learn
## Day 25: NFT
-So from yesterday I have been watching explainer videos on NFT.
-I learnt how create an NFT collection (1000+).
-I just looked at  ERC721 standard but didn't put it to practice.
## Day 26: 
-I read on secure development of smart contracts.
- I learnt that during the development of any contract the following recommendations should be followed:
~Use caution when making external calls
~Mark untrusted contracts
## Day 27: 
-Building a cryptocollectible game from cryptozombies by implementing the ERC721 standard.
## Day 28:
-I learnt on Solidity specific security recommendations such as:
~Enforce invariants with assert().assert function is used only to test for internal errors.
~Use require(),revert() functions appropriately.
~Use modifiers only for checks. 
The require function should be used to check if a condition is met.
Modifier are used to replace duplicate condition checks in multiple functions
## Day 29: Still on smart contract security 
-I learnt that though smart contracts are immutable they are still subject to attacks stemming from coding errors.
-One of the attacks I focused on today is Reentracy .
•Reentrancy mostly takes place when calling external contracts.
~Reentrancy led to the collapse of Decentralized Autonomous Organization ( DAO ) smart contract leading to a loss of 3.6million Ether
Some of the fixes to Reentrancy impossible include:
•Mark untrusted contracts
•Mutual Exclusion(Mutex): Locking state  so that it can only be changed by the owner....refreshed my computer science knowledge
## Day 30: Blockchain Attacks
- I learnt on the Front 
running attack,it's different categories and mitigation
-Timestamp dependence and Integer Overflow/Underflow solved using the safeMath.sol library
-Different DOS and more deprecated attacks.
## Day 31: 
Looked into DAO (Decentralized Autonomous Organization) design proposals
## Day 32-33:
-I enrolled in web3 course by @_buildspace it's amazing so far you earn NFTs for completing stuff.There are also co-working sessions with fellow builders.
- After a meeting I attended I got curious on what @PolygonHermez network entails
- I learnt that using Zero-knowledge technology(I'll dive deeper into this in the coming days) enhancing it's powerful capabilities like
-A high throughput of 2000 TPS 
-low token transfer cost allowing more financial services for mainstream adoption
## Day 34: Blockchain Scalability
- I got to understand Blockchain scalabity better.
-Layer1 &2 scaling solutions
-Boosting Blockchain networks Scalability.
## Day 35: Zero Knowledge Proof
-Focused on the @PolygonHermez a ZK-Rollup focusing on payments on Ethereum
- Comparing to Ethereum which can handle 15TPS I understand why 2000 TPS are possible on Hermez,thus low fees,isn't it cool? 
- -Zero Knowledge:When two parties in a transaction are able to verify each other that they have a particular set of information. Without revealing it.
-TPS(Transactions Per Second)
-Read on ProofOfDonation
## Day 36: 
-Resumed buildspace course I finished the 1st section (Storing data on smart contract and deploying).
-I'm now building a website that will interact with a local Ethereum network that I deployed.
## Day 37: 
-Deployed a contract on etherscan 
-Linked my project with @AlchemyPlatform
- Develop the frontend using ReactJs to send me waves(👋🏾) that's what the project is about and connected it with my wallet.
## Day 38:
Completed section 2 of @_buildspace web3 + Solidity course.
## Day 39: Got into researching on how to generate random NFT.
-Looked at chainlink VRF(verifiable Random Function),learnt something but didn't put it to practice.
-I realized there are different types of NFT dynamic and Advanced.
## Day 40-41:
-Winding up on section 3  of @_buildspace course hoping to finish by tomorrow.
-Storing messages on the blockchain
-Spent most of the time debugging but I got help from the wonderful community of devs on buildspace discord.

