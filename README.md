# fetchUserWalletBalance

/* API endpoints to fetch user ETH balance */

/getUserWalletEthBalance/:address -> pass address as query parameter

Eg:  `${baseUrl}/api/getUserWalletEthBalance/0xe688b84b23f322a994A53dbF8E15FA82CDB71127`

API call to fetch user USDT balance 

/getUserWalletUSDTBalance/:address -> pass address as query parameter

Eg:  `${baseUrl}/api/getUserWalletUSDTBalance/0xb23360CCDd9Ed1b15D45E5d3824Bb409C8D7c460`


/* Run the following commands to execute */

1) npm install 
2) npm start


/* A small description  of the soultion */

I have implemented the solution using the web3 (Web3.js) package insted of ethers package since it was already installed


I have made changes to the following files to implement the solution.

user.controller.js

line 858 to 918

getUserBalance -> conmon utility function to fetch both user ETH & USDT balance

getUserWalletEthBalance -> API controller to fetch ETH balance

getUserWalletUSDTBalance -> API controller to fetch USDT balance


routes.js

line 427 to 437

Routes 

1) /getUserWalletEthBalance/:address 

2) /getUserWalletUSDTBalance/:address 

constants/const.js

This file contains the ABI and token address for the USDT token

production.env 

Updated this file with the Infura URL which I found in API/transfer.js file. Did not create a new once since this one worked for me. (I've commented the process.env. usage example in user contoler file)

.gitignore file for nodemodules


Lastly thank you for considering me to work on your product. I am truly grateful.

Looking forward to work with and learn from you and your.

I really hope I have lived upto your expectations.

Best regards :)