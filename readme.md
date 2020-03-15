# Rangkuman

- Data security -> crypthography
- Classical cryptography (penggeseran karakter)
    - caesar cipher (Menambah atau mengurangi string)
        - encrypt
        - decrypt
    - subtitution cipher (Memasukkan karakter unique alphabet)
        - key generation (kunci, proses1, proses2)
        - encrpyt
        - decrypt
    - vigenere cipher
        - encrypt (plain + key % 26 = cipher)
        - decrypt (cipher - key % 26 = plain    )
- Modern cryopto (operasi bit)
    - xor cipher
        - encrypt (cipher = plain xor key)
        - decrpyt
    - assimetric key crpyto (rsa)
        - generate (public key, private key)
        - encryption
        - decryption
    - attack on cryptography
        - known plaintext attack
        - chosen plaintext attack
        - factorization attack
        - padding oracle attack