
# File Tampering Detection System

## About the Project
The File Tampering Detection System is a web-based application that detects unauthorized changes to files using SHA-256 cryptographic hashing. It compares the hash of a registered original file with the hash of a selected file to identify possible tampering.

## Features
- Register an original file.
- Generate SHA-256 hash values.
- Verify file integrity.
- Detect file modifications.
- Simple and user-friendly interface.

## Technologies Used
- HTML
- CSS
- JavaScript
- Web Crypto API (SHA-256)

## How to Run
1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select a file and click **Register Original File**.
4. Select the same file and click **Verify File** to check its integrity.
5. Modify the file and verify it again to test tampering detection.

## How It Works
The system calculates the SHA-256 hash of the original file and stores it in the browser's local storage. When a file is verified, its current hash is compared with the stored hash. If the hashes differ, the system reports that a change has been detected.


## Output
<img width="1600" height="767" alt="WhatsApp Image 2026-10-28 at 10 43 04 PM" src="https://github.com/user-attachments/assets/e71a6366-3d3a-4657-b71a-2aa9e6c41fba" />

<img width="1600" height="770" alt="WhatsApp Image 2026-10-28 at 10 44 16 PM" src="https://github.com/user-attachments/assets/3c87c059-ee54-4077-a384-3fd188f0f097" />

## Limitations
- This is a client-side prototype; it does not use a server or database.
- The original hash is stored in browser local storage.
- The system works best when the original file is registered before verification.
- It detects differences between file contents but does not identify who modified a file.

## Project Purpose
This project demonstrates how cryptographic hashing can be used to check file integrity and detect unauthorized modifications.
## Author
Student Information Security Project
