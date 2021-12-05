---
title: "Communities"
date: 2021-11-24T16:46:57+01:00
draft: false
---

# Communities

We will use the [Louvain method](https://en.wikipedia.org/wiki/Louvain_method) to divide the network into communities of characters in order to see if we can find some intresting groupings from the network alone.

## Methodology

## Results

This yields 11 communities, which are illustrated in the image below. Each community has a diferent color and labels correspond to the characters that are at the center of each community.

![communities_network]({{<baseurl>}}/images/communities_network.png)


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


The groupings found by the Louvain algorithm proof to be quite insightful, since there are some parallelisms between the characters placed in the same group and how close they are in the series.


For example, if we look at community 4, it is formed up of Jim and Pam, their children and family relatives of both. This implies a strong bond between the both of them, and there is one indeed, since they have the main romance storyline throught the series and end up marrying and having a family of their own.

 Similarly, in 3 we find Angela and Dwight to be the main characters in that community which have an on-and-off relationship during the series and also end up marrying in the last episode. In that same category, we find Robert Lipton, which is Angela´s ex-husband, as wll as Angela's cat, Garbage, and some of Dwight's family members. 

The trend where romantic partners and family members being placed within the same community is visible: Michael and Holly in 1, Phyllis and Bob in 9, and Andy's and Erin's families in 1 and 2 respectively, amongst others. In case of community 8, corporate characters are grouped together.

However, there are some character's that don't have an obvious bond with the rest of the characters of the community they belong to. For example, Meredith has little interaction with Angela or Dwight, or Oscar with Jan. We would also expect Ryan and Kelly to be placed together, since they are one of the show's couples with most drama.

All in all, the communities found from the network have in general a strong cohesion. It is also intresting to point out that these communities are mostly tied together by the personal relationships instead of the categorization we chose for the [Network analysis](Network_Analysis.md) section (main characters, warehouse workers, family members, etc).