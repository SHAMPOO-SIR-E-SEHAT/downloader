# Auto Downloader (Split Support)

Put a link in `download.txt` to trigger a download.

## Download Links
<!-- DOWNLOAD_SECTION_START -->
<!-- DOWNLOAD_SECTION_END -->

***

### How to join split files:
If a file is split into parts (e.g., .part_aa, .part_ab), download all parts into one folder and run:
- **Windows (PowerShell):** `gc file.zip.part_* | Set-Content file.zip -Encoding Byte`
- **Linux/Mac:** `cat file.zip.part_* > file.zip`
