### project02
# Morioka: Hidden Gem Chosen by the New York Times
## Description
What I aimed to accomplish was to use API of a travel webiste and analyze whether there was a shortage of hotels due to the increadsed number of travelers to Morioka.
## My findings
I found the number of hotels in Morioka, the fact that they are concentrated in front of Morioka station and both the average of minimum charge and review. I could not tell if there was a shortage of hotels due to lack of travelers statistics for 2023(not yet released).
## Summery of data collection process
1. Statistics on foreign travelers visiting Japan from 1964 to 2021 on [Japan Tourism Agency](https://www.jnto.go.jp/statistics/data/visitors-statistics/pdf/marketingdata_outbound.pdf)
* Used Tabula to extract data from the pdf file and put into csv file
2. Simple Hotel search API from [Rakuten Developers](https://webservice.rakuten.co.jp/explorer/api/Travel/SimpleHotelSearch)
## Data analysis process
By using the Rakuten's simple hotel search API, I called up the data of hotels in Morioka. I created the pandas dataframe and extracted hotel names, latitude, longitude etc... and put it to cvs file and these are where I grew up the most this time. Shomehow all the latitude and longitude were slightely wrong so manually corrected. I analyzed the average minimum charge and average review on pandas.
## New skills
I used API and pandas for data collection and analysis for the first time. Using map on datawrapper was also a new challenge and realized it might not have been the best option for mapping. I also tried to align inserted image and text on html but it does not work well.
## I tried to do or wanted to do
I wanted to analyze bigger data like Rakuten's Hotel Detail Search API and find the Onsen(hot spring) information. I also tried to make my webiste look cooler but had not time for that.
## Data used for analysis:

## Notebooks used for analysis:

## The link
