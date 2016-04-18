# Project-for-Data-Incubator
This repo contains data and initial findings regarding the project proposed to do at Data Incubator

At Stage1, Goals are set. Initial raw data are prepared. General thoughts are generated. Initial explorations of raw data are done.

Goal:
Using machine learning, try novel features to amplify signals for stock prices prediction.

Milestone 1: design a good measure of good individual investors. 
            Thoughts: 
            a. analyze positive/negative signals of tweets from the same twitter ID. correlate it with stock price changes, on a daily basis. Use Pearson correlation as the measure. 
            b. need to be active twitter user. (at least once per two days?)
Milestone 2: allocate all these detected 'good individual investors', and only use their tweets for stock price prediction.

Raw Data: 
Twitter data: collected on a weekly basis, from 2014 02 to 2014 08, using Twitter search API for tweets containing stock related key words, e.g. $AAPL.

General thoughts:


Initial exploration:
active user numer. (have comments at least once a day, two days)
better to find one particular user who has good correlation with stocks of interest to him. If so, then select a ra

challenges:
1. on twitter, the noise is just to large. it is like to find a needle in an giant ocean to find real signal. 
2. Even if you find signal, you may not believe it.
3. There is usually a time lag between events and news. 


Hints from the challenges:
1. that is exactly why we need to filter out noise. not just relevent tweets, but also relevent sources of tweets, i.g. people.
2. so we need to not only look at a short period, but a longer period to validate the credability of the sources of tweets.
3. so we should not aim at a time scale short, or even equivalent, to this time lag. try 1 day as the time scale.
