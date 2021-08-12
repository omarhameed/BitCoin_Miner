# BitCoin_Miner
BitCoin1 is all the rage these days. BitCoin is a virtual currency that is managed by peer-to-peer network
of computers instead of banks. To make a bitcoin transaction a digitally signed message is broadcast in
the peer-to-peer network. Each transaction includes the
• ID: a unique identifier
• payer: the source of the funds (the transaction is digitally signed by the payer)
• payee: the receiver of the funds
• amount: the amount of the funds
• fee: the amount of bitcoin that will be paid for processing the transaction (by the payer)
• signature: of the payer to authenticate the transaction
• Other information
Transactions are processed by adding them to a digital ledger called a blockchain. A blockchain is simply
a sequence of blocks where each block stores a series of transactions and has a reference and the signature of the previous block in the chain. Consequently, it makes it computationally infeasible to modify
(forge) a block because all blocks succeeding it would also need to be modified. Thus, if Transaction 7 in
Block 1 was to be modified, Block 1’s signature would change, requiring Block 2 to be updated, requiring
Block 3 to be updated, and so on. This is computationally infeasible because to generate a block (mining)
requires a lot of computation
