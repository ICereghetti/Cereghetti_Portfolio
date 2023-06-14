# Data Science & Data Analyst Portfolio
By Ivan Cereghetti


## [Protect 1: SQL Database Design using Website's Data Scraped with Selenium, BeautifulSoup, and ChatGPT](https://github.com/ICereghetti/project_funeral_homes.git)

This project involves freelance investigation work for a client who needed assistance in designing a comprehensive SQL database from scratch for their Funeral Homes website. The goal was to create a robust database that could be queried in multiple ways to gain different perspectives on the data. Additionally, the database needed to be flexible enough to accommodate future additions of new data.

### Highlights
1) Scrape Funeral Directors of New Zealand with Selenium (https://funeraldirectors.co.nz)
2) Scrape Relevant Information from Each Business's Website
3) Design the Database using the Gathered Information


### Deliverables

* [New Zealand's Funeral Homes Database](https://github.com/ICereghetti/project_funeral_homes/blob/b45ae90cea72fae99af1870f2f5ad925c75aeed4/funeral_homes_database.csv)
* [Python Code for Scraping and Formatting Text Data from Funeral Homes Websites using OpenAI](https://github.com/ICereghetti/project_funeral_homes/blob/1556a93cb6b031ada01dad035458566a79eef8a2/scrape_website.py)
* [JSON File with Samples of the Data Scraped from Websites](https://github.com/ICereghetti/project_funeral_homes/blob/b45ae90cea72fae99af1870f2f5ad925c75aeed4/samples.json)
* [Database Schema Document with the Recommended Main Structure](https://docs.google.com/spreadsheets/d/1YKqOfKtCx-Bx4KtMh7m7fcoXkl7wU3KPQ9LuyQzWJus/edit#gid=954638511)

### Tools Used

1) Python (Selenium, OpenAI, BeautifulSoup, urllib, time)
2) SQL (BigQuery)
3) Google Docs

![](https://github.com/ICereghetti/Cereghetti_Portfolio/blob/27f2f9b2d88ac78119a6e8f37f4d1b40b93635ab/images/project_funeral_homes_2.png)

## [Protect 2: Upwork Job Tracker + Mail Alarm + Skill Monitor Dashboard](https://github.com/ICereghetti/project_upwork.git)

Personal Upwork Job Tracking and Notification system to help me stay ahead of the competition. The data processed in this project can be seen in this [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/cade079a-6280-43d5-b942-afc4dece03de).

### Tools used

* Python
* Google Platform (Cloud Functions, Cloud Storage, Bigquery, Looker Studio)

![](https://github.com/ICereghetti/Cereghetti_Portfolio/blob/main/images/upwork.png?raw=true)


## [Protect 3: Esports Team Performance Tracker: Twitter Bot and Wordcloud Generation & Analysis](https://github.com/ICereghetti/project_twitter_wordclouds.git)

This personal project involves the creation of a Twitter Bot that analyzes the last 10 days of Tweets related to prominent Esports Teams (T1, FNATIC, Cloud9), selecting one team each day and generating a color-coded Wordcloud in the shape of the team's logo. By applying sentiment analysis using the team's colors, the Wordcloud provides a captivating visual representation of the team's performance. This project offers a dynamic and visually engaging solution for tracking the performance of top Esports Teams through automated analysis of Twitter data, making it valuable for marketing professionals seeking an automated and consistent method to generate quality content.

### Highlights
1) List impotant Esport Teams, Logos and representative colors in a Control Panel to change Wordcloud configurations
2) Once a Day, create a Wordcloud of one team based on the control panel's configuration
3) Upload and post the Wordcloud in the Twitter Bot Account using Twitter API


### Deliverables

* [Wordcloud's Control Panel](https://docs.google.com/spreadsheets/d/1MFIte9Rm4hXk713uXG4DOKKg2gwN8S_GJ-tqEwBi3tk/edit#gid=0): A Google Sheets document that acts as a control panel for changing Wordcloud configurations.
* [A different Wordcloud once a Day](https://github.com/ICereghetti/project_twitter_wordclouds/tree/5baa21324a5e5e0bbfacbb93ea6ea2755713acb8/wordcloud_samples): A collection of Wordcloud images generated daily, each representing a different team's performance.
* [Twitter Bot Code](https://github.com/ICereghetti/project_twitter_wordclouds/blob/5baa21324a5e5e0bbfacbb93ea6ea2755713acb8/code.py): The code used to create and update the Wordclouds and post them on Twitter.
* [Twitter Bot Profile](https://twitter.com/EsportsNews_bot) (Deprecated temporarily after May-22, since Twitter changed their Terms and Conditions): The Twitter profile of the bot used to post the Wordclouds.

### Tools Used

1) Python (tweepy, WordCloud, BeautifulSoup, google.cloud, requests): Python libraries for data processing, web scraping, and generating Wordclouds.
2) Google Cloud Platform (BigQuery, Cloud Functions, Scheduler, Google Docs, Storage): Google Cloud services used for data storage, scheduling tasks, and managing the control panel.
3) Twitter: Twitter API is used to retrieve tweets, post Wordclouds, and manage the bot account.

![Wordcloud Sample](https://github.com/ICereghetti/Cereghetti_Portfolio/blob/a61458d7ca0c47664b3a89a042f665cda465c7e2/images/project_twitter_wordcloud_3.png)

## [Protect 4: Festival Schedue in Tableau](https://public.tableau.com/app/profile/ivan.cereghetti/viz/SampleSchedue/dash?publish=yes)

PDF schedues were having some issues to display the event's information. This issue was solved by replacing these schedues by an interactive Tableau Dashboard:
* Tooltip to show the artist/teacher name, genre/topic and personalized image.
* Solved minor fixes to display times properly
* Added parameter to change each day's schedues

![](https://github.com/ICereghetti/Cereghetti_Portfolio/blob/main/images/resolutions_tableau_sample.png?raw=true)

## [Protect 5: The Movie Database API + ML Model + Twitter Bot](https://github.com/ICereghetti/project2_tmdb.git)

Develop a Machine Learning Model, using [The Movie Database API](https://www.themoviedb.org/) to recommend movies in a Twitter Bot once a week. The model will be trained to predict the average user rating a week after a movie is released. To predict this value, we will use cast, popularity, genre and budget.

### Tools used

* Python
* Google Platform (Cloud Functions, Cloud Storage, Bigquery, Looker Studio)

![](https://github.com/ICereghetti/Cereghetti_Portfolio/blob/main/images/project_2.png?raw=true)


