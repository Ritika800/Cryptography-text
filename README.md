Crytography-text

This program demonstrates encryption and decryption using the cryptography module in Python.
First, the program imports the Fernet class from the cryptography.fernet module. The Fernet class provides the functionality for symmetric encryption.
Next, a string is assigned to the variable message. This is the string that will be encrypted.
A key is generated for encryption and decryption using the Fernet.generate_key() function. The generate_key() function generates a random 32-byte key.
An instance of the Fernet class is created, passing in the generated key as a parameter.
The encrypt() method of the fernet object is then called to encrypt the message. Before encryption, the message is encoded into a byte string using the encode() method.
The encrypted message is stored in the encMessage variable.
The program then prints the original string and the encrypted string using print(). The original string is printed as is, and the encrypted string is printed in its encrypted form.
Next, the program decrypts the encrypted string using the decrypt() method of the fernet object. The decrypted string is returned as an encoded byte string, so it needs to be decoded into a regular string using the decode() method.
The decrypted string is stored in the decMessage variable.
Finally, the program prints the decrypted string using print(). The decrypted string is the original string before encryption.
In summary, this program demonstrates how to use the Fernet class from the cryptography module to encrypt and decrypt a string using a randomly generated key.
