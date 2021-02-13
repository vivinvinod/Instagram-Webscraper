# Instagram - Webscraper
On seeing this very particular link (pasted on the repo), I was curious to scrape them data and see what was it all about. The page opened to 100 other page and each one to 10 other pages with 25 x 5 = 125 accounts. That totals upto 125k accounts present in this peculiar indexing.

The `scrapper.py` scrapped all them accounts and stored in a CSV which then was accessed by `main.py` to hit the accounts and get the basic profile details such as postCount, followerCount and followingCount. 

![alt text](https://github.com/TonyJacb/Instagram-WebScraper/blob/main/terminal.png?raw=true)
Above is the screenshot of the terminal with the preview of the scrapped data

My calculations told me that the entire computation will take 15 hours. So I had to kill it after scrapping ~500 accounts. I dont have that much time.

Viv:
The final aim is to eventually access the follower and following name list for each individual. Process could be sped up using spider splits. 
