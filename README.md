# RSA-Encryption
RSA Encryption in C++. The program calculates two random prime numbers p and q <br />
n is calculated as n = p * q <br />
phi is as calculated as phi = (p - 1) * (q - 1) <br />
modular multiplicative inverse d is calculated as e * d % phi = 1 <br />
The message is then encrypted as C(M) = M^e % n <br />
The message can then be decrypted using M(C) = C^d % n <br />
