# 🔐 Nova Locker v1.0.0

Nova Locker is a next-generation file encryption and decryption utility developed under the **Netbyteware** brand. It aims to maximize digital privacy and security by delivering military-grade encryption standards directly to end-users in a completely **free**, straightforward, and independent package.

---

## 🚀 Key Features

*   **Military-Grade Protection (AES 256-Bit):** Utilizes the Advanced Encryption Standard (AES) with a 256-bit key length—the global benchmark for data security. Your files are secured behind an algorithmic wall that cannot be breached by even modern supercomputers.
*   **Dual-Core Security Mechanism:** Seamlessly encrypt or decrypt your sensitive files within seconds through a unified, intuitive workflow.
*   **Zero-Knowledge Architecture:** Your custom encryption passphrases and keys are processed strictly locally. They are never transmitted, tracked, or stored on any remote servers. Your security remains entirely under your control. 
*   **End-User Focused Design:** Replaces complex cryptographic terminal commands and confusing parameters with a clean, efficient user experience designed for users of all technical backgrounds.
*   **100% Free Software:** We believe digital security is a fundamental right, not a luxury. Nova Locker provides all its core features free of charge.

---

## 🛠️ Technical Specifications & Workflow

Nova Locker operates on a local byte-level manipulation process. Upon execution, your entered passphrase undergoes a secure hashing process to generate a robust 256-bit key for the AES algorithm.

1. **Encryption Mode:** The application reads the target file at a binary level, scrambles it using the AES-256 protocol, and renders the original file completely unreadable without the correct key.
2. **Decryption Mode:** Once the encrypted file is selected and the precise matching passphrase is provided, the algorithm runs in reverse to restore the file to its original, uncorrupted form.

---

## ⚠️ Antivirus Alerts (False Positive Disclaimer)

**Important Notice:** Nova Locker is architected using Python and packaged into a standalone executable (`.exe`) file, allowing end-users to run the application immediately without requiring any pre-installed Python environments or external libraries.

The internal mechanics of modern Python bundlers (such as PyInstaller, cx_Freeze, etc.) involve compressing the entire source tree along with the Python interpreter into a single binary. Due to this compression method, certain heuristic scanning engines of popular antivirus software may flag the executable as a "suspicious or unknown threat". In the software development community, this is a well-known phenomenon called a **False Positive (False Alarm)**.

### 🛡️ Transparency & Trust Report
Our software contains absolutely zero malware, adware, hidden trackers, or telemetry. To give you complete peace of mind, you can transparently inspect the real-time, independent scan reports here:

🔗 **[Click Here to View the Live VirusTotal Scan Results](https://www.virustotal.com/gui/file/b3cc399f4a65ea66d703d30c7812cf1d63bd9d34a53199d2cb49846f6459729e/detection)**

---

## 💻 System Requirements

*   **Operating System:** Windows 10 / Windows 11 (64-bit architectures recommended)
*   **Dependencies:** Completely standalone. No additional framework, runtime, or Python installation required.

---

## 📣 Legal Disclaimer
Nova Locker implements robust cryptographic protocols. Remembering and securely storing the passphrases you assign to your encrypted files is entirely your responsibility. It is technically impossible to brute-force, bypass, or recover data from files if the matching passphrase is lost.

---
*Building the technologies of tomorrow...*  
**Netbyteware © 2026**
