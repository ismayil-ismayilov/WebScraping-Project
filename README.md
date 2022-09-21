# WebScraping-Project
A webscraping project to get all the promotional deals from Rossmann's official website.

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
