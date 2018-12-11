---
title: Machine Learning & Analysis for Twitter Bot Detection
---
Munmun, Daisuke, Motoaki (Group 48)

<img src="index_files/twitcensor.jpg" alt="twitcensor" width="300"/>

## Motivation

There is an increasing prevalence of tweets generated by automated twitter accounts or 'bots', amidst the backdrop of the exponential growth of twitter usage which we have been seeing in recent years. The intensions behind the creation of these tweets varies, from non-malicious ones, such as government agencies ‘automatically’ generating tweets on adverse weather events to promptly alert the public, to malicious ones – seeking to manipulate the twitter community for commercial or political purposes. A simple ‘bot’ may be designed to follow a political figure in order to increase the figure’s follower counts. A more complicated ‘bot’ may send out automated tweets that resemble human behaviour, with the intention of influencing the public discourse. The official Twitter platform has done much work in detecting these automated ‘bots’ with malicious intents, seeking to block them from the platform. However, growing sophistication of the automated bots is making the process of detection increasingly difficult for the Twitter as well as the research community. Social Media, including twitter, has never been more important in our political dialogue, and we believe that the attempts to detect malicious bots would be a meaningful exercise, regardless of one's political affiliation.


## General Approach 

As we sought to detect certain behavioural patterns of the ‘bots’ and apply classification models to detect them, we stumbled upon a simple question which because our starting point.

>how can we devise a reliable model if we don’t know what the right answer is?

In our commitment to adhere to scientific methods, we ruled out a number of approaches suggested in the literature, and focused on methodologies suggested in the paper “cresci-2017” ("Paper" hereafter), for the researchers for the Paper has gone through extensive and rigorous efforts to generate a dataset of genuine twitter users and twitter bots, and they have generously published the relevant data on BotRepository[2], which provided an ideal environment upon which for us to carry out this project.

## Summary:
In summary, our general approach and objective may be summarized as follows:
* Explore dataset published by Cresci-2017
* Devise Classification Models to detect genuine twitter users and automated bots
* Seek to achieve accuracy score at levels at least equivalent to Cresci-2017
* Seek to improve the accuracy score with our unique approach where possible.

picture source: https://www.theverge.com/2017/8/13/16125852/identify-twitter-bot-botometer-spambot-program
bot repository https://botometer.iuni.iu.edu/bot-repository/index.html