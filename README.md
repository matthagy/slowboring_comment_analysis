# Slow Boring Comment Analysis

A basic analysis of comments from [Slow Boring](https://www.slowboring.com/) between January and April of 2022.

Some high-level findings

* 212 articles were posted in this time period of four months
* 29,900 comments were posted on these articles
* 2,040 unique users posted comments
* 2 comments were posted by the median commenter
* 1,508 comments were made by the most prolific user
* 56 users each posted at least 100 comments
* 12.4% of users accounted for 80% of all comments
* 2.35% of users accounted for 50% of all comments
* the Gini coefficient of comments per a user is 0.819

The descriptive stats for comments per a user are:

| stat            |   mean |   min |   25% |   50% |   75% |   90% |   95% |   99% |   max |
|:----------------|-------:|------:|------:|------:|------:|------:|------:|------:|------:|
| comments / user |   14.7 |     1 |     1 |     2 |     7 |    23 |    55 | 243.7 |  1508 |

In terms of likes (i.e., ❤'s)

* 95,423 likes were given in total
* 229 likes were given to the single most-liked comment
* 4,545 likes were awarded to the most liked user summed across all of their comments
* the median commentator received 5 total likes
* the Gini coefficient of total likes per a user is 0.774

The descriptive stats for total likes per a user are:

| stat         |   mean |   min |   25% |   50% |   75% |   90% |   95% |   99% |   max |
|:-------------|-------:|------:|------:|------:|------:|------:|------:|------:|------:|
| likes / user |   46.8 |     0 |     1 |     5 |    23 |    78 |   183 |   841 |  4545 |


The details of the analysis are in the Jupyter notebook [analysis.ipynb](./analysis.ipynb).