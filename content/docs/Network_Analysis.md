---
title: "Network Analysis"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# Network Analysis

## Analysis of degree distributions

![viewership_seasons]({{<baseurl>}}/images/NetworkAnalysis.png)

We plot the degree distributions both before and after making the GCC which we used in the network. The rest of the project will use the GCC for the network, where outliers have been removed.

### Inward degree distribution

We see a power-law distribution, which has a majority of nodes with few in-going links, and few nodes with many in-going degrees. We can explain this by noting that the main characters overwhelmingly have many ingoing links from more minor characters, without referencing those characters in return. While interactions with main characters are significant for minor characters, they are insignificant in the storyline of the main-characters, leading to a one-sided relationship. Similarly, the power law defines that a network usually consists of a few hubs that most other nodes are connected to. The magnitude of nodes with 0 ingoing edges is reduced after discarding all nodes not in the GCC. However, we still observe many nodes with no ingoing edges.

### Outward degree distribution

In the GCC, we see a somewhat Poisson-like distribution. We notice that even after removing outliers, there are still some cases where characters have no outgoing connections. These characters were not removed when creating the GCC as they must still have an ingoing-link connecting them to the giant component. More specifically, they are referenced by a more "central" character, without them referencing that character in return. Lastly, we note that the vast majority of characters that are in the GCC have just one ingoing-link.

## Plot of the Network
![viewership_seasons]({{<baseurl>}}/images/network.png)