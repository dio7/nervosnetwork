# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

A screenshot of the accounts you created (account list) in ckb-cli

![dio_1](https://user-images.githubusercontent.com/89730140/131880531-5a8e5c51-128f-41b6-81de-4a315e9bd2cc.png)

A link to the Layer 1 address you funded on the Testnet Explorer:

https://explorer.nervos.org/aggron/address/ckt1qyqpszpxd4r93hqc8qeawetca0pc20tfjcpqhs0hv4

A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

![dio_3](https://user-images.githubusercontent.com/89730140/131882612-032cc38e-3f64-46aa-a605-28fc7a7e0038.png)

A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

![dio_4](https://user-images.githubusercontent.com/89730140/131884247-5d8cae57-8a70-40ff-820d-9b51d10f5259.png)

The transaction hash of the "Contract call": 
0x12fc4224cffdf806962ad16738ec0894dc6df74a7b4fcdddf6f56104aa6c85b3

The contract address: 0x6d8BfC0B74D12147B46c8600e66E92a0c7cD91AC

The ABI for contract:

[
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
]

Tron address: TTGUFifpfnvckqJbKfAqVxiUoENZsYsPf2
