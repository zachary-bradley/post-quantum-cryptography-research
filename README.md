# Post-Quantum Cryptography Research

**University of North Georgia | Cybersecurity Capstone | May 2025**  
**Research Advisor: Dr. Yong Wei**

## 📄 Overview

This research analyzes post-quantum cryptographic algorithms and protocols in response to the emerging threat of quantum computing to current encryption systems. As quantum computers advance, they pose a significant risk to widely-used cryptographic systems like RSA and ECC.

This study evaluates NIST-standardized post-quantum algorithms including CRYSTALS-Kyber, CRYSTALS-Dilithium, and SPHINCS+, comparing their performance, security levels, and implementation considerations.

## 🎯 Research Objectives

- Analyze quantum computing threats to classical cryptography (RSA, ECC, Diffie-Hellman)
- Evaluate NIST Post-Quantum Cryptography standardization process
- Compare performance metrics: key sizes, computational efficiency, security levels
- Assess real-world implementation considerations for organizations
- Provide guidance for migration to quantum-resistant cryptography

## 🔬 Algorithms Analyzed

### CRYSTALS-Kyber (Key Encapsulation Mechanism)
- Lattice-based cryptography approach
- NIST standard for public-key encryption and key exchange
- Moderate key sizes with strong security guarantees

### CRYSTALS-Dilithium (Digital Signatures)
- Lattice-based signature scheme
- NIST standard for authentication and non-repudiation
- Efficient signing and verification

### SPHINCS+ (Hash-Based Signatures)
- Stateless hash-based signature scheme
- Most conservative security approach
- Larger signatures but highest confidence in long-term security

### Falcon (Lattice-Based Signatures)
- Compact signature sizes
- Fast verification
- Alternative lattice-based approach

## 📊 Key Findings


- **Performance Trade-offs:** PQC algorithms provide quantum resistance with 2-3x computational overhead compared to RSA-2048
- **Key Size Impact:** Post-quantum keys are 3-10x larger than classical cryptography equivalents
- **Security Levels:** NIST algorithms offer security equivalent to AES-128, AES-192, or AES-256
- **Implementation Timeline:** Financial services and cloud providers implementing PQC during 2025-2030 window
- **Migration Challenges:** Hybrid approaches (classical + PQC) recommended during transition period

## 🌐 Real-World Applications

This research is directly applicable to:

- **Financial Services:** Banks implementing quantum-resistant transaction security
- **Cloud Providers:** AWS, Azure, Google Cloud migrating to PQC standards
- **Government Systems:** NIST mandates for federal agency compliance
- **Blockchain/Cryptocurrency:** Securing digital assets against quantum threats
- **Healthcare:** HIPAA-compliant quantum-safe data protection
- **Telecommunications:** Quantum-safe 5G/6G network security

## 📖 Full Research Paper

📄 [Download PDF](./PQC_Capstone_Research.pdf)

## 🛠️ Research Methodology

- **Literature Review:** Analysis of quantum computing advances and cryptographic vulnerabilities
- **Standards Analysis:** Deep dive into NIST PQC standardization project (2016-2024)
- **Algorithm Comparison:** Performance benchmarking and security level evaluation
- **Implementation Study:** Assessment of migration strategies and deployment challenges
- **Industry Survey:** Review of current PQC adoption by major technology companies

## 🎓 Academic Context

- **Institution:** University of North Georgia
- **Program:** Bachelor of Science in Cybersecurity
- **Course:** Cybersecurity Capstone
- **Advisor:** Dr. Yong Wei, Computer Science Department
- **Completion Date:** May 2025

## 🔗 Related Resources

- [NIST Post-Quantum Cryptography Project](https://csrc.nist.gov/projects/post-quantum-cryptography)
- [Open Quantum Safe Project](https://openquantumsafe.org/)
- [NIST PQC Standardization Round 4](https://csrc.nist.gov/Projects/post-quantum-cryptography/selected-algorithms-2022)

## 💡 Why This Matters

**"Q-Day"** - the point when quantum computers can break current encryption - is estimated to arrive in the 2030s. However:

- Data encrypted today could be stored and decrypted later ("harvest now, decrypt later" attacks)
- Migration to PQC takes years for large organizations
- Compliance standards are already requiring quantum-safe roadmaps
- **The time to implement PQC is NOW**

This research provides the foundation for understanding and implementing quantum-resistant cryptography before Q-Day arrives.

## 📫 Contact

**Author:** Zachary Bradley   
**LinkedIn:** www.linkedin.com/in/zachary-bradley-communications
**Email:** zach9508@gmail.com  
**GitHub:** [github.com/zachary-bradley](https://github.com/zachary-bradley)

Questions about this research or interested in collaboration? Feel free to reach out.

---

*This capstone research was completed as part of the Bachelor of Science in Cybersecurity program at the University of North Georgia under the guidance of Dr. Yong Wei.*
