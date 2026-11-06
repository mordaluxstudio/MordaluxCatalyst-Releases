# Mordalux Catalyst: downloads

Installers and release notes for **Mordalux Catalyst**, a Revit add-in by Mordalux Studio. The source code is not published here.

## Download

Get `MordaluxCatalyst_v1.0.0_Setup.msi` from the [latest release](https://github.com/mordaluxstudio/MordaluxCatalyst-Releases/releases/latest).

## What it does

It adds a **Catalyst** tab to Revit:

- **Model Checker:** checks one model, or every model in a folder, against a BIM standard and writes an Excel or HTML report.
- **Export Schedules:** schedules to Excel, HTML or PDF.
- **Export Sheets:** sheets and views to DWG or PDF, with page ordering.
- **Standards Editor:** edits the rules, naming pattern and categories of a standard.
- **Parameter Manager:** creates, cleans and fills parameters from an Excel list, in a project or a family. Every run starts with a preview and is one Undo step.
- **AI assistant:** optional, off by default. It lets AI apps on your computer read the open model.

English and Bahasa Indonesia, light and dark theme. F1 in Revit opens the offline guide.

## Install

1. Close Revit.
2. Run the `.msi`. It installs per user, no administrator rights needed.
3. Start Revit. The installer is not code-signed, so Windows may show a SmartScreen warning, and Revit asks about an unsigned add-in the first time. Choose **Always Load** if you trust the file.

To remove it, use Installed apps in Windows. If you used the old Revit Automation Suite installer, delete `RevitAutomationSuite.addin` and `RevitAutomationSuite.dll` from `%AppData%\Autodesk\Revit\Addins\<year>` so only Mordalux Catalyst loads.

## Requirements

- Revit 2021 to 2027, Windows x64.
- PDF export of sheets needs Revit 2022 or newer. Parameter Manager needs Revit 2024 or newer.

## Privacy

Catalyst runs on your computer. It sends no project data to Mordalux Studio or anyone else. Its only network request is the check for a new version. The AI assistant is off by default; if you turn it on, what a connected AI app reads goes to that app's provider, under its own terms.

## License

Use is under the End User License Agreement shown during installation: a non-exclusive, non-transferable license; the software is provided as is; engineering responsibility stays with your licensed engineers and BIM managers.

## Contact

Mordalux Studio, by Mochamad Dzikri H. Website: <https://mordalux-studio.vercel.app/>. Email: mordaluxstudio@gmail.com.
