
# Password-Locker
Simple Offline Password Locker

## Features
- Options to save and view passwords
- Passwords are saved locally in text file in encrypted version
- Passwords are copied on clipboard when required
- Clipboard is automatically reset after 10 seconds to avoid misuse
- Command line interface

## Drawbacks of Using a Password Vault
Single point of failure:- If a cybercriminal gets hold of the master password, they can steal all passwords in one go, and ultimately compromise multiple accounts.
Vulnerable to malware:- If the main password is used or saved on a computer affected by malware, it may compromise all other passwords controlled by the vault.

## Getting Started

To deploy this project on local machine you have to download complete code on your system.The program can be executed by running the main_window.py.

### Prerequisites

What things you need to install the software and how to install them

Python 3.0 or later
(Tested on Windows)
Python Modules:
 - pyperclip
 - time
 - sys
 - json
 - pathlib

Why Do I Need a Password Vault?
In organizations worldwide, people still use weak passwords, or reuse the same password across multiple accounts. Such practices enable cybercriminals to steal passwords to easily breach enterprise networks. Passwords with privileged access are particularly attractive to cybercriminals, since they can use this one single “key” to access many resources for malicious purposes.
The risks of such attacks increase when organizations don’t properly manage their passwords. A password vault is one way for organizations to minimize the risk of password-based cyberattacks.


A password vault, password manager or password locker is a program that stores usernames and passwords for multiple applications securely, and in an encrypted format. Users can access the vault via a single “master” password. The vault then provides the password for the account they need to access.
