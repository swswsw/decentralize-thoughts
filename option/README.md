# Decentralized Options

## Decentralized and Trustless Options (Covered Options)

### Call Option

Call option allows someone to buy asset at an agreed price.

Contract psuedocode

```
lock asset
if x eth is sent to contract
then
  contract sends asset to purchaser
  contract sends x eth to contract writer

```

We may want to add an owner field to the contract such that only owner of the contract can exercise.  
That way, the contract can be sold to other people like the usual financial contract.  

### Put Option

Put option allows someone to sell asset at an agreed price.

```
lock x eth
if asset is sent to contract
then
  contract sends x eth to purchaser
  contract sends asset to contract writer

```

We may want to add an owner field to the contract such that only owner of the contract can exercise.  
That way, the contract can be sold to other people like the usual financial contract.  

### Advantages

No custodial central party
No need for price oracle
