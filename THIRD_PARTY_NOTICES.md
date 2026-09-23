# Third-party notices

HTML2MP4 1.0.0 is free to use, and its own code is closed source. It is built on the open-source components below, each under its own licence. Those licences apply to those components, not to HTML2MP4's own code.

The full licence texts are in the `licenses` folder next to `HTML2MP4.exe`, and in the app under Help, Third-party licences.

| Component | Version | Licence | Source |
|---|---|---|---|
| Python | 3.12.10 | PSF-2.0 (and the licences it lists) | https://www.python.org/ |
| Tcl/Tk | 8.6 | TCL (BSD-style) | https://www.tcl.tk/ |
| Microsoft Visual C++ runtime | 14 | Microsoft redistributable | https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist |
| Playwright for Python | 1.63.0 | Apache-2.0 | https://github.com/microsoft/playwright-python |
| greenlet | 3.5.6 | MIT and PSF-2.0 | https://github.com/python-greenlet/greenlet |
| pyee | 13.0.1 | MIT | https://github.com/jfhbrook/pyee |
| Pillow | 12.3.0 | MIT-CMU (and the licences it lists) | https://python-pillow.github.io/ |
| Sun Valley ttk theme (sv-ttk) | 2.6.1 | MIT | https://github.com/rdbende/Sun-Valley-ttk-theme |
| imageio-ffmpeg | 0.6.0 | BSD-2-Clause | https://github.com/imageio/imageio-ffmpeg |
| Playwright driver | 1.63.0 | Apache-2.0 | https://github.com/microsoft/playwright |
| Node.js | 24.21.0 | MIT (and the licences it lists) | https://nodejs.org/ |
| PyInstaller bootloader | 6.22.3 | GPL-2.0-or-later with the bootloader exception | https://pyinstaller.org/ |
| Chromium | 153.0.8010.0 | BSD-3-Clause and many others (see file) | https://www.chromium.org/ |
| ffmpeg | 7.1 (gyan.dev essentials build) | GPL-3.0-or-later | https://ffmpeg.org/ |

## Notes

- **Python:** Includes the standard library, OpenSSL, libffi, zlib, bzip2, xz, expat and mpdecimal, whose licences are in the same file.
- **Microsoft Visual C++ runtime:** Not open source. Shipped as Python from python.org ships them.
- **Pillow:** Pillow's own image libraries (libjpeg-turbo, libpng, zlib and others) are listed in its file.
- **Playwright driver:** Includes its NOTICE file and its own third-party notices, as Apache-2.0 asks.
- **Node.js:** Part of the Playwright driver.
- **PyInstaller bootloader:** The exception allows the bootloader to be shipped inside other programs.
- **Chromium:** 754 components, taken from the credits page of Chromium 153.0.8010.12, the same version, because developer builds do not include their own.
- **ffmpeg:** Includes x264 and x265 (GPL).
