# ethHW HW1

# HW link:
https://hackmd.io/wApWgkUpR8WJEaLNbYz5Kw?view

(20%) 1. Please compare hash function and cryptographic hash function and give an example.

(80%) 2. Peter is a noob in cryptocurrency and would like to get some Ethers. First step for him is to have an Ethereum account. He decides to generate an account and manages the wallet himself so he can understand the principles behind. From the class, he knows the account is created by the following steps:

1.Create a keypair of private/public key

2.public_key = ECDSA(private_key)

3.public_key_hash = Keccak-256(public_key)

4.address = '0x' + last 20 bytes of public_key_hash

# -----


(30%) a. Can you print the private/public key with hex string representation? Please give us an example.

duruoyude-MacBook-Pro:Desktop kakitsubatasakai$ cd ethHW

duruoyude-MacBook-Pro:ethHW kakitsubatasakai$ node key.js

privKey: <Buffer dc 53 81 c0 03 0b bf 2a 31 2c 33 ac b1 58 c4 4f 99 33 c0 82 0e 36 ad 4e 22 4a 4e f2 37 50 cc 31>

pubKey: <Buffer 93 8f 31 f4 4c 35 99 7b bd 74 91 b8 49 0f 1a 47 35 92 49 ee e4 a0 b7 a3 f6 74 ef b3 e4 08 a3 0f ac 1d fa 27 62 86 01 88 e8 3f 85 64 39 ff b1 50 31 a3 ... >

address: 0x6e2ab271512a340ffa9ea25c8ab486ac99a004f4

(20%) b. In addition, if we don’t want to use the getAddressString() to get the address, how can we obtain the address by hashing the public key?

(30%) c. There is a file called Keystore that is used to encrypt the private key and save in a JSON file. Can you generate a Keystore with the password “nccu”? You can find the details about Keystore below.