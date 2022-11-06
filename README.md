# Twitter Verified Users

All 413,137 verified users on Twitter as of Saturday, November 5th 2022.

[@verified](https://twitter.com/verified) is following 423,617 accounts. 10,480 of them are not verified and have been excluded from this csv file.

| Statistic  | Num |
| ------------- | ------------- |
| Total verified users  | 413,137  |
| Have tweeted in 2022 | 387,967 |
| Have tweeted in the past week | 287,198 |
| Average number of followers | 120,882 | 
| Have default profile picture  | 228  |
| Have never tweeted (or deleted them all)| 4,929 |
| Have tweets withheld in a country | 105 |
| Have protected account | 4,395 |
| Have no followers | 2 ([@rmghd19](https://twitter.com/rmghd19) and [@MBCLOUDFM](https://twitter.com/MBCLOUDFM)) |



| Column  | Description |
| ------------- | ------------- |
| `id`  | Twitter id  |
| `name`  | Account name  |
| `screen_name` | Twitter handle |
| `is_default_profile_image` | 0=false 1=true |
| `is_protected` | Is private account |
| `followers_count` | Number of twitter followers |
| `statuses_count` | Number of tweets |
| `is_verified` | Every account in this dataset = 1 |
| `is_default_profile` | Has the user changed their theme or background |
| `listed_count` | The number of public lists that the user is a member of |
| `withheld_in_countries` | Two-letter country codes this user is withheld from |
| `friends_count` | Number of accounts they are following |
| `favourites_count` | Number of tweets they have liked |
| `most_recent_tweet_date` | Timezone = UTC. Null if every tweet is deleted |
| `created_at` | When the account was created. Timezone = UTC |

