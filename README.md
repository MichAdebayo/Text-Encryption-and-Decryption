# Text Encryption and Decryption: Implementing the Caesar Cipher and Columnar Transposition Cipher

## Case Description

Cryptography is a critical problem in programming that has engaged researchers for many decades. With better encryption methods, we can better protect sensitive information—such as passwords and personal data—and ensure secure online communication. Exploring such methods as the caesar cipher and the transposition cipher is an essential step towards contributing to the ongoing efforts to maintain data integrity and confidentiality.

### The Caesar Cipher

The caesar cipher is a simple yet effective way of encrypting a text to render it unreadable to anyone without the key to decrypting/decoding the text. It relies on substituting texts by shifting each letter in the text by a fixed number of places down or up the alphabet. In this project, I implement the caesar cipher by creating a **CaesarCipher class**.

### The Columnar Transposition Cipher

The transposition cipher is another way of encrypting a text in a more secure way (than the caesar cipher) that becomes unreadable to anyone who doesn’t possess the key to decryption. It relies on scrambling the words in plaintext by rearranging its characters. While transposition ciphers come in various forms, each contributing a unique layer of complexity, in this project, I implement the columnar transposition cipher by creating a **TranspositionCipher class**.

For both ciphers, the following were implemented: 

* A constructor function that accepts the cipher's key as an argument.
  
* A method designated for encrypting a message requiring a single parameter—the plaintext message to be encrypted.
  
* A method dedicated to decrypting a message that calls for one argument—the previously encrypted message in ciphertext format.
