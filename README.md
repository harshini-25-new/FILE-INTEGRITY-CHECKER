# FILE-INTEGRITY-CHECKER-- TASK 1

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: HARSHINI
**INTERN ID**: CT08GDC

**DOMAIN**: CYBERSECURITY AND ETHICAL HACKING

**BATCH DURATION**: DECEMBER 25TH,2024 TO JANUARY 25TH,2025

**MENTOR NAME**: NEELA SANTHOSH

**DESCRIPTION**:

  The File Integrity Checker is a Python-based security tool that monitors file changes by calculating and comparing hash values. It ensures data integrity by detecting unauthorized modifications, deletions, or corruptions.

**Tools Used**:

Python – Core programming language.
hashlib – Generates SHA-256 hash values for files.
os – Traverses directories to find files.
json – Stores and retrieves file hashes for comparison.
Google Colab – Runs the script in a cloud environment.
**How It Works**:

Baseline Hash Creation: The tool scans a directory, calculates hashes for files, and stores them in hash_database.json.
Integrity Verification: It rescans files, compares new hashes with stored values, and reports any changes.
**Expected Output**:

plaintext

Copy

Edit

[INFO] Checking file integrity...

[ALERT] File modified: /content/sample_files/file1.txt

[WARNING] File missing: /content/sample_files/file2.txt

[OK] File intact: /content/sample_files/file3.txt

**This tool is useful for cybersecurity, intrusion detection, and forensic analysis**. 








