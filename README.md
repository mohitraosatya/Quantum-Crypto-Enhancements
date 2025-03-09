# Quantum-Enhanced Cryptography Projects

This repository contains two proof-of-concept notebooks that demonstrate quantum-enhanced cryptography. Both projects leverage quantum randomness to improve encryption key generation and integrate classical cryptographic techniques with emerging quantum security concepts.

## Projects

### 1. Quantum Secure Cryptography Sandbox
- **Description:**  
  This notebook demonstrates a hybrid cryptographic system that integrates quantum randomness with classical encryption. It fetches quantum random numbers (from the ANU QRNG API, with a fallback to Python’s secure randomness) to generate AES keys and encrypt/decrypt sample messages.
  
- **Key Features:**  
  - Retrieves quantum randomness with robust error handling.  
  - Generates AES keys and performs encryption/decryption.  
  - Visualizes the distribution of the quantum random numbers.

### 2. Quantum-Enhanced Dynamic Key Rollover System
- **Description:**  
  This notebook extends the previous concept by simulating a dynamic key rollover system. It combines a simulated post‑quantum key encapsulation mechanism (PQC KEM), quantum randomness, and a nonce to derive fresh encryption keys for each message. This approach is designed to enhance security in environments like IoT or secure messaging by continuously refreshing encryption keys.

- **Key Features:**  
  - Simulates a PQC KEM to generate a base shared secret.  
  - Derives dynamic keys by combining the base secret, quantum randomness, and a nonce.  
  - Encrypts and decrypts multiple messages with dynamically derived keys.  
  - Provides an interactive dashboard using IPyWidgets for real-time experimentation.

## Future Enhancements

- **Integrate Real PQC:** Replace the simulated PQC KEM with a production-grade post‑quantum cryptographic library (e.g., Kyber or PQClean).
- **Quantinuum Integration:** Use Quantinuum’s Quantum Origin API directly for obtaining quantum random numbers.
- **API and Dashboard:** Develop RESTful APIs and more detailed dashboards for scalable key management and monitoring.
- **Security Audits:** Perform comprehensive security audits and optimize performance for potential production deployment.

## Contact:
Email: saka4332@colorado.edu
Linkedin: https://www.linkedin.com/in/mohitraosatya/
