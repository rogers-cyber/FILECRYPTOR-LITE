# FILECRYPTOR LITE – Simple Secure File Encryption Tool v1.0.0

FILECRYPTOR LITE v1.0.0 is a lightweight desktop application designed for secure file encryption and decryption using password-based protection. It allows users to quickly encrypt multiple files into secure `.enc` format and decrypt them back using the correct password.

Built with a modern Tkinter + ttkbootstrap interface, FILECRYPTOR LITE focuses on simplicity, speed, and offline security. It uses strong cryptographic standards including PBKDF2 key derivation and Fernet symmetric encryption to ensure data safety.

------------------------------------------------------------
WINDOWS DOWNLOAD (EXE)
------------------------------------------------------------

Download the latest Windows executable from:

https://matetools.gumroad.com

- No Python installation required  
- Standalone Windows executable  
- Fully offline encryption/decryption  
- Lightweight and fast performance  
- Simple drag & batch workflow  

------------------------------------------------------------
FEATURES
------------------------------------------------------------

CORE CAPABILITIES

- 🔒 AES-grade symmetric encryption using Fernet
- 🔑 Password-protected file encryption
- 📂 Batch file encryption and decryption
- ⚡ Fast processing with real-time progress tracking
- 🧠 Secure key derivation using PBKDF2HMAC (SHA-256)
- 🧂 Unique salt generation per file for maximum security
- 🗂 Multiple file selection support
- 🧹 Clear session and reset workflow
- 💻 Fully offline operation (no internet required)
- 📊 Activity log system for all operations

ENCRYPTION DETAILS

- PBKDF2HMAC key derivation (390,000 iterations)
- SHA-256 hashing algorithm
- 16-byte random salt per file
- Fernet symmetric encryption (AES-based)
- Secure password validation dialog
- Protection against invalid token decryption

FILE HANDLING

- Supports encryption of any file type
- Output format: `.enc`
- Automatic restore naming during decryption
- Handles multiple file processing safely
- Skips corrupted or invalid encrypted files
- Continues batch processing even on errors

USER INTERFACE

- Modern ttkbootstrap UI (Flatly theme)
- Clean file selection panel
- Drag-and-drop ready architecture (TkinterDnD)
- Password confirmation dialog
- Real-time progress bar
- Live activity log system
- Simple Encrypt / Decrypt workflow buttons
- About window with app details and links

------------------------------------------------------------
USAGE GUIDE
------------------------------------------------------------

1. Select Files  
Click "Select Files" to choose one or more files for processing.

2. Choose Action  
- Click "Encrypt" to secure files  
- Click "Decrypt" to restore files  

3. Set Password  
Enter and confirm a secure password in the dialog box.

4. Processing  
The app will encrypt/decrypt files and display progress in real time.

5. Output  
- Encrypted files are saved as `.enc`  
- Decrypted files are restored automatically or saved with `.restore`

------------------------------------------------------------
SECURITY DESIGN
------------------------------------------------------------

FILECRYPTOR LITE ensures strong protection through:

- Unique salt per file encryption
- Strong PBKDF2 key stretching
- Industry-standard Fernet encryption layer
- Password-based key generation
- Protection against wrong password decryption (InvalidToken handling)
- No data transmission (fully offline)

------------------------------------------------------------
ERROR HANDLING & SAFETY
------------------------------------------------------------

- Detects invalid or corrupted encrypted files
- Handles incorrect password attempts safely
- Continues batch processing even if a file fails
- Prevents crashes from unsupported file structures
- Displays detailed logs for debugging and tracking
- Safe overwrite handling for output files

------------------------------------------------------------
INTENDED USE
------------------------------------------------------------

FILECRYPTOR LITE is ideal for:

- Securing personal documents
- Encrypting sensitive project files
- Protecting backups before storage or sharing
- Lightweight offline file security tasks
- Batch encryption workflows for developers
- Portable encryption utility for USB drives

------------------------------------------------------------
UPGRADE TO PRO
------------------------------------------------------------

Upgrade to FILECRYPTOR PRO for advanced security features:

- Advanced encryption algorithms (multi-layer encryption)
- Secure password vault integration
- Cloud-safe encrypted backup system
- File shredding (secure delete)
- Folder-level encryption
- Automated encryption pipelines
- Key management system
- Enterprise-grade security controls

Website:

https://matetools.gumroad.com

------------------------------------------------------------
ABOUT
------------------------------------------------------------

FILECRYPTOR LITE is developed by Mate Technologies, focused on building lightweight, offline desktop tools for security, productivity, and automation workflows.

Website:

https://matetools.gumroad.com

© 2026 Mate Technologies  
All rights reserved.

------------------------------------------------------------
LICENSE
------------------------------------------------------------

FILECRYPTOR LITE is distributed as commercial software.

License terms:

- Personal and commercial usage allowed  
- Redistribution or resale as a competing product is prohibited  
- Repackaging or rebranding for resale is prohibited  
- Source modification allowed for internal/private use  
- Compiled executable usage permitted under license  

For commercial licensing or enterprise deployment, contact the developer.

------------------------------------------------------------
📷 PREVIEW
------------------------------------------------------------

<img alt="FILECRYPTOR LITE Main Interface" src="https://github.com/rogers-cyber/FILECRYPTOR-LITE/blob/main/FILECRYPTORLITE%20-%20Main%20Interface.png" />

<img alt="FILECRYPTOR LITE Activity Log" src="https://github.com/rogers-cyber/FILECRYPTOR-LITE/blob/main/FILECRYPTORLITE%20-%20Activity%20Live%20Log.png" />
