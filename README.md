# Substitution
Substitution is a program that is created for CS50 Problem Set 2. The program is used to encrypt plaintext into ciphertext and it is created by using C. The users have to run the C file with an extra command line argument known as "key", in the format of "./substitution key". Then, the users will be prompted to enter plaintext in strings. After that, the plaintext will be encrypted into ciphertext based on the "key" entered in the command line argument.

# Information about Substitution (Encryption)
In a substitution cipher, we “encrypt” (i.e., conceal in a reversible way) a message by replacing every letter with another letter. To do so, we use a key: in this case, a mapping of each of the letters of the alphabet to the letter it should correspond to when we encrypt it. To “decrypt” the message, the receiver of the message would need to know the key, so that they can reverse the process: translating the encrypt text (generally called ciphertext) back into the original message (generally called plaintext).

A key, for example, might be the string NQXPOMAFTRHLZGECYJIUWSKDVB. This 26-character key means that A (the first letter of the alphabet) should be converted into N (the first character of the key), B (the second letter of the alphabet) should be converted into Q (the second character of the key), and so forth.

A message like HELLO, then, would be encrypted as FOLLE, replacing each of the letters according to the mapping determined by the key.

# How to Run the Project
1) Download all the files.
2) Open the "substitution.c" file and run the project.
3) Run the command `./substitution [24 unique uppercase characters]`

# Some Screenshots from the Program 
![cs50 pset 2 ss1](https://user-images.githubusercontent.com/95561298/178780713-7ed243c2-bde3-45c6-ba51-61721e1e5970.png)

# Reference 
https://cs50.harvard.edu/x/2022/psets/2/substitution/
