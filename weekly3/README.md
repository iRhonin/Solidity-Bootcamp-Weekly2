# Tokenized Ballot

## Mint/Buy Tokens

```sh
yarn hardhat run scripts/BuyToken.ts --network goerli
```

TX: https://goerli.etherscan.io/tx/0x5f19de0f12a9507d187003e7f92098374fee9b53c3d3d5a9e1a221c930f3bd53

Output:

`Successfully Bought Tokens for 0.001 ETH and Delegated Votes to self.`

## Delegate Votes

```sh
yarn hardhat run scripts/DelegateVotes.ts --network goerli
```

TX: https://goerli.etherscan.io/tx/0xb5547ff0e4eff8c3b83dc5c1a7c5e512237db487cd55f4edc0b98009b14accdf

Output:

`You have successfully delegated to 0xD9aF6C670B49C4b1239B86bb472E877f5BdF13Bf, on txn 0xb5547ff0e4eff8c3b83dc5c1a7c5e512237db487cd55f4edc0b98009b14accdf My Delegatee: 0xD9aF6C670B49C4b1239B86bb472E877f5BdF13Bf `

## Get Voting Power

```sh
yarn hardhat run scripts/GetVotes.ts --network goerli
```

TX: It is a non payable TX therefore there is no TX.

Output:

`Votes for Address 0xD9aF6C670B49C4b1239B86bb472E877f5BdF13Bf at Reference Block 7741766 are 0`

_Because I minted the tokens after the refrence block my voting power is 0._

## Cast Votes

```sh
yarn hardhat run scripts/GetVotes.ts --network goerli
```

TX: https://goerli.etherscan.io/tx/0x23635574006b98ea2b2e5c538ffb9299426d74ee05a1c2f9010292a50bd98446

Output:

```sh
You have successfully voted on proposal 0, on txn 0x23635574006b98ea2b2e5c538ffb9299426d74ee05a1c2f9010292a50bd98446
My Voted Stats:

BigNumber { value: "0" }
```
