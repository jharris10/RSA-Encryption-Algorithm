# RSA-Encryption-Algorithm
RSA encrpytion algorithm implement in Python using sys, random, pickle libraries

# Introduction
RSA is a very strong encryption algorithm, so using it should be simple for everyone, as I am a very strong believer in the right of privacy and getting information the right way.
I present to you the simplest way to write the RSA encryption algorithm, the code contains the encryption and decryption methods in addition to that, the RSA key generator. 
You are free to use it however you want without adding my name to the code.

Thank you

# Usage
Install Python 3.4
Clone the repo
Using Python CLI, run py/python(Depends on your system) RSA-Encryption-Algorithm.py 
Giving it the parameters according to the usage needed

# To generate:

# RSA keys: 
  python RSA-Encryption-Algorithm.py  init <keys_filename> <prime_bitlength>
  ex. python RSA-Encryption-Algorithm.py  init bodineac_keys 512
   
   
 # To encrypt data: 
 python RSA-Encryption-Algorithm.py  encrypt <keys_filename> <plaintext_filename> <ciphertext_filename>
 ex. python RSA-Encryption-Algorithm.py  encrypt bodineac_keys plaintext ciphertext
  
  
  # To decrypt data: 
  
  python RSA-Encryption-Algorithm.py  decrypt <keys_filename> <ciphertext_filename> <decrypted_filename>
  ex. python RSA-Encryption-Algorithm.py decrypt bodineac_keys ciphertext decrypted
  
  Thank you :D
  
  # TO-DO:
  -Create a Voice encryption software by changing the voice notes into a BSON file
  -Create a block-chain RSA encryptor

