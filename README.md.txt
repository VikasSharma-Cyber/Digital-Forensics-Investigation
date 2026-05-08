# Digital Forensics Case B4DM755 using FTK Imager and Autopsy

## Overview
This project demonstrates a beginner-level digital forensic investigation based on the TryHackMe room "Digital Forensics Case B4DM755".

The investigation was performed using FTK Imager and Autopsy to acquire and analyze forensic evidence.

---

# Objectives

- Perform forensic evidence acquisition
- Create a forensic disk image
- Verify evidence integrity using hash values
- Analyze digital evidence
- Recover deleted files
- Maintain chain of custody

---

# Tools Used

- FTK Imager
- Autopsy
- Windows
- TryHackMe Lab

---

# Skills Learned

- Digital Evidence Acquisition
- Disk Imaging
- Hash Verification (MD5/SHA1)
- Deleted File Recovery
- File System Analysis
- Chain of Custody Documentation
- Digital Forensics Reporting

---

# Investigation Workflow

## FTK Imager Investigation

- Opened FTK Imager
- Added Evidence Item
- Investigated Evidence Tree Pane
- Analyzed File List Pane
- Used Viewer Pane for analysis
- Created forensic disk image
- Verified image integrity using hashes
- Investigated deleted files
- Exported recovered evidence

## Autopsy Investigation

- Created forensic case
- Added disk image as data source
- Performed file analysis
- Reviewed deleted files
- Investigated suspicious activity

---

# Project Structure

```text
Digital-Forensics-Case-B4DM755-FTK-Autopsy
│
├── README.md
│
├── screenshots
│   ├── ftk_imager
│   └── autopsy
│
├── reports
│   ├── case_report.md
│   ├── evidence_log.md
│   └── chain_of_custody.md
│
├── notes
│   └── investigation_notes.md
│
├── evidence
│
└── recovered_files