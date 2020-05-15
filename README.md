# Sentiment Analysis of COVID-19

For the full experience, please [click here](https://nbviewer.jupyter.org/github/wellace/02806_covid19/blob/master/%5B02806%20Project%20B%5D%20Sentiment%20Analysis%20of%20COVID-19.ipynb) to view on nbviewer. 

### Motivation

The coronavirus outbreak, COVID-19 has taken the world by storm. Newsrooms filter tons of information every day — articles, official briefings, expert interviews etc. Medical personnel struggle to follow hundreds of scientific publications each week, concerning drug research, epidemiological reports, intervention policies and many more. Moreover, social network platforms need to reduce the noise and promote verified stories to avoid nurturing misinformed and terrified users.

We decided to do an analysis on the coronavirus situation because it is on everyone's minds in every country, regardless race, language, religion, class status. It has brought the world to its knees and while the situation still remains uncertain, we thought there was good value in doing some analysis on the current situation.

In addition, we wanted to do some text analytics to understand people's sentiments on the COVID-19 situation around Europe. We therefore downloaded tweets data from Twitter from specifically Denmark, France, Germany, Italy, Spain, Switzerland, United Kingdom and did some sentiment analysis. We also explored the relationship between sentiments and the number of cases.

At the end of the day, we want users to get a clearer idea of the magnitude of the crisis on the international scale as well as understand the sentiments of people around Europe.

## Data Sources

The dataset has been elaborated using three different data sources:

- John Hopkins University: The COVID-19 time series dataset has been downloaded from this source which consists of number of confirmed cases, death cases and recovered cases for each day and country. 


- IEEEDataPort: The IDs of all the tweets made in reference to coronavirus since the major outbreak of the virus on 6th February 2020 were downloaded from  this data source. The datasets were separated by day, so the individual datasets have been combined into one huge dataset. 


- Twitter: Using the Tweepy library, we have downloaded all the tweets with the tweet IDs collected and processed from IEEEDataPort. 

After downloading all the relevant tweets, we grouped them by the selected countries and cleaned the tweets in order to remove hashtags, symbols, smileys, numbers and stop words. The tweets have been cleaned in order to ensure the an emphasis on the words that contains essential sentiments. 

To store all this information we used a storage space of around 400 megabytes. In order to better manage the big data, we have created structured folders to adapt the data as part of the codes for the purpose of our analysis on the COVID-19 coronavirus.

## Contributions

Throughout the entirety of the project, the group has placed strong emphasis on verbal communications with the use of Skype. This has allowed us to remain efficient and true to the implementation plan that we have presented as part of Project A, despite the circumstances in the COVID-19 pandemic. 

- Leong Wei Jie Wellace
- Ashwinth Mathivanan
- Julian Chris Lopez

## Acknowledgements

We would like to provide our deepest gratitude to Sune Lehmann, Associate Professor for DTU Informatics — Technical University of Denmark (DTU) for his unique teaching methodology in this course that greatly enhanced our interest in this field. 

We would like to thank Alexandra, Germans, Pierre and João — Teaching Assistants of the course for their unwavering support in the entirety of the course. 

Thank you, the Center for Systems Science and Engineering (JHU CSSE) for compiling and granting access to the COVID-19 data. And thank you Rabindra Lamsal for providing the API to download the COVID-19 Tweet IDs from the Twitter. 

