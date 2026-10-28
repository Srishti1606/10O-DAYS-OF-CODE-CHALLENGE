# Day-76 (28 October 2026)

## Problem Statement
Ask the user for a filename. Check if it exists by trying to open it in read mode. If the file pointer is NULL, print an error message; otherwise, read and display its content.

### Sample Test Cases
```text
Input:  Filename: sample.txt (File Exists: Yes)
Output: File opened successfully.
(Displays file content)
```
```text
Input:  Filename: nofile.txt (File Exists: No)
Output: Error: File does not exist!
```
