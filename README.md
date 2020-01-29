# MediumArticle-Selenium
Using Python and Selenium to get coordinates from street addresses. In this repository you'll find the Jupyter Notebook and the generated maps


This is a step by step article on how to use Python and Selenium to scrape coordinates data (Latitude and Longitude values) from Google Maps based on street addresses. In this case example, I'm going to work with an official dataset containing the street addresses of all Australian charities and nonprofits. At the end, I'll proceed to map all the charities and nonprofits in the city of Melbourne using Folium, to demonstrate what can be done with the newly acquired coordinates data.


The dataset: ACNC charities and nonprofits registry :
Australia is ranked 4th worldwide by the CAF World Giving Index in its 10th edition that covers the last 10 years. By visiting the ACNC's website, you'll quickly notice how easy they make it for researchers to access all the data about charities and nonprofits in Australia.

The dataset we'll be using can be downloaded here (along with a useful user notes document explaining the variables ):

ACNC Charity Register dataset: Excel file XLSX | 7.7 Mb | 74155 rows and 60 columns as of 23/01/2020
The dataset presents many interesting aspects about the charities and nonprofits in Australia: unique identifier, legal name, address (for correspondence), registration date, size, purpose, beneficiaries and more (read the user notes for more info).

Here, we're mainly interested in the street address features which span several columns: Address_Line_1, Address_Line_2, Address_Line_3, Town_City, State, Postcode and Country. Also, for simplicity, we will only look into charities and nonprofits in the city of Melbourne.
