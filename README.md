# SEED-Lab

This is an information security report with regards to practical implementations of RSA Public-Key Encryption and Signatures, Buffer Overflow Attacks and TCP/IP Attacks.

## RSA

RSA (Rivest Shamir Adleman) is one of the first public-key cryptosystems and is widely used for secure communications. The RSA algorithm can generate two large random prime numbers, and then use them to generate public and private key pairs, which can be used for encryption, decryption, digital signature generation, as well as digital signature verification. The RSA algorithm is built upon number theories and it can be quite easily implemented with the support of various libraries.

## Buffer Overflow

Buffer overflow is defined as the condition in which a program attempts to write data beyond the boundaries of the pre-allocated buffer length. This vulnerability can be used by a malicious user to alter the flow control of the program, leading to the execution of malicious code. This vulnerability is due to the mixing of the storage for data (e.g. buffers) and the storage for controls (e.g. return addresses). An overflow in the data part can affect the control flow of the program since an overflow can change the return address.

## TCP/IP

The vulnerabilities in the TCP/IP protocols represent a special genre of vulnerabilities in protocol design and implementations. They provide an invaluable lesson as to why security should be developed in the first place, rather than being added as an afterthought. Moreover, studying these vulnerabilities can help understand the challenges of network security and the reason that many network security measures are needed.
