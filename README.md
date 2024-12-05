ki# EncryptSafe Local - Password Manager

**EncryptSafe Local** is a secure, local password manager with encryption and two-factor authentication using Google Authenticator. Built with Python and Tkinter, it provides a user-friendly GUI for managing encrypted passwords securely on your local machine.

## Features
- **Password Management:** Save, view, and delete encrypted passwords.
- **AES Encryption:** Ensures secure password storage.
- **Google Authenticator Support:** TOTP-based two-factor authentication.
- **SQLite Database:** Stores all user data locally.
- **Full-Screen Interface:** Clean, user-friendly UI.

## Prerequisites
Make sure you have Python 3.8 or higher installed.

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Encryptsafe_local.git
cd Encryptsafe_local
```
### 2. Install Dependencies
Install the required Python libraries using pip:

```bash
pip install -r requirements.txt
```
### 3. Create a Requirements File (if not done)
Ensure your requirements.txt file includes the following:

```
tkinter
Pillow
pyotp
qrcode
sqlite3
```
### 4. Run the Application
```bash
python main.py
```
Replace main.py with your script name if it's different.

###Usage
Launch the application and log in.
Save a password by entering the app name, password, and encryption key.
View saved passwords using your encryption key and Google Authenticator code.
Delete passwords securely if needed.

###Security
Encryption: Passwords are AES encrypted before being stored in the SQLite database.
Two-Factor Authentication: Google Authenticator TOTP adds an extra layer of security.
File Structure
```
encryptsafe-local/
├── database/
│   └── db_utils.py         # Database connection and utility functions
├── encryption/
│   └── aes_encryption.py   # Encryption and decryption methods
├── main.py                 # Main script to run the application
├── requirements.txt        # Python package dependencies
└── README.md               # Project README
Contributing
Contributions are welcome! Please:
```
### Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.


