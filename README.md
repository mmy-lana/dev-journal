# 🚀 Dev Journal - 2025

This repository contains development work logs for various bug fixes and feature enhancements undertaken in 2025. Each entry provides a summary of the problem, investigation, solution, and outcomes, along with affected files and technologies used.

---

## ✅ 2025 Work Log Highlights

Here's an overview of key tasks and their resolutions as of July 2025:
**Total Tickets Finished: 16**

### Q1 2025 (January - March)
**Tickets: 5**

* **[#BUGS25-25] - Penyelesaian temuan VA - Inhouse KLN (February 19 - March 05)**
    * **Summary:** Addressed findings from a Vulnerability Assessment (VA) related to the Inhouse KLN system.
* **[#BUGS25-57] - (Details to be added) (March 03 - March 17)**
    * **Summary:** Completed a task related to an unspecified bug or feature.
* **[#BUGS25-76] - Perbaikan Validasi Entitas Pembeli Dok BC 3.0 (March 25 - April 02)**
    * **Summary:** Corrected validation issues for buyer entities in BC 3.0 documents within the Portal application.
* **[#BUGS25-140] - Perubahan value param NPWP15 (March 18 - April 11)**
    * **Summary:** Modified the `npwp15` parameter to use `nitku` instead of `npwp` in customs document forms for correct payload submission.
* **[#BUGS25-163] - (Details to be added) (March 21 - May 28)**
    * **Summary:** Completed a task related to an unspecified bug or feature.

### Q2 2025 (April - June)
**Tickets: 11**

* **[#BUGS25-205] - (Details to be added) (April 11 - April 26)**
    * **Summary:** Completed a task related to an unspecified bug or feature.
* **[#BUGS25-228] - Perbaikan filter hasil pemeriksaan barang default (April 16 - April 28)**
    * **Summary:** Implemented default filtering for "hasil pemeriksaan barang" to use the logged-in user's `kode kantor` and a one-month date range, and fixed search results clearing on "Detail" button click.
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
* **[#BUGS25-435] - (Details to be added) (May 28 - June 21)**
    * **Summary:** Completed a task related to an unspecified bug or feature.
* **[#BUGS25-529] - Perbaikan endpoint /update-token pada setting-aplikasi (June 19 - July 05)**
    * **Summary:** Corrected the `/update-token` endpoint within the setting application from `amws` to `authws` and updated its version to `v3` to ensure proper token management.
* **[#BUGS25-535] - Konfirmasi BC 1.1 Dokumen Pabean (June 20 - July 03)**
    * **Summary:** Implemented confirmation mechanisms for BC 1.1 status (found or already used) in the customs document module. This involved handling date format conversions from the API, mapping `kodeTps` to `kodeGudang`, and adding robust error management for clearer user feedback.
* **[#BUGS25-573] - (Details to be added) (June 30 - July 01)**
    * **Summary:** Completed a task related to an unspecified bug or feature.

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
