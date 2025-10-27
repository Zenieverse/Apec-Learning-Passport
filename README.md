# Apec-Learning-Passport
This application provides a working model for your Learning Passport problem, specifically focusing on Data Standardization &amp; Source Verification using a mock Verifiable Credentials (VC) approach.



Summary of Solution

Issuance (The University's Role): When you click "Issue Credential", the app sends the student data to the Gemini API. The API generates a unique, cryptographically-secure hash and a digital signature. This simulates the university signing the credential and recording its hash on the blockchain. The complete record is saved to Firestore (our distributed data ledger).

Verification (The Employer's Role): You can copy the generated Record ID and paste it into the Verification View. The app instantly checks the ID against the secure record, providing a "CREDENTIAL VERIFIED" confirmation, along with the immutable Credential Hash and Digital Signature.

This addresses the core issues of forgery prevention, instant verification, and reduced administrative burden—the three key advantages of a Learning Passport.

What would you like to explore next? We could:

Expand the Data Model: Integrate Problem 1.3 by adding fields to capture "hidden skills" like Peer Review Scores or Project Links (Proof of Skill).

Create the Reward Token: Implement a basic version of Problem 2 by creating a UI to mint and display a mock $APECTOKEN reward for completing this credential.

Design the Dual-Degree Structure: Outline the curriculum and module structure for the "Entrepreneurship & Data Science" dual degree.
