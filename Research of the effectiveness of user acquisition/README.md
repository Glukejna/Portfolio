# Research of the effectiveness of user acquisition

## Description

The company develops and promotes entertainment applications for various types of devices. Despite huge investments in advertising, the company has been losing money for the past few months.

The goal of the project is to find out:

- where users come from and what devices they use
- how much does it cost to attract users from various advertising channels
- how much money each client brings
- when the cost of attracting a client pays off
- What are the factors hindering customer acquisition?

## Data Description

We have data about users attracted from May 1 to October 27, 2019:

*visits_info_short.csv* (server log with user visit data) structure:

*User Id* - unique user identifier,
*Region* — user's country,
*Device* — user device type,
*Channel* - transition source identifier,
*Session Start* — date and time of session start,
*Session End* — date and time when the session ended.

*orders_info_short.csv* (is information about purchases):

User Id - unique user identifier,
Event Dt - date and time of purchase,
Revenue — order amount.

*costs_info_short.csv* (is information about advertising costs) structure:

*Channel* — advertising source ID,
*Dt* — date of the advertising campaign,
*Costs* - Costs for this campaign.

## Installation

    - matplotlib==3.1.0
    - numpy==1.18.3
    - pandas==0.25.1
    - plotly==4.1.0
    - scipy==1.4.1
    - seaborn==0.9.0
    - statsmodels==0.10.1
