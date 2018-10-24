# ethHW HW1

# HW link:
https://hackmd.io/wApWgkUpR8WJEaLNbYz5Kw?view

(20%) 1. Please compare hash function and cryptographic hash function and give an example.

(80%) 2. Peter is a noob in cryptocurrency and would like to get some Ethers. First step for him is to have an Ethereum account. He decides to generate an account and manages the wallet himself so he can understand the principles behind. From the class, he knows the account is created by the following steps:

1.Create a keypair of private/public key

2.public_key = ECDSA(private_key)

3.public_key_hash = Keccak-256(public_key)

4.address = '0x' + last 20 bytes of public_key_hash

#-----


(30%) a. Can you print the private/public key with hex string representation? Please give us an example.

(20%) b. In addition, if we don’t want to use the getAddressString() to get the address, how can we obtain the address by hashing the public key?

(30%) c. There is a file called Keystore that is used to encrypt the private key and save in a JSON file. Can you generate a Keystore with the password “nccu”? You can find the details about Keystore below.