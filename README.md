# Merge-PDF-MiniProject

This Python script allows you to merge multiple PDF files into a single PDF file. The script uses the PyPDF2 library to handle PDF manipulation



Script Explanation
merge_pdfs Function
This function takes two arguments:

input_pdfs: A list of paths to the input PDF files to be merged.
output_pdf: The path where the merged PDF file will be saved.
The function performs the following steps:

Creates a PdfWriter object.
Iterates over each input PDF file:
Opens the PDF file.
Reads the PDF file using PdfReader.
Adds each page of the PDF to the PdfWriter object.
Closes the PDF file.
Writes the combined pages to the output PDF file
