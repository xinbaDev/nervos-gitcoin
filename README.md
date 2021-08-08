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