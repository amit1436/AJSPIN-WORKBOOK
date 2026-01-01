# AJSPIN-WORKBOOK: High-Speed NMR Reporting Tool
A web-based environment for converting NMR peak data into journal-ready text. 
Designed to replace manual Excel-based workflows like ASpin.

## 🚀 Live Demo
[Access the Tool Here](https://github.com/amit1436/AJSPIN-WORKBOOK/)

The Problem: In synthetic chemistry, converting raw NMR data into journal-ready experimental paragraphs is a bottleneck. Existing tools like ASpin provide helpful color-coding in Excel, but they require manual data entry, are prone to formatting errors, and rely on proprietary spreadsheet software. Furthermore, industry-standard tools like Mnova can be cost-prohibitive for independent researchers and students, and often require a steep learning curve for simple reporting tasks.

## ✨ The Solution
AJSPIN is an open-source, HTML5-based tool designed to bridge the gap between spectral processing and manuscript preparation. 

## ✨ Key Features
* **Zero-Installation:** Runs entirely in the browser.
* **Automated J value calculations:** Algorithmic assignment of J values for doublets, triplets, doublets of doublet etc.
* **Dynamic Color-Coding:** Instant visual feedback without manual cell painting.
* **Journal Formatting:** One-click export to ACS, RSC, and Wiley styles.

## 📖 How to Use
For writing 1H NMR data-Download the html file double click on it and it will open in your default browser.
1. Choose solvent, spectrometer frequency and journal styles.
2. With the help of OCR tool like Capture2text select the peaks and insert them into each section.
3. You can also enter the peaks manually, also you can insert the peaks in any order.
3. Click on the +H button to add hydrogens or edit the 1H in text part below each section or in the result section.
4. After pasting the peak values in each section click on update final report.
5. All the values are then displayed in descending order, also j1, j2 values are in descending order, also the final report is fully editable.
6. Click " copy final report" and your 1H nmr data is ready to be pasted into manuscript.

For writing 13C NMR data-Download the html file, double click on it and it will open in your default browser.
1. Choose solvent, spectrometer frequency and journal styles.
2. Paste all ppm values in the "input 13c value" section.
3. After putting all the values in this section (values need not to be in any order), click convert & format.
4. Now it will display the final result in descending order and also round off the values to one or two decimal places as desired.
5. Carbon counter has also been added to count all the peaks and display the total number of 13C peaks.
6  Click "copy to clipboard" to copy the final result and paste it into your manuscript.

Why It Is Superior:
Unlike its predecessors, this tool is:
1.	Platform Independent: Runs in any modern web browser without installation. While previous tools like ASPIN runs only in excel also tool like Mnova can be costly for some students.
2.	Visually Integrated: Replaces the static Excel grid of ASpin with a coloured multiplicities sections.
3.	Privacy-Centric: All data is processed client-side; no sensitive chemical data is ever uploaded to a server.
4.	Instant Formatting: Outputs data directly into ACS, RSC, and Wiley formatting styles, reducing "typo" errors in chemical shift and coupling constant (J) reporting.

