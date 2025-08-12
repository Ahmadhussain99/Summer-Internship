# Detection & Recovery of Encrypted VHD  
**Cyber Gyan Virtual Internship — CDAC Noida**  
**Intern:** Ahmad Hussain · **Mentor:** Prateek Saraswat · **Duration:** Jun–Jul 2025

---

## Summary
This repo contains the materials and evidence for a virtual internship project where I simulated a forensic investigation of an encrypted Virtual Hard Disk (VHD) recovered from a crime-scene scenario. The goal was to detect encryption, attempt data recovery using open-source tools, and document the forensic process with reproducible logs and reports.

---

## Problem statement
A USB drive (VHD) recovered from a simulated crime scene was encrypted. The task was to:
- Detect encrypted volumes and classify the encryption type.
- Attempt mounting/decryption and recover accessible artifacts.
- Maintain reproducible evidence logs and chain-of-custody documentation.

---

## Tools & Technologies
- **MAGNET Encrypted Disk Detector** — encrypted-volume detection  
- **VeraCrypt** — mounting & decryption attempts  
- **Elcomsoft Forensic Disk Decryptor** — password analysis & decryption attempts  
- Filesystem analysis tools (various open-source utilities)  
- Basic scripting & logging to consolidate outputs

---

## Methodology (high-level)
1. Created a forensic image (VHD) to preserve the original data.  
2. Ran MAGNET Encrypted Disk Detector to identify suspicious/encrypted volumes.  
3. Attempted to mount volumes with VeraCrypt and performed password-analysis with Elcomsoft.  
4. Extracted filesystem artifacts (file listings, metadata, timestamps) where possible.  
5. Consolidated outputs (listings, hashes, timestamps) into a single verification log for cross-checking.  
6. Documented chain-of-custody steps and prepared concise summary reports for mentors and reviewers.

---

## Key outcomes / learnings
- Built a repeatable checklist/workflow for encrypted-storage analysis.  
- Gained hands-on experience using forensic tools for detection and recovery.  
- Learned to handle evidence integrity, create reproducible logs, and prepare summary reports for non-technical stakeholders.

---

## Artifacts (click to view)
- [Certificate — Internship Completion](https://github.com/<Ahmadhussain99>/<Summer-Internship>/blob/main/certificate.pdf)  
- [Presentation — Slides (331eb532-edef-44ca-bf8d-b46901e22c37.pptx)](https://github.com/<Ahmadhussain99>/<Summer-Internship>/blob/main/331eb532-edef-44ca-bf8d-b46901e22c37.pptx)  
- [Presentation — Slides (4cc758de-fbe9-4f0e-9e37-baa3a697f39e.pptx)](https://github.com/<Ahmadhussain99>/<Summer-Internship>/blob/main/4cc758de-fbe9-4f0e-9e37-baa3a697f39e.pptx)  


---

