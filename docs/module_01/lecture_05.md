# How Mining Works

The Nonce allows for variance in the hash. When Mining you are trying to get the Nonce.

* The blockchain sets a target. To be included in the blockchain, the hash to be found
must be smaller than the target. There is no reason for how the target is set and is
only there for a challenge for the miner. Any hash larger than the target cannot
be made into a block. 

* The nonce is the only thing that can be changed in a block. Miners try to guess
a nonce that will create a hash that is below the target. The only way that the
block can be accepted by the blockchain is if it is lower than the target. Finding
a nonce which creates a hash smaller than the target will allow it to be added to the blockchain.

* A smaller nonce does not mean a smaller hash.
