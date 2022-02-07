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
