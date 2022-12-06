#What is goatMUD

goatMUD is a simple goat simulator game that uses the MUD game engine https://mud.dev/ from http://lattice.xyz MUD is an amazing game engine to create blockchain games as it abstracts the networking part of the loop and allows the developer to focus on the game itself. The game can be deployed to an Optimistic rollup or our own fork of optimism bedrock that allows for cheaper or free transactions for players while still preserving the blockchain properties of OP rollups like settlement to l1 ethereum , fraud proofs etc.


#Why Build this?

We wanted to build a fully on-chain game where every asset and action is recorded on-chain unlike most games which only has some on-chain components, we also didn't want to do a yet another nft gaming project ;) 

#Tech Stack
````
```
MUD Game Engine
OPtimism Bedrock
Hardhat
Typescript
Solidity
````
```

#Preview
![goatMUD](https://raw.githubusercontent.com/antojoseph/goatMUD/main/goat.png)

#Youtube Demo
````
```
https://www.youtube.com/watch?v=5sKfpKGrw98
```
````
## Getting started
````
```

yarn install in root dir
cd to packages/contracts
yarn anvil:node
yarn deploy:anvil
cd to packages/client
yarn start

```
````
