# Covid News

# Python Packages Needed

1. newsapi 
2. kivy 
3. robin_stocks

### NEWS_PULLER.py

The newspuller.py uses the NEWS API to bring recent Covid-19 updates form reliable sources and then stores the headlines in one text file locally 
(path must be provided)and the corresponding links in different text file (path must be provided). This class is used by news_web_app.py

### NEWS_WEB_APP.py

The new_web_app.py requires your Robinhood credentials (2-factor auth) must be turned off. It provides you with recent financial trends which are downloaded locally 
(filepath must be given) as well as Covid-19 updates (from the news_puller.py). 

Working on sending the updates directly to the email of the user when they fill in the textboxes on the side. Also working on enhancing the UI of the web app. 
