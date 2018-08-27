# "Proof of Existence dApp" 

## Description  
This application allows users to register and obtain time stamped picture

All image and video data are stored in **IPFS (Inter Planetary File System)** in order to become decentralized. 

***

## User Stories  
<!-- A user logs into the web app by **uPort**. The user can upload some data (pictures/video) to the app, as well as add a list of tags indicating the contents of the data.

In connection with Ropsten testnetwork by **MetaMask**, the smart contract reads the user’s address and shows the data that they have previously uploaded. -->

Users can retrieve necessary reference data about their uploaded items to allow other people to verify the data authenticity.

***

## How to set up
<!--  -->

Clone the project repository.

```
git clone https://github.com/martagonz/proof-of-existence-dapp.git
```

Go to the project directory

```
cd proof-of-existence-dapp
```

Install node modules

```
npm install
```

Compile Smart Contracts

```
truffle compile
```

Start a development blockchain network

```
ganache-cli
```

Migrate smart contracts

```
truffle migrate [--reset]
```


Start Dapp

```
npm run start
```

Start using Dapp

```
http://localhost:3000/




