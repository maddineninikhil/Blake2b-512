# Blake2b-512
BLAKE2 is cryptographic hash function based on Dan Bernstein's ChaCha stream.
A new hash function with its design based on that of BLAKE called BLAKE2 was announced in December 21, 2012. It was created by Jean-Philippe Aumasson, Samuel Neves, Zooko Wilcox-O'Hearn, and Christian Winnerlein with the goal to replace widely used, but broken MD5 and SHA-1 algorithms.The reference implementation code was released under CC0.

BLAKE2 removes addition of constants to message words from BLAKE round function, changes two rotation constants, simplifies padding, adds parameter block that is XOR'ed with initialization vectors, and reduces the number of rounds from 16 to 12 for BLAKE2b (successor of BLAKE-512).

The source-code here is a Blake2b-512 implemention in python.
This is just a sample code which meets all the conditions presented in Whitepaper and Wikipedia.
