# Project5
# 2019 Metro Bike Share Data Exploration and Visualization  ## Dataset  [Metro Bike Share] (https://en.wikipedia.org/wiki/Metro_Bike_Share)  is a bicycle sharing system in the Los Angeles, California metropolitan area. The service was launched on July 7, 2016. It is administered by the Los Angeles County Metropolitan Transportation Authority (Metro) and is operated by Bicycle Transit Systems.[ The system uses a fleet of about 1,400 bikes and includes 93 stations in Downtown Los Angeles, Venice, and the Port of Los Angeles. The dataset used for this exploratory analysis consists of [monthly individual trip data](https://bikeshare.metro.net/about/data/) from January 2019 to December 2019 in CSV format.  ##### Data wrangling process: - fix multiple fields that are not in the correct dtype, i.e. `start_time`, `end_time` should be DateTime type, `passholder_type`  should be categorical data type, etc - add new columns for the day of week and month - filter out outlier trip records where the duration was very long   ## Summary of Findings I could define the riders into two groups, Royal customers, (annual, and monthly- pass holders) and regular customers (single-pass holders).   In general, there were more trips on workdays (Mon-Fri) compared to weekends. Summar time was the most popular season of a year, likely due to the weather. The riding trips tend to be shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the bike-sharing system on normal workdays, while more casual flexible use on weekends.  The users who have a monthly pass are the main end-users with the highest trips per year. And more than half of the total trips were done by using a standard type of bikes. Indeed, More than two-third of trips were booked a one-way trip, larger than a round trip.   ## Key Insights for Presentation  Different usage patterns/habits between all types of riders are seen from the exploration. Royal customers, (annual, and monthly- pass holders) use the system heavily on workdays i.e. Monday through Friday whereas customers ride a lot on weekends. The efficient/short period of usage for royal customers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is primarily for the work commute. The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike-sharing system quite different from the regular customers, heavily over weekends, for city tour or leisure purpose probably.
