# ESMA-Equity-Transparency-Report
The code is to webscrape ESMA's Equity Transparency table based on FIRDS Transparency System (https://registers.esma.europa.eu/publication/searchRegister?core=esma_registers_fitrs_equities).
Given that the table is rendered dynamically, the code utilises selenium.
As such, the original function is in Python.
Nevertheless, I created an R script using reticulate for non-Python users.

It is important that the user has Google Chrome on her computer installed.
The script opens Chrome and leads the website load so that the table can render.
Then it webscrapes the table identified with detailParent.
Finaly, the website closes it.

Disclaimer: The script is only for equity instruments and only for the YEAR method.