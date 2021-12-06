---
title: "Communities"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# Communities


## Methodology

We will use the [Louvain method](https://en.wikipedia.org/wiki/Louvain_method) to detect communities within the larger network. This algorithm is a [hierarchical clustering algorithm](https://neo4j.com/docs/graph-data-science/current/algorithms/louvain/), that recursively merges smaller communities in order to maximize the modularity score, which measures how densely connected the nodes are within the same community.

## Plot

The Louvain method yielded the following 11 communities, illustrated in the table below. In addition, the communities are plotted using Force Atlas, with nodes colored by community and labeled with the largest character in each community. 

![communities_network]({{<baseurl>}}/images/communities_network.png)

## Table
Now let's take a closer look at the members of each community. The following table shows the seven most connected characters, in descending order, for each community.

| 1                  | 2               | 3                  | 4               | 5                 | 6                  | 7                  | 8               | 9                     | 10             | 11                   |
|--------------------|-----------------|--------------------|-----------------|-------------------|--------------------|--------------------|-----------------|-----------------------|----------------|----------------------|
| Andy Bernard       | Erin Hannon     | Dwight Schrute  | Jim Halpert     | Robert California | Michael Scott      | Kelly Kapoor     | David Wallace  | Phyllis Vance         | Kevin Malone   | Jan Levinson         |
| Walter Bernard Jr. | Erin's Mother   | Angela Martin   | Pam Beesly      | Toby Flenderson   | Holly Flax         | Darryl Philbin   | Ryan Howard    | Karen Filippelli      | Stanley Hudson | Oscar Martinez       |
| Walter Bernard Sr. | Erin's Father   | Robert Lipton   | Cecelia Halpert | Gabe Lewis        | Creed Bratton      | Deangelo Vickers | Charles Miner  | Bob Vance             | Cynthia        | Michael Scarn        |
| Ellen Bernard      | Irene           | Mose Schrute    | Phillip Halpert | Todd Packer       | Scranton Strangler | Pete Miller      | Nellie Bertram | Hannah Smoterich-Barr | Melissa Hudson | Goldenface           |
| Nick               | Glenn (Florida) | Garbage         | Helene Beesly   | Jo Bennett        | Ed Truck           | Julius Erving    | Alan Brand     | Josh Porter           | Teri Hudson    | Pizza Delivery Kid   |
| Sadiq              | Reed            | Aunt Shirley    | Betsy Halpert   | Cathy Becker      | Michael Klump      | Clark Green      | David Brent    | Danny Cordray         | Stacy          | Astrid Levinson      |
| Cathy Simms        |                 | Meredith Palmer | William Beesly  | Jordan Garfield   | Mr. Flax           | Jada Philbin     | Neil Godwin    | Phyllis' Sister       | Abby           | Catherine Zeta-Scarn |


## Analysis

The groupings found by the Louvain algorithm prove to be very insightful, as we can find many reasonable links between the communities and the series. 

We see in `Community 1` Andy and his family.

In `Community 2`, we find Erin and her family.

Next, in `Community 3` we find Angela and Dwight, who share an on-and-off relationship during the series and get married in the last episode. In that same category, we also find Robert Lipton, Angela's ex-husband, as well as Angela's cat, Garbage, and some of Dwight's family members, including Mose.

`Community 4` consists of Jim and Pam, their children, and their relatives. We expect to find them together, as their relationship is the many storyline throughout the series. 

`Community 5` consists of many of the executives from the later seasons, including Jo Bennett, Gabe, and Robert California. We also notice the Toby is put in this group, which can be explained by the fact that he has very few meaningful connections to the rest of the employees, and mainly is involved in HR issues and disciplinary meetings where other executives also are present.

In `Community 6`, we find Michael and Holly. Very oddly, Creed and the Scranton Strangler are also in this group.

In `Community 7` we also find an unlikely pairing. We would have expected Kelly and Ryan to be placed together, as they were also in a very toxic drama-filled on-and-off relationship throughout much of the series. However, Kelly was placed in a community with Darryl, with whom she only shared a brief relationship.

In `Community 8` we find another group of executives, including Alan Brand, David Wallace, Charles Miner, and Ryan Howard. In this regards, we find that Ryan was placed with respect to his position (as a previous executive) rather than his interpersonal relationships.

`Community 9` consists of Phyllis and her husband Bob Vance, as well as Karen Filipelli.


We notice a clear trend where romantic partners and families are placed together, including Michael and Holly in 1, Phyllis and Bob in 9, and Andy's and Erin's families in 1 and 2 respectively, amongst others. 

While many minor characters seem to be placed with some randomness, there are also some significant characters that didn't seem to have an obvious bond with the rest of the characters in their community. For example, Meredith does not have a particular connection to Angela or Dwight, neither does Oscar to Jan, nor Creed to Michael.

All in all, the communities detected by the algorithm had a strong cohesion. It is also intresting to point out that these communities are mostly tied together by the personal relationships instead of the categories we chose for the [Network analysis](Network_Analysis.md) section (main characters, warehouse workers, family members, etc).