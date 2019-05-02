Code scrapes Central Bank of Ireland enforcement notices(public).

The function of interest uses multiple Python libraries to extract publicly available information from the Central bank of Ireland's webpages. 

Once called it utilises the following libraries(requests, Beautiful soup and spaCy) to ultimately produce a current list of any organisation or person that was subject to an enforcement action and whose details were publicly available at time of scrape from the Central Bank's website. 

The content of interest was contained with a table which had 13 pages of a href's within td's. Soup was more than sufficient  in terms of extracting text from the relevant script classes.

From start to finish the function took less than four seconds to run on a laptop with standard cpu capacity.
 
