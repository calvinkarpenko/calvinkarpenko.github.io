---
title: "UK General Election dataset"
layout: single-project
excerpt: "A project to create a dataset of tweet IDs that cover the next UK General Election"
collection: project
---

## Indefinitely Paused

Please read [my blog post](https://www.calvinkarpenko.com/posts/2023/05/twitter-pausing-my-elections-project/) to find out why the project is indefinitely being paused.

## Aims and Motivation

The aim of this project is primarily to create a dataset of tweets relating to the next UK General Election, whenever that may be. This is a dataset that can then be used by other researchers (as well as myself) for research into disinformation, bots, or used for election prediction modelling.
The motivation behind this is the lack of large datasets that can be used, as well as the existence of large datasets for the US Presidential Elections.

## Current Progress

The project is loosely split into three separate phases:

### Phase 1 - Streaming Client Development

The development of a Twitter Streaming Client is almost complete. This is a GUI interface for the Tweepy program that allows users to archive tweets and add/delete rules to filter tweets. There are a few remaining features left to add such as minor changes to layout and additional configuration options. Once the program has these features, I will release it open source on my Github. A screenshot of the current look of the program is below.

![The interface of the Twitter Streaming Client](http://www.calvinkarpenko.com/images/election-twitter-streaming-client.png)

### Phase 2 - Dataset Creation

As soon as a general election is announced, the streaming client will start archiving tweets and creating a dataset of them. Twitter's terms and conditions do not allow the publication of the contents of tweets so I will publish a dataset of tweet IDs that can be hydrated by those looking to use them. 

### Phase 3 - Election Modelling

During the campaign cycle I will use a similar methodology as I used for my masters thesis to train models and use them to (hopefully) predict the outcome of the election in percentage terms. 