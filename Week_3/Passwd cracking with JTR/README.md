# John the Ripper – PDF Password Cracking Lab

## Project Overview

This project demonstrates the use of **John the Ripper (JTR)**, a widely used open-source password security auditing and recovery tool, to recover passwords from encrypted PDF documents.

The lab was performed using **John the Ripper on Kali Linux** to extract PDF password hashes, perform dictionary-based password attacks, and recover the original passwords.

The exercise demonstrates how password cracking works, the importance of password complexity, and why strong password protection is essential for securing sensitive documents.

## Objectives

- Understand the fundamentals of password cracking.
- Explore John the Ripper and its capabilities.
- Extract password hashes from encrypted PDF documents.
- Perform dictionary-based password attacks.
- Recover passwords from protected PDF files.
- Understand the importance of strong passwords and document security.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| John the Ripper | Password recovery and auditing |
| pdf2john | Extract password hashes from PDF files |
| Terminal | Execute password recovery commands |

## Lab Environment

- **Operating System:** Kali Linux
- **Password Cracking Tool:** John the Ripper
- **Attack Method:** Dictionary Attack
- **Target Files:** Three password-protected PDF documents

## Methodology

### 1. Environment Preparation

Used Kali Linux, where John the Ripper is available for password auditing and recovery.

### 2. PDF Hash Extraction

Extracted password hashes from the protected PDF documents using the PDF hash extraction utility (`pdf2john`).

### 3. Hash Preparation

Saved the extracted PDF password hashes into text files for processing by John the Ripper.

### 4. Password Cracking

Used John the Ripper with a wordlist to perform dictionary-based password attacks against the extracted hashes.

### 5. Password Verification

Verified the recovered passwords by opening the corresponding encrypted PDF documents.

## Results – Password Recovery

Successfully recovered passwords from all three protected PDF documents.

| PDF File | Recovered Password | Recovered Flag |
|---|---|---|
| My Locked PDF1.pdf | `good-luck` | `nm{Cybersecurity_flag_captured_2608}` |
| My Locked PDF2.pdf | `password1` | `nw{networkwalks_persistence_jtr_270521}` |
| My Locked PDF3.pdf | `1qaz2wsx` | `nw{networkwalks_flag_260821_1}` |

**Result:** 3 out of 3 PDF passwords successfully recovered.

## Key Learnings

- Learned how password-protected PDF files store password verification data.
- Understood PDF hash extraction and its role in password auditing.
- Practiced dictionary-based password cracking using John the Ripper.
- Learned how password complexity affects password recovery time.
- Understood the security risks associated with weak and commonly used passwords.
- Gained practical experience with Linux-based security testing tools.

## Security Takeaways

This lab demonstrates that weak or commonly used passwords can be vulnerable to dictionary-based attacks.

**Recommended security practices:**

- Use long and unique passwords.
- Avoid common passwords and predictable patterns.
- Use password managers to generate and store strong passwords.
- Apply appropriate encryption to sensitive documents.
- Never reuse passwords across multiple accounts or files.

## References

- [John the Ripper – Official Website](https://www.openwall.com/john/)
- [John the Ripper – Documentation](https://www.openwall.com/john/doc/)
- [Johnny GUI – Official Website](https://openwall.info/wiki/john/johnny)
- [Kali Linux – Official Website](https://www.kali.org/)

## Disclaimer

This project was conducted strictly for educational purposes in a controlled cybersecurity learning environment.

Password recovery was performed only on provided lab documents. Do not attempt to crack passwords or access protected files without proper authorization.

---

**Project Category:** Cybersecurity | Password Security | Password Auditing

**Tools:** Kali Linux | John the Ripper | pdf2john

**Lab Status:** Completed
