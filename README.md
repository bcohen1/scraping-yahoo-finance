# Scraping Yahoo Finance
As an avid biopharmaceutical investor, I am always looking for new investment opportunities and therefore need to be up to date on what companies are doing. The challenge with finding new investment opportunities, particularly with small-caps where things can move fast, is where to start looking. I developed this script to scrape all of the NASDAQ biopharmaceutical company descriptions from Yahoo Finance and flag key words to help identify potential investment opportunities. 
# How it works
To expedite the process of performing ~500 http GET requests, I implemented multi-threading to greatly reduce the run-time from approximately 30 minutes to just over a minute!
