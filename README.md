# Credt Card Summary
 Automatically downloads all the statments pdfs from gmail and creats a summay excel.
 
 The attachment download from gmail code is generic but the credit card data extraction is very specific to my usecase.

 I tried to use a lot of data extractors like PDFMiner, Camelot, tabula, tabulate but hit a deadend at installation of ease of use. At last I chose to do this with simple regex and this was much more easier. Though the code is very specific to data extraction from Axis Flipkart Credit Card, with little tweaks can be used for other statments as well.

 Hope it helps someone :)

# References:
 1. Email Extraction:
 https://github.com/datacourses/dataanalysis/blob/master/Extract%20Data%20From%20Gmail%20Files.ipynb
 https://pypi.org/project/gmail/
 
 2. PDF Data Extraction
 https://pypi.org/project/PyPDF2/
 https://pypdf2.readthedocs.io/en/latest/

