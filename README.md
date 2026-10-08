# Label Printer for Windows

Windows 10/11 x64 desktop app for manually entering label data or importing/searching Excel workbooks, then printing product labels to a GK888-compatible Zebra queue.

## Download

Open [Releases](https://github.com/walid-al-hinnawi/label-printer/releases) and download either:

- `Label.Printer-1.0.3.msi` — Windows installer.
- `LabelPrinter-1.0.3-windows-x64.zip` — portable app image. Extract the complete folder and run `Label Printer.exe`.

The app bundles its Java runtime. A Zebra printer driver and a working ZPL printer queue must be installed separately. If more than one GK888 queue is installed, set the desired queue as the Windows default printer.

## Important: unsigned preview

These files are currently **not code-signed**. Windows Smart App Control may block them. Do not disable Windows security to run this preview. A signed release will be published when trusted code signing is configured.

The installer was built and its MSI database verified; the portable app image was tested earlier, but this exact unsigned installer has not been tested on a clean computer. Please test with a sample label before operational use.