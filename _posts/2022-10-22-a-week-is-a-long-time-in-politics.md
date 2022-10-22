---
title: 'A week is a long time in politics'
date: 2022-10-22
permalink: /posts/2022/10/a-week-is-a-long-time-in-politics/
tags:
  - personal
  - politics
---

As the saying goes, a week is a long time in politics. Assuming that to be true, a month is like an eternity. 

It certainly feels that way. Less than a month ago, I wrote a [post](https://www.calvinkarpenko.com/posts/2022/09/progress-update) stating that I felt that the risk of a general election had subsided with the appointment of Liz Truss, and that I was going to take a bit more time to work on my general election project. That was before the mini-budget and the resulting fallout from that. Two weeks ago I decided that the fall in the polls was so disastrous that it wouldn't be long before the Conservative Party would remove Truss, causing some instability and increasing the risk of a general election again, so I began working on the project again. 

I'm glad I did as on Thursday, Truss resigned. I don't think it was a big surprise to anyone that she resigned as she was clearly causing damage to the Conservative Party's electoral prospect. As it happens, when she resigned I was at my graduation ceremony for my masters degree (delayed due to Covid) and had been discussing my project plans with others. 

So what is the project I'm working on? Essentially it's the natural extension of my masters thesis, essentially applying the methodology of my thesis to another election, namely the next UK General Election. 

The first phase of the project is already underway and is actually almost finished. This phase is the creation of a program that can be used to interface with Twitter's Streaming API to collect and archive tweets based on filtering rules defined by a user. So, for example, if I want to search for tweets that contain the phrases 'GeneralElection' and 'GE2022', I would apply a rule to filter the stream for those tweets. Those filtered tweets would then be printed to a console and archived for later analysis. 

The current progress of the program is shown in the image below.

![The interface of the Twitter Streaming Client](http://www.calvinkarpenko.com/images/election-twitter-streaming-client.png)

I have been focusing on getting the program ready for my own data collection, so much of the configuration is based on my own requirements. I do have the intention of releasing the program on Github but I want to improve it before I do so. I am intending to move the configuration into its own window and allow the customisation of the fields that are collected by the filter. But as a first pass it works well and does what I need it to do.

The second phase of the project is the collection of tweets and creation of a dataset of tweets, as soon as the next election is announced. This will mean there is a good dataset of tweets that can be used by researchers for further academic research. 

The third phase will be the research that I will carry out on the same dataset - to apply my methodology I used in my research on the 2020 US Presidential Election to predict the outcome of the UK General Election. 
