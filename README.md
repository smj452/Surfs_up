# Surf and Ice Cream Shop Busines Analysis using SQLite and SQLAlchemy

## Project Overview

A Surf n’ Shake shop serving surfboards and ice cream to locals and tourists requires some real investor backing to get off the ground. A strong business plan was put together in front of investor W. Avy who is famous for his love of surfing. W. Avy is willing to invest but he has one concern about the weather condition. He had invested in a surf shop early in his career. However, he did not ask for any weather analysis and that early venture was rained out of existence. W. Avy has a SQLite weather dataset for Oahu where Surf n’ Shake shop will be opened. The propose of this project is to run analytics on the dataset provided by W. Avy using SQLAlchemy, ORM queries, Pandas, and Matplotlib. Specifically, he wants temperature data for June and December in Oahu, to determine if the surf and ice cream shop business is sustainable year-round.

## Results

The key differences in weather between June and December are as follows:

-	The average temperature for June is 74.9°F and for December is 71.0°F.
-	Max temperature for June is 85°F and for December is 83°F.
-	Min temperature for June is 64°F and for December is 56°F.

**June Temperature Statistics**

![June Temperature Statistics.png](https://github.com/smj452/Surfs_up/blob/main/Resources/June%20Temperature%20Statistics.png)

**December Temperature Statistics**

![December Temperature Statistics.png](https://github.com/smj452/Surfs_up/blob/main/Resources/December%20Temperature%20Statistics.png)

## Summary

June and December do not show an extreme temperature difference, so the Surf and Ice Cream Shop business should be sustainable year-round. Two additional queries that can be performed to gather more weather data for June and December are as follows:

-	Query to group TOBS(Temperature Observation Data) by Station for the month of June and December.
-	Query to get the precipitation Data for the month of June and December.

