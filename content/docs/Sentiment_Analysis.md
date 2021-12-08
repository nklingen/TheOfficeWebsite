---
title: "Sentiment Analysis"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# Sentiment Analysis

In this section, we explore the happiest, saddest, and most emotionally unstable characters. We will also analyse the character development of some main characters across the seasons, based on their sentiment evolution.

## Sentiment for all characters

From the dialogue, we can analyze the characters' sentiments. 

![sentiment_distribution]({{<baseurl>}}/images/sentiment_distribution.png)

We find that the distribution resembles a right-skewed Gaussian distribution with one peak around 0 specifically for the characters that had too few lines to be placed by the analysis. The majority of characters fall within a neutral sentiment or are generally happy, with a few notable exceptions of particularly unhappy characters. This is appropriate for a comedy like The Office, where the tone is generally comedic and fun. If we look at the happiest character, we find `Walter & Walter Jr`, Andy's dad and brother, singing a very cheerful song. On the other extreme, we find `Michael`, `Pam` and `Ryan` also synchronously signing the song U.G.L.Y., which is quite negative. 

## Sentiment for main characters
We will now focus the main characters, individually.

![sentiment_per_character]({{<baseurl>}}/images/sentiment_per_character.png)

We find that Clark, Michael and Gabe are the happiest characters. It doesn't come as a suprise for the bubbly intern Clark, nor for naively optimistic Michael. However, Gabe doesn't come off as a genuinely happy characters, but rather as awkward and restrained in his behavior. Here, we speculate that the dialogue analysis is purely based on word choice and script, rather than the delivery of the words and genuine emotion conveyed. 

On the other side of the spectrum, we have Stanley, Meredith and Angela. Stanley is an obvious character to fall here, as his character is always grumpy. Angela, similarly, is cold and stern, and very rarely shows positivity. Finally, we speculate that Meredith was placed here due to her messy personal life in which she often is victim of unfortunate events. Thus, the sentiments computed seem to be generally accurate.

## Emotional Stability of main characters
We also look at the boxplots for each characters' sentiments to analyze how emotionally stable they are - that is, how much their sentiment varies.

![sentiment_distribution_boxplot]({{<baseurl>}}/images/sentiment_distribution_boxplot.png)

We observe that there characters with low standard deviation and few outliers, such as `Michael`, `Dwight`, `Jim`, `Karen` or `Pam` and others with high standard deviation and many outliers, specially `Creed`, `Meredith` or `Stanley`. In general, we note that characters depicted as more unstable generally had less screentime and often appeared for particularly comical moments, which might explain their more exagerated reactions in more exageratic situations.

## Average sentiment for each season.

{{< include-html "content/interactive/combined.html" >}}

The while the average sentiment per episode seems to very a lot, in general it was more stable across seasons. The happiest episode is `Threat Level Midnight`, where Michael finishes his movie, featuring several of his coworkers. The saddest eppisode is `Murder` where the branch learns that it is likely to be closed. Moreover, they play a murder mystery game to distract themselves, using many words related to "murder" and "kill",  which are words with a very low sentiment.

## Sentiment development of the main characters

Next, we plot the character development of the main characters throughout the series. We begin by plotting their average sentiment throughout the seasons and examining their evolution.

{{< include-html "content/interactive/sentimentdevelopmainmaincharacters.html" >}}

One can see that Dwight is the saddest, but he does get happier with the seasons. In the last seasons his career takes off and he becomes Regional Manager, his dream. He also marries Angela and discovers that her son is his. Finally, he inherits a farm. 

Pam also gets happier; she is at first not very happy either with her fiance Roy nor her position as a secretary. Both these things change; she ends up forming a family with Jim and having a job better suited to her potential.

Jim starts sentiment seems to decrease when he is rejected by Pam and moves to Stamford, but then increases as he forms a family with Pam and starts his dream job in Athlead.

Michael's sentiment also seems to decrease with the seasons, probably because of the multiple unfortunate events that happen to him. He looks happier in his last season, when he finally marries Holly.

Finally, Andy seems very happy in season 4, possibly because he is dating Angela and his sentiment has a noticable decrease in season 5, after he discovers Angela was cheating with Dwight all along.

Now let us look at the average sentiment of these characters per episode, in order to see if we can highlight some episodes which were particularly emotional for them.

{{< include-html "content/interactive/sentimentanalysisperep.html" >}}

There are a few episodes that had a high emotional load for Pam, Dwight and Andy, but we cannot observe any significant ones for Michael or Jim.

For Pam, she's happiest at `Threat Level Midnight`, where she has great fun watching Michael's movie, followed by `Saint Patrick's day`, the day after she gives birth to her first child with Jim. In contrast, she is saddest at `Dwight K. Schrute, (Acting) Manager`, where Dwight is named acting regional manager and terrorizes everyone, and `The Negotiation`, where Roy gets furious at Jim because of Pam.

For Dwight, the saddes moments are `Diwali`, where Michael´s girlfriend breaks up with him after he proposes. Since Dwight is Michael´s closest friend, he feels very sad for him. He is also sad is `Spooked`, where he is upset with Toby for removing the weapons from his Halloween costume.

For Andy, the happiest is `The Banker`, where Andy pretends to be very excited to impress the banker. He is also happy in `Night Out`, where he and Angela are voted the best couple.