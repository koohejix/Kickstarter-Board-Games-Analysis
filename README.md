# Kickstarter Project: Analysis of Campaigns for Boardgames

## __Project Overview__

This project seeks to find what factors, trends, and qualities of a Kickstarter for a board game lead to successful campaign outcomes. This project analyzes data of Kickstarter campaigns from the years 2009 - 2012, focusing in particular on the "Board & Card Game" category. The project explores metrics such as funding goals, campaign duration, reward levels, and launch timing to determine the primary driving factors of success in a Kickstarter campaign.

## Objectives

- Compare the success rate of campaigns in the board games subcategory with the success rate of campaigns in other categories and ones in the wider games category.
- Identify the optimal funding goal for campaigns in the board games subcategory.
- Determine the impact of different metrics such as campaign duration, launch timing, and number of reward levels on the success rate of campaigns.
- Conduct research on the components of the most successful board game Kickstarter campaigns to determine what wider traits they have in common that may not be represented in the dataset, as well as which of these traits is lacking in less successful campaigns.

## Dataset and Data Dictionary

__Kickstarter Dataset:__ 45957 rows across 17 columns with each row representing one Kickstarter campaign. The columns in the dataset include:

__1. project id:__ A unique 5 digit identifier representing each Kickstarter campaign.

__2.name:__ The title of the campaign

__3.url:__ Direct link to the Kickstarter campaign page.

__4.category:__ General category of the project.

__5.subcategory:__ More specific classification, e.g. Category: Games, Subcategory: Board & Card Games

__6.location:__ City and state where the project is based.

__7.status:__ Result of the campaign, successful means the funding goal was met, failed means the funding goal was not met, canceled denotes the campaign being ended prematurely before the funding duration was completed, and live denotes the campaign being ongoing.

__8.goal:__ The target funding amount set by the creator in dollars.

__9.pledged:__ Amount of money the campaign recieved from backers in dollars.

__10.funded percentage:__ How much of the funded goal was earned, represented as a decimal number, with values above 1 signifying pledge amounts recieved in excess of the funding goal.

__11.backers:__ Number of people who backed the project.

__12.funded date:__ When the campaign ended or was funded.

__13.levels:__ The number of different reward tiers offered to backers by the campaigns.

__14.reward levels:__ Comma seperated dollar amounts representing the required pledge for each of the reward levels in the campaign.

__15.updates:__ Number of updates posted during the campaign.

__16.comments:__ Total number of public comments.

__17.duration:__ Campaign length in days.

Filtering the dataset to only the boardgames subcategory results in a dataset of 553 campaigns across the same 17 columns.

## Analysis

- Board game campaigns have a 55% success rate, with the rate being the highest in the wider Games category.
- Projects with a goal under $20,000 dollars had higher success rates on average.
- Campaigns which had between 10 and 13 reward levels attracted a higher amount of backers in total.
- Campaigns which ran for longer than 45 days were more likely to fail than campaigns with shorter funding durations.
- The month with the highest amount of successful campaigns was May.
- The most successful campaigns in terms of total pledge amount tended to be submitted by established board game designers under game publishing companies.
- Successful campaigns had much clearer descriptions, deliverables, video demonstrations, and roadmaps for the future compared to failed campaigns.

## Conclusion

The results of the analysis found that campaigns for board games had the highest success rate in the games cateogories, and was consistent with success rates for campaigns across all categories. The analysis showed that for campaigns in the board games subcategory, the campaign duration should be kept shorter and more focused, with durations under 45 days yielding higher success rates than longer running campaigns. The ideal funding goal for board games tended to be under $20,000 dollars, with larger funding goals tending to fail more often, while campaigns having an amount of reward tiers between 10 and 13 attracted the most total backers. The analysis showed that more successful board game campaigns were launched in May compared to every other month. When browsing the campaigns of the most successful projects in terms of total pledges recieved, it was observed that the most successful campaigns tended to be published by experienced game designers under the umbrella of established games publishing companies. These campaigns also tended to have a clearer demonstration of the product being delivered, with higher quality videos and thorough descriptions of the rules and exact deliverables of each reward tier compared to less successful projects, as well as a greater leveraging of the advantages of Kickstarter as a crowdfunding website through the introduction of stretch goals and Kickstarter exclusive benefits, leading to pledge amounts far exceeding the designated funding goals.

## How to Run

1. Clone the repository.
2. Install the necessary dependencies listed below.
3. Run the notebook file to reproduce the EDA, including creating the clean datasets.
4. Run the Microsoft Power BI .pbix file to view the visualizations.

## Dependencies

- Python 3
- Jupyter Lab
- Pandas
- Numpy
- Microsoft Power BI


```python

```
