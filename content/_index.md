---
title: "About"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# About
This website was created by [Blanca Robledo Díaz](https://github.com/Blankuca), [Oliver Zeman](https://github.com/oliverzeman9) and [Natasha Ø. Klingenbrunn](https://github.com/nklingen) as a final project for the course [02805 Social graphs and interactions](https://github.com/SocialComplexityLab/socialgraphs2021/wiki) offered by the Technical University of Denmark.


Each of the following sections will analyse and visualize different datasets relating to the office.

Read our [Explainer Notebook](https://nbviewer.org/github/nklingen/SocialGraphsProject/blob/main/Explainer_Notebook.ipynb) to learn more about motivation for this project, our methodology, a breakdown of the theory used in the project, and a conclusion/discussion to sum up our thoughts. Also, feel free to download [GitHub repo](https://github.com/nklingen/SocialGraphsProject) and explore the datasets and our code!

# Our goal

We will focus on analyzing The Office, which is an American mockumentary sitcom television series that depicts the everyday work lives of office employees in a branch of the Dunder Mifflin Paper Company [1]). We decided to focus on this because we are huge fans and it's a topic we are very familiar with.

We want to a do an in-depth analysis of The Office to find some intresting insights and fun facts about the series and its characters. Given that the network is not big enough (less than 1000 characters) to find some intresting patterns in their social behaviour, our approach will heavily focus on a more qualitative analysis of the series. More specifically, we will do the following:

- Model the network of characters and extract information such as who is related to who, which characters are more popular and some other basic statistics (number of links and nodes, distrbution, etc).
- Find possible underlying communities and analyze what they have in common.
- Extract the most descriptive words that characterize each character from their wiki pages and analyze the characters´ dialogue to explore any visible personality traits in their way of speaking, using wordclouds.
- Determine which characters have the most lines throghout the series and see who interacts the most with whom.
- Analyze the sentiment of the series on average throughout the seasons and episodes and also for the individual characters, to determine who are the happiest, the saddest or who are the most emotionally stable/unstable.
- Explore the sentiment developement for the main characters throughout the series as well as determine the episodes that had a biggest emotional charge for them and why.
- Analyze the viewership and ratings of the series per episode and find possible explanations for the observed trends, while correlating them other parameters in the network.
- Explore the different directors for each episode, such as who had the highest ratings and who directed the most episodes.

For this, we use the following datasets:

- The Office Wiki. For retrieving the characters and the links between each other, their category, the seasons they appear in and their biographical information.
- The Office script. To retrieve the dialogue of the characters that will allow us to extract their sentiment, any characterisitc expresions and the interaction network.
- IMBd ratings. To explore how the ratings varied throughout the episodes.
Kaggle Dataset. For directors and viewership.