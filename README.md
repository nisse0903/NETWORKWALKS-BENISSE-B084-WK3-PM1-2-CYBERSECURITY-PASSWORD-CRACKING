# NETWORKWALKS-BENISSE-B084-WK3-PM1-2-CYBERSECURITY-PASSWORD-CRACKING

## Author
- Benisse Villasoto
- My LinkedIn: [https://www.linkedin.com/in/benisse-villasoto/](https://www.linkedin.com/in/benisse-villasoto/)

## Project Information
- **Program Name:** Cybersecurity at Networkwalks | **Week:** 03 | **Project:** Password Cracking Lab (John the Ripper & Networkwalks Tools) | **Repository:** GitHub

## Project Overview

This project demonstrates two approaches to cracking a password-protected PDF file for educational purposes: using **John the Ripper (with the Johnny GUI)** on a Windows PC, and using the **Networkwalks online hash and password cracking tools**. Both methods extract the hash of an encrypted PDF and run an attack against it until the correct password is recovered.

## Method 1: John the Ripper (JTR) + Johnny GUI

### Step 1. Download John the Ripper from the official website.

### Step 2. Download and install Johnny GUI, then set it to point to john.exe.

![Install Johnny GUI](install.png)
![Select john.exe in Settings](executable.png)

### Step 3. Upload the encrypted PDF to the online hash extractor and copy the hash.

![Upload PDF to hash extractor](file.png)
![Copy hash value](gethash.png)

### Step 4. Paste the hash into Notepad and save it as hash1.txt.

![Paste into Notepad](notehash.png)
![Save hash as hash1.txt](savehash.png)

### Step 5. Open hash1.txt in Johnny and click Start new attack.

![Open password file in Johnny and start new attack](enterjohnny.png)

### Step 6. Password cracked — open the PDF with it.

![Password cracked](results.png)
![PDF unlocked with cracked password](one.png)
![Repeat with the other locked documents. Doc #2](two.png)
![Doc #3](three.png)

## Method 2: Networkwalks Online Tools

### Step 1. Download the encrypted PDF from the lab page.

### Step 2. Open the Networkwalks Hash Calculator.

### Step 3. Upload the PDF and generate the hash.

### Step 4. Copy the full hash value starting with $pdf$.

![Copy full hash value](nwhashcalc.png)

### Step 5. Open the Networkwalks Password Cracker.

### Step 6. Paste the hash and start the attack.

### Step 7. Password cracked.

![Cracked password result](nwpass.png)

### Step 8. Open the locked PDF and enter the cracked password.

### Step 9. PDF opens successfully.

![PDF successfully opened](nwpdf.png)

## What I Learned

- **PDF Hash Extraction:** I learned how encrypted PDFs store password-protection data as a hash, and how that hash can be extracted using online tools or local utilities.
- **Local vs Online Cracking Tools:** I learned the difference between cracking a password locally with John the Ripper/Johnny (full control, works offline) versus using online tools like the Networkwalks Hash Calculator and Password Cracker (faster setup, no installation required).
- **Johnny GUI Workflow:** I learned how to configure Johnny to point to `john.exe`, load a hash file, and run an attack.
- **Documentation Practice:** I learned to document each step with screenshots for future reference.

## Security and Ethical Use

This lab is intended strictly for educational purposes, using a PDF file created for lab practice. Password cracking tools and techniques should only ever be used on files and systems you own or have explicit authorization to test.

## Resources
- John the Ripper: https://www.openwall.com/john/
- Johnny GUI: https://openwall.info/wiki/john/johnny
- Online Hash Extractor: https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
- Networkwalks Hash Calculator: https://networkwalks.com/hash-calculator/
- Networkwalks Password Cracker: https://networkwalks.com/password-cracker/
