# Game_Analysis
Mobile gaming makes up nearly 75 percent of global mobile revenue during first half of 2019. A report reveals that gaming made up approximately $29.6 billion of mobile revenue.

As a gamer myself, I have motivated myself to analyse an open Kaggle open dataset "17K Mobile Strategy Games" that contains 17,000 unique games & 16 variables to work with. Data handling & Visualization done by using Python in Jupyter Notebook.

## Objective

To expose the best combination for strategy games available in the AppStore in order to get a good user rating (4.0/5.0 and above).

## Investigation Strategy

To analyse the dataset, we will look at the following relationship:

1.Size vs User Rating (Grouped by Genre)

2.Original Release date vs Size (Grouped by Genre)

3.Game Price and In-App Purchase Factor (Grouped by Genre)

4.Age Rating Factor Data are cleaned and then visualized in Jupyter Notebook

## Assumptions

1.Games without User Rating are dropped.

2.Games with less than 200 user rating are dropped. This is to prevent biased rating from developer and/or their friends' rating.

3.There are about 600 unique game genre in the dataset due to different combination of genre, and sequence of genre. However final genre will be only 5 types.
