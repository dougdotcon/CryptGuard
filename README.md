# 🔐 CryptGuard

<div align="center">

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Security](https://img.shields.io/badge/security-audited-green.svg)](SECURITY.md)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

**CryptGuard is an advanced encryption solution with a modern interface, focused on security and usability.**

[🚀 Quick Start](#-quick-start) •
[📖 Documentation](#-documentation) •
[🛡️ Security](#-security) •
[🤝 Contribute](#-contribute) •
[📜 License](#-license)

</div>

## ✨ Features

- 🔒 **Robust Encryption**
  - ChaCha20Poly1305 for authenticated encryption
  - Argon2id for key derivation
  - Reed-Solomon for error correction

- 🎯 **Advanced Functionality**
  - Text and file encryption
  - Multi-file support
  - Hidden volumes with plausible deniability
  - Ephemeral tokens for added security

- 💫 **Modern Interface**
  - Design inspired by Meta apps
  - Responsive and intuitive UI
  - Real-time visual feedback
  - Password strength indicator

- 🛡️ **Enhanced Security**
  - Password strength verification via zxcvbn
  - Key file support
  - Encrypted metadata
  - Protection against known attacks

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
bash
git clone https://github.com/Crypt-Guard/CryptGuard.git
cd CryptGuard


2. Install dependencies:
bash
pip install -r requirements.txt


3. Run CryptGuard:
bash
python cryptguard_ui.py


## 💡 Usage Guide

### Encrypt File

1. Enter a strong password
2. (Optional) Configure advanced Argon2id parameters
3. Click "Encrypt File"
4. Select the desired file
5. Wait for success confirmation

### Decrypt File

1. Enter the correct password
2. Click "Decrypt File"
3. Select the .encrypted file
4. The file will be restored with its original name

### Hidden Volumes

1. Prepare two sets of files (decoy and real)
2. Use different passwords for each volume
3. Save the generated ephemeral token
4. Use the token to access the real volume

## 📖 Documentation

- [RoadMap](ROADMAP.md) - Features and future plans
- [Security](SECURITY.md) - Security guide and best practices
- [Contributing](CONTRIBUTING.md) - How to contribute to the project
- [License](LICENSE) - Licensing terms

## 🛡️ Security

CryptGuard is designed with security in mind, but we recommend:

- Performing independent audits
- Following security best practices
- Keeping backups of important data
- Verifying legal compliance

See [SECURITY.md](SECURITY.md) for more information.

## 🤝 Contribute

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📜 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.