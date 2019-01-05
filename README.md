# Bitcoin Script Transactions
We implement programmatically transactions that are able to submit bitcoin scripts and broadcast them onto mainnet/testnet blockchain.
1. PayToPubKey (P2PK): direct signed payment to a specified address.
2. PayToPubKeyHash (P2PKH): signed payment to the hash value of a specified address.
3. LinearEquationTransaction: create a transaction that can only be redeeemed by the solution to linear equations
    - x + y = PIN_1
    - x - y = PIN_2
4. MutiSigTransaction - a four-party transaction that requires a bank's and 1-of-3 customer's signature to redeem

Switch mainnet/testnet in **ScriptTests.java** and run it as JUnit to execute the transactions<br>
Addresses (public key) can be generated by <i>printAddress()</i> function

## Reference
- [BTC transaction](https://en.bitcoin.it/wiki/Transaction)
- [BTC script](https://en.bitcoin.it/wiki/Script)
- [Free bitcoins on testnet](https://en.bitcoin.it/wiki/Script)