# 🔐 FTP vs SFTP Network Traffic Analysis

## 📘 Project Overview
This project analyzes FTP and SFTP traffic using Wireshark to identify how sensitive data such as usernames, passwords, and file transfers are transmitted. The goal is to understand the risks of plaintext FTP and the security benefits of encrypted SFTP.

## 🎯 Objectives
- Capture and inspect FTP traffic to locate login credentials and transferred files  
- Compare with SFTP traffic to observe encryption protecting sensitive information  
- Highlight differences between insecure and secure file transfer protocols

---

## 🧰 Tools Used
- Wireshark (latest version)  
- Virtual lab environment or live capture

---

## ✅ Task Breakdown

### Task 1: Capture and Inspect FTP Login
- Used Wireshark to filter FTP traffic  
- Inspected the login sequence to locate username and password fields  
- **Result:** Successfully identified the user’s login credentials in plaintext  
📷 *Screenshot: <img width="1392" height="682" alt="Screenshot 2025-08-01 135647" src="https://github.com/user-attachments/assets/87280ccd-82c3-46f9-b814-0d2c46601afa" />


---

### Task 2: Identify Transferred File in FTP Traffic
- Analyzed FTP data stream to find the file transfer command (RETR)  
- Located the transferred file named `report.txt`  
📷 *Screenshot: <img width="1392" height="681" alt="Screenshot 2025-08-01 141905" src="https://github.com/user-attachments/assets/ccfabda4-a5e5-42c4-992a-ac6f46219cc7" />


---

### Task 3: Analyze SFTP Traffic Encryption
- Filtered Wireshark to show only SFTP (SSH) traffic  
- Attempted to locate login credentials and file names  
- Observed that sensitive data was encrypted and not visible in plaintext  
- **Result:** Confirmed SFTP secures session data preventing readable content exposure  
📷 *Screenshot: <img width="1385" height="683" alt="Screenshot 2025-08-01 142352" src="https://github.com/user-attachments/assets/1168604b-1a03-4f27-9154-ba7981e9b984" /> <img width="1390" height="687" alt="Screenshot 2025-08-01 142402" src="https://github.com/user-attachments/assets/a3e80789-2922-4540-bb7e-09ae6eb87af0" />




---

## 📝 Final Summary
This analysis demonstrates the critical importance of using secure protocols like SFTP for file transfers. FTP transmits sensitive information in plaintext, exposing it to interception, whereas SFTP encrypts the data, protecting confidentiality and integrity.

---

## 📁 Repository Structure

