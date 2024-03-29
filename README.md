# Profitable-App-Profiles
Identifying the best types of apps to develop in order to generate maximum revenue on the Google Play Store &amp; Apple App Store

## Getting Started
This repository contains the jupyter notebook and necessary csv files required to run this analysis.

A description of the columns contained for each dataset is given in the tables below:

### PlayStore.csv columns

Column|Description
---|---
App|Application name
Category|Category the app belongs to
Rating|Overall user rating of the app (as when scraped)
Reviews|Number of user reviews for the app (as when scraped)
Size|Size of the app (as when scraped)
Installs|Number of user downloads/installs for the app (as when scraped)
Type|Paid or Free
Price|Price of the app (as when scraped)
Content Rating|Age group the app is targeted at - Children / Mature 21+ / Adult
Genres|An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
Last Updated|Date when the app was last updated on Play Store (as when scraped)
Current Ver|Current version of the app available on Play Store (as when scraped)
Android Ver|Min required Android version (as when scraped)

### AppleStore.csv columns

Column|Description
---|---
id|App ID
track_name|App Name
size_bytes|Size (in Bytes)
currency|Currency Type
price|Price amount
rating_count_tot|User Rating counts (for all version)
rating_count_ver|User Rating counts (for current version)
user_rating|Average User Rating value (for all version)
user_rating_ver|Average User Rating value (for current version)
ver|Latest version code
cont_rating|Content Rating
prime_genre|Primary Genre
sup_devices.num| Number of supporting devices
ipadSc_urls.num|Number of screenshots showed for display
lang.num|Number of supported languages
vpp_lic|Vpp Device Based Licensing Enabled
