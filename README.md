Diffie-Hellman key exchange Coding Project

Explanation of the algorithm :

The following algorithm illustrates the Diffie-Hellman key exchange, which allows two parties to establish a shared secret securely over an unsecured medium.
In the following algorithm, we will take two fictive persons : Alice and Bob, trying to share a secret over an unsecured medium. For the secret to be kept Alice and Bob will need to compute each one private and public key ; for their private and public key to be computed they will need to agree uppon a prime number ("p" in the program) and a generator of the prime number ("g" in the program). The public key will then be exchanged between the two parties, and knowing the public key, both Alice and Bob will be able to know the shared secret.
