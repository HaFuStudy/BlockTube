# Simple Ethereum + InterPlanetary File System (IPFS)+ React.js DApp

#A simple DApp to upload a document to IPFS and then store the IPFS hash on the Ethereum blockchain. Once the IPFS hash number is sent to the Ethereum blockchain, the user will receive a transaction receipt. We will use Create-React-App framework to make a front-end. This Dapp works with any user that has MetaMask installed in their browser.

#Run with npm start.

This application apply blockchain technology to decentralized media streaming using the InterPlanetary File System (IPFS). In order to save and retrieve big amounts of data (videos in our case) We used IPFS to address this data by saving the permanent, immutable IPFS hashes to the blockchain. We’ve built a simple decentralized web application (front-end) using React framework for uploading videos to IPFS. IPFS will store this videos and address it by a hash, our app will get this hash and send it to Ethereum blockchain where it’s going to be stored with some information that identifies this video. Our solidity smart contract will be responsible for connecting the web application with the blockchain and saving hashes to it. After that we will send the hashes to a player to play it. Metamask browser extention should be added to enable the interaction with the blockchain.
