# Secure Online Voting System

A system that explores the challenges of **high-integrity online voting**: preventing tampering, coercion, and duplicate votes, while ensuring verifiability.

## ✨ Features
- **Voting Process**
  - Anonymous ballot submission  
  - Prevention of duplicate votes (per user/session)  
  - Resistance against vote tampering  

- **Security & Integrity**
  - Audit logs for verifiable counting  
  - Raw ballot storage in MongoDB for audit and forensic analysis  
  - Hash-based signatures to ensure immutability  
  - Optional end-to-end encryption for ballots  

- **Counting & Verification**
  - Transparent tallying process  
  - Detect inconsistencies in vote records  
  - Observer mode for external verification  

- **Extensions (Future)**
  - AI-based anomaly detection in voting patterns  
  - Coercion-resistance protocols  

## 🛠 Tech Stack
- Java 25 (LTS), Spring Boot 3  
- MySQL (ACID transactions for ballot storage)  
- Redis (session control, duplicate prevention)  
- MongoDB (raw ballot & audit log storage)  
- Docker, Testcontainers  

## 📚 What I Learned
- Balancing **performance with data correctness** under sensitive conditions  
- Designing **tamper-proof audit logs**  
- Understanding trade-offs between **anonymity and verifiability**  
- Extending business logic with **security-first mindset**  
