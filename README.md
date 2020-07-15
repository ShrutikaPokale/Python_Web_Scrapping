# Python_Web_Scrapping
A scraper which fills the form at https://parivahan.gov.in/rcdlstatus/?pur_cd=101 and scrapes the resultant data using the Python library requests and lxml.

The required URL is extracted using 'Requests.get' function.
In order to fill the form, 'Viewstates' are considered since it changes every time an input is inserted.
Function is also added to check for incorrect captcha and incorrect login details.
