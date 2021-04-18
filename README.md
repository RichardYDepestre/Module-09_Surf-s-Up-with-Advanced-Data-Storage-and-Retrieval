# Weather Analysis Surf Up (Module 9 Challenge)

## Project Overview

We are to collect and anlyse temperature data trends in Oahu and provide them to W. Avy.
W. Avy is interested in opening a surf and ice cream shop business in Oahu. 'He wants temperature data
for the months of June and December in Oahu, in order to determine if the surf and ice cream shop
business is sustainable year-round.'

## Data gathering approach

Drawing from our experience with pandas, python, and other concepts, learned in this class, we have created
scripts to use sqlachemy. From the database 'hawaisqlite' provided to us we have extracted the temperature \
data and extracted the data for our analysis.
SQLAlchemy is defined as 'a well-regarded database toolkit and object-relational \
mapper (ORM) implementation written in Python. SQLAlchemy provides a generalized interface for creating and \
executing database-agnostic code without needing to write SQL statements.'

## Analysis

The [June][1][2] historical temperature dataset shows that the weather was hot in Oahu; it fluctuated between 71 and \
80.0 degrees farenheit. [December][3][4] was not as hot but showed temperature marks between 66.0 and 77.0 degrees. \
Below are the key observations that we make:
- The summary data shows a ~4 degree difference between the two months;
- The maximum temperature appeals to both activities: surfing and ice cream;
- The drop in temperature is significant around the last days of december.


## Conclusion

We believe opening an ice cream and surf shop in Oahu is sustainable. The temperature in June and December will \
be attractive to visitors. As show in the attached summary snapshots on avarage, for both months, the temperature is \
above 71 degrees.

[1]:https://github.com/RichardYDepestre/surfs_up/blob/main/images/m10_challenge_temp_june.jpg
[2]:https://github.com/RichardYDepestre/surfs_up/blob/main/images/m10_challenge_temp_summary_june.jpg
[3]:https://github.com/RichardYDepestre/surfs_up/blob/main/images/m10_challenge_temp_dec.jpg
[4]:https://github.com/RichardYDepestre/surfs_up/blob/main/images/m10_challenge_temp_summary_dec.jpg
