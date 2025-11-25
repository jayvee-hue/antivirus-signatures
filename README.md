# Antivirus Pro Signatures Repository

Open-source virus signature database for **Antivirus Pro** (Python/PySide6 antivirus).

## Features
- MD5 + SHA256 hashes of real malware
- Versioned updates
- YARA rule references
- Used by thousands of users (soon!)

## Format
```json
{
  "version": "1.0.0",
  "md5": ["..."],
  "sha256": ["..."],
  "yara_rules": [", updatedAt": "ISO timestamp"
}
