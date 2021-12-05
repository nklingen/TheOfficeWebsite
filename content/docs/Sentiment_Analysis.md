---
title: "Sentiment Analysis"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# Sentiment Analysis

In this section, we will see which characters are the saddest and which are the happiest and which are more emotionally stable and unstable. There is also drama thorughout the season, so we will explore the character's emotional developement for the main characters. Finally, we explore the sentiment evolution throughout the seasons and the saddest and happiest characters. 

## Sentiment profile of the characters

From the dialogue, we can analyze the characters' sentiments and determine the distribution of these. 

![sentiment_distribution]({{<baseurl>}}/images/sentiment_distribution.png)

One can see that distribution resembles that of a Gaussian one, but skewed to the right. The majority of characters fall within a neutral sentiment, a few others very sad and the rest happy, which is appropritate for a comedy like The Office. If we look at the happiest character, we find `Walter & Walter Jr`, Andy's dad and brother, singing a very cheerful song. On the other extreme, we find `Michael`, `Pam` and `Ryan` also synchronously signing the song U.G.L.Y., which is quite negative. 

We will now focus on the sentiment of the main characters, individually, to see which are the happiest and saddest main characters, as shown in the plot below.

![sentiment_per_character]({{<baseurl>}}/images/sentiment_per_character.png)

One can appreciate that Clark, Michael and Gabe are the happiest characters. It doesn't come as a suprise for Clark, who is an excited intern in the laste season and for Michael, who is always naively optimistic. However, Gabe doesn't come off as one of the happiest characters, but rather emotionless. It could have to do with the subset of the dialogue chosen. On the other hand, we have Stanley, Meredith and Angela. Stanley is always grumpy, Meredith has a messy personal life and is often the victim of some unfortunate incidents in the office and Angela is cold and stern and is rarely seen smiling. Thus, the sentiments computed seem to be in general quite accurate.

We also look at the boxplots for their sentiments to analyze how emotionally stable they are.

![sentiment_distribution_boxplot]({{<baseurl>}}/images/sentiment_distribution_boxplot.png)

One can observe from the graph above that there characters with low standard deviation and few outliers, such as `Michael`, `Dwight`, `Jim`, `Karen` or `Pam` and others with high standar deviation and many outliers, specially `Creed`, `Meredith` or `Stanley`. In general, those more stable are the characters that are more developed in the series and have more lines, so the analysis is more accurate. On the other hand, those that are more unstable have less screentime and they often appear for comical moments, which might explain their more exagerated reactions to more exageratic situations.

Finally, we also plot the average sentiment for each season.

![avg_sentiment_episode]({{<baseurl>}}/images/avg_sentiment_episode.png)

The average sentiment per episode seems to very a lot from one episode to another, but the average sentiment throught the series is apparently stable. The happiest episode is `PDA`, where Michael and Holly just started dating and have public displays of affection (PDA), Andy and Erin go on a romantic treasure hunt and Jim and Pam get tips on champagne. The saddest eppisode is `Double Date` where Jim, Pam, Michael and Pam´s mum go on a double date but Michael ends up breaking up with Pam´s mom. She gets very upset and Pam gets extremely angry with Michael.

## Sentiment developement of the main characters

We will focus on the character development of the main characters throughut the series: Michael, Dwight, Jim, Pam and Andy. We start with plotting their average sentiment throughout the seasons and examining their evolution.

![character_sentiment_developement]({{<baseurl>}}/images/character_sentiment_developement.png)

TODO: analysis of this

Now let us look at the average sentiment of these characters per episode, in order to see if we can highlight some episodes which were particularly emotional for them.

![sentiment_per_episode_main]({{<baseurl>}}/images/sentiment_per_episode_main.png)

There are a few episodes that had a high emotional load for Pam, Dwight and Andy, but we cannot observe any significant ones for Michael or Jim.

For Pam, she's happiest at `PDA`, when her and Jim drink champagne during lunch spend the whole episode goofing around in the office, followed by `The Delivery`, where she gives birth to her first child with Jim.

etc ...