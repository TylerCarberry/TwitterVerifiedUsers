# Twitter Verified Users <img width="30" alt="Twitter Icon" src="https://user-images.githubusercontent.com/6628497/200177212-48cb29b6-2c21-4da5-94ef-fa9fc2f48f05.png">

All 413,137 verified users on Twitter as of Saturday, November 5th 2022.

[@verified](https://twitter.com/verified) is following 423,617 accounts. 10,480 of them are not verified and have been excluded from these csv files.

## Datasets
| File name  | Size | | |
| ------------- | ------------- | -- | -- |
| `verified.csv`  | 46 MB  | [Download](https://github.com/TylerCarberry/TwitterVerifiedUsers/releases/download/v2022-11-05/verified.csv) | [Description](https://github.com/TylerCarberry/TwitterVerifiedUsers#verifiedcsv) |
| `verified_full.csv` | 252 MB | [Download](https://github.com/TylerCarberry/TwitterVerifiedUsers/releases/download/v2022-11-05/verified_full.csv) | [Description](https://github.com/TylerCarberry/TwitterVerifiedUsers#verified_fullcsv) |

## Statistics

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


## verified.csv

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


## verified_full.csv

| Column  | Description |
| ------------- | ------------- |
| `id`  | Twitter id  |
| `name`  | Account name  |
| `screen_name` | Twitter handle |
| `location`| Profile location |
| `description` | Twitter bio |
| `profile_image_url_https` | Profile picture in medium resolution |
| `is_default_profile_image` | 0=false 1=true |
| `url`| Link to the profile. May be null |
| `is_protected` | Is private account |
| `followers_count` | Number of twitter followers |
| `profile_background_color` | Hex code |
| `profile_text_color` | Hex code |
| `profile_link_color` | Hex code |
| `peofile_sidebar_fill_color` | Hex code |
| `profile_sidebar_border_color` | Hex code |
| `profile_use_background_image` | 0=false 1=true |
| `profile_background_image_url_https` | No longer displayed |
| `profile_banner_image_url` | Header image |
| `profile_background_tiled` | No longer displayed |
| `statuses_count` | Number of tweets |
| `is_geo_enabled` | If the user enabled location |
| `is_verified` | Every account in this dataset = 1 |
| `is_default_profile` | Has the user changed their theme or background |
| `translator` | |
| `listed_count` | The number of public lists that the user is a member of |
| `withheld_in_countries` | Two-letter country codes this user is withheld from |
| `friends_count` | Number of accounts they are following |
| `favourites_count` | Number of tweets they have liked |
| `most_recent_tweet_date` | Timezone = UTC. Null if every tweet is deleted |
| `created_at` | When the account was created. Timezone = UTC |
| `most_recent_tweet_text` | null for private accounts |
