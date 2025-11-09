# **<ins>Ciphers</ins>**:-
A cipher is a method used to convert readable information (plaintext) into an unreadable form (ciphertext) to protect it from unauthorized access. Ciphers work by applying a specific set of rules or algorithms, often controlled by a key. Only someone with the correct key or decoding method can reverse the process and recover the original message.

Ciphers can be classical, based on simple letter substitutions or shifts, or modern, using complex mathematical algorithms to secure digital communication. They form the foundation of cryptography and are widely used in secure messaging, data protection, network security, and authentication systems.

## **<ins>Types of ciphers</ins>**:-

### **1.<ins>Base64</ins>**:-
**<ins>Category</ins>**: Encoding (not encryption).<br>
Base64 converts binary data into ASCII characters using a 64-symbol set. It ensures safe text transmission over systems that may not handle binary data correctly. Base64 provides no confidentiality because the process is fully reversible without a key. It is widely used in email encoding, image embedding, and data transfer in web technologies.

### **2.<ins>Caesar Cipher</ins>**:-
**<ins>Category</ins>**: Classical substitution.<br>
The Caesar cipher shifts every letter in the plaintext by a fixed number of positions. For example, a shift of 3 replaces A→D, B→E, etc. Although historically important, it is trivial to defeat. Only 25 possible keys exist, allowing easy brute-force attacks and frequency analysis.

### **3.<ins>Vigenère Cipher</ins>**:-
**<ins>Category</ins>**: Polyalphabetic substitution<br>
The Vigenère cipher improves on the Caesar method by using a keyword. Each letter of the keyword specifies a different shift, producing a sequence of Caesar ciphers. While once called “unbreakable,” it can be solved using the Kasiski examination and statistical analysis. It demonstrates the transition from simple to more sophisticated classical ciphers.

### **4.<ins>ROT13</ins>**:-
**<ins>Category</ins>**: Caesar variant.<br>
ROT13 is a fixed shift of 13 positions. Because the alphabet has 26 letters, applying ROT13 twice returns the original text. It is used only for lightweight text obfuscation in forums, puzzles, and spoiler tags. It is not a security mechanism.

### **5.<ins>Monoalphabetic Substitution Cipher</ins>**:-
**<ins>Category</ins>**: Substitution.<br>
A monoalphabetic cipher replaces each letter with another symbol or letter using a fixed mapping. Although the possible number of keys is extremely large (26!), frequency analysis makes these ciphers easy to break. They highlight the weaknesses of fixed substitution systems.

### **6.<ins>Four-Square Cipher</ins>**:-
**<ins>Category</ins>**: Polygraphic substitution.<br>
The Four-Square cipher uses four 5×5 letter grids to encrypt digraphs (pairs of letters). This approach hides patterns better than monoalphabetic ciphers and slows frequency attacks. However, it still lacks the complexity needed for modern security.

### **7.<ins>Pigpen Cipher</ins>**:-
**<ins>Category</ins>**: Symbol substitution.<br>
The Pigpen (or Masonic) cipher maps letters to geometric symbols derived from grid patterns. It is visually appealing and simple to use. Security is low because symbols follow predictable shapes and are widely recognized.

### **8.<ins>Zodiac 340 Cipher</ins>**:-
**<ins>Category</ins>**: Custom mixed cipher.<br>
The “340 cipher,” sent by the Zodiac Killer in 1969, combines substitution, transposition, diagonal reading patterns, and irregular symbol placement. It remained unsolved for 51 years until deciphered in 2020. Although not a formal cipher system, it demonstrates how complexity and irregular structure can delay cryptanalysis.

### **9.<ins>AES (Advanced Encryption Standard)</ins>**:-
**<ins>Category</ins>**: Modern symmetric encryption.<br>
AES is the global standard for secure data encryption. It uses 128-bit blocks and supports keys of 128, 192, or 256 bits. AES employs substitution–permutation networks and repeated rounds to ensure resistance to cryptanalytic attacks. It is used in TLS, VPNs, Wi-Fi (WPA2/WPA3), mobile devices, and disk encryption. AES remains one of the strongest and most trusted ciphers.

### **10.<ins>RSA (Rivest–Shamir–Adleman)</ins>**:-
**<ins>Category</ins>**: Asymmetric encryption.<br>
RSA uses a public key for encryption and a private key for decryption. Its security comes from the difficulty of factoring large numbers produced from two large primes. RSA is widely used for secure key exchange, digital signatures, and authentication.
It is computationally heavy, so it does not encrypt large data directly. Instead, it protects small keys that are then used by faster symmetric ciphers. RSA remains widely deployed in HTTPS, email security, and authentication systems, though larger key sizes are required to maintain security.

### **11.<ins>DES (Data Encryption Standard)</ins>**:-
**<ins>Category</ins>**: Symmetric block cipher.<br>
DES encrypts data in 64-bit blocks using a 56-bit key. It uses a 16-round Feistel structure based on substitution and permutation operations. DES was once a global standard but is now considered insecure because its key size is too small and vulnerable to brute-force attacks.
Its extended form, Triple DES (3DES), improved security but introduced performance overhead. DES is now replaced by AES in modern systems but remains historically important in the evolution of cryptography.
