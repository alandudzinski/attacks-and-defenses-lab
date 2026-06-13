# Attacks and Defenses Lab: CIA Triad, Cryptography, and Security Controls

## 1. Project Overview
This project goes over the key concepts from TryHackMe's Attacks and Defenses module. The goal is to explain how attackers and defenders think by mapping common attacks to the CIA Triad, security controls, and detection methods.

## 2. The CIA Triad
The CIA Triad is a core cybersecurity model.

| Principle | Meaning | Example |
|---|---|---|
| Confidentiality | Protecting data from unauthorized access | Encrypting customer passwords |
| Integrity | Making sure data is accurate and unchanged | File hashes and digital signatures |
| Availability | Keeping systems accessible when needed | DDoS protection and backups |

## 3. Cryptography Basics
Cryptography protects data by making it unreadable or verifiable to the recipient that the data has not been tampered with.

Common uses:
- Encrypting data in transit
- Encrypting stored files
- Verifying data/file integrity
- Protecting passwords
- Supporting HTTPS

| Concept | Simple Meaning |
|---|---|
| Encryption | Scrambles data so unauthorized users cannot read it |
| Decryption | Converts encrypted data back into readable form |
| Hashing | Creates a fixed-length fingerprint of data |
| Digital signature | Proves data came from a trusted source and was not changed |
| HTTPS | Uses encryption to protect browser-server communication |

## 4. Attack vs Defense Matrix
The following is also located [HERE](https://github.com/alandudzinski/attacks-and-defenses-lab/blob/main/attack-defense-matrix.md) for reference.
| Attack | What It Targets | CIA Impact | Defense | Detection |
|---|---|---|---|---|
| Phishing | Users and credentials | Confidentiality | Security awareness, MFA, email filtering | Suspicious login alerts |
| Brute-force login | Passwords | Confidentiality | Strong passwords, MFA, account lockout | Repeated failed logins |
| Malware | Endpoints and files | Integrity, Availability | Antivirus, patching, least privilege | Unknown processes, alerts |
| DDoS | Servers and networks | Availability | Rate limiting, CDN, DDoS protection | Traffic spikes |
| Man-in-the-middle | Network traffic | Confidentiality, Integrity | HTTPS, VPN, secure Wi-Fi | Certificate warnings |
| SQL injection | Web apps and databases | Confidentiality, Integrity | Input validation, prepared statements | Unusual database queries |
| Ransomware | Files and systems | Availability, Integrity | Backups, endpoint protection, patching | File encryption behavior |
| Weak passwords | User accounts | Confidentiality | Password policy, MFA | Failed login patterns |

## 5. Offensive vs Defensive Thinking

## 6. Example Scenarios

## 7. Security Controls

## 8. Cybersecurity Importance

## 9. What I Learned

## References
- TryHackMe. "Attacks and Defenses." TryHackMe, [https://tryhackme.com/](https://tryhackme.com/module/attacks-and-defenses)

## Disclaimer
This project is for educational purposes only. It summarizes concepts learned through TryHackMe and does not include walkthrough answers, flags, or private room solutions.
