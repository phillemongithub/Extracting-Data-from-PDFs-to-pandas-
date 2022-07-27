### Extracting-Data-from-PDFs-to-pandas-
Extracting Data from PDFs to pandas 
### Steps to follow:

1. load libraries:

from datetime import datetime
import re
from dateutil.parser import parse
import datefinder
import PyPDF2
import pandas as pd

2. Create an onject.
3. Importing data in to list in pages.

4. Extracting data from the list using a for loop 
4.1. if condition to allow to see if specific texts exist in a line of text.

4.2. if that line exists use regular rexpression 

looking for a currency in your line.
e.g re.findall(r'ZAR')


##### The the code which is incoparated with the comments is attached together with the pricing supplements pdf documnets to check.


