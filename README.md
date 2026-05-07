# Auto Downloader (Split Support)

Put a link in `download.txt` to trigger a download.

## Download Links
<!-- DOWNLOAD_SECTION_START -->
n- [code_1.118.1-1777474985_amd64.deb.part_aa](https://raw.githubusercontent.com/SHAMPOO-SIR-E-SEHAT/downloader/main/downloads/code_1.118.1-1777474985_amd64.deb.part_aa)
- [code_1.118.1-1777474985_amd64.deb.part_ab](https://raw.githubusercontent.com/SHAMPOO-SIR-E-SEHAT/downloader/main/downloads/code_1.118.1-1777474985_amd64.deb.part_ab)
<!-- DOWNLOAD_SECTION_END -->

***

### How to join split files:
If a file is split into parts (e.g., .part_aa, .part_ab), download all parts into one folder and run:
- **Windows (PowerShell):** `gc file.zip.part_* | Set-Content file.zip -Encoding Byte`
- **Linux/Mac:** `cat file.zip.part_* > file.zip`
