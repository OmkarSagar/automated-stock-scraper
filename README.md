# Automated Stock Scraper
Using the online brokerage services of Charles Schwab, this python script scrapes the following variables for a highlighted stock:
#### Greek Values                   
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

 #### Call & Put Values
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

**The script does require a Chalres Schwab account login and password to work. Furthermore, while the scrapping and storing of the variables is automated, the script is not _fully_ automated and requires some initial input. Code should be run as follows:** 

### Cell 1:
Upon running cell one a new chrome browser session is started with the landing page being the login screen to Charles Schwab. Login and password then need to be _manually inputted_. _Manually_ navigate to page of stock of interest.

### Cell 2:
Cell two creates the scrapping function with automated tasks built in for page navigation and refreshing. 

### Cell 3:
In cell three the script can be adjusted to run every ______ (second(s), minute(s), hour(s)) until an end time of choice. Upon running the script will automatically naviagate to appropriate pages, refresh, and scrape and store the above listed variables during the inputted interval of time.





