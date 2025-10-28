# Apec-Learning-Passport
This application provides a working model for your Learning Passport problem, specifically focusing on Data Standardization &amp; Source Verification using a mock Verifiable Credentials (VC) approach.

https://gemini.google.com/share/b2857157f740

<img width="1536" height="1024" alt="IMG_1321" src="https://github.com/user-attachments/assets/44f24695-94f1-4035-8b1a-4873eb4b8b7d" />


![IMG_1323](https://github.com/user-attachments/assets/47e64e86-7fe8-4f39-8250-c5be9e269148)


Summary of Solution

Issuance (The University's Role): When you click "Issue Credential", the app sends the student data to the Gemini API. The API generates a unique, cryptographically-secure hash and a digital signature. This simulates the university signing the credential and recording its hash on the blockchain. The complete record is saved to Firestore (our distributed data ledger).

Verification (The Employer's Role): You can copy the generated Record ID and paste it into the Verification View. The app instantly checks the ID against the secure record, providing a "CREDENTIAL VERIFIED" confirmation, along with the immutable Credential Hash and Digital Signature.

This addresses the core issues of forgery prevention, instant verification, and reduced administrative burden—the three key advantages of a Learning Passport.

