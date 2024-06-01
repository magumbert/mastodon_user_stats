# Mastodon: User Statistics

<img src="mastodon_icon.png" alt="Msastodon icon" width="400" height="400" />


[Mastodon](https://joinmastodon.org/) is a free and open-source social networking service established in 2016 by Eugen Rochko. It offers microblogging features akin to X (formerly Twitter). Notably, Mastodon experienced a surge in popularity following Elon Musk's acquisition of Twitter, with approximately 2 million users migrating from Twitter to Mastodon. This project aims to delve deeper into Mastodon user statistics to gain insights into user behavior and platform dynamics.

## Project Objectives

The primary objectives of this project include:

1. **Top 80 Accounts Analysis**: Investigating the top 80 Mastodon accounts to understand their activity levels and engagement.
   
2. **Activity Patterns**: Analyzing when these top accounts are most active to identify peak engagement periods.
   
3. **Trending Topics Analysis**: Exploring trending hashtags and statuses to determine prevalent topics of discussion on the platform. These are independent of the top 80 accounts considering the whole Mastodon community.

## Findings and Insights

- **Top Account Activity**: The analysis reveals insights into the activity levels of the top 80 Mastodon accounts, shedding light on their posting frequency and engagement metrics.
  
- **Activity Patterns**: Examining activity patterns uncovers when these top accounts are particularly active.
  
- **Trending Topics**: Investigating trending hashtags and statuses allows identification of prevalent topics of discussion on Mastodon and observes any convergence of discussions around specific themes.

## Requirements & Setup:
### Requirements:
- Python 3.11.15
- Mastodon.py 1.8.1
- Pandas 2.1.1
- Plotly 5.22.0

### Setup:
To run this project, you will need your own Mastodon account. This allows you to get access to Mastodon's API providing you with a client_id, client_secret, and access_token. Save these in a seperate py-file named "mastodon_access_info". 

Running the "mastodon_user_has_info" juypter notebook then allows to retrieve todays user statistics. The script was last run on June 1st 2024, thus your results will most likely differ from what I got.

**Have fun!**
