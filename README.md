# 🚀 Dev Journal - 2025

This repository contains development work logs for various bug fixes and feature enhancements undertaken in 2025. Each entry provides a summary of the problem, investigation, solution, and outcomes, along with affected files and technologies used.

---

## ✅ 2025 Work Log Highlights

Here's an overview of key tasks and their resolutions as of July 2025:  
**Total Tickets Finished: 20**

---

### Q1 2025 (January – March)  
**Tickets: 5**

- **[#BUGS25-25]** – Penyelesaian temuan VA - Inhouse KLN (Feb 19 – Mar 05)  
  * **Summary:** Addressed findings from a Vulnerability Assessment (VA) related to the Inhouse KLN system.  
- **[#BUGS25-57]** – SonarQube Cleanup (Mar 03 – Mar 17)  
  * **Summary:** Fixed SonarQube warnings in the Dokumen Pabean module by cleaning up unused variables and refactoring logic.  
- **[#BUGS25-76]** – Perbaikan Validasi Entitas Pembeli Dok BC 3.0 (Mar 25 – Apr 02)  
  * **Summary:** Corrected validation issues for buyer entities in BC 3.0 documents within the Portal application.  
- **[#BUGS25-140]** – Perubahan value param NPWP15 (Mar 18 – Apr 11)  
  * **Summary:** Modified the `npwp15` parameter to use `nitku` instead of `npwp` for improved backend compatibility.  
- **[#BUGS25-163]** – SonarQube Cleanup (Mar 21 – May 28)  
  * **Summary:** Resolved vulnerabilities by removing redundant try/catch blocks and consolidating reusable functions in the Entitas module.

---

### Q2 2025 (April – June)  
**Tickets: 11**

- **[#BUGS25-205]** – SonarQube Cleanup (Apr 11 – Apr 26)  
  * **Summary:** Resolved string hardcoding and log level issues in PKBE frontend to improve maintainability and reduce code smells.  
- **[#BUGS25-228]** – Perbaikan filter hasil pemeriksaan barang default (Apr 16 – Apr 28)  
  * **Summary:** Applied default filters based on logged-in user and improved behavior on "Detail" button.  
- **[#BUGS25-248]** – Penyesuaian Filter Kode Gudang (Apr 21 – Apr 28)  
  * **Summary:** Adjusted async fetching of Kode Gudang and fixed endpoint pathing.  
- **[#BUGS25-264]** – Penyesuaian Endpoint Get NITKU (Apr 23 – May 23)  
  * **Summary:** Corrected the endpoint used for fetching NITKU data in the Entitas tab.  
- **[#BUGS25-298]** – Perbaikan Menu Penutupan Semua Pos (Apr 29 – May 07)  
  * **Summary:** Removed pre-filled date filters to allow manual selection in search form.  
- **[#BUGS25-364]** – Referensi Entitas History (May 19 – May 27)  
  * **Summary:** Fixed user identity reference by enforcing `userData.nitku` consistently.  
- **[#BUGS25-420]** – Perbaikan Menu Edit Penutupan Pos (May 26 – Jun 11)  
  * **Summary:** Removed default values in date range fields in the Edit Penutupan Pos menu.  
- **[#BUGS25-435]** – Penambahan Parameter Offset (May 28 – Jun 21)  
  * **Summary:** Added `offset` parameter support for pagination in Penutupan Semua Pos API call.  
- **[#BUGS25-529]** – Perbaikan endpoint `/update-token` pada setting-aplikasi (Jun 19 – Jul 05)  
  * **Summary:** Repointed `/update-token` API from `amws` to `authws` and changed version to `v3`.  
- **[#BUGS25-535]** – Konfirmasi BC 1.1 Dokumen Pabean (Jun 20 – Jul 03)  
  * **Summary:** Implemented feedback logic for reused document codes and handled date format changes.  
- **[#BUGS25-573]** – Perubahan Payload Kirim Redress (Jun 30 – Jul 01)  
  * **Summary:** Adjusted the redress payload format per backend requirements, including changes to key fields.

---

### Q3 2025 (July – September)  
**Tickets: 4**

- **[#BUGS25-590]** – Penyesuaian Penomoran Faktur Pajak (Jul 02 – Jul 17)  
  * **Summary:** Adjusted invoice numbering format and enhanced fallback logic for missing invoice segments.  
- **[#BUGS25-620]** – Tombol Kirim Ulang Faktur Pajak (Jul 08 – Jul 11)  
  * **Summary:** Added a resend invoice button with PIB/SPTNP options and secure API integration.  
- **[#BUGS25-630]** – Perbaikan Format Tanggal Perekaman LHP (Jul 08 – Jul 10)  
  * **Summary:** Changed timestamp format from 12-hour (`hh`) to 24-hour (`HH`) in the LHP section.  
- **[#BUGS25-642]** – Perbaikan Medium Security Hotspots (Jul 08 – Jul 15)  
  * **Summary:** Removed insecure random generator usage and closed 3 medium SonarQube hotspots.

---

## ⚠️ Excluded from Count

- **[#BUGS25-592]** – ❌ **INVALID**: Change to SCE API URL was rolled back and not merged due to deployment rejection.

---

## 🔍 How to Navigate

Each journal entry is detailed in its respective Markdown file, often named after the Jira ticket ID. These files contain:

* A detailed problem description.
* Investigation steps.
* The implemented solution, including code snippets where applicable.
* The results of the fix.
* A list of affected files and technologies used.
* Personal reflections on the task.