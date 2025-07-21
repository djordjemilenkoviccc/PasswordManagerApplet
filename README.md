# PasswordManagerApplet

Secure Password Storage: Passwords are stored on the smart card in secured memmory.
Diffie-Hellman Key Exchange: Uses the Diffie-Hellman protocol to securely establish a shared symmetric key between the card and the external terminal.
Symmetric Encryption: After the DH key exchange, all communication is encrypted using a shared symmetric key.
Access Control: Passwords can only be accessed after successful authentication and key agreement.
All sensitive data remains on the smart card and is never exposed externally.
Session encryption is achieved through secure key exchange, ensuring confidentiality and integrity of communications.
Resistant to eavesdropping and man-in-the-middle attacks via proper cryptographic protocol usage.
