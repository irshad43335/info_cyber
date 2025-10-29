# 🔐 Encryption Techniques — 05

## 🎯 Learning Objectives
- Understand cryptography basics  
- Differentiate between symmetric and asymmetric encryption  
- Learn hashing and digital signature concepts  

---

## 🧩 Cryptography
Cryptography is a technique of securing information and communications using codes to ensure confidentiality.

---

## 🔸 Symmetric Encryption
- Uses one key for both encryption and decryption.  
- Fast, suitable for bulk data encryption.  

---

## 🔹 Asymmetric Encryption
- Uses two keys: public key (for encryption) and private key (for decryption).  
- Used for secure key exchange and digital communication.  

---

## 🔑 Hashing
- Converts data into a fixed-length string.  
- Used for secure data integrity verification.
- used for password storage and integrity checking.
- common algorithm: sha-256, mds(deprected)


  ## digital signature and certifications
   -ensure authenticity and non-repudiation
   - A digital signature uses private key to sign data and public key to verify.
   - Certificates (X.509) are issued by Certificate Authorities (CAs) for trust verification (used in HTTPS)
 
## example:
when visiting htttps://bank.com
- browser verifies certification by ca to ensure authenticity
