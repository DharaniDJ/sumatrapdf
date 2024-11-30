[![Build](https://github.com/sumatrapdfreader/sumatrapdf/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/sumatrapdfreader/sumatrapdf/actions/workflows/build.yml)
## SumatraPDF Reader

SumatraPDF is a multi-format (PDF, EPUB, MOBI, CBZ, CBR, FB2, CHM, XPS, DjVu) reader
for Windows under (A)GPLv3 license, with some code under BSD license (see
AUTHORS).

More Information:
* [Website](https://www.sumatrapdfreader.org/free-pdf-reader)
* [Manual](https://www.sumatrapdfreader.org/manual)
* [Developer Information](https://www.sumatrapdfreader.org/docs/Contribute-to-SumatraPDF)

## Features added to SumatraPDF

### PDF Page Export

- Export PDF pages as high-quality images
- Customize resolution (DPI)
- Select specific page ranges for conversion

### Machine Learning Integration

- Process exported images through ML models
- Generate bounding boxes based on ML analysis
- Automatically save processed images with "\_processed" suffix
- Instant viewing of processed images within SumatraPDF

#### These features can be accessed from the file menu in SumatraPDF

## Building from Source

### Prerequisites

- Install Go
- Install Visual Studio

### Build Steps

1. Open a command prompt in the root directory
2. Run .\doit.bat -build-release
3. Navigate to the vs2022 folder and open SumatraPDF.sln in Visual Studio
4. Build the solution using Ctrl + Shift + B
5. Find the built SumatraPDF.exe in the newly generated folder within the out directory

To open the SumatraPDF executable with the new features (export as images and integrated ML model), follow these steps:<br>

- Navigate to the out folder in the SumatraPDF project directory.<br>
- Locate the newly generated folder containing the built application.<br>
- Find and run SumatraPDF.exe within this folder.
