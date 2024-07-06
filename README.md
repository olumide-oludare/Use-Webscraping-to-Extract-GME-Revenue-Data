# Use-Webscraping-to-Extract-GME-Revenue-Data
Use the `requests` library to download the webpage https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html. Save the text of the response as a variable named `html_data_2`.
Parse the html data using `beautiful_soup` using parser i.e `html5lib` or `html.parser`.
Using `BeautifulSoup` or the `read_html` function extract the table with `GameStop Revenue` and store it into a dataframe named `gme_revenue`. The dataframe should have columns `Date` and `Revenue`. Make sure the comma and dollar sign is removed from the `Revenue` column.
Display the last five rows of the `gme_revenue` dataframe using the `tail` function. Take a screenshot of the results.
