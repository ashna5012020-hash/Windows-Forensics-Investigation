# Windows Forensics Investigation using Autopsy

## 📌 Project Overview
This project is a hands-on Windows Digital Forensics investigation performed using **Autopsy** on the publicly available **NPS 2009 DomexUsers forensic image**.  
The goal was to analyze user activity, browser artifacts, executable files, USB usage, and timeline events to reconstruct system behavior and identify suspicious actions.

This project simulates a real-world DFIR (Digital Forensics & Incident Response) case workflow.

---

## 🛠 Tools & Technologies
- Autopsy 4.22.1
- Windows Forensic Artifacts
- E01 Disk Image (NPS 2009 DomexUsers)
- Hash Analysis (MD5, SHA-256)
- Timeline Analysis
- Keyword Search
- CSV Evidence Export

---

## 📂 Evidence Collected
The investigation produced structured evidence stored as CSV files and screenshots:

### 🔹 Browser Artifacts
- Web History
- Web Cookies
- Web Downloads

### 🔹 System & Execution Artifacts
- Executable files (.exe, .dll, .bat)
- Prefetch evidence (e.g., Thunderbird)
- Installed Programs
- Run Programs

### 🔹 User Activity
- LNK file analysis (Sample Pictures.lnk)
- My Documents / My Pictures artifacts
- EXIF Metadata

### 🔹 External Devices
- USB device connection history (VMware virtual devices)

### 🔹 Timeline
- Filtered timeline focusing on:
  - 2008-10-21 (User activity)
  - 2008-10-30 (Browser & system events)

---

## 🧪 Key Findings
- Evidence of browser-based activity involving external domains
- Execution of programs from user directories
- Presence of executable files in suspicious locations
- User interaction with image folders via shortcut (.lnk) files
- USB device connections identified
- Timeline reconstruction confirms activity clustering around late October 2008

---

## 📊 Reports Generated
Final analysis reports were documented in structured text files:

- Case Overview
- Browser Activity Analysis
- Email Analysis
- Installed Programs
- Executed Programs
- User Activity Recovered
- Final Conclusion

All reports are located in the **Final_Report/** directory.

---

## 🧠 Skills Demonstrated
- Digital Forensics Investigation
- Evidence Collection & Preservation
- Windows Artifact Analysis
- Timeline Reconstruction
- Report Writing & Documentation
- DFIR Methodology

---

## 📁 Project Structure
Windows_Forensics_Investigation/
│
├── Evidence/
│ ├── Browser/
│ ├── Keywords/
│ ├── Timeline/
│
├── Screenshots/
├── Final_Report/
├── Notes/
└── README.md

---

## 📎 Dataset Reference
NPS 2009 DomexUsers Forensic Image  
Provided by National Institute of Standards and Technology (NIST)

---

## 👤 Author
**Ashna**  
Aspiring DFIR & Cybersecurity Analyst
