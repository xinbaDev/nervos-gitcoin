# Gitcoin: 0) Setup a Local CKB Node and CKB Indexer for the Testnet

## 1. Setup a CKB Node

![](pic/task1.png)

## 2. Setup a CKB Indexer

![](pic/task2.png)


# Gitcon1: 1)

## 1. A screenshot of the accounts you created 

![](pic/task_1_1.png)
## 2. A link to the Layer 1 address you funded on the Testnet Explorer

https://explorer.nervos.org/aggron/address/ckt1qyqyqvztuz5syu574mt34cm43dd9xu86smeqcsp0ef

## 3. A screenshot of the console output immediately after you have successfully submitted a deposit to Layer 2

![](pic/task_1_3.png)


# Gitcoin: 2) Deploy A Simple Ethereum Smart Contract On Polyjuice

## 1. A screenshot of the console output immediately after you have successfully deployed a smart contract.

![](pic/task_2_1.png)

## 2. The transaction hash from the contract deployment (in text format).

0xfdcbd95f408cc639454855ad32cd8fbd5236c546f9c95651d006c34d20cd9135

## 3. The deployed contract address from the contract deployment (in text format).

0xBBEaFABf6CA88509E7f6F4b7670b38ff72c7b5A8

# Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![](pic/task_3_1.png)

## 2. The transaction hash from the console output (in text format).

0x3ef91e3620bb7f72ed0de19a4be0f4f4d455727fd120986d0636df9763d8053c
## 3. The contract address that you called (in text format).

0xBBEaFABf6CA88509E7f6F4b7670b38ff72c7b5A8

## 4. The ABI for contract you made a call on (in text format).

```
abi = [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ];
```

# Gitcoin: 4) Issue An SUDT Token On Layer 1 And Deposit It To Layer 2

## 1. A link to the Layer 1 address you funded on the Testnet Explorer.

https://explorer.nervos.org/aggron/address/ckt1qyqyqvztuz5syu574mt34cm43dd9xu86smeqcsp0ef
## 2. A screenshot of the console output immediately after using sudt-cli to create your SUDT tokens on Layer 1.

![](pic/task_4_2.png)

## 3. A link to the transaction ID created by sudt-cli on the Testnet Explorer.

https://explorer.nervos.org/aggron/transaction/0xc3857f7b32106ea7a31f988807be740cdd91007395aff9c23e9d4b645bdf026a
## 4. A screenshot of the console output immediately after you have successfully submitted a deposit to Layer 2 using the account-cli tool.

![](pic/task_4_4.png)

## 5. The SUDT ID from the console output after executing the deposit script (in text format).

392

# Gitcoin: 5) Deploy The ERC20 Proxy Contract For The Deposited SUDT

## 1. A screenshot of the console output immediately after deploying smart contract.

![](pic/task_5_1.png)


## 2. The address of the ERC20 Proxy Contract you deployed (in text format).

0xE674ae36a9242Ca285E1BBcf8e9973B4B72C0333

## 3. A screenshot of the console output immediately after checking your SUDT balance.

![](pic/task_5_3.png)


## 4. The Ethereum address that was checked (in text format).

0x467eA556fF83ae2A763F38F246bbb4f3f6e9558A

# Gitcoin: 6) Use Force Bridge To Deposit Tokens From Ethereum To Polyjuice

## 1. A screenshot of the console output immediately after you have successfully generated your Deposit Receiver Address.

![](pic/task_6_1.png)

## 2. Your Deposit Receiver Address (in text format).

ckt1q3dz2p4mdrvp5ywu4kk5edl2uc4p03puvx07g7kgqdau3n3dmypkqnxzuefxyp9wdghglncj77k5wt6p59sx6kukyjlwh5s467qgp8m25yqqqqqsqqqqqvqqqqqfjqqqqp9252w6analwy5q0ednz2vag5t6pfe3x97f2pu6z2akzwegrt6cs6gqqqqpqqqqqqcqqqqqxyqqqqx7asf60w8pqpte2sfcfn90fdfzxue7ff2g8sawe9wacnqat6jmygqngqqqqpxv9ejjvgz2u63w3l839aadguh5rgtqd4devf97a0fpt4uqsz0k53n754t0lqaw9fmr7w8jg6amfulka92c5q9rqgqqqqqqcq46cweq

## 3. The Ethereum address used to generate the Deposit Receiver Address (in text format).

0x467eA556fF83ae2A763F38F246bbb4f3f6e9558A

## 4. A link to the Etherscan explorer for the successful Force Bridge transaction. This can be found on Force Bridge under History→Succeed.

https://rinkeby.etherscan.io/tx/0x8bed5aa59e046a8913157b15fe3844e5faa6e371b2d987db701e4744d835d520
## 5. A link to the Nervos explorer for the successful Force bridge transaction. This can be found on Force Bridge under History→Succeed.

https://explorer.nervos.org/aggron/transaction/0xe90541523e93f6c206e8b0a70a1c794a5bb6752086baac88aaa452064b9a5cfe

# Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

![](pic/task_7_1.png)
## 1. Screenshots or video of your application running on Godwoken.


## 2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

https://github.com/xinbaDev/nervos-simple-diary/tree/gitcoin7
## 3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)


contract address: 0xCd4b07221e4525D9B5D71ccd14E6cfc0B24E94AA
transaction hash: 0x8f4872b355f393d70dddc1c01adb2c68f150ba651c43a548bb49c41bdf55fbfc

```
"abi": [
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_dPubKey",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_dPrivKey",
          "type": "string"
        }
      ],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint32",
          "name": "",
          "type": "uint32"
        }
      ],
      "name": "diaries",
      "outputs": [
        {
          "internalType": "string",
          "name": "content",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "timestamp",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "isOwner",
      "outputs": [
        {
          "internalType": "bool",
          "name": "",
          "type": "bool"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getdPubKey",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getdPrivKey",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "setNewRecord",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint32",
          "name": "recordNum",
          "type": "uint32"
        },
        {
          "internalType": "string",
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "setExistingRecord",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint32",
          "name": "number",
          "type": "uint32"
        }
      ],
      "name": "get",
      "outputs": [
        {
          "components": [
            {
              "internalType": "string",
              "name": "content",
              "type": "string"
            },
            {
              "internalType": "uint256",
              "name": "timestamp",
              "type": "uint256"
            }
          ],
          "internalType": "struct Diary.Record",
          "name": "",
          "type": "tuple"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getLatestDiaryNumber",
      "outputs": [
        {
          "internalType": "uint32",
          "name": "",
          "type": "uint32"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ],

```