# 🚀 Dev Journal - 2025

This repository contains development work logs for various bug fixes and feature enhancements undertaken in 2025. Each entry provides a summary of the problem, investigation, solution, and outcomes, along with affected files and technologies used.

---

## ✅ 2025 Work Log Highlights

Here's an overview of key tasks and their resolutions as of July 2025:

### Q2 2025 (April - June)

* **[#BUGS25-248] - Peyesuaian Filter Kode Gudang (April 21 - 28)**
    * **Summary:** Adjusted the "Kode Gudang" filter on the Browse PKB menu to correctly fetch and display data, including adding an async fetch for `kode gudang` options. A new "Nama Gudang" column was added to the Browse PKB page table, and a missing slash in an API endpoint call was fixed.
* **[#BUGS25-264] - Penyesuaian Endpoint Get NITKU (April 23 - May 23)**
    * **Summary:** Corrected the endpoint address used to fetch NITKU (Nomor Identitas Tempat Kegiatan Usaha) data in the customs document's "Entitas" tab, resolving issues with data retrieval.
* **[#BUGS25-298] - Perbaikan Menu Penutupan Semua Pos (April 29 - May 07)**
    * **Summary:** Removed the default date range filter in the `DrawerCari` component for the "Penutupan Semua Pos" menu, allowing users to manually select their desired date range without pre-filled values.
* **[#BUGS25-364] - Referensi Entitas History (May 19 - 27)**
    * **Summary:** Fixed an issue preventing the retrieval of previously sent entity history by refining the logic for the `idPerusahaan` parameter, ensuring it consistently used `userData.nitku` for accurate data fetching.
* **[#BUGS25-420] - Perbaikan Menu Edit Penutupan Pos (May 26 - June 11)**
    * **Summary:** Eliminated the default date range filter when opening the "Edit Penutupan Pos" menu in the Inhouse Manifest, providing users with a clear and empty input for manual date selection.
* **[#BUGS25-535] - Konfirmasi BC 1.1 Dokumen Pabean (June 20 - July 03)**
    * **Summary:** Implemented confirmation mechanisms for BC 1.1 status (found or already used) in the customs document module. This involved handling date format conversions from the API, mapping `kodeTps` to `kodeGudang`, and adding robust error management for clearer user feedback.

### Q3 2025 (July - September)

* **[#BUGS25-630] - Perbaikan Format Tanggal Perekaman LHP (July 08 - 10)**
    * **Summary:** Updated the timestamp display format for "Tgl Perekaman LHP" in the "Hasil Pemeriksaan LHP" menu from 12-hour to 24-hour format (`hh` ➝ `HH`) to improve clarity and alignment with standard practices in CEISA systems.

---

## 🔍 How to Navigate

Each journal entry is detailed in its respective Markdown file, often named after the Jira ticket ID. These files contain:

* A detailed problem description.
* Investigation steps.
* The implemented solution, including code snippets where applicable.
* The results of the fix.
* A list of affected files and technologies used.
* Personal reflections on the task.

Feel free to explore the individual entries for more in-depth information on each resolved issue or enhancement.