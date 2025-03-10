# Topic: Predicting Traffic Safety of Chicago Streets Based on Frequency &amp; Severity of Accidents

_____

A study by the World Health Organization reveals that there are approximately 1.25 million annual fatalities from traffic accidents. Despite advancements in traffic safety and road conditions, there is an approximate annual rate of 5.5 million accidents in the United States. Further analysis of accident features such as road conditions, driver behavior and weather can improve our understanding of recent higher crash rates. 

This project assesses driving risk levels for individual road segments at a given time in Chicago. To achieve this, we first provide a danger rating score for each accident occurrence and then classify streets into various accident risk levels based on aggregated street rating scores of the streets, which considers both the severity and frequency of the accidents. Combining the geospatial data and danger scores of each accident allowed us to generate intuitive visualizations of traffic accidents, and allowed for street safety risk level predictions at different times of the day. 

----

The following short clip demonstrates how our software categorizes the roads of Chicago into various risk bands for different times of the day, and different days of the week. Roads which are coloured red possess the highest risk while those coloured green have the least risk.

The yellow dots represent actual traffic accidents which occurred in the heart of Chicago. Note how these accidents tend to occur along roads which are deemed as risky (in the orange-red spectrum) by our algorithm. Only data from the first week of January 2018 are demonstrated in this video (traffic volume can be seen to fluctuate periodically on the lower right-hand corner).



https://github.com/user-attachments/assets/985bdfa4-a1ca-4690-a7a5-a36ac8fe8160


