
# Twitter Scraping

Built this app for Twitter Scraping by creating a web app using Streamlit. It scrapes the twitter data for the given hashtag/ keyword for the given period using snscrape library. The tweets are uploaded in MongoDB and can be dowloaded as CSV or a JSON file.

## Acknowledgements

 - [GUVI](https://www.guvi.in/)
 - [Mentor Mr.Nethaji Nirmal](https://www.linkedin.com/in/nethaji-nirmal/)
 - [Streamlit Docs](https://docs.streamlit.io/)


## LANGUAGES

Python Libraries: Snscrape, pandas, pymongo, NoSQL

Database:: MongoDB GUI

Framework: Streamlit Web
## Scrap tweets
 snscrepe liabrary has function TweetSearchScrape() method scrape the Twitter data without Twitter API. The method is passed with a query conating the hashtag to be search and the search dates (From start date to end date)
## Upload data in MongoDB
Tweets that are scraped using the Snscrape library is inserted into the MongoDB database by establishing the clinet connection. The tweet datas are strored under the twitter db collections.
## Streamlit usage
Creating the UI Used Streamlit app GUI for Twitter Scraping. Used menus for searching, dispalying the tweets and to download.

Menu 1 -- Home Home page of the UI conatins title of the app

Menu 2 -- About Conatins small description about the Twitter Scraping, Snscrape librray, MongoDB and Streamlit framework.

Menu 3 -- Search Search menu which is used to search the tweet data usng the #hashtag and for given dates. Everytime the search menu deletes the existing datas while searching the new tweet in order to retrive the tweet information correctly.

Menu 4 -- Display The scraped data from the MongoDB database are dispalyed as a DataFrame

Menu 5 -- Download The scraped data from the MongoDB database is downloaded as CSV/ JSON file formats as per the requirement.


## Linkedin
[Ajay D. Wanekar](https://www.linkedin.com/in/ajay-wanekar-245a50230/)
