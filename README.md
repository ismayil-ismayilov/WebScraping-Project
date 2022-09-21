# WebScraping-Project
A webscraping project to get all the promotional deals from Rossmann's official website.

Discount on a product is something everyone looks for. Our team (Me and my teammate) tried to achieve an access to all
discount details and enjoy exploring the best out of those deals. One of the chain drug stores, Rossmann has a
very varied product offering. It has also an online store. The website has a separate page called Promotions
for discounted products. At the time of this project, there are more than 6000 products on promotion. Going
over each of them and finding the best deal can be overwhelming for a user. Scraping discounted products
provides detailed information about each product in a short period. In the end, a user has an access to:
• Brand and products names
• The original and discounted price
• Discounted products by percentage, or product category | which can be filtered to see the most
discounted products.
• Tp filter for only reviewed/rating products since all of the products are not reviewed.
• To easily detect if a product is not available in an online store.
This data can be used furthermore for data analysis. For example, one may interested in if there is a significant
relationship between product category and discount rate. As the promotional products change, two scraping
results can be compared to each other for further analysis.

- - - - -
####################
#  BEAUTIFUL SOUP  #
####################
Please download whole folder named “BeautifulSoup”. 
Open the folder in an an applicable software (i.e VSCode), open “rossmann_BS” python file and run the file. 
Alternatively, in terminal, go to the folder directory and run the script with the command:
“python rossmann_BS.py”

As a results you will obtain csv file and log.txt file.

To change the program settings, such as number of products to scrape 
please open the file rossmann_BS.py and take a look at the CONSTANT section.


##############
#  SCRAPY    #
##############
Please download whole folder named “Scrapy”.
In terminal, go to the folder directory/Rossmann and run the script with the command:
“scrapy crawl products -O results/results_SCRAPY_120.csv --logfile results/log_SCRAPY_120.txt”

As a results you will obtain csv file and log.txt file in folder Rossmann/results.

To change the program settings, such as number of products to scrape 
please open the file rossmann_SCRAPY.py and modify the constants.

##############
#  SELENIUM  #
##############
Please download the folder named “Selenium”.
To execute the scraping process, open and run the python file named "Rossmann_Selenium".
To change the program settings, such as number of products to scrape, modify the constant in python file.

As a results you will obtain csv file.

Further description is provided in the file.
