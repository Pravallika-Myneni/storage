# Introduction
In December 2020, the polling company Ipsos surveyed adults in 15 countries about whether they intended to get vaccinated. In some countries, the findings were not encouraging. Only 12% of French respondents “strongly” agreed with the statement, “If a vaccine for Covid-19 were available, I would get it.” Only 40% agreed overall. According to the US Centers for Disease Control and Prevention (CDC) and other global health bodies, vaccine hesitancy is a nuanced concept that describes people who, for various reasons, wait to accept or refuse to take a vaccine even when it is available to them.In order to tackle vaccine hestiancy, some US states, for example, offer lottery tickets and free beer to adults who get vaccinated. These kinds of creative incentives a might help nudge vaccine receptive or vaccine neutral adults. There is growing evidence that incentives do motivate those who are either reluctant to get a shot or just haven’t gotten around to it. Our focus is to use the Sentiment & Opinion Mining Natural Language API to analyze and visualize how people respond about such **#vaccine-incentives** on twitter

# Features 
The main features of NLP Vaccine Analysis include
* Presents a bar chart with *distribution of sentiments*
* Explains the *composition of Emotions* and *Composition of Behaviour* through pie charts
* A word cloud

# How we Built NLP Vaccine Analysis
We started off with an active brainstorm session regarding how we can effectively use the  expert.ai API and came up with an idea of analyzing the tweets on Vaccine incentives.
We have scraped the tweets using tweepy, performed text cleaning.
Developed the website using HTML, CSS, Flask and python

# How to use NLP Vaccine Analysis
steps to try NLP Vaccine Analysis
## To get the website running
1. mkdir new_folder_git_website
2. git clone https://github.com/yjzhang3/Vaccine-Sent-NLP.git
3. git checkout dev_Main
4. pip3 install -r requirements.txt
5. python3 app.py
Boom!! The NLP Vaccine Analysis website will be running on http://127.0.0.1:5000/

## In the webpage
Select the state from the dropdown and click on the button *Get the selected State Analysis* to get * A bar graph for distribution of sentiments*, 
*composition of Emotions*  and *Composition of Behaviour* through pie charts and a wordcloud for the selected state

# What's next for NLP Vaccine Analysis
* Hosting the website
* Working on a larger number of tweets
* Increasing the scope in terms of location
