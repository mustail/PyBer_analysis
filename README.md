# PyBer_analysis
PyBer ride-sharing app assignment

## Overview
In response to V. Isualize's request, this project aims to create a summary DataFrame of the PyBer ride-sharing data with respect to urban, suburban, and rural city types. The project also includes the preparation of a multiple-line chart that presents total weekly fares for each city type. The following outlines some of the findings.

## Results

### Summary per city types

As the below table shows, urban rides (1,625) are almost three times as many as the suburban rides, and around 13 times as many as the rural rides (125). Clearly, there are so much more rides and drivers for urban rides than there are for rural and suburban ones.

![Summary DataFrame](https://github.com/mustail/PyBer_analysis/blob/424e644fce4eca70ea054b5a0f3caaa6b04014cc/Analysis/summary_dataframe.png)

However, when one looks at the fare data totals, fare date per ride and per driver, the image changes drastically. Urban fares are higher per ride and per driver than suburban ones, and the suburban fares are in turn higher than the urban ones. To give an example, despite the comparably very small number of rides in urban cities, fares per driver there are more than three times higher ($55.49) than those in urban areas ($16.57).

### Total fares over time

The time series analysis shows that change in total fare over time for all three city types remains similarly limited. Total fares peak in late February and early April and decline towards May in all three city types. There is a disparity, however, in terms of the total fares for individual types of cities. As our summary DataFrame also suggested, total fares in rural areas tend to remain much lower than those in urban cities. During the late-February peak, for instance, urban fares are more than five times more than rural fares.

![Multiple-line fare summary](https://github.com/mustail/PyBer_analysis/blob/424e644fce4eca70ea054b5a0f3caaa6b04014cc/Analysis/PyBer_fare_summary.png)

There are few instances of disparities across the lines for each city types, such as the decline in January in rural areas compared to rise in the same perido in both urban and suburban cities. This is a curious case and one can only guess the cause in the absence of more evidence. It could be, for example, that people in urban areas depend on different seasonal schedules for their economic activities.

## Summary

As mentioned above, despite the higher number of rides and the higher totals of fares, PyBer fares per ride and per driver remain very low in urban cities. The situation is the opposite for the rural areas as fares per ride tend  to be be very high.

### Recommendation 1

Increase the number of drivers available for the rural areas. It seems that the interest in ride-sharing is impeded by the limited number of drivers.

### Recommendation 2

In urban cities, it seems that the interest in ride-sharing is not matched by the interest in offering ride-shares by drivers. There are already an abundant amount of drivers, however, and this discrepancy may be because there is less interest in urban areas in ride-sharing. This may be mitigated by offering incentives for ride-sharing and getting people in urban cities more familiar with PyBer ride-sharing.

### Recommendation 3

Assuming we can get more data on the rural cities than we presently have, we can look into the reasons why there is a decline in PyBer ridership in January. Further analysis into this question can help us understand __i__ how to offset this decline and increase ride-share in this period, and, __ii__ what other factors go into the difference in ridership between rural and urban (and suburban) communities. After an evalution of economic activities and schedules that underlie changes in ridership, we may be able to diversify PyBer functionalities to better adapt riders' habits.
