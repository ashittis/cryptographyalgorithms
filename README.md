### **Classical Ciphers - 14 Encryption Algorithms**

This repository provides implementations for **14 classical cipher algorithms**, commonly used for educational purposes and cryptography practice. It includes both **encryption and decryption** functions for each algorithm, enabling users to explore and experiment with traditional cryptographic techniques interactively.

---

### **Ciphers Included:**

**1. Caesar Cipher**  
Shifts each letter in the plaintext by a fixed number of positions in the alphabet.  
*Example*: A shift of 3 turns "A" into "D", "B" into "E", etc.

**2. Atbash Cipher**  
A substitution cipher where the alphabet is reversed.  
*Example*: "ABC" becomes "ZYX".

**3. August Cipher**  
A polyalphabetic cipher that applies a fixed pattern of shifts to the plaintext.  
*Example*: Key 3 → shifts like 3, 2, 1.

**4. Affine Cipher**  
Uses a formula `E(x) = (ax + b) mod m` for encryption.  
*Example*: With `a = 5`, `b = 8`, the transformation is applied to each character.

**5. Vigenère Cipher**  
Uses a keyword to determine shifting of letters in the plaintext.  
*Example*: Key "KEY" shifts the text based on K, E, Y.

**6. Gronsfeld Cipher**  
Like Vigenère, but with numeric keys.  
*Example*: Key "31415" → shifts like 3, 1, 4, 1, 5.

**7. Beaufort Cipher**  
Similar to Vigenère but uses reverse operations.  
*Example*: Subtract letter index from a fixed value.

**8. Autokey Cipher**  
The key extends with the plaintext itself.  
*Example*: First key letter is used, then the rest comes from the message.

**9. N-Gram Cipher**  
Analyzes sequences of n letters in ciphertext for pattern detection.  
*Example*: "TH", "HE", "ER" are common English 2-grams.

**10. Hill Cipher**  
Uses matrix multiplication on letter blocks.  
*Example*: Encrypt 2-letter pairs with a 2x2 matrix.

**11. Rail Fence Cipher**  
Zigzag text across multiple rails and then read row by row.  
*Example*: Text distributed in 3-rails pattern.

**12. Route Cipher**  
Arranges text in a grid, then reads it in a set pattern.  
*Example*: Spiral inwards or zigzag across the grid.

**13. Myszkowski Cipher**  
Uses keyword repetition and a specific read order based on repeating key digits.  
*Example*: Key "CONVOY" → Read columns based on repeated characters.

**14. Columnar Transposition Cipher**  
A transposition cipher where plaintext is written in rows under columns labeled by a keyword. The ciphertext is formed by reading columns in the order defined by the alphabetical order of the keyword's letters.  
*Example*: Key "ZEBRAS" → Arrange message under it in rows, then read columns in alphabetical key order (A to Z).

---

### **Features:**

- **Encryption and Decryption** for all 14 classical cipher types.  
- **Interactive Interface** for user inputs and mode selection.  
- **Educational Resource** for exploring traditional encryption methods.

---

### **Conclusion:**

This repository is perfect for anyone interested in learning and experimenting with classical cryptography techniques. Whether you're a beginner or exploring historical ciphers, this serves as a hands-on guide to mastering the foundations of encryption.
cryptoalgos mukkiyam biguluu
