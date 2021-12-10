# Mint Your Own NFT Collection - Hardhat Project

This project demonstrates a basic Hardhat use case

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

### uploaded image and json

https://anarkrypto.github.io/upload-files-to-ipfs-from-browser-panel/public/

```
image:
[
  {
    "path": "LisiDjangoGirls.jpg",
    "hash": "QmWUVRV93yMnNrDzHtzwTdMB5ew5dRhdt7r1cNgGAXDrJ1",
    "size": 120503
  }
]
```

https://bafybeidy36sdw7ugldpwthallgk7zb7bo54ys5bxsthfpxhxpc43wqtoly.ipfs.infura-ipfs.io/

### JSON

```
{
  "name": "Lisi Dajango Gilrs",
  "description": "Mi adorable hijo es un encuentro de Djano Girls en Campus Olegario.",
  "image": "https://bafybeidy36sdw7ugldpwthallgk7zb7bo54ys5bxsthfpxhxpc43wqtoly.ipfs.infura-ipfs.io",
  "strength": 200
}
```

JSON Keeper
https://jsonkeeper.com/b/WWFG
Set json in _setTokenURI


### Deploy 

```
$ npx hardhat run scripts/deploy.js --network rinkeby

$ Contract deployed to: 0x792b1027A50fd876b99aC662A8De98e53ee263d1
```

### Chek NFTs Deployed in Rarible

https://rinkeby.rarible.com/collection/0x792b1027a50fd876b99ac662a8de98e53ee263d1


### Verify contract on Etherscan.

```
npm i -D @nomiclabs/hardhat-etherscan
```

Get api key from etherscan and config hardhat.config.js

```
require("@nomiclabs/hardhat-etherscan");

  etherscan: {
    // Your API key for Etherscan. Obtain one at https://etherscan.io/
    apiKey: process.env.ETHERSCAN_KEY,
  },
  ```

```
$ npx hardhat verify YOUR_CONTRACT_ADDRESS --network rinkeby 
$ npx hardhat verify 0x792b1027A50fd876b99aC662A8De98e53ee263d1 --network rinkeby 
```

NOTE: it does not work with the url and apikey values from .env, you have to hardcode the values

verified contract:
https://rinkeby.etherscan.io/address/0x792b1027a50fd876b99ac662a8de98e53ee263d1#code


Have fun! 😀 Let's #BUIDL 🚀
![BUIDL_Logo_White](https://user-images.githubusercontent.com/330947/145647135-a6a42001-cab7-4814-a8b6-988c460be582.png)
