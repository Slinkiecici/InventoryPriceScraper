# InventoryPriceScraper
GUI built with wxpython that allows user to login to Siemens mall website with credentials and scrape products from an odoo product export sheet.

GUI built with packages in requirements.txt
Credentials for Siemens mall and Odoo database saved in two seperate .txt files to be used by program.
GUI functions:

***Main Application run on AccessSiteGUI.py***

<h2>Siemens scraper tab:</h2>

1) Takes input from .xlsx document for products to scrape
2) Outputs Stock code, Description, List Price and Customer Price
3) GUI will displayed failed scrapes.
4) GUI displays successful scrapes.
5) User required to enter a file name, for products scraped, to save before program initiates.

<h2>Odoo Inventory tab:</h2>

1) Displays all products currently listed on site on start up
2) Allows user to search stock code.
3) displays product code, description, quantity available in Grid.


<h2>To improve:</h2>

1) Allow user to provide credentials via input instead
2) Allow upload of document other than .xlsx
3) Include loop to determine column products are in.
4) Update Scraped Product TextCtrl in realtime rather than at the end of code run.
5) Include function to try variation suggestions for failed products.
6) Error check format of product code provided.
7) Allow user to manually enter stock codes to be scraped.
8) Imporive layout of TabOne (Looks like it's straight out of windows xp currently)
9) Check whether to overwrite for file name provided to save to, if file already exists.
10) Allow user to change quantity on odoo database (Big task, need to understand Odoo model structures better)
11) Update Inventory Search in realtime rather than at end of code.
12) Block Buttons when code runs **Important**
