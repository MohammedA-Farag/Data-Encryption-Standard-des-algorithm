# Data-Encryption-Standard-des-algorithm
The Data Encryption Standard (DES ) is a symmetric-key algorithm for the encryption of electronic data.

The Data Encryption Standard (DES )
is a symmetric-key algorithm for the encryption of electronic data. 
Although insecure, it was highly influential in the advancement of modern cryptography.
 
 

The Feistel (F) function
The F-function, depicted in Figure 2, operates on half a block (32 bits) at a time and consists of four stages:
 
The Feistel function (F-function) of DES
1.	Expansion: the 32-bit half-block is expanded to 48 bits using the expansion permutation, 

2.	Key mixing: the result is combined with a subkey using an XOR operation. Sixteen 48-bit subkeys—one for each round—are derived from the main key using the key schedule 


3.	Substitution: after mixing in the subkey, the block is divided into eight 6-bit pieces before processing by the S-boxes, or substitution boxes.  produce 32bit

4.	Permutation: finally, the 32 outputs from the S-boxes are rearranged according to a fixed permutation, the P-box. This is designed so that, after permutation, the bits from the output of each S-box in this round are spread across four different S-boxes in the next round.

