# digital-strike
Digital Climate Strike by Greta Thunberg

Gamze Bozkurt

Fundamentals of Data Science
HU University of Applied Science Utrecht


1. Introduction
The Young climate activist from Sweden, Greta Thunberg was Time magazine’s Person of the Year for 2019. As she has become an influencer, her tweeter account plays an important role in society and she has become a figurehead for the climate movement (Murray, 2020). This project examines how sustainable does Greta Thunberg persuade her audience to start digital climate strikes on Twitter through Rhetorical Communication Theory.
2. Theoretical Framework
Rhetorical Communication Theory centers on the notion of rhetoric, which Aristotle calls the available means of persuasion. That is, a speaker who is interested in persuading his or her audience uses three rhetorical proofs: logic (logos), emotion (pathos), and ethics/credibility (ethos) (West, 2007). Aristotle identified five subjects: revenue, war and peace, the defence of the country, commerce, and legislation (Arnhart, 1981). Greta Thunberg uses rhetoric theory in her digital identity to motive her audience to do climate strike by pointing out environmental issues but after the coronavirus pandemic she has started to arrange it digital. Thus, traditional strike has been digitalizated. She shows facts about climate change what makes logical reason to strike for audience (logos). She is a credible information source as she is the future generation who will inherit the earth (ethos). She makes the audience think and touch their emotions about the future generations and persuades them to strike (pathos).
3. Problem Definition
The aim of this project is to understand to what extend climate activist Greta Thunberg’s tweets with #DigitalStrike #ClimateStrikeOnline and #DigitalClimateStrike hashtags trigger people for online activism through digital world. To see the impact on her audience, operationalization is needed.

Table of Operationalization
Concept	Variable	Indicator
Greta Thunder’s tweets about digital strike	Hashtags with Digital Strike, Climate Strike Online, Digital Climate Strike	Greta's timeline
	Frequency	Amount of contents
Audience Reactions of Greta Thunder’s tweets about digital strike	Likes	Number of likes
	Retweets	Number of retweets
Fridayforfuture. Org	Strikes	Number of strikes 

4. Methodology
The number of retweets is a good indicator of an issue’s dissemination because retweets are automatically presented to new audiences and retweeting is a more active (Jung et al., 2020). However, like counts were also important to see the effects therefore number of likes and retweets were collected. Twitter’s Application Programming Interface (API) was used to retrieve Twitter data because it makes JavaScript Object Notation (JSON) format. The selected period was from March 2020 (when Greta made her first digital climate strike because of social distancing), until October 2020. Initial step was to retrieve Greta’s all tweets with hashtags #DigitalStrike #ClimateStrikeOnline and #DigitalClimateStrike (excluding responses) and save them to a JSON file (Tweetswithhashtags). In total, 161 tweets were collected. Afterwards, the retweet counts, the favourite counts and the date information were extracted from each tweet and a data frame object was created using this information. Besides that, statistics of climate strike were collected by web scraping from her FridaysforFuture.org social movement website to see whether there is any relations with her tweets (Although FridaysforFuture.org does not have digital strikes, it was included in my study for web scraping experience). The date formats on the website for were not suitable for analysing. Therefore, these dates were formatted into date/month/year format with using datetime library. Also, the table shape was changed since the original table had an empty column. It was deleted and for the ease of use with the dataframe objects from pandas library.
5. Results
According to the graphic between the given period, there was a fluctuation however the first two weeks of the digital strike concept is the highest in the chart. It has neither upward nor onward trends after March 2020. 
6. Conclusion: 
Due to the coronavirus outbreak, strikes has become digitalized with digital identities on a platform. The concept of digital strike seems to continue driving public awareness digitally considering the graphic however there is not always sustainable persuasion of the Greta Thunberg from her timeline in every digital strike call when we see it does not have on-going increase. 









References
Arnhart, L. (1981). Aristotle on political reasoning: A commentary on rhetoric. DeKalb: Northern Illinois University Press.
ELA Virtual Learning. (2020, April 15). English II. Webcache.Googleusercontent.Com. http://webcache.googleusercontent.com/search?q=cache:OGZ_4z-c9LQJ:sites.isdschools.org/hs_ela_remote_learning_resources/useruploads/english-ii/English%2520II_McCain_April%252015.pdf+&cd=19&hl=en&ct=clnk&gl=nl&client=opera
Jung, J., Petkanic, P., Nan, D., & Kim, J. H. (2020). When a Girl Awakened the World: A User and Social Message Analysis of Greta Thunberg. Sustainability, 12(7), 2707. https://doi.org/10.3390/su12072707
Murray, S. (2020). Framing a climate crisis: A descriptive framing analysis of how Greta Thunberg inspired the masses to take to the streets. http://uu.diva-portal.org/smash/record.jsf?pid=diva2%3A1386491&dswid=-593






