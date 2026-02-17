### Theory

The Data Encryption Standard (DES) is a symmetric key block cipher developed by IBM and adopted by the U.S. National Institute of Standards and Technology (NIST) in 1977. It works on 64-bit blocks of plaintext and uses a 48-bit effective key derived from DES key generation process. 
      
The DES follows a Feistel network structure consisting of 16 rounds, where each round applies substitution and permutation operations to perform confusion and diffusion.
     
The encryption process begins with an Initial Permutation (IP), followed by splitting the block into left and right halves. In each round, the right half is expanded, XORed with a round-specific subkey generated from the main key, and passed through S-boxes, which provide nonlinearity. The output is then permuted and XORed with the left half to form the new right half. After 16 rounds, the halves are swapped and passed through a Final Permutation (FP) to produce the ciphertext.
