## COMMUNICATING DATA FINDINGS
BY OGOCHUKWU ELEANOR

### DATASET
Data for this analysis are sourced programmatically using python's libraries and gotten from three sources: the first is the twitter-archive-enhanced dataset already supplied by Udacity, the second will be scraped from a web url and the third from @dogrates twitter account using Twitter's API.

### PRELIMINARY WRANGLING
Information is the oil of the next century and data is its combustion engine. Without data, you are just another person with an opinion (Anonymous quotes). But then, real-world data hardly comes clean. To clearly analyze data to gain insights, this raw unclean data will have to be structured and cleaned into a more manageable and assessable format.

@WeRateDogs rates people’s dogs on its twitter and other social media accounts with humorous comments about these dogs. They have a unique rating system which rates dogs over 10. Besides that, they have a classification for these dogs based off their stage of maturity, these are:-
1. ***doggo*** (a really smart older dog), 
2. ***floofer*** (dogs with seemingly excess fur), 
3. ***pupper *** (a small dog, usually younger) and 
4. ***puppo*** (not too big or small, usually between a doggo and a pupper).  

Python libraries were imported and used to download, scrape and query these data. The datasets were individually assessed for quality and tidiness issues such as missing values, inconsistent data, erroneous datatypes e.t.c.

These issues were cleaned programmatically employing pandas and its functions. The cleaning process involved defining the issue, stating what action will be taken to resolve the issue, using code to resolve the issue then testing to ensure the issues are resolved. These cleaned datasets were eventually merged into one DataFrame for analysis and visualization to determine how dogs are rated @WeRateDogs twitter account.

### SUMMARY OF FINDINGS
Dog ratings @WeRateDogs are neither influenced by the time of posting, number of postings, likes and retweets of postings, but by the creators of the account and how they view the dog pictures posted on their twitter account. One interesting aspect of their rating system though is the cumulative rating of dogs posted in pairs, (i.e., if a picture of 5 puppers are posted in one time, they are rated together like 500/100 meaning 10/10 per pupper) and incredibly high ratings for dogs perceived to do something of significance to society e.g., Atticus who was covered in American regalia celebrating the 4th of July, America’s Independence Day. He was rated 1776/10. In the end, > they are all good dogs (winks).
