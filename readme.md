## Decentralized Star Notary Service DAPP
Udacity Blockchain Developer Nanodegree Program (Project 5)

## DAPP info
1. ERC-721 Token Name = "Star Notary System"
2. ERC-721 Token Symbol = "SNS"
3. Version of the Truffle and OpenZeppelin used:
   	Truffle v5.0.30 (core: 5.0.30)
4. Token Address on the Rinkeby Network (work desktop) = 0xAC24Ae0a92Bd0e60b365dc763e97829786337198



## installing and setup
1. Open terminal and navigate to project folder
2. Make sure that you have Truffle v5 installed or type:
	npm install -g truffle
3. Start the truffle development console by run:
	truffle develop
4. Compile the contract from inside the development console by typing:
	compile
5. For migrating the contract to the locally running Ethereum network,
   inside the development console, run:
	migrate --reset
6. For running unit tests the contract, inside the development console, run:
	test
7. For migrating the contract to the Rinkeby test network,
	- inside the development console, run:
		truffle migrate --reset --network rinkeby
	- From Metamask select Rinkby test Network
	- Add Token by contract token address shown from the above migrate result

8. For running the Front End of the DAPP:
	- open another terminal window and go inside the project directory
	- run:
		cd app
		npm run dev
	- Open web browser with this url:
		http://localhost:8080/




## Built With
Visual Studio Code
Metamask
Infura
Truffle
Openzeppelin


## Author
Riman Bin Sulaiman
