# RSA-Encryption

![Example](https://raw.githubusercontent.com/AdilRabbani/RSA-Encryption/master/example.PNG)

RSA Encryption in C++ <br />
1) The program first calculates two random prime numbers p and q <br />
2) n is calculated as n = p * q <br />
3) phi is as calculated as phi = (p - 1) * (q - 1) <br />
4) modular multiplicative inverse d is calculated as e * d % phi = 1 <br />
5) The message is then encrypted as C(M) = M^e % n <br />
6) The message can then be decrypted using M(C) = C^d % n <br />
Note that only alphabets (lowercase or uppercase) and spaces can be used in a message to be encrypted/decrypted. <br />
Other characters may give unexpected results.
