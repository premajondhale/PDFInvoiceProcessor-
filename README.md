# PDFInvoiceProcessor-
**💡 Description**
PDFInvoiceProcessor is a Python tool designed to automate the extraction of invoice data from PDF files (especially French invoices). It analyzes VAT breakdowns, client numbers, invoice dates, and other key fields, then compiles everything into a clean Excel dashboard for easier analysis and reporting.
This project supports different invoice formats and includes automatic mapping of client numbers to store names.

**✨ Features**
Extract detailed invoice data (VAT rate, base amounts, VAT amounts, credit)
Detect and process different PDF formats automatically
Map client numbers to store names
Output clean Excel dashboards
Interactive folder selection using Tkinter

**⚙️ Requirements**
Python 3.7+
pandas
PyMuPDF (fitz)
PyPDF2
tabula-py (optional, if table extraction is needed)
tkinter
xlsxwriter

**Install dependencies:**
pip install pandas PyMuPDF PyPDF2 tabula-py xlsxwriter

**🚀 Usage**
1. Clone this repository:

git clone https://github.com/premajondhale/PDFInvoiceProcessor.git
cd PDFInvoiceProcessor

2. Run the script:

python PDFtoExcelInvoiceExtractor.py

3. A window will prompt you to select the folder containing PDF invoices.

4. Select an output folder for the Excel file.

5. The tool processes all PDFs, and an Excel file named <output_folder>_Suivi des prélévements_Dashboard.xlsx will be generated.

**🏷️ Output**
An Excel dashboard summarizing invoice data, including:

Invoice number
Invoice date
Prelevement Echeance date
VAT breakdown
Credit totals
Store name mappings

**🤝 Contributing**
Contributions, issues, and feature requests are welcome!

**📄 License**
This project is open source and available under the MIT License.

💬 Contact

Created by Prema Pingale. Feel free to reach out via GitHub Issues or pull requests.

