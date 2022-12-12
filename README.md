# Automated Stock Scraper
Using the online brokerage services of Charles Schwab, this python script scrapes the following variables for a highlighted stock:
### Greek Values                   
+ Vega                             
+ Theta                            
+ Gamma
+ Delta
+ IV
+ Bid
+ Ask 
+ Strike
+ Bid2
+ Ask2
+ IV2
+ Delta2
+ Gamma2
+ Theta2
+ Vega2

 ### Call & Put Values
+ Volume
+ OI
+ Volume
+ OI
+ Last
+ Change
+ Bid
+ Ask
+ Strike
+ Bid2
+ Ask2
+ Last2
+ Change2
+ Volume2
+ OI2

The scrapped data is then formatted into a pandas dataframe and then locally stored using sqlite3.

**The script does require a Chalres Schwab account login and password to work. Furthermore, while the scrapping and storing of the variables is automated, the script is not _fully_ automated and requires some initial input. Code should be run as follows: ** 








In the last cell of the code the script can be adjusted to run every ______ (second(s), minute(s), hour(s)) until an end time of choice. In that time the script will automatically naviagate to appropriate pages, refresh, and scrape and store the above listed variables upon running.
